# 📊 Insurance Risk Analysis & Premium Optimization
### *Data-Driven Pricing Strategy & Risk Segmentation*

---

## 🎯 Objective
The objective of this project is to analyze health and lifestyle risk factors to design a **data-driven insurance premium pricing model**. By simulating how insurance providers adjust premiums based on customer risk profiles, this project creates a transparent, rule-based framework for actuarial analysis.

---

## 📌 Dataset Overview
The analysis is based on a dataset of **10,000 records** featuring key health and lifestyle attributes:
*   **Smoking Status:** Current, Former, or Never.
*   **Alcohol Consumption:** Heavy, Moderate, or None.
*   **Physiological Markers:** Systolic Blood Pressure levels.
*   **Genetic Factors:** Diabetes Family History.

---

## 🔍 Key Observations & Risk Drivers

### 1. 🚬 Smoking Behavior
*   **High Risk:** Current smokers represent the most significant risk segment.
*   **Residual Risk:** Former smokers show moderate risk due to potential long-term health effects.
*   **Impact:** Justifies substantial premium loading to cover increased morbidity probability.

### 2. 🍺 Alcohol Consumption
*   **Heavy Consumption:** Strongly correlates with elevated health risks.
*   **Moderate Consumption:** Shows lower but non-negligible risk factors.
*   **Impact:** Acts as a primary lifestyle-driven variable in the pricing engine.

### 3. ❤️ Blood Pressure (BP)
*   **Critical Indicator:** High BP individuals form a major high-risk category.
*   **Correlation:** A direct linear relationship is observed between rising BP levels and premium surcharges.

### 4. 🧬 Diabetes (Family History)
*   **Predictive Risk:** Individuals with a family history show an elevated probability of future complications.
*   **Impact:** Influences pricing even in the absence of current illness, accounting for future liability.

---

## 💰 Premium Pricing Methodology

### **The Base Model**
*   **Base Premium:** ₹5,000 (Standardized starting point for low-risk individuals).
*   **Final Premium Calculation:** `Base Premium + Risk Additions`

### **Risk-Based Adjustments (Surcharges)**
| Category | Condition | Surcharge | Additional Terms |
| :--- | :--- | :--- | :--- |
| **Smoking** | Current Smoker | **+25% (₹1,250)** | — |
| | Former Smoker | **+10% (₹500)** | Waiting Period Applied |
| **Alcohol** | Heavy | **+25% (₹1,250)** | — |
| | Moderate | **+10% (₹500)** | — |
| **Diabetes** | Family History | **+15% (₹750)** | **2-Year Waiting Period** |
| **Blood Pressure** | High BP | **+20% (₹1,000)** | — |

---

## 📈 Model Results
*   **Minimum Premium:** ₹5,000
*   **Maximum Premium:** ₹9,250
*   **Average Premium:** ~₹6,988
*   **Max Increase:** High-risk individuals experience up to an **85% increase** over the base rate.

> **Key Insight:** Customers with combined risks (High BP + Smoking + Diabetes History) demonstrate the most volatile premium variance, highlighting the necessity of **multi-factor evaluation**.

---

## 🚀 Business Value
This model demonstrates how modern insurers can:
*   Implement **Dynamic Risk-Based Pricing** strategies.
*   Improve **Customer Segmentation** for targeted policy offerings.
*   Reduce **Underwriting Uncertainty** through data-backed logic.
*   Design **Transparent Systems** that are easily interpretable by stakeholders.

---

## 🔮 Future Enhancements
*   **Machine Learning:** Integrate predictive risk scoring via Random Forest or XGBoost.
*   **Real-Time Tool:** Build a web-based premium calculator for instant quotes.
*   **Feature Expansion:** Incorporate BMI, Cholesterol levels, and Age demographics.
*   **Actuarial Accuracy:** Align surcharges with real-world mortality/morbidity tables.

---

## ✅ Conclusion
This project showcases a professional approach to insurance pricing, blending **Exploratory Data Analysis (EDA)** with **Business Intelligence**. The result is a scalable and interpretable framework that aligns lifestyle data with financial risk.

**Author:** Parjanya Vasisht  
*A project by PV Labs*
