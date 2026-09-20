
# problem statement 
ProWidget Systems is a UK-based B2B (business-to-business) retailer. They asked us to report on spending volumes for customers based in London compared with those based in the rest of the United Kingdom.
They want to know : 
Which UK cities are currently underserved
Whether their customers are primarily London based


# desired outcome 
Are different cities underserved? This requires us to calculate total customer spending by city and find cities with the lowest customer spending.
How does London compare to the rest of the United Kingdom? This can then be
answered from the output of the first answer.

 we need to add a city column to our data, which we will extract from the address. 

 As for the final output, a table or a bar chart will suffice for both cases. 

# Data Source 

The project involved combining our own customer data with the government’s official public list of companies.

In this project, the available data was not organized cleanly enough to provide a separate city column. We only had a single customer address column, which may or may not contain the city somewhere within the address.

The address data for this project comes from Companies House, an executive agency sponsored by the UK government’s Department for Business and Trade.

https://mng.bz/mGxr. 

# Data Dictoinary 

|---|---|
| company_id | A unique identifier for each customer company in the dataset |
| address | A single field to store the customer address |
| total_spend | The total amount this customer has spent to date (in GBP) | 

# project workflow 

Investigate missing data 
Try to extract city column from address   
Create city column from external list 
Explore new city column
Analyze and visualize spend by city and London versus rest of United Kingdom



