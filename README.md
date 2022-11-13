# Project: Diabetes Prediction Using ML
### Project Intro/Objective 

The purpose of this project is to predict whether a person is suffering from Diabetes or not on the basis of his/her input data. The prediction has been done by using Machine Learning (ML) classification algorithm.

### Install

This project requires **Python** and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- Seaborn
- scikit-learn

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, you can install the Anaconda distribution of Python, which already has the above packages and more included. 

### Code

Code is provided in the `Diabetes_Prediction.ipynb` notebook file. You will also be required to use the `diabetes.csv` dataset file to complete your work.

### Run

In a terminal or command window, navigate to the top-level project directory `Diabetes-Prediction-ML/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Diabetes_Prediction.ipynb
```  
or
```bash
jupyter notebook Diabetes_Prediction.ipynb
```
or open with Jupyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The diabetes dataset consists of 768 data points, with each datapoint having 8 features. This dataset is Pima Indians Diabetes Database found on the kaggle.

**Features**
1. `Pregnancies`: Number of times pregnant
2. `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. `BloodPressure`: Diastolic blood pressure (mm Hg)
4. `SkinThickness`: Triceps skin fold thickness (mm)
5. `Insulin`: 2-Hour serum insulin (mu U/ml)
6. `BMI`: Body mass index (weight in kg/(height in m)^2)
7. `DiabetesPedigreeFunction`: Diabetes pedigree function
8. `Age`: Age (years)

**Target Variable**
9. `Outcome`: Class variable (0 or 1) 268 of 768 are 1, the others are 0