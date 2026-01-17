# E-commerce Order Data Cleaning & Analysis

## Overview
This project analyzes large-scale e-commerce order data to identify **systemic drivers of order rejection and returns**.  
The focus is on transforming messy, ambiguous transactional data into **analysis-ready signals** that can support operational and product decisions.

The work mirrors real-world analytics problems: inconsistent schemas, missing values, and noisy status labels.

---

## Dataset
- ~129,000 e-commerce orders
- Mixed categorical and numerical fields
- Key challenges:
  - Ambiguous order status definitions
  - Missing and inconsistent values
  - Imbalanced outcomes (completed vs rejected / returned)

---

## Key Problems Addressed
- What factors are most strongly associated with **order rejection**?
- What patterns distinguish **returned orders** from successful ones?
- How much signal is lost if data quality issues are ignored?

---

## Approach

### 1. Data Cleaning & Preparation
- Standardized order status fields with inconsistent naming
- Handled missing and malformed values using rule-based logic
- Validated assumptions through controlled distribution checks

### 2. Feature Construction
- Engineered order-level features capturing:
  - fulfillment patterns
  - payment and logistics attributes
  - customer-level aggregation signals
- Ensured features were interpretable and business-relevant

### 3. Exploratory & Statistical Analysis
- Compared distributions across successful, rejected, and returned orders
- Used controlled comparisons to isolate high-confidence drivers
- Avoided black-box modeling in favor of explainable insights

---

## Key Insights
- Identified high-confidence factors correlated with order rejection
- Highlighted operational patterns linked to elevated return rates
- Demonstrated how schema ambiguity can mask or distort true drivers if not handled carefully

---

## Tools & Technologies
- Python (Pandas, NumPy)
- SQL-style querying and joins
- Exploratory data analysis
- Statistical validation

---

## Why This Project Matters
This project reflects **real production analytics work**:
- messy transactional data
- imperfect labels
- need for defensible, interpretable insights

It demonstrates the ability to move from raw data to decision-ready analysis without relying on overfitted models.

---

## Author
**Gagandeep Singh**  
MSc Physics (TIFR) | B.Tech (IIT Mandi)  
Aspiring Data Analyst / Product Analyst
