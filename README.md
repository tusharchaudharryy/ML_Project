# Student Marks Predictor - End to End Machine Learning Project

## Overview

This project aims to **predict student marks** based on various input features such as study hours and other academic factors using machine learning techniques. It is an end-to-end solution covering data preprocessing, model training, evaluation, and deployment via a web application interface.

The project leverages Python libraries and machine learning algorithms to provide accurate predictions that can help students and educators understand and improve academic performance.

---

## Features

- **Data Preprocessing:** Handles missing values, feature selection, and normalization.
- **Model Training:** Implements regression models (e.g., Linear Regression, Random Forest, CatBoost) to predict student marks.
- **Model Evaluation:** Uses metrics like R² score and accuracy to evaluate model performance.
- **Web Application:** A Flask-based interface to input student data and get predicted marks in real-time.
- **Deployment Ready:** Includes setup scripts and requirements for easy deployment.

---

## Project Structure

├── .ebextensions/ # AWS Elastic Beanstalk configuration files (if applicable)
├── artifacts/ # Saved models and artifacts
├── catboost_info/ # CatBoost model training info
├── notebook/ # Jupyter notebooks for exploratory data analysis and model development
├── src/ # Source code for data processing and model training
├── static/css/ # CSS files for web frontend styling
├── templates/ # HTML templates for Flask web app
├── application.py # Flask application entry point
├── requirements.txt # Python dependencies
├── setup.py # Setup script for installing the package
├── README.md # Project documentation
└── .gitignore # Git ignore rules

text

---

## Getting Started

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. **Clone the repository:**
git clone https://github.com/tusharchaudharryy/ML_Project_Student_Marks_Predictor.git
cd ML_Project_Student_Marks_Predictor

text

2. **Install the required dependencies:**
pip install -r requirements.txt

text

### Running the Application

1. **Start the Flask web server:**
python application.py

text

2. **Open your browser and navigate to:**
http://localhost:5000

text

3. **Use the web interface to input student data (e.g., study hours) and get predicted marks.**

---

## How It Works

1. **Data Collection:** Dataset includes student study hours and marks.
2. **Data Preprocessing:** Cleaning, handling missing data, and feature extraction.
3. **Model Training:** Various ML algorithms are trained (Linear Regression, Random Forest, CatBoost).
4. **Model Evaluation:** Models are evaluated on test data; the best performing model is selected.
5. **Prediction:** The trained model predicts student marks based on input features.
6. **Web Interface:** Flask app provides a user-friendly interface for predictions.

---

## Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- CatBoost
- Flask (for web app)
- HTML/CSS (frontend)
- Pandas, NumPy (data processing)
- Matplotlib/Seaborn (visualization)

---

## Future Enhancements

- Incorporate more features such as attendance, previous grades, and socio-economic factors.
- Improve model accuracy with larger and more diverse datasets.
- Add user authentication and admin dashboard for managing student data.
- Deploy the app on cloud platforms like AWS or Heroku for public access.

---

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, bug fixes, or new features.

---
