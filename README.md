# RCB-Bank-Customer-Churn-Analysis
In this project, I have analyzed the customer's leaving the bank using the PowerBI dashboard

## About the Dataset:
Here I have a bank churn excel file that contains the data of customers of RCB bank.
Also, there is another excel file with customer info, gender info, credit card holder, etc.
all these files are linked to the bank churn file.

## Data Cleaning Process:
First, I collected the data into our PowerBI query editor through our system.
Then I cleaned the data and make it into a usable format.

## Columns & Measure
I created a column named Date Master
The date master column contains the month name, year, and date.
I created a column name calculation where I have different measures such as
Total customers in the bank, active inactive customers, credit card holders, and non-credit card holders.

## Data Modelling:
I kept bank churn data as a fact table and other data as a dimension table.
I linked all the dimension tables to the fact table. Also, I linked the Date Master table to the fact table by DOJ column.

## Dashboarding

In the dashboard, I have used different types of visualization charts and bars. Also, I have created bookmarks with button functions.
The dashboard contains two pages one is Homepage and another page is the Churn percentage.
On the homepage I have given a forward button, By clicking on the forward button I can directly jump to the churn percentage page.

## Conclusion

By seeing the dashboard we can conclude that:
1) The percentage of leaving the bank is more for the customer who has no
credit card and whose credit score is fair.
2) Exit customer is always higher than the previous month's exit customer throughout the year.
3) Exit customer by gender has no significant effect.
4) Exit customer in France is 50 % whereas in Spain and Germany is 25 %.
5) For the month of march 2019 the churn % (Exit customer percentage) is lowest and higher for august month 2019.
