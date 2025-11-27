# 🖼️ AI Image Caption Generator

*A Mini Project – Batch 17*

This project uses **AI + Deep Learning** to automatically generate meaningful captions for uploaded images. It also provides **Text-to-Speech (TTS)** support, making the system highly accessible for visually impaired users.

---

## 📌 Project Overview

The AI Image Caption Generator takes an uploaded image and produces a human-like caption describing the content. It uses:

* **BLIP (Bootstrapped Language-Image Pre-training)** model for caption generation
* **Convolutional Neural Networks (CNN)** for image feature extraction
* **LSTM/Transformer-based decoder** for text generation
* **TTS** for converting captions into audio

This solves the problem of information overload, improves accessibility, and enhances the searchability of visual content.

---

## 🎯 Problem Statement

With millions of images uploaded daily, users struggle to understand and search through visual content due to lack of descriptions. This project aims to:

* Automatically generate context-aware image descriptions
* Improve accessibility for visually impaired users
* Enhance content management and search
* Reduce manual effort in tagging and organizing images

---

## 📚 Dataset

Dataset Used: **VizWiz Image Captioning Dataset**
Size: ~10 GB
Contains ~20,000 images along with captions

Source: [https://vizwiz.org/tasks-and-datasets/image-captioning](https://vizwiz.org/tasks-and-datasets/image-captioning)  fileciteturn2file0

---

## 🧠 System Features

* ✔️ Upload any image and get an AI-generated caption
* ✔️ BLIP model for high-quality caption generation
* ✔️ TTS support to convert captions into audio
* ✔️ Clean UI for easy interaction
* ✔️ Deployed using Render for online access

---

## 🧩 Modules

### 1️⃣ User Interface Module

* Built using HTML, CSS, JavaScript
* Allows users to upload images and view captions + audio

### 2️⃣ Flask Backend Module

* Handles image uploads and routes requests
* Sends images to preprocessing and caption generation modules

### 3️⃣ Image Preprocessing Module

* Resizes, normalizes, and converts the uploaded image into tensor format

### 4️⃣ Caption Generation Module (BLIP)

* Generates descriptive text from the processed image using vision-language features

### 5️⃣ Text-to-Speech (TTS) Module

* Converts generated text captions into audio using **gTTS**

### 6️⃣ Audio Playback Module

* Allows users to listen to the generated audio in the web interface

### 7️⃣ Deployment Module

* Hosted using **Render** to make the app accessible online

---

## 🔧 Technologies Used

**Frontend:** HTML, CSS, JavaScript
**Backend:** Flask (Python)
**AI Model:** BLIP (Hugging Face Transformers)
**Image Processing:** PIL, TorchVision, NumPy
**TTS:** gTTS
**Deployment:** Render

---

## 📐 System Design

### System Architecture

The system follows a modular architecture with:

* Frontend (UI)
* Flask Backend
* BLIP Captioning Model
* TTS Engine
* Deployment Server

### Data Flow Diagram

1. User uploads image → 2. API receives → 3. Preprocessing → 4. Caption Generation → 5. TTS → 6. Output returned to UI

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Flask Server

```bash
python app.py
```

### 3️⃣ Open in Browser

```
http://localhost:5000
```

---

## 📈 Future Enhancements

* Add multilingual caption generation
* Add voice-based story narration
* Build mobile app version
* Improve performance using Vision Transformers (ViT)
* Add user feedback learning system

---

## 👩‍💻 Team Members

* **Alaboina Sai Priya (22QM1A6602)**
* **Bovani Anusha (22QM1A6607)**
* **Ayesha (22QM1A6636)**

**Guide:** Mr. Mohd. Mustafeez-ul-Haque

---

## 🙏 Thank You

This project enhances image accessibility, improves content understanding, and demonstrates the power of AI in real-world applications.
