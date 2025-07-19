# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 19**

**Date**: 17 July 2025  

---

## LLaMA 3 Frontend Chat Application  

### Setup Instructions  



### **Step 1: Run LLaMA 3 Backend**  
If you use **Ollama**, run:  
```bash
ollama run llama3
```
### **Step 2: Basic Frontend to Connect to Ollama API**
 Create an i.html file to serve a basic web UI
 ```bash
vim i.html
```
Paste the following code:
```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>LLaMA 3 Chat</title>
  <style>
    body { font-family: sans-serif; margin: 20px; }
    #chat { width: 100%; height: 300px; border: 1px solid #ccc; padding: 10px; overflow-y: auto; white-space: pre-wrap; background: #f9f9f9; }
    #input { width: 80%; padding: 10px; }
    #send { padding: 10px; }
  </style>
</head>
<body>
  <h2>LLaMA 3 Chat (via Ollama)</h2>
  <div id="chat"></div><br>
  <input type="text" id="input" placeholder="Type a message..." />
  <button id="send">Send</button>

  <script>
    const chatBox = document.getElementById('chat');
    const input = document.getElementById('input');
    const sendBtn = document.getElementById('send');

    sendBtn.onclick = async () => {
      const userText = input.value.trim();
      if (!userText) return;

      appendMessage('You', userText);
      input.value = '';
      input.disabled = true;
      sendBtn.disabled = true;

      let aiMessage = '';
      appendMessage('LLaMA', '');

      const response = await fetch('http://localhost:11434/api/chat', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({
          model: 'llama3',
          messages: [{ role: 'user', content: userText }],
          stream: true
        })
      });

      const reader = response.body.getReader();
      const decoder = new TextDecoder();

      while (true) {
        const { value, done } = await reader.read();
        if (done) break;
        const chunk = decoder.decode(value);
        const lines = chunk.split('\n').filter(line => line.trim());

        for (const line of lines) {
          try {
            const json = JSON.parse(line);
            const delta = json?.message?.content || '';
            aiMessage += delta;
            updateLastMessage('LLaMA', aiMessage);
          } catch (e) {
            console.error('Invalid JSON chunk:', line);
          }
        }
      }

      input.disabled = false;
      sendBtn.disabled = false;
      input.focus();
    };

    function appendMessage(sender, message) {
      const div = document.createElement('div');
      div.className = 'message';
      div.innerHTML = `<strong>${sender}:</strong> <span>${message}</span>`;
      chatBox.appendChild(div);
      chatBox.scrollTop = chatBox.scrollHeight;
    }

    function updateLastMessage(sender, newText) {
      const messages = chatBox.getElementsByClassName('message');
      if (!messages.length) return;
      const last = messages[messages.length - 1];
      const span = last.querySelector('span');
      span.textContent = newText;
      chatBox.scrollTop = chatBox.scrollHeight;
    }
  </script>
</body>
</html>
```

### **Step 3: Serve Frontend on localhost**
Use a simple local server
```bash
python -m http.server 8000
```
Then go to:
```bash
http://localhost:8000
```

Your simple LLaMA 3 chat interface should now be running!


---




**By** : Aditi Tangri

**URN** : 2302460

**CRN** : 2315004


