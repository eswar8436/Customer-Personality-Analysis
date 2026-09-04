# Customer Personality Analysis

## Overview

This project explores customer personality and purchasing behavior using the **Marketing Campaign dataset**.

The analysis focuses on preparing the raw customer data for analysis by identifying data-quality issues, handling missing values and duplicates, cleaning categorical variables, and converting date-related fields into appropriate formats.

The project demonstrates a practical **data preprocessing and exploratory analysis workflow using Python and Pandas**.

## Objectives

- Understand the structure and quality of the customer dataset
- Identify missing values and duplicate records
- Clean and standardize categorical data
- Convert date columns into appropriate formats
- Prepare the dataset for downstream analysis and machine learning
- Explore customer demographics, purchasing behavior, and campaign-related attributes

## Dataset

The project uses the **Marketing Campaign dataset**, containing customer demographic, purchasing, and marketing campaign information.

### Dataset characteristics

- **Rows:** 2,240 customers
- **Columns:** 29 attributes
- **Data types:** Numerical, categorical, and date-related features

The dataset includes information related to:

- Customer demographics
- Education and marital status
- Income
- Purchase behavior
- Website and catalog purchases
- Campaign responses
- Customer enrollment dates

## Data Preprocessing

The notebook performs several data-quality and preprocessing steps:

### 1. Data Inspection

- Loaded the dataset using Pandas
- Examined dataset dimensions
- Reviewed column names and data types
- Inspected the structure and contents of the dataset

### 2. Missing Value Analysis

- Identified columns containing missing values
- Examined the distribution of missing records
- Applied appropriate preprocessing to improve data quality

### 3. Duplicate Detection

- Checked the dataset for duplicate records
- Identified potential duplicate observations
- Prepared the data for further analysis

### 4. Categorical Data Cleaning

Categorical variables were reviewed and cleaned to improve consistency and usability during analysis.

### 5. Date Conversion

Date-related columns were converted into appropriate datetime formats to support time-based analysis.

## Analysis Workflow

The overall workflow followed in the notebook is:

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Quality Assessment
     ↓
Missing Value Analysis
     ↓
Duplicate Detection
     ↓
Categorical Data Cleaning
     ↓
Date Conversion
     ↓
Cleaned Dataset
     ↓
Ready for Further Analysis
