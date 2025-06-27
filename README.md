# 🏠 Home Credit - Score Card Model

## 📊 Project Description
This project is the final assignment of Ibnu Richo Kurniawan in the field of Data Science. The goal is to help Home Credit expand financial inclusion by predicting the payment ability of prospective clients, especially those who do not have a credit history. This project uses alternative data to develop an accurate credit score model.

## 🧠 Background of the Problem
Many individuals have difficulty getting loans due to a lack of credit history. Home Credit seeks to address this by providing a safe and positive lending experience using a data-driven approach.

## 📁 Dataset
- **Train Data:** 307,511 rows, 122 columns
- **Test Data:** 48,744 rows, 121 columns

## 🛠️ Steps Taken
1. **Data Cleaning & EDA**
2. **Model Building**
3. **Model Evaluation**
4. **Business Insight**
5. **Business Recommendations**

## 📈 Machine Learning Model Used

| Algorithm | Training Accuracy | Testing Accuracy | Error Margin | ROC AUC Score |
|------------------------|------------------|------------------|--------------|----------------|
| Logistic Regression | 67.21% | 67.15% | 0.06% | 0.6715 |
| Gaussian Naive Bayes | 59.91% | 60.10% | 0.19% | 0.6008 || Decision Tree | 100% | 85.32% | 14.68% | 0.8532 |
| Random Forest | 100% | 99.69% | 0.31% | 0.9969 |

✅ **Conclusion:** The **Random Forest** model was chosen because it produced the best performance without overfitting/underfitting.

## 🔍 Key Insights
- Clients aged 35–45 years are less likely to have payment difficulties.
- **Student** and **Manager** clients have a high application pass rate.
- Clients on **Maternity leave** or **Unemployed** face challenges with **Cash loans**, but not with **Revolving loans**.

## 📌 Business Recommendations
- Focus on targets: students, accountants, highly skilled technical staff, and managers.

- Further review of loan contracts for **maternity leave** and **unemployed** clients.
- Education and segmentation of loan products according to job type and financial status.

## ⭐ Key Features
- Car ownership
- Credit activity
- Price of goods
- House area
- Job position
- Length of employment
- Age at application
- City rating
- Last phone number change

## 🔗 Links
- 📂 [GitHub Repository](https://github.com/IbnuRicho/HOME-CREDIT-Final-Task-Data-Scientist)
- 💼 [LinkedIn](https://www.linkedin.com/in/ibnurichokurniawan/)

---

> 🧠 *"With data, we empower financial inclusion and fair credit decisions."*
