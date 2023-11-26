### EDA-and-Feature-engineering-on-black-Friday-data-set
### Problem Statement
A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

### Dataset
I acquired a comprehensive Black Friday dataset from Kaggle, offering intricate insights into individuals and their purchasing behavior, particularly focusing on the purchase amount. The dataset is thoughtfully organized into both test and train data, and I seamlessly merged them to consolidate the available information.

<br>Key Features:
<br>Product_ID: Identifier for the purchased product.
<br>Gender: Gender of the individual making the purchase.
<br>Age: Age group of the consumer.
<br>Occupation: Numeric code representing the occupation of the buyer.
<br>City_Category: Category of the city where the consumer resides.
<br>Stay_In_Current_City_Years: Duration of stay in the current city.
<br>Marital_Status: Marital status of the buyer (1 for married, 0 for unmarried).
<br>Product_Category_1, Product_Category_2, Product_Category_3: Categories of the purchased products.
<br>Purchase: The purchase amount made by the individual.
<br> * Total number of rows in data: 783667
<br> * Total number of columns: 12

### Data Cleaning and Feature Engineering
*1)Handling null values*
<br>* Null values in columns Product_Category_2 and Product_Category_3 were replaced by mode.
#### 2)Converting columns to appropriate data types
<br> * Changed data type of Stay_In_Current_City_Years to int type.















