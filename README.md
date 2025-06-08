# ✍️ Signature Detection
Detects signature copied is false or real as the exact copy that is given as input
## 🧠 Overview

The **Signature Forgery Detection App** is a powerful AI-based tool that helps verify the authenticity of handwritten signatures using image processing and machine learning. This application is especially useful for banks, educational institutions, legal bodies, and document verification services, offering an automated and reliable way to detect forgeries in real-time.

---

## 🔍 Key Features

- 📤 Upload and compare signature images
- ✅ Detects whether a signature is **genuine** or **forged**
- 📊 Displays a **similarity score**
- 🧠 Uses deep learning (CNNs or Siamese Networks)
- 💻 Web-based interface for ease of use
- 🗃️ Trained on real signature datasets (e.g., CEDAR)

---

## 🛠️ Tech Stack

| Component       | Technology           |
|----------------|----------------------|
| Frontend       | HTML, CSS, JavaScript |
| Backend        | Python, Flask         |
| ML Framework   | TensorFlow / PyTorch  |
| Image Processing | OpenCV, NumPy       |
| Deployment     | Streamlit / Heroku / Localhost |

---

---

## ⚙️ How It Works

1. **Image Upload**: User uploads two signature images – one reference and one test.
2. **Preprocessing**: Images are converted to grayscale, resized, and normalized.
3. **Feature Extraction**: Convolutional Neural Networks (CNN) extract key features.
4. **Comparison**: A Siamese Network or feature-based algorithm compares the signatures.
5. **Prediction**: Model returns a similarity score and verdict (Genuine or Forged).

---

## 📦 Dataset Used

We use the **CEDAR Signature Dataset**, a popular dataset for offline handwritten signature verification, and optionally other datasets like **GPDS Synthetic Corpus**.

📎 [CEDAR Dataset Download](http://www.cedar.buffalo.edu/NIJ/data/signatures/)

---

## 🖥️ Installation & Running Locally

### 🔧 Prerequisites

- Python 3.7+
- pip

### 📦 Step-by-step

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/signature-forgery-detection.git
   cd signature-forgery-detection
# 🧠 Model Training - Signature Forgery Detection

This guide explains how to train the deep learning model used for detecting signature forgeries in the Signature Forgery Detection App.

---

## 🗂️ Dataset Preparation

To train the model, you need a dataset containing **genuine** and **forged** signatures.

### 🔸 Dataset Used

- **CEDAR Signature Dataset**  
  [Download Link](http://www.cedar.buffalo.edu/NIJ/data/signatures/)

Each folder should contain `.png` or `.jpg` signature images.

---

## 🏁 Let’s Detect Forgery, One Signature at a Time!

Secure documents. Prevent fraud. Power verification with AI.  
Thank you for visiting this repository! 


<p align="center">
  <img src="![SignDetect](https://github.com/user-attachments/assets/ad576fa2-bdf5-490c-ab03-54e077b5f39f)" width="400"/>
</p>

<p align="center">

  <img src="![WhatsApp Image 2025-06-07 at 16 23 36_11c87de1](https://github.com/user-attachments/assets/a1b9231a-fe8a-4f3f-8ac4-e214dd22b03c)" alt="Signature Image 1" width="300"/>
  <br><br>
  <img src="![WhatsApp Image 2025-06-07 at 16 25 23_fb92e3b7](https://github.com/user-attachments/assets/01f0a1d4-6899-40b3-a88b-ad1417cbacb6)" alt="Signature Image 2" width="300"/>
</p>
<p align="center">
  <img src="" alt="![WhatsApp Image 2025-06-07 at 16 25 23_fb92e3b7](https://github.com/user-attachments/assets/2154d201-d3c6-4ca2-8f81-d1c7f6619daf)" width="300"/>
  <br><br>!
   <img src="![WhatsApp Image 2025-06-07 at 16 23 36_11c87de1](https://github.com/user-attachments/assets/ebcf3701-fa65-4ff4-bde9-4c841926781f)" alt="Signature Image 2" width="300"/>
</p>

