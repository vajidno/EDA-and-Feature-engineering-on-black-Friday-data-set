# EDA and Feature Engineering on Black Friday Dataset

## Problem Statement

Retail company "ABC Private Limited" aims to understand customer purchase behavior, specifically the purchase amount, for various products across different categories. The dataset, comprising purchase summaries, customer demographics, and product details, serves as the foundation for building a predictive model. This model will enable personalized offers, contributing to a more tailored customer experience.

## Dataset Overview

I acquired a comprehensive Black Friday dataset from Kaggle, offering detailed insights into individuals and their purchasing behavior. The dataset, meticulously organized into test and train data, has been seamlessly merged to consolidate available information.

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

- Replaced null values in columns Product_Category_2 and Product_Category_3 with the mode.

### 2. Converting Columns to Appropriate Data Types

- Converted the data type of Stay_In_Current_City_Years to int.

### 3. Handling Categorical Values

- Encoded values in the "Gender" column, with "Male" represented as 1 and "Female" as 0.
- Numerically encoded age groups in the "Age" column for analytical convenience.

## Challenges

- **Data Format:** Data was present in the wrong datatype format.
- **Visualization Techniques:** Choosing appropriate visualization techniques posed difficulties.
- **Null Values:** A significant number of null values were present in the dataset.

## Conclusion from EDA

- The proportion of men making purchases significantly surpasses that of women.
- The highest number of purchases occurred within Product Category 1.
