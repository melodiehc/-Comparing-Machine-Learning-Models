# Comparing Machine Learning Models

## What is This Project About?
This project aims to determine which machine learning model is most effective at predicting whether a person will sign up for a term deposit at a bank. The dataset originates from an English bank’s marketing campaigns conducted through phone calls. By testing six different machine learning models, we compare their performance to find the best predictor.

---

## The Data
The dataset, sourced from the UCI Machine Learning Repository, includes features such as:
- Age
- Job
- Education
- Marital Status
- Response to past campaigns

Our goal is to use these features to predict whether a person will say "yes" to signing up for a term deposit.

---

## What Are We Doing?
We implemented six machine learning models using Python:
1. **Logistic Regression (LR)**  
   Predicts categories rather than numbers, commonly used in fields like medicine and marketing.
2. **Naive Bayes (NB)**  
   A probabilistic model assuming feature independence; performs well for tasks like spam detection.
3. **K-Nearest Neighbors (KNN)**  
   Assigns categories based on the closest neighbors; simple but sensitive to noisy data.
4. **Decision Tree (DT)**  
   Splits data into branches based on features; interpretable but prone to overfitting.
5. **Random Forest (RF)**  
   A collection of decision trees that provides higher accuracy and less overfitting.
6. **XGBoost (XGB)**  
   A fast, accurate gradient boosting model popular in machine learning competitions.

We evaluated these models using metrics like:
- **Accuracy**
- **Precision**
- **Recall**
- **ROC-AUC scores**

---

## Steps We Followed
### 1. Preprocessing the Data
- Handled missing values and converted text categories to numeric representations.
- Normalized features to ensure all are on the same scale.

### 2. Visualization
- Created bar charts, histograms, and heatmaps to gain insights into the data.

### 3. Modeling
- Split the dataset into training and testing subsets.
- Trained each model and evaluated its performance.
- Compared results using metrics and ROC curves.

---

## What Did We Learn?
### Model Insights:
- **Logistic Regression (LR)** and **Naive Bayes (NB)**: Simple and interpretable but less effective for complex data.
- **KNN** and **Decision Tree (DT)**: Intuitive and flexible but may struggle with noisy or unbalanced data.
- **Random Forest (RF)** and **XGBoost (XGB)**: Most accurate models, capable of handling complex datasets effectively.

### Key Takeaway:
The choice of the best model depends on the specific problem and dataset. While **Random Forest** and **XGBoost** excelled in this project, simpler models like **Logistic Regression** are still valuable for their ease of interpretation.

---

## Conclusion
This project highlighted the importance of selecting the right machine learning model for a given task. By comparing six models, we observed their unique strengths and weaknesses. Random Forest and XGBoost emerged as the top performers for this dataset, but the simpler models remain essential tools for their transparency and simplicity.

This project was a hands-on opportunity to deepen our understanding of machine learning and model evaluation techniques.

---

## Author
CS-377 Melodie Cornelly - Project 2
