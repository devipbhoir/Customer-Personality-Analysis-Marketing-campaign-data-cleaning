# Data Cleaning and Preprocessing — Marketing Campaign Dataset

This repository contains the cleaned and preprocessed version of the original dataset `marketing_campaign.csv`, renamed as `cleaned_dataset.csv`. The data cleaning was performed using Python in Google Colab to prepare it for analysis or further machine learning tasks.

---

## Overview of the Cleaning Process

### 1. Importing the Dataset

The original dataset `marketing_campaign.csv` was imported into Google Colab for processing.

*Reference Image 1: Dataset import in Google Colab*

---

### 2. Checking for Missing Values

We used the `.isnull().sum()` method to identify columns with missing values.

*Reference Image 2: Missing values check*

---

### 3. Handling Missing Values in the Income Column

The `Income` column contained missing values. These were filled with the column's mean value to maintain data consistency.

*Reference Image 3: Filling missing values with mean*

---

### 4. Encoding Categorical Variables

Categorical columns such as `Education` and `Marital_Status` were converted into one-hot encoded columns, which initially resulted in Boolean (True/False) values for each category.

*Reference Image 4: One-hot encoding of categorical columns*

---

### 5. Converting Boolean Columns to Numeric

Boolean columns from the one-hot encoding step were converted to numeric (0 and 1) for better compatibility with data analysis and modeling tools.

*Reference Image 5: Conversion of Boolean to numeric*

---

### 6. Ordering the ID Column

The `ID` column was sorted in ascending order to organize the dataset properly.

*Reference Image 6: Sorting ID column*

---

## Final Output

The cleaned and preprocessed dataset is saved as `cleaned_dataset.csv` and is ready for further use.

---

## How to Use

1. Clone this repository.
2. Use the `cleaned_dataset.csv` file for your analysis or machine learning projects.

---

