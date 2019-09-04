# survival-talk-pntlab
Best practices for survival analysis given at the Mayo Clinic Precision Neurotheraputics Lab (Summer 2019). 

## Goals
The talk is meant to introduce non-statisticians to 
several topics needed for survival analyis including:
* Multivariable regression strategies
* Do's and don'ts of variable selection
* Maximizing sample size with imputation
* Interpretation and reporting of statistical results
* Awareness of problems with observational data (covariate imbalance, confounding etc)

## Dependencies
Make sure the following `R` packages are installed before running the notebook
```
install.packages(c("rms", "rpart", "dplyr", "ggplot2", "mice", "stringr", "tidyr"))
```

## About the Authors
**Tomas Bencomo** is a B.S candidate in Computer Science at Stanford
University. His research interests include using informatics to accelerate
biological discoveries, building tools to improve physician decision making, and 
using evidence based medicine to evaluate medical practices.

**Kyle W. Singleton** is a Research Fellow at the Precision Neurotheraputics Lab
at Mayo Clinic Arizona. He received his PhD in Biomedical Informatics from UCLA. His
research focuses on radiomics methods using Magnetic Resonance Imaging (MRI) to
guide treatment decisions for Glioblastoma patients. 
