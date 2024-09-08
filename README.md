# Exploring-Differential-Gene-Expression-and-Molecular-Signatures-in-Dengue-Virus-Infections
This project focuses on the analysis of gene expression data related to dengue virus infections, specifically comparing Dengue Fever (DF), Dengue Hemorrhagic Fever (DHF), and healthy controls. Using advanced exploratory data analysis and machine learning methods, the goal was to uncover molecular patterns and potential biomarkers for differentiating between clinical stages of dengue infection.

Datasets
The study utilized gene expression datasets related to dengue virus infections, integrating clinical and transcriptomic data for robust analysis. The primary dataset includes gene expression profiles of patients with DF, DHF, and healthy controls.

Methods and Tools
The analysis incorporated several key techniques:

Principal Component Analysis (PCA): Applied for dimensionality reduction and visualizing variance across different disease states, revealing distinct separation between DF, DHF, and healthy groups.

Hierarchical Cluster Analysis (HCA): Used to explore the clustering of samples based on gene expression similarities, highlighting molecular signatures within each group.

Statistical Analysis (t-tests and Volcano Plots): Performed pairwise comparisons between disease states to identify significantly differentially expressed genes and their associated fold changes.

Random Forest Classifier: Trained on gene expression data to classify samples between DF and DHF, achieving an accuracy of 82.3%. This model suggests potential for diagnostic applications.

Key Findings
Identified significant differences in gene expression between DF and DHF, providing insights into disease pathogenesis.
PCA and HCA showed clear separations between clinical stages, indicating distinct molecular signatures.
Volcano plots and fold-change analysis revealed key genes with potential as biomarkers for disease progression and recovery.
