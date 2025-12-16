# A/B Test Analysis: Website Button Color Experiment

## 📌 Project Overview
This project analyzes the results of an A/B test conducted by a product team to determine whether a new website button color improves user sign-up rates.

Using statistical hypothesis testing, the analysis provides a clear **Go / No-Go recommendation** based on data, while communicating results in simple, business-friendly language suitable for non-technical stakeholders.

---

## 🎯 Business Scenario
The product team tested a new button color against the existing one:
- **Control Group:** Existing button color
- **Test Group:** New button color

Users were randomly assigned to one of the two groups, and sign-up behavior was recorded.

---

## 🧠 Objective
- Determine whether the new button color leads to a **statistically significant increase** in sign-up rates
- Apply statistical rigor using a **5% significance level (α = 0.05)**
- Communicate findings clearly to support product decision-making

---

## 🧪 Methodology
The analysis follows these steps:

1. **Hypothesis Formulation**
   - Null Hypothesis (H₀): No difference in conversion rates
   - Alternative Hypothesis (H₁): A difference exists between groups

2. **Data Quality Checks**
   - Missing values
   - Data types and structure

3. **Exploratory Analysis**
   - Conversion rates per group
   - Absolute uplift calculation

4. **Statistical Testing**
   - Z-test for proportions
   - 95% confidence intervals for conversion rates

5. **Decision Framework**
   - p-value < 0.05 → **GO**
   - p-value ≥ 0.05 → **NO-GO**

---

## 📊 Key Metrics
- Conversion Rate (Control vs Test)
- Absolute Uplift
- Z-statistic
- p-value
- Confidence Intervals

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Jupyter Notebook

---

## 📁 Project Structure
