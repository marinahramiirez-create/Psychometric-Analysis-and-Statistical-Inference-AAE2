# Reliability Analysis and Item Assessment (AAE2)

![Analysis](https://img.shields.io/badge/Analysis-Reliability%20%7C%20Item%20Metrics-blue)
![Stats](https://img.shields.io/badge/Stats-Cronbach's%20Alpha-green)

## Project Overview
This project focuses on the **Reliability Analysis** and **Item Calibration** of a 12item psychometric instrument. Using a sample of **N=245**, the objective was to evaluate the internal consistency and the individual contribution of each item to the overall scale quality.

## Methodology
The analysis followed the Classical Test Theory (CTT) framework:
1. **Descriptive Statistics:** Calculation of means, standard deviations, and distribution (Skewness and Kurtosis).
2. **Reliability:** Estimation of Internal Consistency via **Cronbach's Alpha**.
3. **Item-Total Correlation:** Evaluation of the discrimination power of each item.
4. **"Alpha if Item Deleted":** Sensitivity analysis to optimize the scale.

## Dataset Description
| File | Description |
| :--- | :--- |
| `DATOS ESTUDIO 1 AAE2.csv` | Raw scores for the initial 12-item scale. |
| `DATOS ESTUDIO 2 AAE2.csv` | Comparative dataset for cross validation. |

---

## Key Results

### 1. Global Reliability
* **Cronbach's Alpha:** The scale achieved a coefficient of **.882**, indicating high internal consistency.
* **Standardized Alpha:** **.884**, suggesting that the items have similar variances and consistent metric properties.

### 2. Item Analysis (Item-Total Correlation)
The analysis identified the contribution of each item to the construct:
* **Best Performing Items:** Items 4 ($r = .653$) and 7 ($r = .642$) showed the highest corrected item total correlations.
* **Consistency:** All items maintained correlations above the critical threshold (>.30), confirming they all contribute significantly to the measured dimension.

### 3. Sensitivity Analysis
* Removing any item did not significantly increase the global Alpha (all "Alpha if deleted" values remained around **.86 - .87**), which confirms a robust and well-balanced pool of items.

## Conclusions
1. **Instrument Precision:** With an $\alpha = .882$, the instrument is highly reliable for both research and clinical application.
2. **Homogeneity:** The items show high inter item correlation, proving they successfully capture the same latent construct.
3. **Quality Assurance:** No items required elimination during this phase, validating the preliminary content work done in AAE1.

---

## Technical Stack
* **Software:** R (Librería `psych`) / SPSS.
* **Statistical Indices:** Mean, SD, Skewness, Corrected Item-Total Correlation, Cronbach's Alpha.
