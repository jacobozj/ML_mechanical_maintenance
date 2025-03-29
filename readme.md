# 🔧 Predictive Maintenance using Machine Learning

## 📌 Project Overview

This project applies **Machine Learning (ML) algorithms** to predictive maintenance, analyzing sensor data to classify the operational state of machinery. The goal is to enhance **preventive maintenance strategies** and reduce unexpected failures.

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Scikit-Learn**: Machine Learning models (KNN, Random Forest)
- **Pandas & NumPy**: Data manipulation and preprocessing
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive environment for model evaluation

## 📊 Machine Learning Models

This project utilizes the following ML algorithms for predictive maintenance:

- **K-Nearest Neighbors (KNN)**: Used for classifying machine operational states based on historical sensor data.
- **K-Means Clustering**: Applied for unsupervised learning to identify patterns in the data.
- **StandardScaler**: Used for feature normalization to ensure better model performance.
- **Evaluation Metrics**:
  - **Accuracy Score**: Measures the overall correctness of the KNN model.
  - **Confusion Matrix**: Provides insights into misclassified instances and helps fine-tune the model.

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/jacobozj/ML_mechanical_maintenance.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook mecanica.ipynb
   ```
   Run the notebook mecanica.ipynb to train and evaluate the models.

## 🔍 Key Features

Data Preprocessing & Normalization: Uses StandardScaler to normalize sensor readings.

Model Training & Evaluation: Compares KNN vs. Random Forest for accuracy.

Real-time Prediction: Allows input of new sensor values to classify machine status.

Confusion Matrix & Performance Metrics: Used to validate predictions.

## 📈 Results & Insights

The project evaluates how well the models detect critical operational states, helping in:

Predicting machinery failures before they occur

Reducing downtime with better maintenance scheduling

Improving decision-making for industrial maintenance teams
