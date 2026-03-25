# 🧠 Oral Cancer Detection using Deep Learning + Machine Learning

An intelligent AI-based system designed to detect oral cancer from medical images using a hybrid approach combining Deep Learning (EfficientNet) and Machine Learning (SVM).

---

## 🚀 Project Overview

Early detection of oral cancer is critical for improving survival rates.  
This project leverages advanced AI techniques to analyze medical images and classify them as **Normal** or **Cancerous**.

Unlike traditional models, this system uses a **hybrid architecture**:
- Deep Learning for feature extraction
- Machine Learning for classification

---

## 🧠 Model Architecture

### 🔹 Feature Extraction (Deep Learning)
- **EfficientNetB0 (Pretrained CNN)**
- Transfer learning used for extracting high-level image features

### 🔹 Classification (Machine Learning)
- **Support Vector Machine (SVM)**
- Classifies extracted features into:
  - Normal
  - Cancer

---

## ⚙️ Tech Stack

- Python  
- TensorFlow / Keras  
- Scikit-learn  
- NumPy  
- Matplotlib  
- Joblib  

---

## 📂 Dataset Structure
archive/
│
├── train/
├── val/
└── test/


Each folder contains categorized images for:
- Normal tissue
- Cancer tissue

---

## 🔬 Workflow

1. Load dataset from Google Drive  
2. Preprocess images using ImageDataGenerator  
3. Extract features using EfficientNetB0  
4. Train SVM classifier  
5. Evaluate model using:
   - Accuracy
   - Confusion Matrix
   - ROC Curve  

---

## 📊 Results

- ✅ Validation Accuracy: **~76%**
- 📈 ROC Curve plotted
- 📉 Confusion Matrix generated

---

## 💡 Key Highlights

✔ Hybrid AI Model (Deep Learning + Machine Learning)  
✔ Transfer Learning using EfficientNet  
✔ Real-world healthcare application  
✔ Efficient feature extraction pipeline  
✔ Lightweight classification using SVM  

---

## 📸 Output

- Predicts whether input image is:
  - **Normal**
  - **Cancer**

- Provides:
  - Accuracy metrics
  - ROC Curve visualization

---

## 📁 Project Files

- `oral_cancer_detection.py` → Main model implementation  
- `requirements.txt` → Dependencies  
- Dataset sample images  
- README documentation  

---

## 📌 Future Improvements

- Improve accuracy using fine-tuning  
- Add CNN-based end-to-end classifier  
- Deploy using Flask / Streamlit  
- Integrate real-time image prediction  

---

## 👨‍💻 Author

**Ramanjamma Biladugu**  
🎓 B.Tech CSE (2026)  
💻 Aspiring Software Developer | Backend & AI Enthusiast  

🔗 LinkedIn:  
https://www.linkedin.com/in/ramanjamma-biladugu/  

📧 Email:  
ramanjammabailodugu@gmail.com  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

