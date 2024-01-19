

PROJECT REPORT LINK : https://github.com/MAmouzouvi/Heart-disease-predictor/blob/main/group10_project_report.ipynb

Heart Disease Prediction

1.1 - Introduction

Heart disease and its effective diagnosis is a global health challenge. In this proposal, we aim to address diagnosing heart diseases using machine learning techniques. We will attempt to detect the presence of heart disease in patients by leveraging a heart disease dataset obtained from Kaggle.

Data Selection and Justification

While the original dataset from Kaggle comprises 16 variables, we have strategically chosen 6 variables based on their clinically established correlation with heart disease. By focusing on a subset of six variables, we aim to create a model that is both efficient and effective, avoiding the complexity and potential overfitting associated with using a larger number of variables.

Patient ID (id): This identifier is used to track individual patient data.

Age (age): Age is a well-known risk factor for heart disease. Older individuals have a higher risk, making this variable crucial for our model.

Resting Blood Pressure (trestbps): High blood pressure is a known risk factor for heart disease. It can lead to hardening and thickening of the arteries, increasing heart disease risk.

Serum Cholesterol (chol): High cholesterol levels can lead to atherosclerosis, increasing heart disease risk.

Maximum Heart Rate (thalch): Lower maximum heart rate during exercise is associated with a higher risk of heart disease.

Heart Disease (presence): This variable, indicating the degree of blockages in major vessels, is a direct measure of heart disease. In the initial dataset, the diagnosis (num) ranges from 0 (no presence) to 4. However, we have compressed it into two categories:

P (present): < 50% diameter narrowing, indicating significant heart disease.
A (absent): > 50% diameter narrowing, indicating no significant heart disease.
The decision to compress the "num" column (or presence in our study) into two classes (P and A) stems from the need for a clear, binary classification for our KNN classification model. This simplification also addresses potential issues with ambiguous labels in the dataset —allowing us to effectively train our model to distinguish only between two crucial states of heart diseases (present or absent).

Project Goal:

Can a K-nearest neighbors (KNN) classification effectively diagnose heart disease using age, resting blood pressure, cholesterol levels, and maximum heart rate as predictors?

This approach aims to provide a simplified yet accurate tool for early heart disease diagnosis, potentially aiding in prompt treatment and management.



