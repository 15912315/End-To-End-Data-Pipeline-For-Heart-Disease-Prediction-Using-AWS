# 💓 Heart Disease Prediction Using AWS - End-to-End Data Pipeline


## 📌 Project Overview

- **Objective**: To create an **automated, cloud-native ML pipeline** for early detection of heart disease.
- **Cloud Integration**: AWS (S3, Glue, EC2) + GCP (Vertex AI).
- **ML Model**: Random Forest classifier with 90.16% accuracy, 0.88 precision, and 0.91 recall.
- **Interface**: Real-time dashboard using Streamlit on AWS EC2.

---

## 🏗️ System Architecture


![System Architecture](https://github.com/15912315/End-To-End-Data-Pipeline-For-Heart-Disease-Prediction-Using-AWS/blob/3188d30d67d7ef761217fd244ca71a70d486c827/architecture_diagram.jpg)



## 🚀 Key Features

- **Automated ETL Pipeline**: AWS Glue processes raw clinical data with 60% faster preparation time  
- **Hybrid Cloud Architecture**: Leverages AWS for data processing + Google Cloud for ML  
- **Real-Time Predictions**: Vertex AI endpoints deliver results in <400ms  
- **Interactive Dashboard**: Streamlit UI hosted on EC2 for clinical decision support  
- **Explainable AI**: Feature importance analysis identifies critical risk factors  

## 🧩 Stepwise Workflow

A detailed breakdown of the hybrid cloud-based heart disease prediction pipeline:

---

### 🔹 1. Data Ingestion
- **Source**: Raw clinical datasets (demographics, vitals, diagnostic results)
- **Storage**: Securely stored in **Amazon S3**

---

### 🔹 2. ETL & Preprocessing
- **Tool**: AWS Glue Studio (visual ETL)
- **Processes**:
  - Data Cleaning (missing values, outlier handling)
  - Transformation (normalization, encoding)
  - Feature Engineering for clinical relevance

---

### 🔹 3. Model Training
- **Platform**: Google Cloud Vertex AI
- **Algorithms Tested**:
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Decision Tree  
  - **Random Forest** (Best performer)

---

### 🔹 4. Deployment
- **Model**: Random Forest Classifier
- **Endpoint**: Deployed to **Vertex AI Endpoint**
- **Purpose**: Real-time predictions via scalable API

---

### 🔹 5. Inference & UI
- **Interface**: **Streamlit dashboard** hosted on **AWS EC2**
- **Features**:
  - User inputs patient data
  - Immediate prediction (Low Risk / High Risk)
  - Explainable results via feature importance

---



## 📊 Performance Metrics

| Metric              | Score   |
|---------------------|---------|
| Accuracy            | 90.16%  |
| Precision           | 0.88    |
| Recall              | 0.91    |
| F1-Score            | 0.89    |
| Cross-Val Accuracy  | 84.8%   |

---

## 🛠️ Technical Stack

### AWS Services
- **S3**: Secure data storage  
- **Glue**: Automated ETL pipelines  
- **EC2**: Streamlit dashboard hosting  

### Google Cloud
- **Vertex AI**: Model training & deployment  

### Machine Learning
- **Random Forest (Best Performer)**  
- Logistic Regression, SVM, Decision Trees  
- Scikit-learn, Pandas, NumPy  

### Visualization
- Streamlit  
- Matplotlib  
- Seaborn  

---

## 🧠 Critical Risk Factors Identified

- **Maximum heart rate** (*thalach*)
- **Chest pain type** (*cp*)
- **ST depression** (*oldpeak*)
- **Number of major vessels** (*ca*)
- **Thalassemia** (*thal*)

---

## 📈 Future Enhancements

- Quantum ML integration  
- Multimodal data (**ECG + EHR + imaging**)  
- Real-time wearable integration  
- Explainable AI (**SHAP / LIME**)  
- Federated learning for privacy  

---

## 📚 References

- IEEE Access Papers on Heart Disease Prediction  
- Google Cloud Vertex AI Documentation  
- AWS Glue Best Practices  
- Scikit-learn Random Forest Implementation  

---

## 👥 Contributors

- **Akshay Kumar** *(RA2412033010021)*  
- **Ritesh Kumar Verma** *(RA2412033010024)*  
- **Akshay Ladha** *(RA2412033010035)*  

> Under the guidance of **Dr. S. Prabakeran**,  
> SRM Institute of Science and Technology

---



