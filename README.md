# PHP2550_Project3

## Title
Optimizing Study Designs for Cluster Randomized Trials under Budget Constraints: A Simulation Study

## Abstract
Cluster randomized trials pose unique challenges in balancing cost and study design, particularly under budget constraints. This study investigates optimal combinations of clusters and within-cluster observations for estimating treatment effects. Using simulations, we evaluate designs with outcomes following normal and Poisson distributions. The model parameters and costs-related parameters are systematically varied. Our results demonstrate that when the data come from normal distribution, the optimal design is likely to take a large value of the number of clusters with fewer observations. If data come from poisson distribution, the optimal number of clusters tends to be evenly distributed in its possible range. However, the interdependence of parameters complicates straightforward recommendations.  The simulation results do not clearly support some of the expected impacts of parameters on the optimal design. Future work should address model convergence issues, incorporate broader parameter spaces, and consider practical constraints to refine recommendations for optimal study designs.

## Files

Project3_JT.Rmd: The Rmarkdown version of the Simulation report, which includes both written text interpretations and raw code used in the analysis.

Project3_JT.pdf: The PDF version of the Simulation report, which includes both written text interpretations and a Code Applendix with the raw code used in the analysis.

## Dependencies
The following packages were used in this analysis:

- **Data Manipulation:**  tidyverse

- **Table Formatting:** knitr, kableExtra, gridExtra

- **Model building:** lme4
