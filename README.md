# DABM-EXPERIMENT-1
# Experiment No. 1: Data Cleaning and Preprocessing

## Aim

To perform data cleaning and preprocessing on a business dataset using Python libraries for better data quality and analysis readiness.

## Dataset

The dataset used for this experiment is `heartdisease.csv`. It contains
medical and demographic information related to heart disease patients.

The dataset is opened and analyzed using Jupyter Notebook to study its
data structure, identify data types, and perform basic statistical
analysis for data-cleaning and preprocessing purposes.

## Algorithm

1.  Import essential Python libraries.
2.  Load the dataset using Pandas.
3.  View the dataset structure, data types, and memory usage.
4.  Check for missing values and duplicates.
5.  Perform data summary statistics using `describe()`.
6.  View initial and final records using `head()` and `tail()`.
7.  Sort and group the data based on key attributes.
8.  Rename columns or modify data where necessary.
9.  Save the cleaned dataset for further analysis.

## Functions and Methods Used in the Experiment

### 1. Data Loading and Basic Exploration

  Function / Method      Description  
  ---------------------- ------------------------------------------------------\
  `pd.read_csv()`        Reads a CSV file into a Pandas DataFrame.\
  `df.info()`            Displays column names, data types, and memory usage.\
  `df.dtypes`            Returns the data types of all columns.\
  `df['column'].dtype`   Returns the data type of a specific column.\
  `df.describe()`        Provides summary statistics for numerical columns.\
  `df.head()`            Displays the first 5 rows of the DataFrame.\
  `df.tail()`            Displays the last 5 rows of the DataFrame.\

### 2. Sorting and Grouping

  Function / Method    Description  
  -------------------- ---------------------------------------------  
  `df.sort_values()`   Sorts the DataFrame by one or more columns.  
  `df.groupby()`       Groups data based on one or more columns.  
  `groupby.sum()`      Returns the sum for each group.  
  `groupby.mean()`     Returns the mean for each group.  
  `groupby.median()`   Returns the median for each group.  
  `groupby.max()`      Returns the maximum value in each group.  
  `groupby.min()`      Returns the minimum value in each group.  

### 3. Data Summary and Manipulation  

  Function / Method   Description  
  ------------------- ----------------------------------------------  
  `df.mean()`         Calculates the mean for all numeric columns.  
  `df.rename()`       Renames columns in the DataFrame.  

### 4. Optional Additions  

  Function / Method         Description  
  ------------------------- ----------------------------------------------  
  `df.isnull().sum()`       Checks for missing values in each column.  
  `df.duplicated().sum()`   Counts duplicate rows.  
  `df.dropna()`             Removes rows containing missing values.  
  `df.fillna()`             Fills missing values with a specified value.  
  `df.drop_duplicates()`    Removes duplicate rows.  
  `df.shape`                Returns the number of rows and columns.  
  `df.columns`              Lists column names in the DataFrame.  

## Program 
## Input

#Import essential Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
## Input 1
#load the dataset
df=pd.read_csv("/content/heartdisease.csv")

## Output 1
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=PsbCXRZl31ur&fullscreenOutput=true

# Input 2
#More detailed info including memory usage

df.info()

df.dtypes

#Get the summary of all variables / columns

df.describe()

#View first 10 rows

df.head()

#View last 10 rows

df.tail()


## Output 2
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=V-X1eHYg3b1G&fullscreenOutput=true
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=KYpVWe0y4KIv&fullscreenOutput=true
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=6wglzC-34Emr&fullscreenOutput=true
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=svCYan3T4CMA&fullscreenOutput=true
https://colab.research.google.com/drive/14AHGl4ABh4IPo5AToxMBlTQiqL3s5cVB#scrollTo=Dcd9hn134Rzb&fullscreenOutput=true

 

## Result

<< Enter the program execution result>>
