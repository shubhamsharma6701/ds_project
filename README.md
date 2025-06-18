# Student Math Score Prediction
This project predicts student math scores based on various parameters using machine learning regression and classification models. Additionally, it features a Flask web application to interactively predict and classify math scores.

## Project Overview
Use machine learning models to predict math scores.

Classify student performance into categories.

Deploy a Flask app for easy user interaction.

## Dataset
Includes features like gender, parental education, test preparation, lunch type, and scores in math, reading, and writing.

## Machine Learning Models
Regression: Linear Regression, Decision Tree Regressor, Random Forest Regressor

Classification: Logistic Regression, Decision Tree Classifier, Random Forest Classifier

## Installation & Setup

Clone the repo:
```
git clone https://github.com/yourusername/math-score-prediction.git
cd math-score-prediction
Create and activate a virtual environment:
```
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install dependencies:

```
pip install -r requirements.txt
```

## Running the Flask App
Start the Flask web app by running:
```
python app.py
```
By default, the app will be accessible at http://127.0.0.1:5000.

Features
Input student parameters via web form.

Predict the math score using regression models.

Classify student performance into categories (e.g., low, medium, high).

View prediction results instantly on the web interface.

## Usage
Open the browser and go to the URL above.

Fill in the required student information fields.

Submit to get the predicted math score and classification.

## Evaluation Metric - R2 Score
