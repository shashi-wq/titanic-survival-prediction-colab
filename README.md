#  Titanic Survival Prediction (Google Colab)

##  Objective
The goal of this project is to **predict whether a passenger survived the Titanic disaster** using machine learning.  
This project demonstrates the complete data analysis and model-building process using the **Titanic dataset** in **Google Colab**.

---

##  Project Overview
The Titanic dataset is a classic introduction to data science and classification problems.  
This project includes:
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering and encoding  
- Model building with **Random Forest Classifier**  
- Model evaluation and explainability using **SHAP**

---

##  Tools & Libraries Used
- **Google Colab**
- **pandas**, **numpy**
- **matplotlib**, **seaborn**
- **scikit-learn**
- **shap**

---

##  Dataset
- **Dataset Name:** titanic.csv  
- **Source:** [Kaggle – Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)  
- **Target Variable:** `Survived` (1 = Survived, 0 = Not Survived)  
- **Main Features:** `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`

---

## 📊 Workflow

### Step 1: Data Cleaning
- Filled missing values in `Age` and `Embarked`
- Dropped column `Cabin` due to many missing values

### Step 2: Feature Encoding
- Converted `Sex` into numeric format using LabelEncoder  
- Applied one-hot encoding for `Embarked`

### Step 3: Model Training
- Algorithm used: **Random Forest Classifier**  
- Data split: 80% Training, 20% Testing  
- Scaled features using **StandardScaler**

### Step 4: Evaluation Metrics
- Accuracy Score  
- ROC-AUC Score  
- Confusion Matrix  
- Classification Report  

### Step 5: Model Explainability
- Used **SHAP (SHapley Additive Explanations)** to interpret model decisions  
- Generated feature importance plots  

---

## 📈 Key Insights
1. **Females** had a higher survival rate than males.  
2. **First-class passengers** had better survival chances than those in lower classes.  
3. **Younger** passengers were more likely to survive.  
4. The **Random Forest model** achieved around **82% accuracy**.

---
## 🗂️ Project Files
| File Name | Description |
|------------|-------------|
| `titanic.ipynb` | Google Colab notebook with full code |
| `titanic.csv` | Input dataset |
| `titanic_predictions.csv` | Model predictions (True vs Predicted) |
| `titanic_insights.txt` | Key findings and insights |
| `titanic_shap.png` | Global feature importance (SHAP) |
| `README.md` | Documentation file |

---

## 🚀 How to Run (Google Colab)
1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload the files: `titanic.ipynb` and `titanic.csv`.  
3. Run all cells sequentially.  
4. The following output files will download automatically:
   - `titanic_predictions.csv`
   - `titanic_insights.txt`
   - `titanic_shap.png`

---

## 📌 Results Summary
| Metric | Value |
|---------|--------|
| Accuracy | ~82% |
| ROC-AUC | ~0.84 |
| Key Predictors | Sex, Pclass, Age, Fare |

---

## 🏁 Conclusion
The **Titanic Survival Prediction** project successfully demonstrates how machine learning can be applied to a real-world dataset for classification tasks.  
The model identifies critical survival factors and provides interpretable insights using SHAP — making it both **accurate** and **explainable**.

---

## 👨‍💻 Author
**Shashidhar R**  
AI & Machine Learning | Data Analytics | Python   
