# ADNI Blood Gene Expression DSCI2 Capstone Project

## Background

- 1 in 9 Americans older than 65 have Alzheimer’s dementia
- Treatment in the United States cost $305 billion in 2020
- 12.5 million projected to have Alzheimer’s dementia by 2050
- Disease still not fully understood
- Alzheimer’s has certain gene expressions: https://www.nia.nih.gov/news/gene-expression-signatures-alzheimers-disease

## Data

<img src="https://github.com/Liam-RA-Fisher/Single-Door-Raspberry-Pi-Security-System/blob/master/reed.jpg" width=30% height=30%>

I am using the micro array gene expression and diagnosis data from the Alzheimer’s Disease NeuroImaging Initiative.
http://adni.loni.usc.edu/
The data contains Alzheimer’s diagnoses based on MRI scans, PET scans, and professional evaluations.

The data tables that I am using are:

1. ADMIMERGE: Contains basic patient information and their diagnoses.
2. ADNI_Gene_Expression_Profile: Contains gene expression data from blood samples.

To aapply for the data tables you can visit the Image and Data Archive from the University of Sothern California.
https://ida.loni.usc.edu/login.jsp?project=&page=HOME

## Objective

To Use the blood gene expression data to build a predictive model for the detection of Alzheimer’s data.
If blood gene expression data can predict Alzheimer's it may be a more acessible doagnosis compared to MRI and PET scans.
I also intend to do some exploratory analysis to see which gene expressions have evidence that they are associated with Alzheimer’s.

## Directory

#### Capstone Presentation Technical.pptx
A final presentation of the project and the results

#### Capstone_Project_Pt1.Rmd
The initial data wrangling in R. Here the data is loaded and wrangled. The data is also visualized and train test splits are created for modelling.

#### Capstone_Project_Pt2.ipynb
The modelling portion of the project in Python. Her various dimensionality reduction and machine learining teqniques are applied to the genetic data in the attempt to predict Alzheimers.

#### Capstone_Project_pt3.Rmd
A further analysis of the genetic data. Here the Analysis of Variance is used to detect which genes are the most correlated with Alzheimer's diagnosis.

#### Capstone_Project_Pt3_continued.ipynb
A continuation of the deeper analysis. Here Random Forest feature importances are used to detect which Genes are the most usefull in preicting Alzheimers.

**Note:** Each Notebook / Markdown is rendered into an html file.
