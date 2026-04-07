# 📊 Insurance Risk Analysis & Premium Optimization

## 🎯 Objective

The objective of this project is to analyze health and lifestyle risk factors and design a **data-driven insurance premium pricing model**.

The goal is to simulate how insurance providers can adjust premiums based on customer risk profiles using interpretable rules.

---

## 📌 Dataset Overview

The dataset consists of **10,000 records** with attributes related to customer health and lifestyle, including:

* Smoking Status
* Alcohol Consumption
* Blood Pressure Levels
* Diabetes Family History

These variables were used to assess risk and design premium adjustments.

---

## 🔍 Key Observations

### 1. Smoking Behavior

* Current smokers represent a high-risk segment
* Former smokers show moderate risk due to potential long-term effects

-> Smoking significantly increases health risk and justifies premium loading.

---

### 2. Alcohol Consumption

* Heavy alcohol consumption correlates with higher health risks
* Moderate consumption shows relatively lower but non-negligible risk

-> Alcohol acts as a lifestyle-driven risk factor influencing premiums.

---

### 3. Blood Pressure (BP)

* High BP individuals form a major high-risk category
* Strong correlation observed between BP levels and premium increase

-> BP is one of the most critical medical indicators in risk assessment.

---

### 4. Diabetes (Family History)

* Individuals with family history show elevated probability of future complications

-> Even without current illness, **predictive risk** impacts pricing.

---

## 💰 Premium Pricing Assumptions & Methodology

### Base Premium

A base premium of **₹5000** was assumed as a standardized starting point.

This represents the cost for a low-risk individual before applying any adjustments.

---

### Pricing Logic Design

Based on general insurance practices and reference materials:

* Premiums are adjusted using **percentage-based loadings**
* Risk severity determines magnitude of increase
* Certain conditions introduce **waiting periods** in addition to price changes

---

### Risk-Based Adjustments

#### 🚬 Smoking

* Current smoker → +25% (₹1250)
* Former smoker → +10% (₹500) + waiting period

---

#### 🍺 Alcohol Consumption

* Heavy → +25% (₹1250)
* Moderate → +10% (₹500)
* None → No additional cost

---

#### 🧬 Diabetes (Family History)

* +15% (₹750)
* Additional **waiting period of 2 years**

---

#### ❤️ Blood Pressure

* High BP → +20% (₹1000)
* Normal → No additional cost

---

## 📈 Premium Model

Final Premium is calculated as:

Final Premium = Base Premium + Risk Additions

Where:

* Base Premium = ₹5000
* Risk additions depend on individual profile

---

## 📊 Results

* Minimum Premium: ₹5,000
* Maximum Premium: ₹9,250
* Average Premium: ~₹6,988

👉 High-risk individuals can experience up to **85% increase over base premium**

---

## 💡 Key Insight

Customers with **high BP, smoking habits, and diabetes history** demonstrate significantly higher risk profiles.

* Lifestyle factors (smoking, alcohol) strongly influence premium variation
* Medical indicators (BP, diabetes) further amplify risk
* Combined risks lead to substantial premium increases

👉 This highlights the importance of **multi-factor risk evaluation** in insurance pricing.

---

## 🚀 Business Value

This model demonstrates how insurers can:

* Implement **risk-based pricing strategies**
* Improve **customer segmentation**
* Reduce underwriting uncertainty
* Design transparent and interpretable pricing systems

---

## 🔮 Future Enhancements

* Integrate machine learning for predictive risk scoring
* Use real-world insurance datasets
* Build a real-time premium calculator application
* Incorporate additional factors (BMI, cholesterol, age)

---

## ✅ Conclusion

This project showcases a **data-driven approach to insurance pricing**, combining:

* Exploratory data analysis
* Business-oriented thinking
* Rule-based modeling

The result is a scalable and interpretable premium optimization framework aligned with real-world insurance practices.
