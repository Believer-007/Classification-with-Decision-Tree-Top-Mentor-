# Decision Tree Classifier – iPhone Purchase Prediction

This repository contains a **Decision Tree Classification model** built using the `iphone_purchase_records.csv` dataset. The model predicts whether a customer will purchase an iPhone based on demographic and financial factors.

---

##  **Project Overview**

This project demonstrates:
- Exploratory Data Analysis (EDA)
- Feature transformation & encoding
- Train–test split
- Decision Tree model creation
- Model evaluation using accuracy, confusion matrix & classification report

This repository is suitable for **beginners and intermediate ML practitioners** who want to understand how classical ML models work on structured data.

---

##  **Dataset Description**

**Columns:**
- `Gender` – Male/Female
- `Age` – Age of the customer
- `Salary` – Annual salary
- `Purchase` – Target variable (0 = No, 1 = Yes)

**Target Variable:**  
`Purchase` (Categorical – binary)

---

##  **Exploratory Data Analysis (EDA)**

Key findings from the dataset:

### **1. Gender Distribution**
- Balanced distribution of male and female customers.

### **2. Age Distribution**
- Age is normally distributed with customer clusters around mid-age groups.

### **3. Salary Distribution**
- Wide salary range.  
- Useful for modeling income-based purchase decisions.

---

##  **Tools & Technologies Used**

### **Languages & Libraries**
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  

### **Algorithms**
- Decision Tree Classifier

### **Techniques**
- Label Encoding  
- Train–Test Split  
- Confusion Matrix  
- Classification Report  

---

##  **Modeling Approach**

### ✔ 1. **Data Preprocessing**
- Converted categorical `Gender` column to numeric (Male=0, Female=1)
- Split dataset into `X` and `y`
- Performed 75:25 train–test split

### ✔ 2. **Model Creation**
```python
model = DecisionTreeClassifier()
model.fit(X_train, y_train)
```

### ✔ 3. **Predictions & Evaluation**
- Achieved strong prediction score using:
  - **Accuracy Score**
  - **Confusion Matrix**
  - **Classification Report**

---

##  **Insights Gathered**

- **Age and Salary strongly influence iPhone purchase decisions.**
- Individuals with **higher salary** show a greater tendency to purchase an iPhone.
- Gender has **minimal impact**, indicating that purchase behavior is income-driven.
- Decision Trees offer clear interpretability for marketing insights.

---

##  **Use Cases**

###  **1. Marketing & Advertising**
- Segment customers based on likelihood to purchase.
- Optimize digital ad targeting.

###  **2. Retail Sales**
- Predict potential buyers.
- Personalize offers or discounts.

###  **3. Business Strategy**
- Understand customer demographics influencing high-value phone purchases.

---

##  **Relevant Keywords for the Repository**

`Decision Tree`  
`Classification Model`  
`iPhone Purchase Prediction`  
`Supervised Learning`  
`Machine Learning EDA`  
`Customer Segmentation`  
`Python Scikit-learn`  
`ML Classification Project`  
`Business Analytics`  

---

##  **Conclusion**

This project demonstrates how Decision Tree models can be used for **binary classification tasks** such as purchase prediction. It highlights how demographic and income features influence consumer decisions.

