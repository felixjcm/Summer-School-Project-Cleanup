# Drug–Gene Interaction Network Analysis

🏆 **3rd Place** — Biomedical Data Science Summer School, Semmelweis University

## Overview

This repository contains a cleaned and documented version of the notebook our team developed during the **Biomedical Data Science Summer School at Semmelweis University**.

The project analyzes the **ChG-InterDecagon** drug–gene interaction dataset by representing it as a **bipartite network**. The workflow covers data acquisition, graph construction, computation of fundamental network statistics, and visualization of structural properties to provide an accessible overview of the dataset and its underlying interactions.

The notebook was cleaned, reorganized, and documented to improve readability, reproducibility, and ease of understanding.

## Dataset

The analysis uses the **ChG-InterDecagon** drug–gene interaction dataset provided by the **SNAP Biodata** repository. The dataset models interactions between drugs and their target genes, making it suitable for graph-theoretic and network biology analyses.

## Features

* Automatic download and preprocessing of the dataset
* Construction of a bipartite drug–gene interaction graph
* Computation of descriptive network statistics
* Analysis of graph topology and connectivity
* Visualization of relevant network properties
* Clean, well-documented notebook suitable for educational purposes

## Technologies

* Python
* Pandas
* NumPy
* NetworkX
* Matplotlib

## Repository Structure

```text
analysis_cleaned.ipynb   # Main analysis notebook
figures/                 # Generated visualizations
README.md
ChG-InterDecagon_targets.csv # Data
```

## Results

The notebook generates several visualizations and summary statistics describing the structure of the drug–gene interaction network. Selected figures are included in the `figures/` directory for quick inspection without executing the notebook.

## Contribution Disclaimer

This repository represents a **team project** completed during the Biomedical Data Science Summer School at Semmelweis University.

The project was developed collaboratively, and a substantial portion of the analysis, implementation, and scientific work was carried out by my teammates. My primary contribution afterwards was cleaning, restructuring, documenting, and polishing the notebook after the project concluded to improve its readability and maintainability. 

As stated above, a large share of the groundwork for the project was created by my teammates who are more knowledgeable than me in, among other things pharmaceutical science and math. Thank you for your input and the amazing collaboration and result.

## Acknowledgements

* Biomedical Data Science Summer School
* Semmelweis University
* SNAP Biodata for providing the ChG-InterDecagon dataset
* Botond and Àngel
