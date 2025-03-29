# 🔧 Predictive Maintenance using Machine Learning

## 📌 Project Overview

This project applies **Machine Learning (ML) algorithms** to predictive maintenance, analyzing sensor data to classify the operational state of machinery. The goal is to enhance **preventive maintenance strategies** and reduce unexpected failures.

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Scikit-Learn**: Machine Learning models (KNN, Random Forest)
- **Pandas & NumPy**: Data manipulation and preprocessing
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive environment for model evaluation

## 📂 Project Structure

├── data/ # Dataset files ├── notebooks/ # Jupyter notebooks with analysis ├── src/ # Source code for ML models ├── results/ # Output files and performance reports └── README.md # Project documentation

## 📊 Machine Learning Models

This project evaluates the following ML algorithms for maintenance prediction:

- **K-Nearest Neighbors (KNN)**: Used for initial classification
- **Random Forest**: Applied for improved accuracy and robustness
- **Confusion Matrix & Precision Metrics**: Used to assess model performance

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   Install dependencies:
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
   ```

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
