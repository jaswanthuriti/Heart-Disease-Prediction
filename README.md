# Cardiovascular Disease Prediction


A comprehensive web-based system for predicting cardiovascular disease risk using advanced machine learning techniques. This tool aims to assist healthcare professionals in early detection and risk assessment of cardiovascular diseases, potentially improving patient outcomes through timely intervention.


## ✨ Features

- **Data preprocessing and feature engineering pipeline**
  - Handling missing values
  - Feature scaling and normalization
  - Categorical variable encoding
  - Outlier detection and treatment

- **Implementation of multiple ML algorithms**
  - Random Forest
  - Decision Tree
  - Logistic Regression
  - Support Vector Machine (SVM)

- **Model performance evaluation and comparison**
  - Cross-validation
  - Accuracy, precision, recall, F1-score metrics
  - ROC curve and AUC analysis
  - Confusion matrix visualization

- **Feature importance analysis using LIME**
  - Interpretable insights on model predictions
  - Visual representation of feature contributions

- **User-friendly web interface**
  - Form-based input for patient data
  - Clear visualization of risk prediction
  - Explanation of contributing factors

## 🎬 Demo

![Screenshot 2025-02-24 at 9 42 17 PM](https://github.com/user-attachments/assets/3c127fa4-2f22-44db-ae56-c6d296f245f5)

## 🛠️ Tech Stack

<div align="center">

### Programming Languages:
![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Web Technologies:
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/BOOTSTRAP-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Chart.js](https://img.shields.io/badge/CHART.JS-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)

### Backend:
![Flask](https://img.shields.io/badge/FLASK-000000?style=for-the-badge&logo=flask&logoColor=white)

### ML Libraries:
![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/SCIKIT--LEARN-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-11557C?style=for-the-badge&logo=python&logoColor=white)
![LIME](https://img.shields.io/badge/LIME-8E44AD?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/SEABORN-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Database:
![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)

</div>

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jaswanthuriti/cardiovascular-disease-prediction.git
   cd cardiovascular-disease-prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Setup the database:
   ```bash
   python setup_db.py
   ```

## 🚀 Usage

1. Start the Flask application:
   ```bash
   python app.py
   ```

2. Open your web browser and navigate to:
   ```
   http://localhost:5000
   ```

3. Enter patient information in the form and submit to get a prediction.

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | AUC |
|-------|----------|-----------|--------|----------|-----|
| Random Forest | 94% | 0.93 | 0.95 | 0.94 | 0.97 |
| Decision Tree | 89% | 0.88 | 0.90 | 0.89 | 0.91 |
| Logistic Regression | 86% | 0.85 | 0.87 | 0.86 | 0.92 |
| SVM | 88% | 0.87 | 0.89 | 0.88 | 0.93 |



## 📁 Project Structure

```
cardiovascular-disease-prediction/
│
├── app.py                 # Main Flask application
├── requirements.txt       # Project dependencies
├── setup_db.py            # Database setup script
│
├── data/
│   ├── raw/               # Original dataset
│   └── processed/         # Cleaned and preprocessed data
│
├── models/
│   ├── train.py           # Model training script
│   ├── evaluate.py        # Model evaluation script
│   └── saved_models/      # Saved model files
│
├── notebooks/
│   ├── data_analysis.ipynb      # EDA and data analysis
│   ├── feature_engineering.ipynb # Feature processing
│   └── model_comparison.ipynb   # Model testing and selection
│
├── static/
│   ├── css/               # Stylesheet files
│   ├── js/                # JavaScript files
│   └── images/            # Image resources
│
└── templates/
    ├── index.html         # Main page
    ├── predict.html       # Prediction form
    └── results.html       # Results display
```

## 🔮 Future Improvements

- Implement deep learning models for comparison
- Add more detailed visualization of patient risk factors
- Develop a mobile application version
- Integrate with electronic health record systems
- Add time-series analysis for patient monitoring


## 📧 Contact

Jaswanth Uriti - [jaswanthuriti@gmail.com](mailto:jaswanthuriti@gmail.com)


⭐️ From [jaswanthuriti](https://github.com/jaswanthuriti)
