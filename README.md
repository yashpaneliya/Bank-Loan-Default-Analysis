# Bank Loan Default Analysis

## Introduction

This project is done to learn the fundamentals of data analytics that I learned in Data Analytics subject during Autumn semester of my MTech at IIT Kharagpur.

## Problem Statement

Analyze the data of bank loan defaulters and generate key insights that can help the bank to improve its loan default predictions. 

## Data

The data is taken from [Kaggle](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter) which is a dataset of bank loan defaulters. 

*Data dimensions: 3,07,511 records and 122 features*

## Analysis

- Checked null value percentage in each column
- Checked the distribution of each column
- Checked the correlation between columns and target variable
- Removed unneccessary columns that do not contribute to predict target
- Visualized the count of defaulters and non-defaulters in the dataset for several categorical columns
- Standardized the data
- Binning the numerical columns to view the distribution of defaulters and non-defaulters according to ranges
- Replaced the null values with the measures of central tendency according to the type of column from NOIR classification
- Outlier detection using boxplots
- Drew insights by plotting the final features with target prepared after all the above steps (*All the important insights are mentioned in the notebook*)

## Steps to run the code

- Clone the repository
- Install numpy, pandas, matplotlib, seaborn
- Run the notebook