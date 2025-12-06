# Phishing-email-detection_OCC3
Detecting phishing emails using a public dataset and basic text analysis

---
###  Team
- Chloé MIGAUD
- Dan'ella Sara Océane SOSSOU
- Aya TEGUIA

---

### Goal
Create a simple model to detect phishing emails using text analysis.  
The project includes data exploration, cleaning, preprocessing, and a first baseline model.

We then improved the initial solution by testing different algorithms, tuning hyperparameters, and comparing their performance.
The goal is to understand which model works best for this task and how machine learning can help identify phishing attempts more effectively.

---

### Dataset
- **Source:** [Kaggle – Phishing Email Dataset](https://www.kaggle.com/datasets/subhajournal/phishingemails)  
- Each email is labeled as *Safe* or *Phishing*
The model predicts the correct class based on the email text.

---

### Project Overview
In this project, we cleaned the dataset and prepared the email text for machine learning.
We used TF-IDF to turn the text into numbers, then tested several models to detect phishing emails.

Overall, the models performed well, especially Logistic Regression, which gave high accuracy and recall.

---

### Results
All models reached over 95% accuracy.
The best model was the optimized Logistic Regression, with an F1-score of ~0.96.

--- 

### How to run
1. Clone or download the repository
2. Open the files in Jupyter Notebook
3. Run all the cells to see the analysis and model results
