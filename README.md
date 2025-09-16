# Heart Attack Prediction System

This project provides a machine learning–based system to predict the risk of a heart attack based on users’ health data.

---

## About the Project

The **Heart Attack Prediction System** uses data analysis and machine learning to predict whether an individual is at risk of a heart attack.  
The model is trained on health-related features such as age, gender, blood pressure, cholesterol level, maximum heart rate, and detailed information about patients then classifies the individual as **“at risk”** or **“not at risk”**.

---

## Installation

Follow these steps to set up the project on your local machine:

# Clone the repository
git clone https://github.com/ayshegulkoca/heart-attack-prediction-system.git

# Navigate into the project directory
cd heart-attack-prediction-system

# (Optional) Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt


# Usage
Run the project with: python main.py

# Technologies
Python
Pandas, NumPy — Data preprocessing
Scikit-learn — Machine learning
Flask — Web/API interface

# Project Structure
File/Folder	Description
main.py	Model training and prediction
backend.py	Web service / API
heart.csv	Dataset
Images/	Visuals such as graphs or performance plots
__pycache__/	Auto-generated cache files (ignored by git)
