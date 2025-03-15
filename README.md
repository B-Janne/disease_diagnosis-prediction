# Disease Outcome Prediction  

## 📌 Overview  
This project focuses on predicting patient diagnosis outcomes (**Positive/Negative**) for a specific disease based on patient profiles. Various machine learning models are trained and evaluated to enhance predictive accuracy.  

## 🏥 Dataset  
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/uom190346a/disease-symptoms-and-patient-profile-dataset). It contains patient profiles along with diagnostic results for various diseases. It includes:  

- **Demographic details**: Age, Gender  
- **Health indicators**: Blood Pressure, Cholesterol Level  
- **Symptoms**: Fever, Cough, Fatigue, Difficulty Breathing  
- **Disease category**: Indicating the specific disease being assessed  
- **Outcome Variable**: Positive/Negative diagnosis for that disease  

## 🔍 Data Preprocessing  
- **Handling Missing Values**: Not required for this dataset but essential in real-world scenarios
- **Encoding**: Label Encoding applied to categorical variables  
- **Scaling**: Numerical features normalized  
- **Train-Test Split**: Data is split into training and test sets  

## 🚀 Models Trained  
The following models were trained and evaluated:  

- **Logistic Regression**  
- **Random Forest**  
- **Gradient Boosting**
- **XGBoost**
- **Support Vector Machine (SVM)**   

## 📊 Model Evaluation Metrics  
Each model is evaluated using:  

- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1 Score**  
- **AUC-ROC Score**  
