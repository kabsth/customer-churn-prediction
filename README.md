
# Customer Churn Prediction

## Project Overview
This project uses Machine Learning to predict whether a customer is likely to leave a telecommunications company.

It includes data exploration, preprocessing, model training, evaluation, and an interactive Streamlit web application.

## Dataset
IBM Telco Customer Churn Dataset.

## Machine Learning Models
- Logistic Regression
- Random Forest
- XGBoost

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Streamlit

## Project Structure
- data/: Raw and processed datasets
- notebooks/: Data analysis and model development
- models/: Saved machine learning pipeline
- app.py: Streamlit application
- requirements.txt: Project dependencies

## Run Locally

Clone the repository:

    git clone https://github.com/kabsth/customer-churn-prediction.git

Move into the project:

    cd customer-churn-prediction

Create a virtual environment:

    python -m venv venv

Activate it on macOS:

    source venv/bin/activate

Install dependencies:

    pip install -r requirements.txt

Run the application:

    streamlit run app.py

## Model Evaluation
The project compares multiple classification models using:
- Accuracy
- Precision
- Recall
- F1-score
