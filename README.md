# DEGO-project_team50
A/B test for Digital Experimentation course – Group 50, TXB
Benefit Plans Landing Page
This repository contains the analysis of an A/B test evaluating a redesigned version of the **Benefit Plans landing page**.
The objective of the experiment is to assess whether the redesigned page improves user engagement and navigation clarity compared to the original version.

## Dataset
The dataset (`TXB_50_landingpage(in).csv`) contains user-level interaction data collected during the experiment.  
Users are randomly assigned to two groups:
- **Control**: original landing page
- **Treatment**: redesigned landing page

## Key Metrics
The analysis evaluates the following KPIs:
- **Plan CTR (kpi_y)** – primary conversion metric
- **Simulation Interaction Proxy (kpi_x)** – engagement indicator
- **Scroll Depth (%)** – exploration of page content
- **Exit Rate** – guardrail metric measuring early exits

## Analysis Workflow
The notebook performs the following steps:
1. Data loading and inspection
2. KPI computation and descriptive comparison
3. Statistical hypothesis testing
4. Power analysis
5. Visualization of metric differences
6. Interpretation of results

## Main Result
The analysis does not find statistically significant differences between the control and treatment versions for the evaluated KPIs.  
Additionally, the power analysis indicates that the experiment is underpowered to detect small effects with the current sample size.


