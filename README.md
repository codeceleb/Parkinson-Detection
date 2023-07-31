# Parkinson's Disease Prediction using Support Vector Machine (SVM)
This project is a Python-based application that uses a Support Vector Machine (SVM) model to predict Parkinson's disease based on certain measurements. The application loads data from a CSV file, preprocesses it, trains the SVM model, and then makes predictions.

## Requirements
To use this application, you need:

Python (>=3.6)
pandas
scikit-learn (sklearn)
You can install the required packages using pip:
code:
pip install numpy pandas scikit-learn

## How to Use the Application

1.Clone the Repository:
First, clone this repository to your local machine: code 
git clone https://github.com/your-username/parkinsons-prediction.git
cd parkinsons-prediction
Prepare the Data:

2.Ensure you have the 'parkinsons.csv' file in the same directory as the Python script.
The CSV file contains the data required for training and testing the model.
Run the Application:

3.Open the Python script (e.g., 'parkinsons_prediction.py') in a Python environment, such as an Integrated Development Environment (IDE) or a text editor. Then, execute the script.

4.Interpreting the Results:

The application will load the data from 'parkinsons.csv', split it into training and testing sets, and standardize the features.
The SVM model will be trained on the training data, and its accuracy on both training and test data will be displayed.
After the model is trained, the application will predict whether a person has Parkinson's disease or not based on the provided input data.
Note: The input data is provided as a tuple representing various measurements. The application will predict if the person has Parkinson's disease or not based on these measurements.

5.Understanding the Prediction:
  -If the output of the prediction is '0', it means that the person does not have Parkinson's disease.
  -If the output of the prediction is '1', it means that the person has Parkinson's disease.

## Important Information
The predictions made by the model are based on the input data and the patterns it has learned from the training data. However, it is essential to consult a qualified healthcare professional for a proper medical diagnosis.
This application serves as a demonstration of how machine learning models can assist in identifying potential cases of Parkinson's disease. It should not be considered a substitute for medical advice or diagnosis.

## Conclusion
This application demonstrates the use of a Support Vector Machine (SVM) model to predict Parkinson's disease based on measurements from the 'parkinsons.csv' dataset. By following the instructions above, you can run the application and explore its functionality.

If you have any questions or encounter any issues, feel free to reach out to the project developers for assistance.

Thank you for your interest in the Parkinson's Disease Prediction project. Stay healthy and take care!


