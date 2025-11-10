# Ege University IEEE Computer Society – Bioinformatics Unit  
### Bridging Statistics and Biology through Data Science  
#### Analysis Projects by Meriç Özcan

This repository showcases analytical studies conducted within the **Ege University IEEE Computer Society Bioinformatics Unit**,  
focusing on the intersection of **statistics, data science, and molecular biology**.  
The projects demonstrate the use of computational and statistical tools for understanding complex biological data.

---

## Project 1 – Analysis of COVID-19 Cell Data and UMAP Visualization  
**Notebook:** `Analysis of COVID-19 Cell Data and UMAP Visualization.ipynb`

### Overview
This project explores **single-cell RNA sequencing (scRNA-seq)** data from COVID-19 patients.  
The aim is to examine gene expression heterogeneity and visualize cellular structures using **UMAP (Uniform Manifold Approximation and Projection)**.

### Workflow
- Loaded `.h5ad` single-cell dataset via **Scanpy**  
- Filtered cells and genes based on expression thresholds  
- Normalized counts and applied log transformation  
- Selected highly variable genes and performed **PCA**  
- Computed nearest neighbors and UMAP embeddings  
- Visualized **cell-type clusters**, **gene counts**, and **myeloid cell distributions**

### Tools
`Scanpy`, `AnnData`, `Scipy`, `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## Project 2 – Analysis of Genetic Methylation Data and Classification  
**Notebook:** `Analysis of Genetic Methylation Data and Classification According to Methylation Types.ipynb`

### Overview
This study investigates **DNA methylation patterns** and classifies samples according to methylation types.  
It integrates exploratory data analysis, clustering, and machine learning to identify biologically relevant methylation profiles.

### Workflow
- Performed feature extraction from CpG sites and correlation analysis  
- Applied unsupervised models: **K-Means**, **DBSCAN**, and **Hierarchical Clustering**  
- Built supervised classifiers: **Logistic Regression**, **Random Forest**, **SVM**  
- Evaluated models using Accuracy, Precision, Recall, and F1 Score  
- Interpreted methylation patterns in relation to gene regulation

### Tools
`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## Key Takeaways
- The **COVID-19 single-cell dataset** revealed distinct immune cell groupings, highlighting myeloid cell variation.  
- The **methylation dataset** showed that both clustering and classification models effectively distinguish methylation-based subgroups.  
- These analyses demonstrate how combining **bioinformatics preprocessing** with **statistical modeling** yields interpretable biological insights.

---

## License
All rights reserved © 2025 Meriç Özcan  
The code and notebooks are shared for academic and educational purposes.  
Unauthorized commercial use or redistribution is prohibited.

---

## References
- [Scanpy Documentation](https://scanpy.readthedocs.io/en/stable/)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [COVID-19 Cell Atlas](https://www.covid19cellatlas.org/)  
- [Ege University IEEE Computer Society](https://ieeecs.ege.edu.tr/)

---

### About the Author
**Meriç Özcan** is a statistics student passionate about **bioinformatics, artificial intelligence, and data-driven risk modeling**.  
He focuses on connecting **quantitative methods** with **biological and genomic data**,  
aiming to bridge disciplines through analytical thinking and scientific integrity.
