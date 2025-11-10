# Ege University IEEE Computer Society – Bioinformatics Unit  
### Analysis Projects by Meriç Özcan

This repository contains my bioinformatics studies conducted within the **Ege University IEEE Computer Society Bioinformatics Unit**, focusing on genetic data analysis and visualization using Python-based computational biology tools.

---

## Project 1 – Analysis of COVID-19 Cell Data and UMAP Visualization  
**Notebook:** `Analysis of COVID-19 Cell Data and UMAP Visualization.ipynb`

### Overview
This project analyzes **single-cell RNA sequencing (scRNA-seq)** data from COVID-19 patients.  
The goal is to explore cellular heterogeneity and visualize gene expression differences using **UMAP (Uniform Manifold Approximation and Projection)**.

### Workflow
- Loaded `.h5ad` dataset via **Scanpy**  
- Performed filtering, normalization, and log-transformation of raw counts  
- Identified **highly variable genes** and applied PCA for dimensionality reduction  
- Constructed nearest-neighbor graphs and computed UMAP embeddings  
- Visualized total counts, gene counts, and **cell-type clusters**  
- Subselected **myeloid cells** to observe immune-related variations  

### Tools
`Scanpy`, `AnnData`, `Scipy`, `NumPy`, `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## Project 2 – Analysis of Genetic Methylation Data and Classification  
**Notebook:** `Analysis of Genetic Methylation Data and Classification According to Methylation Types.ipynb`

### Overview
This study investigates **DNA methylation patterns** and classifies samples according to methylation types.  
It combines statistical analysis, clustering, and supervised learning to interpret biological variation in methylation data.

### Workflow
- Conducted exploratory data analysis (EDA) and feature extraction from CpG sites  
- Applied clustering algorithms (**K-Means**, **DBSCAN**, **Hierarchical Clustering**)  
- Implemented supervised models (**Logistic Regression**, **Random Forest**, **SVM**)  
- Evaluated model performance using accuracy, precision, recall, and F1-score metrics  
- Interpreted methylation profiles to identify biologically meaningful patterns  

### Tools
`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## Key Takeaways
- The **COVID-19 dataset** revealed clear clustering among immune cell populations, notably myeloid cells.  
- The **methylation dataset** demonstrated that both supervised and unsupervised models can successfully separate methylation-based sample groups.  
- These analyses illustrate how **bioinformatics preprocessing** and **machine learning** can be combined for deeper biological insight.

---

## License
All rights reserved © 2025 Meriç Özcan  
The code and notebooks in this repository are provided for academic and educational use.  
Unauthorized commercial use or redistribution is not permitted.

---

## References
- [Scanpy Documentation](https://scanpy.readthedocs.io/en/stable/)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [COVID-19 Cell Atlas](https://www.covid19cellatlas.org/)  
- [Ege University IEEE Computer Society](https://ieeecs.ege.edu.tr/)

---

### About the Author
**Meriç Özcan** is a statistics student specializing in **bioinformatics, data analysis, and AI-based risk modeling**.  
He is a member of the Ege University IEEE Computer Society and focuses on projects that connect **statistical modeling with biological data**.
