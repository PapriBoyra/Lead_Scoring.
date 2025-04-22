# 🔍 Lead Scoring Model for X Education

## 🧠 Problem Overview
X Education, an ed-tech company, aims to improve its **lead-to-sale conversion rate**, which currently hovers around 30%. They want to identify the most promising leads (called **Hot Leads**) to prioritize sales team efforts and boost conversion rates toward a target of 80%.

This project builds a **logistic regression model** that:
- Assigns a **lead score (0–100)** to each lead
- Helps sales teams target leads most likely to convert
- Supports business decision-making with clear, interpretable insights

---

## 📊 Dataset Summary
- ~9,000 leads
- Binary target variable: `Converted` (1 = converted, 0 = not converted)
- Includes features such as:
  - Lead Source
  - Total Time Spent on Website
  - Last Activity
  - Total Visits
  - Specializations
  - What is your current occupation?
  - Tags and other categorical indicators

⚠️ Note: Some categorical variables have a "Select" option that behaves like missing values and must be cleaned.

---

## 🛠️ Project Deliverables

### 1. **Python Jupyter Notebook (.ipynb)**
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Model building using Logistic Regression
- Model evaluation using metrics like accuracy, precision, recall, F1-score, ROC-AUC
- Assigning lead scores

### 2. **Word Document (.docx)**
- Answers to business questions and case-specific scenarios provided by the company

### 3. **Presentation (.pdf)**
- Business-friendly visualization of findings
- Summary of model performance
- Actionable insights for business stakeholders

### 4. **Summary Report (.pdf)**
- ~500-word summary of methodology, learnings, and recommendations

---

## 🧪 Model Evaluation Metrics
- **Accuracy**
- **Precision, Recall, F1-Score**
- **ROC-AUC Score**
- **Confusion Matrix**

---

## 📈 Key Results
- The model can help X Education increase efficiency by focusing only on high-potential leads.
- Logistic regression provides a balance between **interpretability** and **performance**.
- Lead scores enable **threshold-based decision making**.

---
