# README for Optimizing Smoking Cessation Strategies for Adults with Major Depressive Disorder

## **Project Overview**
This project evaluates the effectiveness of **Behavioral Activation for Smoking Cessation (BASC)** and **varenicline**, a pharmacological intervention, for adults with Major Depressive Disorder (MDD). Using data from a 2x2 randomized placebo-controlled trial of 300 participants, this analysis investigates key predictors of smoking abstinence at the end of treatment (EOT) and examines interactions between behavioral and pharmacological treatments. By identifying baseline factors that influence treatment outcomes, the study offers guidance for tailoring smoking cessation strategies for individuals with MDD.

---

## **Files Overview**
### **1. Main Report (Project2.pdf)**
- **Description**: A comprehensive document detailing the methodology, results, and conclusions of the study.
- **Sections**:
  - **Abstract**: Summary of the study’s goals, methodology, and findings.
  - **Introduction**: Overview of the challenges of smoking cessation for individuals with MDD.
  - **Methods**: Explanation of the trial design, data preparation, and modeling techniques.
  - **Results**: Key findings, including predictors of abstinence and treatment interactions.
  - **Limitations**: Discussion of constraints, such as sample size and short-term outcomes.
  - **Conclusion**: Summary of findings and implications for personalized smoking cessation interventions.
  - **Code Appendix**: Annotated R code for data preparation, analysis, and visualization.

---

### **2. Code Files**
- **R Code for Analysis**:
  - Implements **multiple imputation** to address missing data.
  - Uses **LASSO regression** for predictor selection and model building.
  - Evaluates model performance using ROC curves, calibration plots, and other metrics.

- **Sample Data (project2.csv)**:
  - Dataset containing baseline characteristics and trial results used in the analysis.

---

### **3. Key Visualizations**
The report includes several key visualizations:
- **ROC Curves**: Displays model performance on training and test sets (AUC = 0.703 on validation data).
- **Calibration Plots**: Assesses alignment between predicted probabilities and observed abstinence rates.
- **Correlation Matrix**: Shows relationships between continuous variables and smoking abstinence predictors.

---

## **Key Insights**
- **Baseline Predictors**:
  - Higher **nicotine dependence** (FTCD score) reduces the likelihood of abstinence.
  - The **Nicotine Metabolism Ratio (NMR)** positively correlates with abstinence rates.
  - Readiness to quit smoking enhances the efficacy of **Behavioral Activation (BASC)**.

- **Treatment Interactions**:
  - **Varenicline** combined with high nicotine dependence increases abstinence rates.
  - BASC is more effective for participants with greater readiness to quit smoking.

- **Model Performance**:
  - The LASSO model achieved an AUC of **0.703**, indicating reasonable discriminatory power.
  - Calibration results suggest moderate alignment between predicted probabilities and observed outcomes.

---

## **How to Reproduce the Analysis**
1. **Required Software**:
   - Install **R** with the following libraries: `ggplot2`, `dplyr`, `glmnet`, `caret`, `pROC`, `mice`, `kableExtra`.

2. **Steps**:
   - Load the dataset (`project2.csv`) into R.
   - Run the R scripts provided in the **Code Appendix** of the report.
   - Generate visualizations and evaluate model performance using the scripts.

---

## **Limitations**
- Small sample size (300 participants) limits generalizability.
- Reliance on self-reported measures (e.g., cigarettes smoked per day) introduces potential bias.
- The study focuses on **short-term abstinence** without accounting for long-term outcomes like relapse rates.

---

## **Contact**
For inquiries, reach out to **Morgan Cunningham** at [morgan_cunningham@brown.edu](mailto:morgan_cunningham@brown.edu).
