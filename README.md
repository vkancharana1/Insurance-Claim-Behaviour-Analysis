## 📊 From Data to Decision: Predictive Claim Risk Modeling

## Project Overview

This project builds a **data-driven risk assessment system** to identify **high-risk insurance policies** with a low probability of claims.
The goal is **early risk detection and prioritization**, not automated decision-making.

---

## Short Description

Using **machine learning classification models**, this project predicts which policies are more likely to file claims in a **highly imbalanced dataset (2.4% claim rate)**.
The models support **underwriting review, claims triage, and portfolio risk management**.

---

## Technology / Tools Used

* **Python**
* Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `imbalanced-learn`
* Techniques:

  * Logistic Regression
  * Random Forest
  * SMOTE (Synthetic Minority Oversampling)
  * Precision–Recall analysis
  * Feature importance & model diagnostics

---

## Key Features

* Real-world **imbalanced classification problem**
* Business-oriented evaluation beyond accuracy
* Recall-focused modeling for rare events
* Side-by-side comparison of models with different trade-offs
* Actionable risk insights for underwriting and claims teams

---

## Project Process

1. **Problem Framing**
   Identified the challenge of detecting rare claim events (~2.4% of policies).
2. **Data Exploration & Feature Engineering**
   Analyzed policy structure, coverage, buyer/seller attributes, and historical claims.
3. **Class Imbalance Handling**
   Applied **SMOTE** to balance training data and improve learning.
4. **Model Development**

   * Logistic Regression (high recall)
   * Random Forest (better precision trade-off)
5. **Model Evaluation**
   Focused on **Recall, Precision, F1-Score**, and confusion matrices instead of accuracy.
6. **Business Interpretation**
   Converted predictions into **risk-based recommendations**.

---

## What I Learned

* Why **accuracy is misleading** for rare-event prediction
* How to design models for **decision support**, not automation
* Trade-offs between **recall and precision** in risk systems
* Practical application of **SMOTE** and PR-based metrics
* Translating ML outputs into **business-ready insights**

---

## How This Project Can Be Improved

* Introduce **cost-sensitive learning**
* Add **time-based validation** to detect model drift
* Calibrate probability thresholds using financial cost functions
* Expand to **real-time scoring pipelines**

---

## Running This Project

### 1. Clone the Repository

* Clone the repository to your local machine

### 2. Open the Project

* Open the folder in **VS Code / Jupyter Notebook**
* Install required Python libraries

### 3. Run the Main Notebook

* Execute the notebook top-to-bottom
* All preprocessing, modeling, and evaluation steps will run automatically

