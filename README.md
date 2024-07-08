# FIT5196: Assignment 2

This repository contains the work and materials for Assignment 2 of the FIT5196 unit (Data Wrangling).

The project focuses on exploring, understanding, and cleaning a food delivery dataset from Melbourne, Australia. 

## Project Overview

This assignment emphasizes the critical role of data exploration and understanding in the data wrangling process. Students are required to perform both graphical and non-graphical Exploratory Data Analysis (EDA) methods to gain insights into the dataset and identify potential data issues.

## Dataset Description

- Food Delivery data from a restaurant in Melbourne, Australia
- Information about three branches around the CBD area (sharing the same menu but different management)
- Each instance represents a single delivery order
- Additional files: `branches.csv`, `edges.csv`, and `nodes.csv`

## Main Objectives

- Perform thorough EDA to understand the data structure and identify problems
- Clean and preprocess the data to address missing values and anomalies
- Prepare the data for further analysis

## Tasks

### Data Cleansing 
- Detect and fix errors in `<group_id>_dirty_data.csv`
- Impute missing values in `<group_id>_missing_data.csv`, with focus on imputing the missing `delivery_fee` attribute
- Detect and remove outlier rows in `<group_id>_outlier_data.csv`; outliers are to be found with respect to the `delivery_fee` attribute only 

### Data Reshaping 
- Analyze `suburb_info.xlsx` file
- Study effects of normalization/transformation methods
- Prepare data for a linear model to predict `median_house_price`
