******Bioinformatics Project - Computational Drug Discovery******
This repository contains a step-by-step guide to building a machine learning model for predicting bioactivity using the ChEMBL database. The project is divided into several parts:

**Part 1: Data Collection and Pre-Processing**
In this part, we retrieve bioactivity data for the target protein, Acetylcholinesterase, from the ChEMBL database. The data is cleaned and pre-processed by handling missing values and labeling compounds based on their bioactivity.

**Part 2: Descriptor Calculation and Exploratory Data Analysis**
We calculate molecular descriptors, which are quantitative descriptions of the compounds in the dataset. We also perform exploratory data analysis to visualize the chemical space and distribution of the bioactivity classes.

**Part 3: Descriptor Calculation and Dataset Preparation**
Here, we calculate fingerprint descriptors using the PaDEL software and prepare the dataset for model building by combining the descriptors with the pIC50 values.

**Part 4: Regression Models with Random Forest**
We build a regression model using the Random Forest algorithm to predict the pIC50 values of the compounds. The model's performance is evaluated using a scatter plot of experimental vs. predicted pIC50 values.

**Part 5: Comparing Regressors**
In this part, we compare the performance of various machine learning algorithms for building regression models of Acetylcholinesterase inhibitors. We use the LazyPredict library to automate the comparison.

**Requirements**
To run this project, you will need to install the following dependencies. You can do this by creating a requirements.txt file with the following content:

**numpy
pandas
scikit-learn
matplotlib
seaborn
lazypredict
padelpy
requests
rdkit
**

