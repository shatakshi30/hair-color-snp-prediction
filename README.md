# Hair Color Prediction from SNP Data

This project explores the use of informative **single nucleotide polymorphisms (SNPs)** for predicting human **hair color phenotypes**. We applied **dimensionality reduction (PCA)**, **clustering**, and **machine learning models** on SNP genotype data using three different panels/tools: **HIrisPlex**, **HIrisPlexS**, and **Snipper**.

---

## 📊 Datasets

- Total SNPs: **283 SNPs**
- Source: **OpenSNP database**  
- Genotype data includes SNPs known to be associated with pigmentation traits.

---

## Objectives

- To identify the most informative SNPs for **hair color** prediction.
- To compare the performance of different SNP panels:
  - **HIrisPlex**
  - **HIrisPlexS**
  - **Snipper**
- To evaluate how **PCA** and **clustering** reflect phenotype separability.
- To build **predictive models**:
  - **Support Vector Machine (SVM)**
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest (RF)**

---

## Methods

### Tools & Workflow:

- **PCA Analysis**:
  - Dimensionality reduction to visualize SNP variance.
  - Identification of top-contributing SNPs per principal component.

- **Clustering**:
  - Unsupervised clustering to group individuals by genotype profiles.

- **Predictive Modeling**:
  - Built and compared **SVM**, **KNN**, and **Random Forest** models.
  - Performed **hyperparameter tuning** and cross-validation.

### SNP Panels Analyzed:

- **Snipper**
- **HIrisPlex**
- **HIrisPlexS**

---

## Results

### PCA & Clustering:

- PCA revealed **clear separation** for certain **hair colors**.
- Identified **top-contributing SNPs** for each panel.
- Clustering aligned with **known hair color groups**.

### Predictive Models:

| Model          | Performance Summary |
|----------------|---------------------|
| **SVM**        | Best for complex patterns, good accuracy |
| **KNN**        | Simpler but effective for highly separated classes |
| **Random Forest** | Performed well, provided feature importance insights |

### Key Finding:

- **HIrisPlexS** gave the best performance for **hair color** prediction.
- Certain **common SNPs** across all panels were consistently top contributors.

---

## Questions Answered

1. What SNPs contribute most to **hair color** prediction?  
- Identified via PCA loadings and Random Forest feature importance.

2. Do certain panels outperform others?  
- **HIrisPlexS** generally outperformed HIrisPlex and Snipper.

3. Can unsupervised clustering reveal phenotype groups?  
- Yes, **PCA + clustering** showed clear **hair color** separability.

4. Which model works best?  
- **Random Forest** and **SVM** both performed strongly.

---
## Discussion

- SNP-based prediction of visible phenotypes like **hair color** is feasible and **biologically interpretable**.
- Different panels vary in **coverage** and **predictive power**.
- Combining PCA visualization + supervised ML modeling was an effective strategy.
- Random Forest helped identify **biologically relevant SNPs**.

---

## Learnings

- Gained hands-on experience with **SNP data analysis**.
- Applied **PCA**, **clustering**, and **classification models** on real genetic data.
- Learned to interpret **SNP biological significance**.
- Practiced **workflow design and comparison** across different tools.
- Improved skills in **bioinformatics pipeline development** and **scientific reporting**.

---

## 📁 Files in This Repository

- `Final_Project_-_HIrisPlex.ipynb` → Analysis of HIrisPlex panel.
- `Final_Project_-_HIrisPlexS.ipynb` → Analysis of HIrisPlexS panel.
- `Final_Project_-_Snipper.ipynb` → Analysis of Snipper panel.
- `Final_Report.pdf` → Final project report.

---
