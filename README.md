# Diabetes Prediction Model and Analysis

This repository contains a dataset related to diabetes, along with a diabetes prediction notebook that provides insights into the dataset.

## Dataset Information

The dataset used in this analysis is the "Pima Indians Diabetes Database," one of the most famous datasets in machine learning and data analysis. It originates from the National Institute of Diabetes and Digestive and Kidney Diseases. The primary objective of this dataset is to predict, based on diagnostic measurements, whether a patient has diabetes or not. The dataset consists of 768 samples and 9 attributes.

### Dataset Columns

1. **Pregnancies**: Number of times a patient has been pregnant.
2. **Glucose**: Blood sugar level after consuming glucose (measured in mg/dL).
3. **BloodPressure**: Resting blood pressure in the arteries (mm Hg).
4. **SkinThickness**: Skinfold thickness on the triceps (mm).
5. **Insulin**: Insulin level in the patient's blood after a 2-hour period (µU/mL).
6. **BMI**: Body Mass Index, a measure of body fat based on height and weight.
7. **DiabetesPedigreeFunction**: Likelihood of having diabetes based on family history.
8. **Age**: Age of the patient in years.
9. **Outcome**: Indicates whether the patient has diabetes (1) or not (0).

## Notebook

The notebook in this repository explores the diabetes dataset in depth. It performs statistical analysis, visualizations, and data preprocessing to uncover relationships and insights. The notebook provides a step-by-step walkthrough of the analysis.

### Diabetes Prediction Model

I have developed a diabetes prediction model using machine learning algorithm, which achieved an accuracy of 77 percent. The model takes measurements as input and predicts whether a patient has diabetes.

## Key Findings

From the analysis, several key findings have been made:

1. **Pregnancies**: The number of pregnancies alone does not significantly contribute to the diagnosis of diabetes.

2. **Glucose**: After consuming glucose, a normal blood sugar level is generally below 140 mg/dL.

3. **BloodPressure**: The normal range for blood pressure when the heart is at rest is typically below 120 mmHg.

4. **SkinThickness**: The normal range for skinfold thickness on the triceps is less than 25 mm.

5. **Insulin**: After a 2-hour period, normal insulin levels are generally below 30 µU/mL.

6. **BMI**: The normal range of BMI is 18.5 to 30. People with a BMI greater than 30 are considered obese, which is a contributing factor to diabetes.

7. Higher levels of **Glucose**, **BMI**, and **DiabetesPedigreeFunction** significantly increase the possibility of having diabetes.

This analysis provides valuable insights into the dataset and contributes to our understanding of the factors associated with diabetes.
