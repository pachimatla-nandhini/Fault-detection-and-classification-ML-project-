# Fault-detection-and-classification-ML-project

Power System Fault Detection and Classification using AI:
This project presents an intelligent system for detecting and classifying power system faults using machine learning, with full deployment on IBM Cloud Lite. It addresses the limitations of traditional rule-based fault detection systems and leverages data-driven methods for improved accuracy and speed.

Problem Statement:
Power systems are crucial for modern infrastructure. Faults in the system can cause severe disruptions and must be identified quickly. Traditional detection methods are often slow and inaccurate. This project introduces an AI-driven solution to automate fault detection using real-time electrical parameters

Proposed Solution:
An ML-based fault classification model is developed using the Random Forest algorithm. It analyzes voltage, current, and phasor inputs to classify fault types. The model is integrated into a user-friendly web application, deployed using IBM services like Watson Studio and Cloud Object Storage.

System Development Approach:
Dataset: Kaggle Power System Fault Dataset
Preprocessing: Cleaning, scaling, label encoding
Model: Random Forest Classifier (best performer vs. SVM & Logistic Regression)
Web App: Developed using Flask/Streamlit
Deployment: IBM Watson Studio + IBM Cloud App Services

Results:
Accuracy: ~93%
Best classification: LG (Line-to-Ground) and LLL (Three-phase faults)
Minimal misclassification
Real-time predictions with high reliability

Future Scope:
Integration with IoT sensors for real-time fault response
Use of deep learning models (LSTM/GRU) for time-series data
Scalability for smart grid applications

Technologies Used:
Python, Scikit-learn
Flask or Streamlit
IBM Watson Studio
IBM Cloud Object Storage
IBM Cloud App Services

 References:
Kaggle Fault Dataset
IBM Developer Docs
Breiman's Random Forest (2001)
IEEE Research Papers
Python & Flask Documentation


