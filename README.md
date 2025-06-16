# Classic Dissemination Network based on Translations (CDNT)

This repository contains the code for generating and analyzing the CDNT, developed for the paper:

> **A Network Analytical Framework for Modeling the Global Transmission of Classics through Translation**

##  **Repository Overview**

The repository includes the full workflow for constructing the CDNT, analyzing its global and node-level structural properties, and estimating influencing factors using ERGM.

##  **Files**

- **`Generation.ipynb`**
  - Python notebook for generating the CDNT based on the translation metadata.
  - Tasks include data cleaning, node-edge construction, and exporting the network in standard formats.

- **`Analysis-1.ipynb`**
  - R notebook for analyzing the overall structural characteristics and node-level properties of the CDNT.
  - Computes metrics such as Average Path Length, Average Clustering Coefficient and Node Degree.

- **`Analysis-2.ipynb`**
  - Python notebook for additional analysis of node-level features in the CDNT.
  - Computes metrics Betweenness Centrality. 

- **`Analysis-3.ipynb`**
  - R notebook for modeling CDNT using **Exponential Random Graph Models (ERGM)**.
  - Estimates the effects of structural variables, node attributes, and edge attributes on network formation.

##  **Requirements**

- Python 3.8  
  - Recommended: NetworkX, Pandas, Matplotlib
- R 4.4.0  
  - Recommended: igraph, statnet, ergm
- **Additional software:**  
  - Some figures in the paper were created or refined using **ArcGIS Pro** (for spatial mapping), **Gephi** (for network visualization layout), and **Origin** (for data plotting and chart design).

##  **How to Use**

1. **Generate the network**  
   Run `Generation.ipynb` to build and export the CDNT.

2. **Analyze network structure**  
   Use `Analysis-1.ipynb` (R) or `Analysis-2.ipynb` (Python) to explore the global and node-level features.

3. **Run ERGM models**  
   Use `Analysis-3.ipynb` (R) to estimate the ERGM and examine the significance of different factors.




