# Data Folder

This folder contains both raw and processed data files related to **BDNF** gene expression in mouse brain regions.

## Table of Contents

1. [Files Included](#1-files-included)
2. [Data Source](#2-data-source)
3. [Usage Notes](#3-usage-notes)

## 1. Files Included

- **Raw_Datasets.zip**  
  - Contains the original raw datasets downloaded from the Allen Mouse Brain Atlas.
  - These files include comprehensive gene expression data across multiple genes and brain regions.
  - Use these files only if you want to explore or replicate the full data processing pipeline.

- **bdnf_expression_subset.csv**  
  - A cleaned and curated dataset focused exclusively on the **BDNF** gene expression values.
  - This file was generated using the instructions in the Google Colab notebook, which can be found in the `documentation` folder.

## 2. Data Source
- All raw data files were sourced from the Allen Mouse Brain Atlas (https://neuroinformatics.nl/HBP/ABA_mouse/).

## 3. Usage Notes
- **For Reproduction**: Use **Raw_Datasets.zip** and **BDNF_Data_Compilation_Notebook.ipynb** to recreate the subset.
- **For Analysis**: Use **bdnf_expression_subset.csv** for focused studies on BDNF expression.
- Please cite the Allen Mouse Brain Atlas if using these data files in your research.
