# Multiple Disease Prediction System

This Streamlit web application allows users to predict the likelihood of various diseases based on different health-related features. It includes models for predicting Diabetes, Heart Disease, Parkinson's Disease, Kidney Disease, and Breast Cancer.

## Models

- **Diabetes Model**: Loaded from 'C:/salman/ML/multi dicesae/diabetes.pkl'
- **Heart Disease Model**: Loaded from 'C:/salman/ML/multi dicesae/heart.joblb'
- **Parkinson's Model**: Loaded from 'C:/salman/ML/multi dicesae/Parkinson.joblib'
- **Kidney Disease Model**: Loaded from 'C:/salman/ML/multi dicesae/kidny.joblib'
- **Breast Cancer Model**: Loaded from 'C:/salman/ML/multi dicesae/breast.joblib'

## Project Structure

- **README.md**: Documentation of the project.
- **main.py**: Streamlit web application for making predictions.
- **models folder**: Contains the pre-trained machine learning models.

## Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd multi-disease-prediction-web-app

## Usage

-Clone this repository to your local machine.

-Ensure you have the pre-trained machine learning models in the 'models' folder.

-Open a command prompt or terminal and navigate to the directory where the script is located.

-Run the Streamlit web application:`streamlit run main.py`

-Select the disease prediction category from the sidebar and enter the required health-related features.
## Disease Prediction Pages
## Diabetes Prediction

-Input Features: Number of Pregnancies, Glucose Level, Blood Pressure, Skin Thickness, Insulin Level, BMI, Diabetes Pedigree Function, Age.

-Prediction Result: The person is diabetic or not.
## Heart Disease Prediction

-Input Features: Age, Sex, Chest Pain types, Resting Blood Pressure, Serum Cholestoral, Fasting Blood Sugar, Resting Electrocardiographic results, Maximum Heart Rate achieved, Exercise Induced Angina, and more.

-Prediction Result: The person has heart disease or not.
##  Parkinson's Disease Prediction
- Input Features: Various features related to voice characteristics (MDVP:Fo(Hz), MDVP:Fhi(Hz), MDVP:Flo(Hz), MDVP:Jitter(%), etc.).

-Prediction Result: The person has Parkinson's disease or not.
## Kidney Disease Prediction

-Input Features: Gravity, pH, Osmo, Cond, Urea, Calc, Diabetes Pedigree Function, Age.

-Prediction Result: The person is diagnosed with kidney disease or not.
## Breast Cancer Prediction

-Input Features: Features related to breast cancer diagnosis, including mean radius, mean texture, mean perimeter, and more.

-Prediction Result: The breast cancer is Malignant or Benign.
## Future Improvements
There are several ways to improve the models and the web application:

-Fine-tune hyperparameters for better model performance.

-Gather more labeled data for improved accuracy.
## References

-Author: [Mirza SLman]

-Contact: [salmansaluu661@gmail.com]
Feel free to customize this README to include any additional information you want to provide about the project.
