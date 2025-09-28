# PRODIGY_DS_03
# 🧠 Task-03: Decision Tree Classifier – Breast Cancer Dataset  

## 📌 Overview  
This project implements a **Decision Tree Classifier** to predict whether a tumor is **malignant** or **benign** using the **Breast Cancer dataset**. The model is built with **scikit-learn** and evaluated using common classification metrics.  

The dataset is publicly available in `sklearn.datasets` and is widely used for benchmarking classification algorithms.  

---

## 📂 Dataset  
- **Name**: Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Source**: [Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)  
- **Target Classes**:  
  - `0`: Malignant  
  - `1`: Benign  

---

## ⚙️ Steps Performed  
1. **Importing Libraries & Dataset**  
   - Loaded Breast Cancer dataset using `sklearn.datasets`.  
2. **Exploratory Data Analysis (EDA)**  
   - Explored features, distribution of target variable, and correlations.  
3. **Data Preprocessing**  
   - Standardized features using `StandardScaler`.  
4. **Model Building**  
   - Implemented a **Decision Tree Classifier** using `sklearn.tree.DecisionTreeClassifier`.  
5. **Model Evaluation**  
   - Evaluated using **accuracy score, confusion matrix, and classification report**.  
6. **Visualization**  
   - Plotted the Decision Tree for better interpretability.  

---

## 📊 Results  
- The Decision Tree model achieved high accuracy on the Breast Cancer dataset.  
- Key insights:  
  - Tree visualization helps interpret how decisions are made.  
  - Certain features (e.g., mean radius, mean texture, worst perimeter) strongly influence predictions.  

---

## 🛠️ Technologies Used  
- **Python** 🐍  
- **Pandas & NumPy** – Data Handling  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning  

---

## 📌 Future Improvements

Tune hyperparameters using GridSearchCV.
Compare Decision Tree with Random Forest, SVM, and Logistic Regression.
Deploy the model with Streamlit/Flask for user interaction.
