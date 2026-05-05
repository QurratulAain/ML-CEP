## Multiclass Weather Classification using Machine Learning

This project focuses on predicting weather conditions using machine learning techniques applied to structured hourly weather data. It addresses a multiclass classification problem by identifying the most frequent weather conditions such as *Partly Cloudy*, *Mostly Cloudy*, and *Overcast*.

The goal of the project is to analyze real-world weather data, apply multiple machine learning algorithms, and compare their performance in terms of accuracy, efficiency, and generalization.

---

##  Project Overview

The dataset consists of hourly environmental features such as temperature, humidity, wind speed, pressure, and visibility. After preprocessing and cleaning, the classification task was simplified by selecting the most frequent weather categories to reduce class imbalance and improve model performance.

The project involves:
- Data preprocessing and cleaning  
- Feature selection and scaling  
- Model training and evaluation  
- Comparative analysis of multiple algorithms  
- Real-time prediction using a trained model  

---

##  Data Preprocessing

Several preprocessing steps were applied:
- Removed missing values to ensure data consistency  
- Reduced classes to handle imbalance  
- Dropped irrelevant features (e.g., date, redundant text fields)  
- Encoded categorical labels using Label Encoding  
- Standardized numerical features using StandardScaler  

---

## Models Implemented

### Parametric Models
- Logistic Regression  
- Naive Bayes (GaussianNB)  

### Non-Parametric Models
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  

### Neural Network
- Multilayer Perceptron (MLP) using TensorFlow/Keras  

---

## Evaluation Metrics

Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC and Precision-Recall Curves  

---

## Key Results

- **Random Forest** showed the most balanced performance across all metrics.  
- **Neural Network (MLP)** achieved the highest accuracy but required more tuning and training time.  
- **Logistic Regression** and **Naive Bayes** were fast but limited in handling complex patterns.  
- **KNN** performance depended heavily on the choice of *k* and dataset size.  



##  Features

- Multiclass classification of weather conditions  
- Comparison of multiple ML algorithms  
- Data preprocessing pipeline  
- Visualization of model performance  
- Real-time prediction interface  


## Technologies Used

- Python  
- NumPy, Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib, Seaborn  
- Jupyter Notebook  

## Challenges

- Handling class imbalance in the dataset  
- Tuning hyperparameters for different models  
- Avoiding overfitting (especially in KNN and ANN)  
- Managing preprocessing consistency for prediction  

