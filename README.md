# manish-getting-cleaning-data-project

This is the course project for getting and cleaning the data. This project is to get and clean the tidy dataset. The data use in this project can be found in 
UCI Machine Learning Repository.

The R script, run_analysis.R is doing the following-
1. Download the dataset if it is not already exist in the working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the two datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the  (mean) value of each variable for each subject and activity pair.


