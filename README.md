Heart Disease Prediction Using AWS - End-to-End Data Pipeline
Project Architecture

📌 Project Overview
This project implements a hybrid cloud-based machine learning pipeline for accurate heart disease prediction, combining AWS services (S3, Glue, EC2) with Google Cloud's Vertex AI. Our Random Forest model achieves 90.16% accuracy with strong clinical metrics (0.88 precision, 0.91 recall), validated through 5-fold cross-validation.

🚀 Key Features
Automated ETL Pipeline: AWS Glue processes raw clinical data with 60% faster preparation time

Hybrid Cloud Architecture: Leverages AWS for data processing + Google Cloud for ML

Real-Time Predictions: Vertex AI endpoints deliver results in <400ms

Interactive Dashboard: Streamlit UI hosted on EC2 for clinical decision support

Explainable AI: Feature importance analysis identifies critical risk factors

📊 Performance Metrics
Metric	Score
Accuracy	90.16%
Precision	0.88
Recall	0.91
F1-Score	0.89
Cross-Val Accuracy	84.8%
🛠️ Technical Stack
AWS Services:

S3: Secure data storage

Glue: Automated ETL pipelines

EC2: Streamlit dashboard hosting

Google Cloud:

Vertex AI: Model training & deployment

Machine Learning:

Random Forest (Best Performer)

Logistic Regression, SVM, Decision Trees

Scikit-learn, Pandas, NumPy

Visualization:

Streamlit, Matplotlib, Seaborn

📂 Repository Structure
heart_prediction/
├── data/                   # Sample datasets
├── notebooks/              # Jupyter notebooks for EDA/modeling
├── aws_glue_scripts/       # ETL job scripts
├── streamlit_app/          # Dashboard source code
├── models/                 # Trained model files
└── docs/                   # Project documentation
🏆 Comparative Algorithm Performance
Algorithm	Accuracy
Random Forest	90.16%
Logistic Regression	85.25%
Naive Bayes	85.25%
SVM	81.97%
Decision Tree	81.97%
KNN	67.21%
🖥️ How to Use the Prediction App
Access the Streamlit dashboard on EC2

Input patient parameters:

Demographic data (age, sex)

Clinical measurements (BP, cholesterol)

Diagnostic test results (ECG, exercise tests)

Get instant risk prediction with confidence score

python
# Sample prediction code
input_data = [[57, 1, 2, 130, 236, 0, 1, 174, 0, 0.0, 1, 1, 2]]
prediction = model.predict(input_data)  # 1 = High Risk, 0 = Low Risk
🧠 Critical Risk Factors Identified
Maximum heart rate (thalach)

Chest pain type (cp)

ST depression (oldpeak)

Number of major vessels (ca)

Thalassemia (thal)

📈 Future Enhancements
Quantum ML integration

Multimodal data (ECG + EHR + imaging)

Real-time wearable integration

Explainable AI (SHAP/LIME)

Federated learning for privacy

📚 References
IEEE Access Papers on Heart Disease Prediction

Google Cloud Vertex AI Documentation

AWS Glue Best Practices

Scikit-learn Random Forest Implementation



👥 Contributors
Akshay Kumar (RA2412033010021)

Ritesh Kumar Verma (RA2412033010024)

Akshay Ladha (RA2412033010035)

Under guidance of Dr. S. Prabakeran, SRM Institute of Science and Technology
