# Analysing the retail data, extracting the insights for business accumen.
 Retail Data analysis with the UCI data set.

 
 # The primary objectives of this analysis are to:

1. Understand Customer Behavior: Identify key purchasing patterns and customer segments.
2. Analyze Sales Performance: Evaluate sales trends over time to determine peak periods and underperforming products.
3. Perform the Exploratory data analysis.
4. Customer Segmentation: Segmentation based on demographics or purchase behavior can help identify groups of customers with similar characteristics or buying patterns.
   
# Dataset Description
The dataset used in this analysis is sourced from the UCI Machine Learning Repository. It is known as the "Online Retail" dataset, which contains transactional data.
The dataset comprises approximately 540,000 rows and 8 columns, detailing transactions occurring from December 1, 2010, to December 9, 2011.
Link : https://archive.ics.uci.edu/dataset/502/online+retail+ii

# Columns

1. InvoiceNo: A six-digit integral number uniquely assigned to each transaction. If this code starts with 'C', it indicates a cancellation.
2. StockCode: A five-digit integral number uniquely assigned to each distinct product.
3. Description: A textual description of each product.
4. Quantity: The quantities of each product per transaction.
5. InvoiceDate: The date and time when a transaction was generated.
6. UnitPrice: The unit price of each product (in pounds).
7. CustomerID: A unique identifier assigned to each customer.
8. Country: The name of the country where the customer resides.

# Process involved and implemented:

1. Data preprocessing
   
    1.1 Data Cleanings

    1.2 Exploratiry data analysis

       1.2.1 univariate analysis

       1.2.2 Multi variate analysis
   
2. Data analysis implementations
   2.1 product analysis
   
   2.2 sales analysis
   
   2.3 customer segmentations
   
     2.3.1 personalized marketing strategies
   
   2.4 customer churn analysis
   
   2.5 Repeat purchase rate analysis.
   
3. Interpretations
4. key Take away

# Visualizations with power bi
file name:  Retail_data_powerBI.pbix

1. The three csv files are used which is the results of above analysis for the purpose of visualizations namely:
   
     a. churned_repeat_purchase_rate.csv
     
     b. retail_data (ORIGINAL DATASET CLEANED)
     
     C. rfm_with_promotions

2. calculated columns are created for finding the Total_Sales.
3. created the graphs for sales analysis with slicer use.
4. created pie-chart graph for customer segmentation visualisations
5. rfm visualizations has been done with the help of colum stacked bar chart.
6. lastly sales by country is visualized along with stock code and invoice date slicers.
