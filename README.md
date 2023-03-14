# PLCO-data-analysis
This repository contains code used for demonstrating the machine learning pipeline validity on the PLCO Ovarian Cancer Biomarkers dataset (https://cdas.cancer.gov/datasets/plco/23/). Based on results from these experiments, a manuscript with title "Explainable discovery of disease biomarkers: The case of ovarian cancer to illustrate the best practice in machine learning and Shapley analysis" is written and is under review for publication. 

## Repo Explanation
1. Pipeline.ipynb: this notebook contains a demonstration pipeline which starts with loading the data, followed by dimension reduction (feature selection) steps and model training and testing. Finally, the model is passed through SHAP (https://github.com/slundberg/shap) where post-hoc feature contribution is generated. 
2. statistical_analysis.ipynb: this notebook contains code used for generating the statistical analysis baselines in the Result chapter of the manuscript. In the analysis, the t-test, Mann-Whitney-U, and the Wilcoxon signed rank test are imported from the scipy.stats package. 
3. requirements.txt: this file contains version information of the packages used/imported by both of the notebooks for better reproducibility of the results. 
4. python version: Python 3.7.6

## Author Contributions
Weitong Huang (repo owner), Amanda S. Barnard, Hanna Suominen and Tommy Liu conceived and designed the experiments and analysis. Weitong Huang collected the data. Carlos Salomon and Greg Rice provided medical domain expertise in background and analysis. Weitong Huang perfomed the model building and data analysis. Tommy Liu provided support in interpreting the results. Weitong Huang took the lead in writing the manuscript. All authors provided critical feedback and helped shape the research, analysis and manuscript.
