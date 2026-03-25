# Heart Disease Diagnostic Model

## Overview
This is a Machine Learning diagnostic model built to predict the probability of heart disease in patients based on 13 standard clinical biomarkers (such as Serum Cholesterol, Max Heart Rate, and ECG results). 

*This project is part of my Day One build-in-public journey, tracking my progress through Month 2 of my Machine Learning curriculum.*

## 🚀 The Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Logistic Regression, StandardScaler)
* **Environment:** Jupyter Notebook

## 📊 Model Performance
The model was trained on the Cleveland Clinical Heart Disease Dataset. To ensure clinical validity, 20% of the data was locked in a "holdout set" for blind testing.
* **Accuracy on Unseen Patients:** 85.24%

## 🧬 Clinical Biomarkers Analyzed
The model processes the following features to output a statistical probability:
1. Patient Age & Biological Sex
2. Chest Pain Type
3. Resting Blood Pressure
4. Serum Cholesterol
5. Fasting Blood Sugar
6. Resting ECG Results
7. Max Heart Rate Achieved
8. Exercise Induced Angina
9. ST Depression & Slope
10. Major Vessels Count
11. Thalassemia Status

## 💻 How to Use
1. Clone the repository.
2. Open the `.ipynb` file in Jupyter or Google Colab.
3. Run the cells in order.
4. Input custom patient data in the final inference cell to receive a live diagnostic probability.
