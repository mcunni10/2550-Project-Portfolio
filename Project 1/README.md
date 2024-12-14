# Effects of Age, Gender, and Environmental Factors on Marathon Performance

### **Overview**
This project investigates how age, gender, and environmental factors (e.g., temperature, humidity, wind, and air quality) affect marathon performance. Specifically, it examines performance trends across age groups, gender-based differences, and the influence of adverse weather conditions, with a focus on the Wet Bulb Globe Temperature (WBGT) and its flag categories indicating heat risk levels.

---

### **Project Objectives**
1. **Assess the effects of age on marathon performance**, analyzing differences by gender and age group.
2. **Explore the impact of environmental factors**, such as temperature, humidity, and air quality, on marathon finish times.
3. **Evaluate interactions between demographic variables and environmental conditions**, identifying which factors most significantly influence marathon outcomes.
4. **Investigate the significance of WBGT flag categories** on performance, determining the effect of heat stress.

---

### **Dataset**
The dataset combines marathon results and environmental data from five major U.S. marathons (Boston, Chicago, New York, Twin Cities, Grandma's) between 1993 and 2016. Key variables include:
- **Finish Time**: Marathon completion time in seconds.
- **Age and Gender**: Runner demographics.
- **Environmental Factors**: Dry bulb temperature, wet bulb temperature, WBGT, humidity, wind speed, solar radiation, and air quality index (AQI).
- **WBGT Flag Categories**: Heat risk levels (White, Green, Yellow, Red, Black).

---

### **Methods**
- **Descriptive Analysis**: Summary statistics by race, age group, and gender.
- **Polynomial Regression Models**: Investigating non-linear relationships between age and marathon finish time, stratified by gender.
- **Multiple Regression Analysis**: Assessing the influence of environmental factors on performance, with interaction terms for age and gender.
- **ANOVA and Tukey’s Test**: Testing differences in performance across WBGT flag categories.
- **Data Visualization**: Using R for plots of performance trends and environmental correlations.

---

### **Key Findings**
- **Age and Gender**:
  - Marathon times increase with age, with peak performance between ages 20–30.
  - Men outperform women across all age groups, though both experience sharp performance declines after age 40.
- **Environmental Factors**:
  - WBGT is the most significant environmental determinant, with higher values strongly correlating with slower times.
  - Poor air quality (higher AQI) negatively impacts performance.
  - Wind speeds improve outcomes, possibly due to cooling effects.
- **WBGT Flag Categories**:
  - Green flag conditions (low heat risk) correspond to the best performance.
  - Performance worsens under Yellow and Red flag conditions, though variability exists.

---

### **Files**
- **`Project1.pdf`**: Final project report detailing the analysis, visualizations, and conclusions.
- **`final_marathon_df.csv`**: Cleaned dataset used for the analysis.
- **R Markdown Files**: Scripts for data processing, analysis, and visualization.
- **`Table1Summary.png`**: PNG of Table 1 Summary Statistics due to the final report pdf not knitting table correctly.
- **`Table2Summary.png`**: PNG of Table 2 Summary Statistics due to the final report pdf not knitting table correctly.

---

### **How to Reproduce the Analysis**
1. **Required Software**: Install R with the following libraries:
   - `ggplot2`
   - `dplyr`
   - `readr`
   - `car`
   - `corrplot`
   - `broom`
2. **Steps**:
   - Load the dataset (`final_marathon_df.csv`) into R.
   - Open the provided R Markdown file to run the analysis and generate visualizations.
   - Adjust paths in the script to match your working directory.

---

### **Acknowledgments**
This project was conducted in collaboration with Dr. Brett Romano Ely and Dr. Matthew Ely, Department of Health Sciences, Providence College. Their expertise and guidance were instrumental in shaping the analysis.

---

### **Contact**
For questions or collaboration, contact **Morgan Cunningham** at [morgan_cunningham@brown.edu](mailto:morgan_cunningham@brown.edu).

