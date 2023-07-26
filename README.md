# **Data Analytics Project: Sales Data Analysis**

**1. Introduction:**
- Project Title: Sales Data Analysis
- Project Objectives: [Describe the objectives of the analysis]
- Data Source: [Specify the source of the sales data]

**2. Data Cleaning and Preparation:**
- Data Cleaning Steps: [Explain the process of data cleaning, handling missing values, and removing duplicates]
- Data Transformation: [Describe any data transformations or feature engineering performed]

**3. Exploratory Data Analysis (EDA):**
- Data Overview: [Provide a brief overview of the dataset]
- Key Metrics: [Present the key metrics and visualizations to understand the data]

## **Average Revenue per Sale of 'Paseo':**
To calculate the average sale for a specific product when there are multiple products, we used Excel's built-in functions. Below is the step-by-step explanation of the process:

- Step 1: Filter the Data: We filtered the sales using product name to create a data validation dropdown list to select sales record related to the particular product we wanted to analyze. This was done using Excel's data validation function in the "Data" tab.

- Step 2: Calculate Total Revenue: We calculated the total revenue generated from the sales of the specific product using the ```=SUMIF($C$2:$C$701,T11,J2:J701)``` function in Excel, summing up the revenue column for particular product 'Paseo'.

- Step 3: Calculate Average Sale: We calculated the average revenue generated from the sales of the specific product using the ```=ROUND(AVERAGEIF($C$2:$C$701,T11, J2:J701), 2)``` function in Excel, These function sum up the revenue column for particular product 'Paseo' and divided the total revenue by the number of sales to get the average sale value for the particular product.

- Result: Our analysis show that the average reneue generated from the sales of Paseo is £163,421.50.
  ![](paseo.PNG)

## **Number of Sales in Government and Midmarket:**
To calculate the number of sale in Government and Midmarket segment, we used ```=COUNTIF()``` function:

- Select a cell where you want to display the count of sales in the Government segment.
- Enter the COUNTIF formula in the cell. The formula syntax is: =COUNTIF(range, criteria).
- For the "range" argument, select the cells in the "Segment" column containing the segment values.
- For the "criteria" argument, enter "Government" (enclosed in double quotes as it is a text value) ```=COUNTIF(A2:A701, "Government")```.
- Repeat the above process fo Midmarket Segment.
- Result: Our Analysis shows that the number of sales in the Government segment is 300 while that of Midmarket is 100.
 ![](gov.PNG)

**6. Total Revenue from Sales of 'Montana' in Canada:**
- Calculation: [Explain how the total revenue from sales of 'Montana' in Canada was calculated]
- Result: [Present the calculated value]

**7. Highest Unit of Goods Sold:**
- Calculation: [Describe how you identified the country, segment, and month with the highest unit of goods sold]
- Result: [Present the country, segment, and month with the highest unit of goods sold]

**8. Monthly Profit Analysis:**
- Calculation: [Explain how you calculated the profit for each sale and the total profit for each month]
- Result: [Present the total profit made in December]

**9. Conclusion:**
- Summary: [Summarize the key findings and insights from the analysis]
- Recommendations: [Provide actionable recommendations based on the analysis]
- Limitations: [Address any limitations or challenges encountered during the project]

**10. Future Work:**
- Future Analysis: [Suggest possible future analysis or improvements to the project]
- Additional Data: [Identify additional data that could enhance the insights gained]

**11. References:**
- Data Source: [List the source of the sales data]
- External Resources: [Include any external resources referenced in the analysis]

You can use this outline as a starting point and customize it to fit the specific details of your data and analysis. In Excel, you can create different sheets for each section and populate them with the relevant information, calculations, and visualizations. Adding charts, graphs, and tables to support your analysis will make the documentation more visually appealing and informative.
