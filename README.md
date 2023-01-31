# RCB-Bank-Customer-Churn-Analysis
In this project i have analyzed the customer's leaving the bank using PowerBI dashboard

## About the Dataset:
Here i have bank churn excel file that contains the data of customers of RCB bank.
Also there are other excel file like customer info, gender info, credit card holder etc.
all these files are linked to bank churn file.

## Data Cleaning Process:
First i collected the data into our PowerBI query editor throgh our system.
Then i cleaned the data and make it to usable format.

## Columns & Measure
I created a column named Date Master
The date master column contains the month name, year and date.
I created a column name calculation where i have different different measures such as
Total customer in the bank, active inactive customer, credit card holder, non credit card holder.

## Data Modelling:
I kept bank churn data as fact table and other data as dimension table.
I linked all the dimension table to fact table. Also i linked Date Master table to the fact table by DOJ column.

## Dashboarding

In the dashboard i have used diffent types of visualization charts and bars. ALso i have created bookmarks with button function.
The dahsboard contains two page one is Homepage and other page is Churn percentage.
In homepage i have given a forward button, By clicking on forward button i can directly jump to churn percentage page.

## Conclusion

By seeing the dashboard we can coclude that:
1) The percentage of leaving the bank is more for the customer who have no
credit card and whose credit score is fair.
2) Exit customer is always higher that previous month exit customer throught all the year.
3) Exit customer by gender has no significant effect.
4) Exit customer in france is 50 % whearese in spain and germany is 25 %.
5) For the month of march 2019 the churn % (Exit customer percentage) is lowest and higher for august month 2019.
