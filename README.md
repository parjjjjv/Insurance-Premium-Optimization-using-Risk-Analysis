# 🏥 Insurance Premium Optimization & Risk Analysis
### *Data-Driven Dynamic Pricing Model for Healthcare Insurance*

---

## 📌 Project Overview
Traditional insurance pricing often relies on broad demographics. This project utilizes a comprehensive health and lifestyle dataset to propose a **Risk-Based Premium Pricing Model**. By analyzing specific physiological markers and lifestyle choices, I have simulated a system where premiums are adjusted dynamically to reflect the true risk profile of the insured.

## 📊 The Pricing Logic
The model starts with a **Base Premium of ₹5,000** and applies incremental surcharges based on the following risk factors:

| Risk Factor | Additional Surcharge | Logic / Condition |
| :--- | :--- | :--- |
| **Smoking** | + ₹1,250 (max) | 25% for Current / 10% for Former (+2y waiting) |
| **Alcohol** | + ₹1,250 (max) | 25% for Heavy / 10% for Moderate |
| **Diabetes History** | + ₹750 | 15% surcharge for positive family history |
| **Blood Pressure** | + ₹1,000 | 20% surcharge for High Systolic levels |

> **Calculated Premium Range:** ₹5,000 – ₹9,250

---

## 📈 Key Insights & Risk Segmentation
* **Compounding Risks:** Customers exhibiting a "Triple Threat" (Smoking + Heavy Alcohol + High BP) see an **85% increase** in premiums compared to the base.
* **Lifestyle Impact:** Modifiable factors like smoking and alcohol are the primary drivers of premium volatility, contributing up to ₹2,500 of the total cost.
* **Cohort Analysis:** Analyzed a base of **5,070 citizens** to identify the most common high-risk segments across demographics.

---

## 🛠 Tech Stack & Methodology
* **Tableau:** Interactive data storytelling, quadrant analysis, and parameter-driven dashboards.
* **Excel / CSV:** Data cleaning and initial feature engineering for risk categories.
* **Business Intelligence:** Developed custom calculated fields in Tableau to simulate the dynamic pricing engine.

---

## 🖥 Dashboard Features
The interactive Tableau dashboard allows for deep-dive analysis through four key quadrants:
1. **Genetic Risk:** Pie chart representing family history of diabetes.
2. **Consumption Patterns:** Tree map for alcohol and Donut chart for smoking status.
3. **Physiological Data:** Bar chart tracking Systolic BP across the patient base.
4. **Dynamic Filtering:** Cross-filtering enabled to see how specific habits (e.g., Heavy Alcohol) correlate with physiological markers (e.g., BP levels).

---

## 🚀 Future Roadmap
* **Predictive Modeling:** Implement Machine Learning (Random Forest) to predict the probability of chronic illness.
* **Web Integration:** Build a web app for real-time premium calculation based on user input.
* **Actuarial Expansion:** Integrate real-world mortality and morbidity tables for higher financial accuracy.

---

## 👤 Author
**Parjanya Vasisht**  
www.linkedin.com/in/parjanya-vasisht-08a06b31b

---
