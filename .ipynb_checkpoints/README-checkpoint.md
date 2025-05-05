# **Early Stage Exploration for Urine Excreted Biomarkers Importance in  Alzheimer’s Detection** 

## 1.)  Problem Outline:
    
### Problem Statement: 

Alzheimer’s is a highly debilitating neurodegenerative disease responsible for about 70% of all instances of dementia. 
Early detection and treatment is necessary to improve overall quality of life, but currently there is no definitive test to diagnose Alzheimer’s disease. 
There are various tests that assist in the diagnosing process; unfortunately the majority of these tests tend to be inaccessible, invasive, and expensive. 
This project uses datasets of collected urine sample reports from both Alzheimer’s patients and the healthy control group to identify biomarkers for detecting Alzheimer’s in urine and create an early-stage machine learning model that can correctly classify between the two sample groups. Doing so would  extend 

### Objectives:

Clean and Process Mass Spectrometry Reports. 
Perform exploratory data analysis (EDA) to identify class variance to set standards. 
Use machine learning algorithms to determine features classification importance.
Train and evaluate machine learning models to classify between samples.
Interpret the models/ identify biomarkers for additional study.

### Datasets:

CSV files: Molecular Network Analysis of the Urinary Proteome of Alzheimer's Disease Patients. 

## 2.) Table of Contents:

- Problem Outline
- Table of Contents
- Project Structure
- Data Dictionary 
- Methods/Usage
- Results
- Extension
- Installation 
- Citation

## 3.) Project Structure:

> 01_data: Folder containing all datasets used
> 02_code
>- 0.5_preprocessing.ipynb
>- 01_EDA_protein_sequence.ipynb
>- 02_EDA_urine_samples.ipynb
>- 03_DT_FeatureImportance.ipynb
>- 04_LogRegClassificationModel.ipynb
> 03_additional_datasets
> 04_images
>-3D Protein_Abundance.png
>-DT_Protein_Feature_Abundance_Distribution.png
>-Important_Features1.png
>-Important_Features2.png
>-Protein_AMBP_Distributions.png
>-Protein_Density_Plots.png
>-Protein_Distributions.png
>-Target_Proteins1.png
>-Target_Proteins2.png

## 4.) Data Dictionary:

| **Feature** | **Type** | **Dataset** | **Description** |
| :-----: |:-----: |:-----: |:-----: |
| emPAI Value | Numeric Float | Present within all datasets | An estimate of protein abundance within a sample |
| Prot_desc | String Variable | Present within all datasets | Name of the Specific protein 
| OS | Column Descriptor | Present within all datasets | Organism or Species |
| GN | Column Descriptor | Present within all datasets | Gene Name |
| PE | Column Descriptor | Present within all datasets | Protein | 
| SV | Column Descriptor | Present within all datasets | Serum |
| Alzheimer’s | Binary Numeric | Present within all datasets | Patient sample group |

## 5.) Methods:

### ** The project utilized a multi-stage analytical approach: **

Data Loading and Preprocessing: 

EDA: 

Feature Importance Selection:

Logarithmic Regression: 


## 6.) Results:



## 7.) Extension:



## 8.) Citation:

