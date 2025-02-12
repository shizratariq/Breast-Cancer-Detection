# Breast Cancer Detection Using Machine Learning  

## 🔬 Project Overview  
This project compares different **machine learning algorithms** for breast cancer detection using the **Wisconsin Diagnostic Breast Cancer (WDBC) dataset**. The models implemented include **Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Logistic Regression, Neural Networks, and XGBoost**. The goal is to determine the most effective model for **early and accurate diagnosis**, reducing false positives and improving clinical decision-making.  

## 📊 Results  
- **Logistic Regression** showed the **best overall performance**, achieving **96.49% accuracy** and the highest **F1-score (0.9512)**.  
- **SVM and XGBoost** had **perfect precision (1.0000)** but slightly lower recall.  
- **ROC Curves and Confusion Matrix** were used to compare model performance.  
- **Real-time mammography image analysis** was successfully implemented, with all models correctly classifying malignant cases.  

### Results Overview  
<img src="https://github.com/user-attachments/assets/6f55986b-c974-4248-b8f1-0b4a5dc76d97" width="600">  

### Comparative Analysis of Models  
<img src="https://github.com/user-attachments/assets/00562fb5-be0e-4ba3-baa6-dffc5db8d973" width="600">  

## 🏥 Added Feature: Detection from Mammography Images  
A new feature was implemented to analyze **real-time mammography images** for breast cancer detection. The process includes:  

- **Feature Extraction**: Extracts key features like **radius, texture, symmetry, and fractal dimension** from the uploaded image.  
- **Preprocessing**: Converts the image to grayscale, applies thresholding, and detects regions of interest.  
- **Model Testing**: The extracted features are fed into trained **machine learning models** for classification.  
- **Prediction Output**: Each model predicts whether the tumor is **benign or malignant**, along with a **probability score**.  

### Breast Cancer Detection in Real-Time Mammography Image  
<img src="https://github.com/user-attachments/assets/ce3b442d-8f37-4b2a-826a-c9eee9235d45" width="600">  

### Results for Mammography Image Testing  
<img src="https://github.com/user-attachments/assets/79e8c793-bd0e-4957-a62f-0f1d8bd1b96b" width="600">  
