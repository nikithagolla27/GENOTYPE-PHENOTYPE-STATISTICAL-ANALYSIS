Genotype–Phenotype Statistical Analysis
Project Overview
This project focuses on the statistical analysis of a simulated genotype–phenotype dataset to study the relationship between genetic variations and observable traits.
The project applies foundational data science techniques such as data manipulation, descriptive statistics, probability analysis, and hypothesis testing using Python.

Objectives
The main objectives of this project are to analyze genotype–phenotype relationships using a simulated dataset, apply Pandas for data manipulation and statistical summarization,
compute probability and conditional probability related to genetic disorders, perform a T-Test to compare treatment response times between affected and healthy patients,
and conduct a Chi-Square test to examine the association between genotype carrier status and phenotype.

Dataset Description
The dataset used in this project is synthetically generated and contains more than 100 patient records.
Each record includes a unique Patient ID, genotype information (AA, Aa, or aa), phenotype status where 0 represents healthy and 1 represents affected,
treatment response time measured in days, and gender information (Male or Female). The dataset is created for educational purposes and does not contain real patient data.

Tools and Technologies
Python was used as the primary programming language. Jupyter Notebook was used as the development environment.
Pandas and NumPy were used for data manipulation and numerical operations. SciPy was used to perform statistical tests such as the T-Test and Chi-Square test.

Methodology
The project began with the creation and loading of a simulated genotype–phenotype dataset. Descriptive statistical analysis was performed to calculate mean, median, and standard deviation of treatment response time grouped by genotype. 
Probability and conditional probability calculations were carried out to estimate the likelihood of being affected by the disorder. Inferential statistical analysis was conducted using a T-Test to compare treatment response times between affected and healthy patients, and a Chi-Square test was performed to assess the association between genotype carrier status and phenotype.

Key Results
The analysis showed variations in treatment response time across different genotypes. A higher probability of being affected was observed for individuals with the aa genotype.
The T-Test indicated a statistically significant difference in treatment response times between affected and healthy patients. The Chi-Square test confirmed a significant association between genotype and phenotype.

Project Structure
genotype_dataset.csv
Genotype_Phenotype_Analysis.ipynb
README.md

How to Run
Clone the repository, open Jupyter Notebook, and run all cells in the provided notebook file to reproduce the results.

Conclusion
This project demonstrates the effective use of basic data science and statistical techniques for analyzing genetic data.
It provides a strong foundation in probability analysis, statistical inference, and hypothesis testing, which are essential skills for data science and bioinformatics applications.
