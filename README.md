# Data_Cleaning_with_Pandas

## Introduction
This project is focused on processing and encoding a dataset from a CSV file named SIS_Faculty_List.csv. The dataset is manipulated to clean, organise, and prepare it for further analysis or machine learning applications. The script handles tasks such as dropping unnecessary columns, renaming columns for consistency, handling missing values, encoding categorical data, and exporting the processed data into new CSV files.

## Installation
To run this project, you'll need the following Python packages:

* pandas
* numpy
* matplotlib
* scikit-learn
* re


These can be installed via pip:

```
pip install pandas numpy matplotlib scikit-learn
```
## Usage

To use this script, ensure you have the required CSV files (_**SIS_Faculty_List.csv**_ and _**countries_list.csv**_ and _**professional_exp_edited.xlsx**_ in the same directory as the script. Simply run the script to process the data and save the cleaned and encoded versions as new CSV files.

## Features
The script includes the following features:

* **Data Cleaning**: Removes unnecessary columns, handles missing data, and corrects formats.

* **Data Transformation**: Renames columns, adjusts data types, and replaces abbreviated text with full words.

* **Data Encoding**: Applies Label encoding and ordinal encoding to categorical data.

* **Data Export**: Saves cleaned and transformed data into new CSV files for easy use in future processes.

## Dependencies
* **pandas**: for data manipulation and analysis.

* **numpy**: For numerical operations.
* **matplotlib**: For generating plots.
* **scikit-learn**: For data preprocessing tools like encoders.
* **re**: For regular expression operations.
