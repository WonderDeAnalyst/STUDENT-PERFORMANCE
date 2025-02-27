# Student Performance Prediction System

## Overview
The **Student Performance Prediction System** is a machine learning project designed to predict students' overall academic performance based on multiple influencing factors. This system utilizes various machine learning algorithms, including:

- **GGBoost**
- **Random Forest**
- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Artificial Neural Networks (ANNs)**

The model is deployed using **Streamlit** and the trained models are saved as **pickle** files for future use.

## Features
The system uses various features to predict student performance, including:
- **CGPA**
- **Study Habits**
- **Class Participation**
- **External Influences**
- **Hours Spent Studying** (Categorical values processed correctly)

## Model Performance
The model was trained and evaluated using multiple techniques to ensure high accuracy. The best-performing model achieved an accuracy of **89%**.

## Installation
To run this project locally, follow these steps:

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required libraries (listed in `requirements.txt`)

### Clone the Repository
```sh
git clone [https://github.com/WonderDeAnalyst/STUDENT-PERFORMANCE.git]
cd student-performance-prediction
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Run the Application
```sh
streamlit run app.py
```

## Model Training
To train the models, run:
```sh
python train_model.py
```
This script processes the data, trains the models, and saves them as pickle files.

## Deployment
The model will be deployed using **Streamlit** for an interactive web-based user interface. Simply run `streamlit run app.py` to launch the application.

## Repository Structure
```
student-performance-prediction/
│-- data/
│   ├── student_performance.csv  # Raw dataset
│-- models/
│   ├── student_performance_model.pkl  # Saved model

│-- app.py  # Streamlit app
│-- requirements.txt  # Dependencies
│-- README.md  # Project documentation
```

## Future Improvements
- Improve feature engineering for better accuracy.
- Optimize hyperparameters for each model.
- Implement deep learning techniques (ANN) which had a low predictive score and later unused since the GGboost and Logistic Regression gave us a best fit.

## Contributors
- **Wonder Paul** 
- **https://github.com/grace2709**



## Acknowledgments
- Inspired by various academic performance prediction research studies.
- Thanks to open-source contributors and libraries that made this project possible.
