# Project overview 
This sales analysis describes the different activities in a sales company including the profit, loss, sale trends, highest product sales and lowest product sales.  
## Project title 
Sales Analysis of products in Tesco
### Aims and objectives 
- Highlight significant sale trends
- Spot patterns affecting sales projection
- Provide strategic suggestions for future sales
- Improve sales outocome over time
### Data Source
The data used was collected from Tesco stores across London 
### Tools used  
Microsoft Excel, Power BI, Python 
### Data cleaning/preparation
- An empty column was dropped
- Null values were removed
- From the age column, the mean values were used to replace the null values
- Non-numeric values were removed from the sales column to allow aggregation of the sales column
### Exploratory data analysis
- The lowest/highest selling tesco store was identified
- The lowest/highest selling product was also identified
- The day with the lowest/highest sales was determined
- The age group with the lowest/highest purchase
- The gender with the lowest/highest purchase
- Poor/best performing sales Tesco store
### Data Analysis 
This is an example code used in this project:
```
Python
sales.drop('link', axis=1, inplace=True)
```
### Results
###### The results showed the following;
- Tesco store in South London recorded the highest sales while Tesco store in North London recorded the lowest sales 
- The day with the lowest sales is Monday while the day with the highest sales is Sunday 
