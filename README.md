# Heart disease prediction

# **Performance Analysis of Machine Learning Models for Heart Disease**  

## **Overview**  
This project analyzes the performance of various machine learning models in predicting heart disease. Given the high mortality rate associated with heart disease, early prediction can significantly improve patient outcomes. The study uses multiple classification models to determine the most effective one for heart disease prediction.  

## **Dataset**  
- **Source:** Kaggle  
- **Number of Samples:** 270  
- **Features (14):** Age, Sex, Chest Pain Type, FBS Over 120, EKG Results, Max HR, Exercise Angina, ST Depression, Slope of ST, Number of Vessels Fluro, Thallium, and Heart Disease.  
- **Target Classes:**  
  - **Presence (1):** 151 samples  
  - **Absence (0):** 119 samples  

## **Methodology**  
1. **Data Collection** – Acquired dataset from Kaggle.  
2. **Data Preprocessing** – Standardization, handling missing values, encoding categorical variables.  
3. **Feature Selection** – Used heat maps and feature importance.  
4. **Feature Extraction** – Principal Component Analysis (PCA) was applied to reduce dimensions.  
5. **Model Training** – Implemented various machine learning models.  

## **Machine Learning Models Used**  
- Support Vector Machine (SVM)  
- Naïve Bayes  
- Decision Tree  
- Random Forest  
- Linear Regression  

## **Results**  
| Model                 | Accuracy  | Recall  | Precision |  
|-----------------------|-----------|---------|-----------|  
| **SVM**               | 74.07%    | 69%     | 93%       |  
| **Naïve Bayes**       | 87%       | 87%     | 90%       |  
| **Decision Tree**     | 72.2%     | 82%     | 62%       |  
| **Random Forest**     | **87.03%  | 82%     | 93%       |  
| **Linear Regression** | 52.06%    | 45%     | 65%       |  

## **Conclusion**  
The **Random Forest** model achieved the highest accuracy of **87.03%**, making it the most effective model for heart disease prediction in this study. Further work includes improving model accuracy with larger datasets and deploying it in real-world healthcare systems.  


