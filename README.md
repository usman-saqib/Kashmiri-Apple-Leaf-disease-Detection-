# 🍎 Kashmiri Apple Leaf Disease Detection
![Python](https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-red?style=for-the-badge&logo=flask&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-orange?style=for-the-badge&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗-Hugging_face-yellow?style=for-the-badge)

> **Final Year Project** – Department of Data Science & Artificial Intelligence  
> *Khwaja Fareed University of Engineering & Information Technology, Rahim Yar Khan*

## 📌 Overview

Apple cultivation in Kashmir is a major agricultural activity, but diseases like **Apple Rot**, **Leaf Blotch**, and **Apple Scab** significantly reduce yield and quality. Manual inspection is time‑consuming, subjective, and often delayed.

This project presents an **intelligent web‑based system** that automatically detects and classifies apple leaf diseases using a **machine learning model**. Farmers and orchard managers can simply upload a leaf image and receive:

- ✅ Whether the leaf is **healthy** or **diseased**
- 🧬 **Specific disease type** (if diseased)
- 💊 **Treatment suggestions** and **preventive measures**

The system achieves **~95% accuracy** and is deployed on **Hugging Face Spaces** for easy, global access.

---

## ✨ Key Features

- 📤 **Image Upload** – Upload apple leaf images (JPG/PNG)
- 🧠 **AI‑Powered Classification** – Identifies 4 classes:
  - Healthy Leaves
  - Apple Rot Leaves
  - Leaf Blotch
  - Scab Leaves
- ⚡ **Fast & Accurate** – Average response time < 3 seconds
- 📱 **User‑Friendly Interface** – Built with Streamlit (no technical skills needed)
- ☁️ **Cloud Deployment** – Accessible via any browser (no installation)
- 🔒 **Privacy First** – Images are processed temporarily and not stored

---

## 🛠️ Technologies Used

| Category          | Tools / Libraries                                      |
|-------------------|--------------------------------------------------------|
| **Language**      | Python 3.9+                                            |
| **Web Framework** | Streamlit                                              |
| **ML Framework**  | TensorFlow / Keras                                     |
| **Image Processing** | OpenCV, NumPy                                      |
| **Environment**   | Kaggle Notebooks (training), VS Code (development)     |
| **Deployment**    | Hugging Face Spaces                                    |
| **Dataset**       | [Apple Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/hsmcaju/dkap/data?select=APPLE_DISEASE_DATASET) |

---

## 📊 Dataset

- **Source:** Kaggle – *APPLE_DISEASE_DATASET*
- **Classes:** 4 (Healthy, Apple Rot, Leaf Blotch, Scab)
- **Split:** Training (80%) / Validation (20%)
- **Preprocessing:** Resizing (224×224), normalization, data augmentation (rotation, flipping, zoom)

---

## 🧪 Model Performance

- **Accuracy:** ~95% on test data  
- **Precision / Recall:** Good balanced performance  
- **Model Format:** Saved as `apple_leaf_disease_model.keras`

> *Note:* Accuracy may vary slightly depending on image quality and lighting conditions.

---

## 🚀 Live Demo

The application is hosted on Hugging Face Spaces. Click the link below to try it live:

🔗 **[Launch Kashmiri Apple Leaf Disease Detector]**  
*(https://usmansaqib1205-apple-leaf-disease.hf.space/)*

---
## 📢 Important Disclaimer – Agricultural & Research Use

> **Agricultural & Research Disclaimer:**  
> This application is developed for **research and educational purposes only**. It is not a substitute for professional agricultural inspection, expert plant pathology advice, or on‑field diagnosis by qualified horticulturists. The system provides a preliminary, AI‑based analysis of apple leaf images; results may not be 100% accurate under all conditions (e.g., poor lighting, image quality, or unrepresented disease variants).  
>  
> - Not intended to replace field experts or laboratory testing.  
> - Not certified by any agricultural regulatory body.  
> - Treatment suggestions are general recommendations; users should consult local agricultural extension services before applying any pesticides or treatments.  
> - Use at your own risk. The developers and the university are not liable for any crop loss or decisions made based solely on this tool’s output.


<div align="center">
Made with ❤️ for the **agricultural community** and smart farming research.

 contributions Welcome! to make AI-powered plant disease detection 

 ⭐ Star this repo
 🐛 Report Issues 
 💡 Suggest Features

</div>
