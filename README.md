# Project-Title-Diabetes-Prediction-using-Machine-Learning-with-GUI
Project Title: Diabetes Prediction using  Machine Learning (with GUI

Project Description:   
This project demonstrates how to build a machine learning 
model to predict disease progression in diabetes patients using 
the Scikit-Learn diabetes datase . 
It includes: 
Data loading and preprocessing 
Model training (Linear Regression) 
Evaluation (MSE and R² score) 
A simple Graphical User Interface (GUI) built with Tkinter that 
allows users to input feature values and get predictions 
interactively.


 
Step 1: Import Libraries 
We import all the necessary Python libraries for data analysis, 
model training, and GUI creation . 
Step 2: Load the Diabetes Dataset 
We use the built-in load_diabetes() dataset from scikit-learn . 
It includes 442 samples and 10 numerical features (e.g., age, 
BMI, blood pressure) . 
Step 3: Convert Data to DataFrame 
We convert the dataset into a pandas DataFrame for easy data 
manipulation and analysis . 
Step 4: Split Data 
We divide the dataset into : 
Training data (80%) — used to train the model . 
Testing data (20%) — used to evaluate model performance . 
Step 5: Train the Model 
We create a Linear Regression model and train it using the 
training data . 
Step 6: Evaluate the Model 
We calculate : 
Mean Squared Error (MSE) — measures prediction error . 
R² Score — measures how well the model fits the data (closer 
to 1 means better) . 
 
 
Step 7: Build the GUI 
Using Tkinter, we create a simple window with text fields for all 
10 features . 
When the user inputs values and clicks "Predict", the model 
makes a prediction and shows the result in a message box . 
�
�  . Example Output 
Console Output : GUI Window: 
Title: "🔮 Diabetes Prediction System " 
entry fields for features : 
age, sex, bmi, bp, s1, s2, s3, s4, s5, s6 
Button: “🔍 Predict Now ” 
A popup appears showing: 
Predicted disease progression value: 163.42
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e04bcecd-c49c-45c8-8886-abb643f76c9e" />
Summary: 
Component Description 
Dataset Scikit-learn’s Diabetes dataset 
Algorithm Linear Regression 
Interface Tkinter GUI 
Evaluation Metrics MSE and R² Score 
Purpose Predict diabetes disease progression based on 10 
medical features

✅ Model trained successfully . 
R² Score: 0.45 
Mean Squared Error: 2859.69
