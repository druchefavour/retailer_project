## PREDICTING CUSTOMER BEHAVIOR ON RETAIL SALES: OPTIMIZING RETURNS BASED ON MARKDOWN SUCCESS

### 1.0 Introduction
In this project, we will be using data sets that reports the weekly sales and other vital information for a retail giant in the United States. The dataset include data on holidays and select major events that come up once a year for each department in the retail store.

It is the objective of the project to anaylse the data set so as to enable store executives make strategic decisions which would ultimately affect the bottom line. It is often suggested that markdowns do affect sales, so this project also sets out to test it as a hypothesis and subsequently predict which departments will be affected and to what extent.

### 1.1 Project Focus
This project shall focus on four distinct aspects:

* Evaluating the impact of holiday and major events that happen once a year (called markdown) on sales
* Predicting future performance based on these factors
* Optimizing sales in different departments based on these factors and
* Answering Environmental Questions

#### 1.1.0 Environmental Questions
There environmental questions to be tackled by the project include the following:

What impact does the following have on customer behavior and sales return?
* Weather (Temperature)
* Customer's income potential (CPI)
* Unemployment
* Type of store
* Size of Store
If the impact is significant, how could future sales performance be optimized based on these factors?
### 1.2 Data
The datasets contain historical sales data for 45 stores located in different regions in the United States. Each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the five largest of which are the Super Bowl, Easter, Mother's Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

One of the major challenges of modeling retail data is the need to make decisions based on limited history.

The data sets are in three tranches. The first is a 8191 x 12 features data set. The 12 columns are as follows:

Contains additional data related to the store, department, and regional activity for the given dates.

* Store - The store number
* Date - The date for the day of the week
* Temperature - The average temperature in the region
* Fuel_Price - The cost of fuel in the region
* MarkDown1-5 - These are anonymized data related to promotional markdowns. Take note that MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
* CPI - The consumer price index
* Unemployment - The unemployment rate
* IsHoliday - This is a boolean variable that determines whether the week is a special holiday week
The next data set tranche is a 46 x 3 Stores data set. This data set contain anonymized information about the 45 stores, indicating the type and size of store.

The last data set is the 421571 x 5 Sales data set. This data set contains historical sales data, which covers weekly sales from 2010-02-05 to 2012-11-01. Within this data set we will find the following columns:

* Store - The store number
* Dept - The department number
* Date - The date for the day of the week
* Weekly_Sales - The weekly sales for the given department in the given store
* IsHoliday - This is a boolean variable that determines whether the week is a special holiday week

### 1.3 Study Strategy
* Data Set Review
* Data Wrangling
* Data Exploration
* Hypothesis Testing
* Unsupervised Learning - Anomaly Detection
* Test of Multicollinearity - Variance Inflation Factor
* Clustering
* Dimensionality 
* Regression
* Classification
* Conclusion/ Recommendation

### 1.4 Study Highlights
* The performance of the promos is dependent on the size of the stores - The bigger the store, the more successful the promo (Markdown). 
* Success of the sales are more pronounced during routine holidays and weekends more than ordinary week days.
* While promo sales tends to behave independently from each other, sales during MarkDown 1 and MarkDown 4 have strong positive correlation
* The MarkDowns (promos) have more effect on sales of kids items and fashion items (for teens and adults) than other items. 
* It is recommended that retailers pay more attention on these items (kids and fashion) during promos 


