# EDA and Feature Engineering on Black Friday Dataset

## Problem Statement

A retail company, "ABC Private Limited," seeks to understand customer purchase behavior, specifically the purchase amount, for various products across different categories. With a dataset containing purchase summaries of high-volume products, along with customer demographics and product details, the company aims to build a predictive model. This model will enable personalized offers based on predicted purchase amounts, contributing to a more tailored customer experience.

## Dataset Overview

I acquired a comprehensive Black Friday dataset from Kaggle, providing intricate insights into individuals and their purchasing behavior. The dataset, thoughtfully organized into test and train data, has been seamlessly merged to consolidate available information.

### Key Features

- **Product_ID:** Identifier for the purchased product.
- **Gender:** Gender of the individual making the purchase.
- **Age:** Age group of the consumer.
- **Occupation:** Numeric code representing the occupation of the buyer.
- **City_Category:** Category of the city where the consumer resides.
- **Stay_In_Current_City_Years:** Duration of stay in the current city.
- **Marital_Status:** Marital status of the buyer (1 for married, 0 for unmarried).
- **Product_Category_1, Product_Category_2, Product_Category_3:** Categories of the purchased products.
- **Purchase:** The purchase amount made by the individual.

*Total number of rows in data: 783,667*
*Total number of columns: 12*

## Data Cleaning and Feature Engineering

### 1. Handling Null Values

- Null values in columns Product_Category_2 and Product_Category_3 were replaced by the mode.

### 2. Converting Columns to Appropriate Data Types

- Changed the data type of Stay_In_Current_City_Years to int type.

### 3. Handling Categorical Values

- In the "Gender" column, values were encoded, with "Male" represented as 1 and "Female" as 0.
- In the "Age" column, age groups were numerically encoded for analytical convenience.

## Exploratory Data Analysis (EDA)

*To be expanded based on insights gained during analysis.*

## Next Steps

*Specify the planned analyses, models, or predictions based on the pre-processing.*
