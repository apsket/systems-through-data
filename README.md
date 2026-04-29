# Data & Systems Analysis Portfolio

## Overview

This portfolio explores how complex systems can be understood through data by combining:

- Modeling assumptions and representation
- Causal reasoning for decision-making
- Time-dependent dynamics under uncertainty
- Interaction between internal behavior and external environments

Rather than focusing solely on predictive performance, these projects emphasize **how conclusions are formed**, **what assumptions are made**, and **how insights translate into decisions**.

---

## Core Themes

### 1. Representation & Inductive Bias
How the structure of features and models determines what can be learned from data.

### 2. Causality & Decision-Making
Distinguishing correlation from actionable relationships in observational settings.

### 3. System Dynamics
Understanding how behavior evolves over time in noisy and non-stationary environments.

### 4. Macro ↔ Micro Interaction
Analyzing how external conditions influence internal system behavior.

---

## Projects

### 1. Representation vs Model Complexity  
**Focus:** Feature engineering vs model flexibility

- Compared linear and non-linear models on non-linearly separable data
- Designed geometric feature transformations (e.g., polar coordinates)
- Showed how appropriate representations allow simple models to match complex ones
- Explored trade-offs between interpretability, robustness, and flexibility

**Key Insight:**  
Model performance is often driven more by **representation choice** than by model complexity.

---

### 2. Causal Analysis of E-commerce Behavior (Olist Dataset)  
**Focus:** Observational data → decision-oriented insights

- Investigated the effect of delivery delays on customer satisfaction
- Compared naive estimates vs adjusted models (regression / matching)
- Identified and analyzed confounding factors (location, product type, pricing)
- Evaluated robustness of observed relationships

**Key Insight:**  
Observed correlations can overstate effects; careful adjustment is required before drawing conclusions.

**Extension:**  
Results are used to propose a structured A/B test to validate the effect in a controlled setting.

---

### 3. Market Dynamics Analysis (Binance Data)  
**Focus:** Time series behavior under uncertainty

- Analyzed price and volume dynamics in cryptocurrency markets
- Explored volatility clustering, regime shifts, and non-stationarity
- Evaluated limitations of standard modeling assumptions in financial data
- Investigated signal vs noise in short-term market behavior

**Key Insight:**  
Financial systems exhibit **non-stationary and regime-dependent behavior**, limiting the reliability of static models.

---

### 4. E-commerce Behavior under Macro Conditions  
**Focus:** External drivers of system behavior

- Combined e-commerce data with macroeconomic indicators
- Explored how demand patterns shift with external conditions
- Analyzed sensitivity of internal metrics to broader economic signals
- Investigated multi-level dependencies in real-world systems

**Key Insight:**  
System behavior cannot be fully understood without accounting for **external context and constraints**.

---

## Approach

Across projects, the workflow emphasizes:

1. **Problem Structuring**  
   Clearly defining what is being measured and why

2. **Assumption Awareness**  
   Identifying what is implicitly assumed in each method

3. **Comparative Analysis**  
   Evaluating multiple approaches rather than relying on a single model

4. **Interpretability**  
   Prioritizing explanations over raw performance metrics

5. **Decision Relevance**  
   Translating results into actionable insights or experimental proposals

---

## Technical Stack

- **Programming:** Python (pandas, numpy, scikit-learn, statsmodels)  
- **Data Handling:** SQL, APIs, ETL workflows  
- **Visualization:** matplotlib, Power BI
- **Systems:** AWS, Docker, Kubernetes
- **Other:** Experimental design, statistical modeling, numerical methods  

---

## Notes

- Projects prioritize clarity and reasoning over scale or complexity
- Many analyses are based on observational data and include explicit discussion of limitations
- Emphasis is placed on **reproducibility and structured experimentation**

---

## Contact

- GitHub: https://github.com/apsket  
- LinkedIn: https://www.linkedin.com/in/albertopinedas  
