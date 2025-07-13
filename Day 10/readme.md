# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 10**

**Date**: 4 July 2025

---

## K-Nearest Neighbor (KNN) Algorithm

K-Nearest Neighbors (KNN) is a **supervised machine learning algorithm** primarily used for **classification**, though it can also be used for **regression**.

- The algorithm identifies the "k" nearest data points (neighbors) to a given input.
- For classification, it uses **majority vote** among neighbors.
- For regression, it takes the **average** of the neighbors' values.

### Example

- Red diamonds represent Category 1.
- Blue squares represent Category 2.
- A new data point is surrounded mostly by blue squares → KNN classifies it as **Category 2**.

KNN works using **proximity** and **majority voting**.

### What is 'K'?

- 'K' is the number of neighbors to consider.
- **Example**:  
  If `K = 3`, and among the 3 neighbors:
  - 2 are apples, 1 is a banana → result = apple

**Choosing K:**
- Small K → Sensitive to noise
- Large K → May dilute important distinctions

---

## Convolutional Neural Network (CNN)

CNNs are **deep learning models** designed for data with a **grid-like structure**, especially images.

### Applications
- Image classification
- Object detection
- Image segmentation

### Components of CNN

1. **Convolutional Layers**
   - Use filters/kernels to detect features like edges or textures.
2. **Pooling Layers**
   - Downsample the image (e.g., **Max Pooling**).
3. **Activation Functions**
   - Introduce non-linearity. Common: **ReLU**.
4. **Fully Connected Layers**
   - Final layers that produce predictions.

### How CNNs Work

1. **Input Image** → Preprocessed
2. **Convolution + Activation** → Feature maps generated
3. **Pooling** → Reduced spatial size
4. **Flatten + Dense Layers** → Classify or predict
5. **Output** → Final prediction

### Evaluating CNN Models

- **Accuracy** – % of correctly predicted images
- **Precision** – Correct positive predictions out of total predicted positives
- **Recall** – Correct positive predictions out of actual positives
- **F1 Score** – Harmonic mean of Precision & Recall

---

## LAMP Stack

**LAMP** is an acronym for:

- **L**inux – Operating system  
- **A**pache – Web server  
- **M**ySQL – Relational database  
- **P**HP – Server-side scripting language

### What is LAMP?

A **free and open-source** stack used to build **dynamic web applications**.

### Components:

#### Linux
- Open-source OS
- Secure and reliable

#### Apache
- Most-used web server
- Handles requests and sends responses
- Supports HTTP/HTTPS protocols

#### MySQL
- SQL-based relational database
- Ideal for storing and managing data

#### PHP
- Server-side scripting language
- Works well with MySQL
- Handles backend logic

### How LAMP Works

1. **Apache** receives a request
2. If it's a PHP file, **PHP** handles it
3. **PHP** communicates with **MySQL** for data
4. Linux OS manages the environment

### Benefits of LAMP

- Open-source and cost-effective
- Large community support
- Cross-platform and customizable

# Install LAMP Stack on Ubuntu

Follow these steps to install the **LAMP Stack** (Linux, Apache, MySQL, PHP) on Ubuntu:

---

## 1. Update Package Index

```bash
sudo apt update && sudo apt upgrade
```
## 2. Install Apache Web Server
```bash
sudo apt install apache2 -y
```

## 3. Install MySQL (or MariaDB)
```bash
sudo apt install mysql-server
```

## 4. Install PHP
```bash
sudo apt install php libapache2-mod-php php-mysql
```

## 5. One Command to Install PHP + Common Extensions
```bash
sudo apt install php php-curl php-json php-mbstring
```

## Open Your Web Browser
In your browser, go to:
```bash
http://localhost/
```

**By**  : Aditi Tangri

**URN**  : 2302460  

**CRN**  : 2315004
