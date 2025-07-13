# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 15**

**Date:** 11 July 2025  

## LLaMA 3

LLaMA 3 is Meta’s (Facebook’s) latest open-source AI language model, released in 2024. It is designed to understand and generate human-like text, similar to ChatGPT.

- Made by Meta (the company behind Facebook, Instagram, and WhatsApp).  
- Available in different sizes: 8B, 70B, and a newer 405B version.  
- Trained on massive text data (15 trillion words!) from books, websites, code, and more.  
- Capable of understanding and answering questions, writing essays, generating code, and even processing images (in newer versions).  

### Example of Use:
You can ask LLaMA 3 things like:  
- "Summarize this article"  
- "Write a poem about space"  
- "Explain Python code"  

And it will respond intelligently, like a chatbot or smart assistant.

---

## Step-by-Step: Install LLaMA 3

### Step 1: Update Your System  
Open your terminal and run:  
```bash
sudo apt update
```

### Step 2: Install Required Dependencies
Make sure curl is installed (used to download Ollama):
```bash
sudo apt install curl
 ```

### Step 3: Install Ollama (LLaMA 3 Runner)
Ollama is the easiest tool to run LLaMA 3 locally:
```bash
curl https://ollama.ai/install.sh | sh
 ```

After installation, you can check if it worked:
```bash
ollama –version
 ```

### Step 4: Run LLaMA 3 Model
To download and run LLaMA 3 (for example, the 8B model), use:
```bash
ollama run llama3
```

This command:

•	Downloads the model (first time only)

•	Starts a chat in your terminal
 
### Step 5: Chat with LLaMA 3
Now that it's running, simply start typing questions or prompts directly into your terminal — just like using ChatGPT.
 









