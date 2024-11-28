# Tidy Data Analysis of Samsung Dataset

## Overview
This repository contains an R script, `run_analysis.R`, that processes and tidies the Samsung Human Activity Recognition Using Smartphones dataset. The script produces a tidy dataset summarizing the mean of each variable for each activity and each subject.

## Files in the Repository
- **`run_analysis.R`**: The main script to process the Samsung dataset.
- **`README.md`**: This file explains the repository and how to use it.
- **`CodeBook.md`**: Describes the variables in the tidy dataset and the transformations applied.

## Dataset Source
The data used in this analysis is from the UCI Machine Learning Repository:  
[Human Activity Recognition Using Smartphones Dataset](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Prerequisites
Before running the script, ensure the following:
- The Samsung dataset is downloaded and unzipped in your working directory. The main directory should contain files like `X_train.txt`, `y_train.txt`, `subject_train.txt`, and their corresponding test files.
- R is installed on your system with the necessary libraries (e.g., `dplyr`).

## How to Run the Script
1. Place the unzipped Samsung dataset in your working directory.
2. Clone this repository or download the files.
3. Run the script `run_analysis.R` in R using the command:
   ```R
   source("run_analysis.R")
   ```
4. The script will produce a tidy dataset named `tidy_dataset.txt` in the working directory.

## Output
- **`tidy_dataset.txt`**: A text file containing the tidy dataset with the average of each variable for each activity and each subject.
