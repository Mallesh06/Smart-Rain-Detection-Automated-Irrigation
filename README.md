# 🌧️ Smart Rain Detection for Automated Irrigation

### Internship: Automotive Object Detection  
**Organization:** AICTE × Edunet × Shell Skills4Future  
**Intern:** Peddagolla Mallesham  
**Repository:** [Smart-Rain-Detection-Automated-Irrigation](https://github.com/Mallesh06/Smart-Rain-Detection-Automated-Irrigation)

---

## 📘 Project Overview
This project aims to develop an **AI-based Smart Rain Detection System** that automatically turns **off the irrigation motor** when it detects rainfall.  
It uses **computer vision and deep learning (Vision Transformer - ViT)** to analyze images and determine weather conditions in real time.

Although this internship focuses on *Automotive Object Detection*, this project applies the **same core AI principles** of visual detection and automation — but in the **agriculture domain** 🌾.

By combining AI with simple automation logic, the project promotes **water conservation** and **smart farming practices**.

---

## 🎯 Problem Statement
When it rains, irrigation pumps in agricultural fields often continue running unnecessarily, leading to **water wastage** and **electricity loss**.  
This system automatically detects rainfall using an AI model and **stops the pump**, ensuring smarter irrigation management.

---

## 🧠 Objectives
- Apply **computer vision** and **deep learning** concepts to detect weather conditions.  
- Use a **pre-trained Vision Transformer (ViT)** model and fine-tune it on a custom dataset (Rainy vs Non-Rainy).  
- Simulate **automatic irrigation pump control** based on detection results.  
- Demonstrate how **AI automation** can benefit **farmers and sustainable agriculture**.

---

## ⚙️ Tools and Technologies
- **Python**
- **Google Colab**
- **Hugging Face Transformers**
- **PyTorch**
- **OpenCV**
- **Pillow**
- **NumPy**
- **Matplotlib**

---

## 🧩 Model Used
- **Base Model:** [`google/vit-base-patch16-224-in21k`](https://huggingface.co/google/vit-base-patch16-224-in21k)  
- **Fine-tuned Dataset:** Custom 2-class dataset → *Rainy* 🌧️ / *Not Rainy* ☀️  
- **Accuracy Achieved:** ~72.48% after 3 epochs  
- Can be improved further by adding more images and training for more epochs.  

---

## 🗂️ Project Structure
<pre><code>```
Smart-Rain-Detection-Automated-Irrigation/
│
├── README.md
├── rain_detection_finetune.ipynb # Colab notebook for training and testing
├── requirements.txt
│
├── dataset/
│ ├── train/
│ │ ├── Rainy/
│ │ └── Not_Rainy/
│ └── test/
│ ├── Rainy/
│ └── Not_Rainy/
│
├── results/
│ ├── accuracy_graph.png
│ ├── loss_curve.png
│ ├── confusion_matrix.png
│ └── metrics.txt
│
└── outputs/
├── rain_detected.png
├── no_rain_detected.png
├── model_prediction_output.png
└── real_time_test.png
``</code></pre>
