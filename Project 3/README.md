# README for Simulation Study: Optimal Design for Cluster Randomized Trials

## Project Overview
This project investigates the optimal design of cluster randomized trials (CRTs) under budget constraints. The study evaluates the effects of varying the number of clusters (e.g., hospitals) and the number of observations per cluster (e.g., patients) on the estimation of treatment effects. The project considers two scenarios:
- **Normal Outcomes**: Continuous data with constant variance.
- **Poisson Outcomes**: Count data with mean-dependent variance.

Key objectives include analyzing bias, variance, and cost efficiency to identify optimal resource allocation strategies in CRTs.

---

## Files Overview

### **1. Main Document (2550Project3.pdf)**
- **Description**: Comprehensive report detailing the methodology, results, and conclusions of the simulation study.
- **Sections**:
  - Abstract: Summary of the study's goals, methods, and findings.
  - Aims of the Study: Defines the objectives and scope.
  - Data-Generating Mechanisms: Explains the hierarchical models used for normal and Poisson outcomes.
  - Estimands: Describes key parameters like treatment effects and variability components.
  - Methods: Details the simulation process and model fitting techniques.
  - Performance Measures: Lists metrics like bias, variance, and cost utilization.
  - Normal Outcome & Poisson Outcome: Results and discussions for each outcome type.
  - Conclusion: Summary of findings and design recommendations.
  - Code Appendix: Annotated R code for simulating data and evaluating designs.

### **2. Simulation Results (Included in Code Appendix)**
- Outputs from simulations, including:
  - Mean bias and variance as functions of design parameters.
  - Trade-offs between cluster size and observation count under budget constraints.
  - Cost and variability impacts on optimal designs.

### **3. Visualizations**
- Heatmaps and line plots illustrating:
  - Bias and variance for normal and Poisson outcomes.
  - Effects of cluster-level and patient-level variability on design efficiency.
  - Cost efficiency across different designs.

---

## Key Insights
- Increasing the number of clusters reduces variance more effectively than increasing the number of observations per cluster.
- Poisson outcomes require careful consideration of mean-variance relationships and cost structures.
- Balancing cluster recruitment and within-cluster observations is critical for efficient resource use.

This project provides actionable guidance for designing cost-efficient CRTs with high precision and reduced bias. For more details, refer to the report or the code appendix for implementation specifics.
