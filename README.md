## Intro
This project has been realized during the 'DataScience Lab' course of the Data Science Master Degree from University of Milano Bicocca.

Combining together data from the OECD Regional Well-Being dataset with Freedom House political freedom scores, the aim of this project is to quantify and analyze the East-West divide in Europe through a multi
dimensional clustering approach, combining socio-economic indicators with measures of political freedom.

## Methods Overview
Our analysis followed a multi-step approach designed to uncover patterns at both the regional and country level.  

First, we harmonized and preprocessed the data to ensure consistency across countries and regions, addressing missing values and standardizing measures. We then reduced the complexity of the dataset using Principal Component Analysis (PCA), thus capturing the main dimensions of variation in socio-economic characteristics.  
This facilitated clustering, allowing us to group regions with similar profiles and to examine how Eastern and Western regions distribute across these clusters.  

Beyond clustering, we assessed internal cohesion within countries, measuring the degree of variation among regions and testing whether patterns differ according to historical EU membership or political freedom.  

Finally, we explored scenario-based counterfactuals using predictive modeling, simulating how changes in selected institutional and infrastructural indicators in Eastern regions could influence predicted economic outcomes.  

These analyses provided descriptive insights into potential mechanisms of inequality, without claiming causal inference.  

Through this combination of descriptive statistics, clustering, and predictive modeling, the project offers a structured, multi-faced view of regional inequality in Europe. It highlights not only the current socio-economic gaps but also the institutional and structural factors that may shape future regional development

## Files
`data` contains the two data sources \
`Regional Inequalities in Europe.zip` contains the Jupyter Notebook used to develop the code \
`Report: Regional Inequalities in Europe.zip`
