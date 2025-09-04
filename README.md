# Task 03 - Decision Tree Classifier (Bank Marketing Dataset)

**Internship:** Data Science Internship at SkillCraft Technology  
**Intern:** Ishika Arora  

## 🎯 Objective
The goal of this task is to build a **Decision Tree Classifier** to predict whether a customer will purchase a product/service (term deposit) based on their **demographic and behavioral data**.

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)  
- Files:  
  - `bank.csv` → smaller dataset (~4,521 rows)  
  - `bank-full.csv` → full dataset (~45,211 rows)  
- Due to size, dataset files are **not uploaded to this repo**. Please download them from the above link.

## ⚙️ Approach
1. **Data Preprocessing**
   - Encoded categorical variables using one-hot encoding.  
   - Converted target variable `y` into binary (yes=1, no=0).  

2. **Model Training**
   - Built a **Decision Tree Classifier** using `scikit-learn`.  
   - Limited tree depth (`max_depth=4`) to avoid overfitting.  

3. **Model Evaluation**
   - Accuracy score  
   - Precision, Recall, F1-score (Classification Report)  
   - Confusion Matrix Heatmap  

4. **Visualization**
   - Plotted the decision tree to interpret decision rules.  

