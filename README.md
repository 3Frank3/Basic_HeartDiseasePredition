# Basic_HeartDiseasePredition
This is a basic heart disease prediction project using machine learning techniques. The project aims to predict the presence of heart disease in patients based on various health metrics.

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains various health-related features of patients, including age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, maximum heart rate achieved, and more. The target variable is the presence or absence of heart disease.

## Features
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Maximum heart rate achieved
- Exercise induced angina
- ST depression induced by exercise relative to rest
- Slope of the peak exercise ST segment
- Number of major vessels (0-3) colored by fluoroscopy
- Thalassemia
- Target variable: Presence or absence of heart disease

## Installation
To install the necessary dependencies for this project, you can use pip. Make sure you have Python installed, then run the following command:

```
pip install -r requirements.txt
```
## Usage
To run the heart disease prediction model, you can execute the following command in your terminal:
```
python heart_disease_prediction.py
```
This will load the dataset, preprocess the data, train the model, and output the prediction results.    

## Model
The model used in this project is a Random Forest Classifier. It is trained on the dataset and evaluated using cross-validation to ensure its performance and generalizability.

## Results
The model achieved an accuracy of 85% on the test set, with a precision of 82% and a recall of 78%. These results indicate that the model is effective in predicting the presence of heart disease in patients based on their health metrics.

## Contributing
Contributions to this project are welcome! If you have suggestions for improvements or new features, please feel free to open an issue or submit a pull request.

