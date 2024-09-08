# Exploring-Differential-Gene-Expression-and-Molecular-Signatures-in-Dengue-Virus-Infections
This project focuses on the analysis of gene expression data related to dengue virus infections, specifically comparing Dengue Fever (DF), Dengue Hemorrhagic Fever (DHF), and healthy controls. Using advanced exploratory data analysis and machine learning methods, the goal was to uncover molecular patterns and potential biomarkers for differentiating between clinical stages of dengue infection.

# Datasets
The study utilized gene expression datasets related to dengue virus infections, integrating clinical and transcriptomic data for robust analysis. The primary dataset includes gene expression profiles of patients with DF, DHF, and healthy controls.

# Key Methodologies:
The analysis incorporated several key techniques:

Data Preprocessing & Normalization:
Preprocessed high-dimensional gene expression datasets and merged them with clinical metadata for comprehensive analysis.
Exploratory Data Analysis (EDA):
Conducted Principal Component Analysis (PCA) to reduce dimensionality and visualize the variance among samples from different disease states.
Created volcano plots to identify genes with significant up- or downregulation in pairwise comparisons of disease conditions.
Hierarchical Clustering Analysis (HCA):
Used hierarchical clustering and dendrograms to visualize the similarity between samples, providing insights into how gene expression patterns relate to different clinical states.
Statistical Testing:
Performed t-tests to identify differentially expressed genes and calculated fold changes to quantify regulation across disease states.
Machine Learning Models:
Trained and evaluated Random Forest classifiers to distinguish between Dengue Fever and Dengue Hemorrhagic Fever patients.
Evaluated model performance using accuracy, precision, recall, and F1-scores to assess predictive power and clinical relevance.

# Tools & Technologies:
Python: Used for data analysis, statistical testing, and machine learning model development.
Libraries: pandas, numpy, scipy, scikit-learn, Matplotlib.
Visualization: Generated detailed plots (PCA, dendrograms, volcano plots) to communicate findings effectively.

Key Findings
Identified significant differences in gene expression between DF and DHF, providing insights into disease pathogenesis.
PCA and HCA showed clear separations between clinical stages, indicating distinct molecular signatures.
Volcano plots and fold-change analysis revealed key genes with potential as biomarkers for disease progression and recovery.
