# 🚨 Suspicious Transaction Detection Using AWS ML & Data Pipeline

This project showcases a low-code, cloud-native machine learning pipeline to detect potentially fraudulent financial transactions using AWS. 
It simulates how a financial institution or regulatory body could automate anomaly detection on a high-volume banking dataset.

---

## 🎯 Project Goal

To build a secure and scalable pipeline that:
- Ingests and cleans raw banking transaction data
- Trains a fraud classification model
- Visualizes suspicious activities
- Supports automation and explainability all in the AWS Cloud

---

## 🛠️ AWS Tools & Services Used

| Tool / Service      | Purpose                            |
|---------------------|-------------------------------------|
| **Amazon S3**        | Store raw and cleaned transaction data |
| **AWS Glue / DataBrew** | Clean and transform data (ETL)         |
| **SageMaker Autopilot** | Train low-code fraud classification model |
| **Amazon QuickSight** | Visualize anomalies and predictions |

---

## 🗂️ Dataset

**Source**: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- About 284,000 transactions
- Features: Time, Amount, V1–V28 (PCA-transformed), Class (1 = fraud, 0 = not fraud)

---

## 🧪 **AWS Steps Summary** 

### Step 1: Upload Data to Amazon S3
Uploaded `creditcard.csv` to S3 as the raw input dataset.

### Step 2: Cleaned Data with AWS Glue DataBrew
- Imported the dataset from S3
- Verified data types and structure
- Exported cleaned data to a new S3 location

### Step 3: Trained a Model with SageMaker Autopilot
- Used **Autopilot** via SageMaker Canvas (low-code)
- Target column: `Class` (fraud label)
- Automatically tuned and evaluated multiple model candidates

### Step 4: Reviewed Model Results in Canvas
- **F1 Score**: High Score
- **Precision**: High Score
- **Recall**: High Score

### Step 5: Exported & Visualized in QuickSight
- Exported prediction results and feature importance
- Created interactive QuickSight dashboard for insights

---

## ✅ Outcome & Value

- ⚡ Built a fraud detection pipeline with zero ML code
- 📊 Visualized insights to support compliance teams
- 🔐 Used only AWS-native, free-tier eligible tools
- 🌐 Ready for real-world use by banks, auditors, and intelligence teams

---

## 📂 Files Included

| File / Folder                      | Description |
|-----------------------------------|-------------|
| `AWS-ML-Cloud.pdf`                | Project presentation |
| `AWS-ML-Cloud.pdf`                | Project presentation PDF |
| `README.md`                       | This project overview |

---

## 📘 Summary

> I built a machine learning model using **Amazon SageMaker Autopilot** to classify fraudulent credit card transactions from real-world-like data.
> With no coding required, the pipeline uses **S3, Glue, and QuickSight** to demonstrate a practical, scalable solution for financial intelligence.
> 
> My model achieved an very high F1 Score, showing strong performance in identifying fraud patterns.
> This project highlights my capability to design and implement cloud-native ML workflows for regulatory or risk-focused environments.

---

👨‍💻 Created by Niall Cleur on my AWS Personal Account.
