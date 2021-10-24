# TARGET-STORE-SALES-PREDICTION
Dataset provided with historical sales data for 45 stores located in different region search store contains a number of departments. The company also runs several promotional  markdown events throughout the year. These markdowns precede prominent holidays, the  four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks  including these holidays are weighted five times higher in the evaluation than non-holiday  weeks.

![image](https://user-images.githubusercontent.com/86415241/138585818-0d7a1a99-6e70-4af2-a577-67c91e6d17da.png)

### Problem description: 
One challenge of modeling retail data is the need to make decisions based on limited history. Holidays and select major events come once a year, and so does the chance to see how strategic decisions impacted the bottom line. In addition, markdowns are known to affect sales the challenge is to predict which departments will be affected and to what extent.

### Variable Description:
- Over here we have 3 Excel Sheet, named as Store_Details, Business_Data and Sales_History.

#### Store_Details:
- Anonymized information about 45 stores indicating store type, Address, Location and size of store.

#### Business_Data:
Contains additional data related to the store, department, and regional activity for the given dates.
- Store - the store number
- Date - the week
- Temperature - Average temperature of surrounding region of store location.
- Fuel_Price –Average price of gas per gallon.
- MarkDown1-5 - Anonymized data related to promotional markdowns. MarkDown data is not available for all stores all the time. Any missing value is marked with an “NA”.
- CPI - The Consumer Price Index (CPI) is a measure of the average change in prices over time that consumers pay for a weighted averaged basket of goods and services.
- Unemployment_Rate - the unemployment rate of the region where the store is located.
- Holiday - whether the week is a special holiday week

#### Sales_History:
Historical sales data of each store from 30th April 2017 to 25th October 2019. Within this tab you will find the following fields:
- Store - the store number
- Department - the department number
- Date - the week
- Total_Sales –Total sales for the given department in the given store
- Holiday - whether the week is a special holiday wee

### Approach:
1. Understand the data variables properly. Check the variable description to understand 
the data properly. 
2. Clean the data: Clean the data, that is, fill the missing values (if any), treat the outliers 
(or odd values), etc. Ensure each variable’s data is as per the nature of the variable (e.g. 
 Date field should contain only date values – can extract year, month and day of the 
week, and numeric column should be formatted as numeric, etc.).
3. Conduct EDA (Exploratory Data Analysis) on the cleaned Data: Summarize, explore the 
data and then decide your strategy. Make note of any important assumptions that you 
make.
4. Uni-variate and Bi-variate Analysis: Check the distribution of independent variables and 
also compare them with the dependent variable.
5. Feature Engineering: Create new meaningful features based on the existing features by 
applying some aggregation functions on them.
6. Hypothesis Testing: Hypothesis testing in statistics is a way for you to test the results of 
a survey or experiment to see if you have meaningful results. You should give a brief 
summary of the data and a summary of the results of your statistical test. In the 
discussion, you can discuss whether your initial hypothesis was supported or refuted.


