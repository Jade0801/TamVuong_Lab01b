##Delivery Charge Calculator
A python program that calculate the delivery charge based on the order total and the delivery day.

## Setup
Open **Anaconda Navigator**
Make sure Jupyter Notebook is installed in the Anaconda environment

##Run
Open **Anaconda Navigator** and click **Launch** button under **Jupyter Notebook**
Open and run lab01.ipynb on Jupyter Notebook

##Explaination
order_total: is the the total amout of the customer order
day_of_week: is the day that customer want to delivery
if the order_total less than 49.99 in the weekdays (Monday - Friday) -> the delivery charge will be 8
if the order_total less than 49.999 in the weekends (Saturdays and Sundays) -> the delivery charges will be 11
if the order_total more than 49.999 in the weekdays(Monday - Friday) -> the delivery charge will be 4
if the order_total more than 49.9999 in the weekends(Monday - Friday) -> the delivery charge will be 6

##Example
Enter the order total: 50
Enter the day of week: Sunday
=> Your delivery charge is: 6 
=> Because the order_total more than 49.999 and the day delivery is Sunday.
