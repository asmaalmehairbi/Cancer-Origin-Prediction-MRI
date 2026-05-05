# Cancer-Origin-Prediction-MRI
Hybrid machine learning model combining radiomic, deep, and clinical features to predict cancer origin from brain metastasis MRI images.
# 🧠 Cancer Origin Prediction from Brain Metastasis MRI

## 📖 Overview  
This project focuses on predicting the **primary origin of brain metastases** using MRI images.  
A **hybrid machine learning framework** was developed by combining:
- Radiomic features  
- Deep learning features (CNN-based)  
- Clinical data  

The goal is to support **clinical decision-making** and improve diagnostic accuracy.

---

## 🎯 Objectives  
- Extract radiomic features from MRI tumor regions  
- Extract deep features using a CNN model with attention  
- Integrate radiomic, deep, and clinical data  
- Train and compare multiple machine learning models  
- Evaluate performance using robust metrics  

---

## 🧠 Methodology  

### 📊 Dataset  
- Brain-Mets-Lung-MRI-Path-Segs (TCIA)  
- Includes MRI images, segmentation masks, and clinical data  
- Focus on lung cancer subtypes  

---

### 🔍 Feature Extraction  
- **Radiomic Features**: Extracted using PyRadiomics  
- **Deep Features**: Extracted using a 3D CNN model with attention  
- **Clinical Data**: Combined with imaging features  

---

### ⚙️ Preprocessing  
- Tumor ROI extraction using segmentation masks  
- Image resizing and normalization  
- Handling missing values  
- Feature selection  

---

### 🤖 Models Used  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- Gradient Boosting  
- XGBoost  
- LightGBM  
- Multilayer Perceptron (MLP)  

---

### 📏 Evaluation Metrics  
- Accuracy  
- F1-score  
- F1-macro  
- ROC-AUC  

---

## 📊 Results  
- **Best performing models**: XGBoost and LightGBM  
- **ROC-AUC**: ~0.93  
- Strong performance for majority classes  
- Lower performance for minority classes due to class imbalance  

---

## 👩‍💻 Authors
This project was developed by:
- Asma Almehairbi
- Alanood Alqemzi
- Fatima Saleh


## 📎 Acknowledgments
- Dataset provided by The Cancer Imaging Archive (TCIA)
- Developed as part of a Senior Project at Zayed University College of Technological Innovation

## 🚀 How to Run  

```bash
git clone https://github.com/your-username/cancer-origin-prediction-mri.git
