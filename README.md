# Algorithmic Audit: Measuring COMPAS Against Google's AI Principles

## 📋 Project Overview

This project presents an interactive Tableau dashboard that evaluates the COMPAS recidivism algorithm for racial bias using multiple fairness metrics, providing data-driven recommendations based on **Google's AI Principles**.

---

## 🎯 Problem Statement

The COMPAS (Correctional Offender Management Profiling for Alternative Sanctions) algorithm has been widely used in the U.S. criminal justice system to predict defendants' risk of recidivism. However, investigations have raised serious concerns about racial bias in its predictions, potentially leading to unfair sentencing decisions and perpetuating systemic inequalities.

---

## 🚀 Objective

Create an interactive audit dashboard that:

* Evaluates COMPAS for racial bias using multiple fairness metrics
* Examines disparities in False Positive Rates between racial groups
* Analyzes whether disparities hold when controlling for prior arrests
* Explores the trade-off between False Positive Rate and False Negative Rate
* Provides a data-driven recommendation based on Google's AI Principles

---

## 🛠️ Tools & Technologies Used

* **Tableau Desktop:** For creating interactive visualizations and dashboard
* **Python / R:** For initial data analysis and preprocessing (optional)
* **Git / GitHub:** For version control and project hosting
* **COMPAS dataset:** From ProPublica's analysis (`compas-scores-two-years.csv`)

---

## 📊 Methodology & Process

### Data Acquisition & Preparation

* Sourced data from ProPublica's GitHub repository
* Performed data cleaning and validation
* Created calculated fields for fairness metrics:

  * High Risk Flag (dynamic threshold)
  * False Positive / False Negative indicators
  * True Positive / True Negative indicators
  * False Positive Rate (FPR)
  * False Negative Rate (FNR)
  * Total Error Rate

### Analysis Approach

1. **Demographic Overview:** Established context of the dataset
2. **Bias Identification:** Measured disparity in FPR between racial groups
3. **Control Analysis:** Examined if disparities persist when controlling for prior arrests
4. **Trade-off Analysis:** Explored relationship between FPR and FNR across groups
5. **Threshold Simulation:** Created dynamic parameter to test different risk thresholds

---

## Google's AI Principles Evaluation

Evaluated COMPAS against these key principles:

* Be socially beneficial
* Avoid creating or reinforcing unfair bias
* Be built and tested for safety
* Be accountable to people
* Incorporate privacy design principles
* Uphold high standards of scientific excellence
* Be made available for uses that accord with these principles

---

## 📈 Results & Business Impact

### Key Findings

* Significant disparity in False Positive Rates between racial groups
* African-American defendants were almost twice as likely to be falsely labeled high risk compared to white defendants
* Disparities persisted even when controlling for prior arrests
* No risk threshold eliminated the racial disparity in error rates

### Business Impact

* **Criminal Justice System:** Highlights need for reform in risk assessment tools
* **Policy Makers:** Provides evidence for regulatory oversight of algorithms
* **Technology Companies:** Demonstrates methodology for algorithmic auditing
* **Civil Rights Organizations:** Offers data-driven support for advocacy efforts

---

## ✅ Actionable Recommendations

### Immediate Actions

* Suspend use of COMPAS for sentencing decisions
* Implement third-party algorithmic audits for all criminal justice algorithms
* Establish transparency requirements for risk assessment tools

### Medium-Term Solutions

* Develop alternative algorithms with fairness constraints
* Create standardized evaluation frameworks for justice algorithms
* Implement ongoing bias testing and monitoring systems

### Long-Term Initiatives

* Establish regulatory bodies for algorithmic oversight
* Develop industry-wide standards for algorithmic fairness
* Invest in research on fair machine learning techniques

---

## 📂 Data & Reproducibility

* **Dataset:** `compas-scores-two-years.csv` (ProPublica)
* **Analysis scripts:** Include Python or R notebooks for data cleaning, metric calculations, and threshold simulations (optional)
* **Tableau workbook:** Interactive dashboard with parameterized thresholds and filters for subgroup analysis

---

