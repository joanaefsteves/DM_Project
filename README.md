README file for Data Mining Project 24/25

Group 36: Eduardo Mendes, 20240850; Joana Esteves, 20240746; João Afonso Freire, 20240528; Tomás Figueiredo, 20240941.

Overview: This project involves multiple notebooks, one notebook generates intermediate files required by subsequent steps.

Main contents: 
- DM2425_Part2_01.ipynb: Preprocessing steps.
- DM2425_Part2_02.ipynb: Clustering using DBSCAN and GMM.
- DM2425_Part2_03.ipynb: Clustering using SOM.
- DM2425_Part2_04.ipynb: Clustering using K-Means.
- DM2425_Part2_05.ipynb: Hierarchical-K-Means for final segmentation and profiling.

Notebook and file dependencies:

1. DM2425_Part2_01.ipynb:
- Requires: DM2425_ABCDEats_DATASET.csv
- Generates: Data_original_values.parquet and Data_preprocessed.parquet

2. DM2425_Part2_02.ipynb; DM2425_Part2_03.ipynb; DM2425_Part2_04.ipynb; DM2425_Part2_05.ipynb:
- Require: Data_original_values.parquet and Data_preprocessed.parquet

Notebook running order:

DM2425_Part2_01 > remaining notebooks in any given order.