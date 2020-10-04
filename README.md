# Explore the Loan Data from Prosper


## Dataset

> The loan data is from a peer-to-peer lending company called Prosper Marketplace which is based in San Francisco, USA. Not only can individual borrow money but also invest in personal loans. This project examines the data and connected variables about borrowers.


## Summary of Findings

> Thorough this project, I have investigated to find out how the unemployed borrowers fare, not only in securing a loan but in getting a fair deal in terms of loan terms and the interest rate. I have also looked into the number of overdue payments and compared these data with their monthly income and monthly loan payment. In conclusion, inspite the difference in the population size between the groups, one can observe similiarties between them as well.


## Key Insights for Presentation

> There are 4 separate columns for employed individuals. It is not specified what the 'Employed' column details. Full-time, self-employed and part-time are also 'employed'. The assumption here is that the 'Not available' and 'Other' are borrowers who are students or simply borrowers who didn't wish to divulge further information.  
> The raw data was examined in Excel to understand this column better. There were missing data and when it was indicated 'NA' in the employment status column actually had job titles in the occupation column. I will proceed to amalgamate all statuses deemed employed as one. This will increase the number of employed. As for the 'others' their classification will be based on their stated income. The OTHERS that have zero income will be classifed as Unemployed. There is a limitation to this assumption as welfare payment receivers are deemed as unemployed unless stated otherwise.  
> As confirmed in the chart above, there are missing values or data in some of the columns. To find out how they are depicted on Excel, the original data was examined. As confirm, there are some missing values in these columns. Will employ 'fillna' method and in the Employment Status column, replaced NaN with 'No_Status'. 

## Link to the project
> More on this project, please click [here.](https://ajeethaa.github.io/Explore-the-Loan-Data-from-Prosper.html)

### References:
> https://www.prosper.com/invest#sec-3 <br />
> https://www.listendata.com/2019/07/how-to-filter-pandas-dataframe.html<br />
> https://en.wikipedia.org/wiki/Income_in_the_United_States<br />
