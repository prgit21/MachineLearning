# Lung Cancer Prediction

This project predicts the likelihood of lung cancer based on various health and lifestyle attributes using machine learning models.

## Dataset
The dataset contains 309 entries with 16 features such as:
- **GENDER**
- **AGE**
- **SMOKING**
- **YELLOW_FINGERS**
- **ANXIETY**
- **PEER_PRESSURE**
- **CHRONIC DISEASE**
- **FATIGUE**
- **WHEEZING**
- **ALCOHOL CONSUMING**

## Models Used
1. **Random Forest Classifier**
   - An ensemble method that builds multiple decision trees and combines their results for robust classification.
   
2. **Support Vector Machine (SVM)**
   - A classification model well-suited for high-dimensional datasets, which attempts to maximize the margin between classes.

## Techniques
- **Data Preprocessing**: Cleaned and prepared the data for training and testing.
- **Cross-Validation**: Used to evaluate model performance.
- **Model Evaluation**: Performance metrics like accuracy, precision, recall, and AUC were used to compare the models.

## Key Outcomes
- The project compares the predictive power of Random Forest and SVM models to identify which performs better at classifying lung cancer cases.
  
## Libraries Used
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Usage
To run the notebook, load the dataset and execute the machine learning models to analyze the results.
