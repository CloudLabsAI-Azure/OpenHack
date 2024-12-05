# Challenge 1 - Restore a SQL Server Backup and Query the Data

### Estimated Duration: 60 Minutes

## Background Story

Woodgrove Retail has been running an online retail website for several years, and we have access to some archived data. Woodgrove This retailer is an Internet-based mail order business (B2C business) that is located in Germany and is also located in a rural area, including storage space (which can be adapted if necessary and with some lead time). There is a small, motivated team, which can be supplemented by auxiliary staff if required.

### Known Challenges for the Company:

* Significant decline in sales and profits last year.
* A high number of returns—partly due to defective or delayed items, partly due to "return kings" among customers, and also from some suppliers.



## Data diagram

Here is a description of the data.

![sqldiagram](images/sqldiagram.png)

* **Orders Table**: Contains the previous orders and if there were any returns, discounts, or delays impacting the sale.
* **Supplier Table**: Contains the location of the supplier.
* **Customer Table**: Contains the customer demographic information.
* **Article Table**: Contains information about

## Technical Details

The team needs to analyze the data in SQL, figure out the best way to use the provided view (or create your own view), and try to find a way to solve the known challenges faced by the company.
In the Azure Portal you can find the connection information for the database. Utilize [SQL Server Management Studio](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16) to query the data. 



## Success Criteria

Connect to the SQL Server instance. After connecting, look into the tables & views and try and come up with a query that helps explain why there are so many returns on some items. The team must be able to explain the thought process behind the decisions to the coach and provide insights into those decisions. 

## Resources


- https://learn.microsoft.com/en-us/azure/azure-sql/database/connect-query-ssms?view=azuresql

## Conclusion

By completing this challenge, you will gain hands-on experience in restoring and managing SQL Server databases in Azure, querying data effectively, and using views to derive meaningful insights. This foundation will help you analyze and solve real-world business challenges using Azure’s data services.


