# 🤖 Machine Learning Models – Titanic, Telco, and Car Data

This project demonstrates my hands-on experience applying key machine learning algorithms across real-world datasets. 
Each section shows a different algorithm with a specific business goal, using well-known Python libraries like `scikit-learn`, `pandas`, and `matplotlib`.

---

## 📌 Algorithms

### 1. 🧼 Data Preprocessing (Titanic Dataset)
**Goal:** Clean and prepare Titanic data for modeling  
- Handled missing values (e.g., age, cabin)
- Converted categorical features to numbers (e.g., sex, embarked)
- Scaled numeric features  
✅ This step is critical before using any ML algorithm to improve accuracy and avoid bias.

---

### 2. 🔍 K-Means Clustering (Telco Dataset)
**Goal:** Segment telecom customers based on behavior  
- Applied K-Means to group customers with similar patterns
- Used Elbow Method to find the best number of clusters
- Visualized clusters using scatter plots  
📊 This is useful for customer segmentation and marketing and business strategies.

---

### 3. 📈 Linear Regression (Car Data)
**Goal:** Predict car prices based on features like Car age and mileage  
- Simple regression using car age vs. price
- Visualized price trends over time  
💡 Regression is ideal when predicting continuous values like prices or incomes.

---

### 4. 📊 Logistic Regression (Car Data)
**Goal:** Predict if a car is available for sale (`Yes` or `No`)  
- Binary classification model (0 = no, 1 = yes)
- Evaluated model using accuracy and confusion matrix  
🚨 Logistic Regression is widely used in fraud detection, email spam, and customer churn.

---

### 5. 👟 K-Nearest Neighbors (Car Data)
**Goal:** Classify car types based on features like fuel, engine, doors, etc.  
- Used KNN to find the most similar cars
- Classified unknown cars based on nearest neighbors  
🔍 KNN is simple yet powerful for small to mid-size datasets.

---

## 📁 Datasets Used

| Dataset       | Description |
|---------------|-------------|
| `titanic.csv` | Passenger survival data from the Titanic (binary classification) |
| `Telco.csv`   | Customer data from a telecom company (used for clustering) |
| `Car Data.csv`| Data about cars and prices (used for regression and classification) |

---

## ✅ Business Applications

| Algorithm        | Business Use Case |
|------------------|--------------------|
| Data Preprocessing | Data cleaning and preparation for any ML workflow |
| K-Means Clustering | Customer segmentation in telecom and banking industry |
| Linear Regression  | Pricing, forecasting, and sales trend analysis |
| Logistic Regression| Fraud detection, churn prediction, binary outcomes |
| KNN Classification | Recommendation systems, product categorization |

---
Created on Jupyter notebooks on my local MacOS system.
