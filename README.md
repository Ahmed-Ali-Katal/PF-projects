1. Function Definitions
totalbill(int itemprice, int itemquantity):
Calculates the total cost for an item by multiplying the item price by the quantity.
generateReport(int salesCount[], int totalSales, string reportType):
Displays how many times each menu item was sold.
Shows the total earnings.
Accepts a report type parameter ("Weekly" or "Monthly") to create different reports.

2. struct customer Definition
Defines a structure called customer with:
name: Holds the customer’s name.
phone: Holds the customer's phone number.

3. main() Function Execution
Customer Handling
The program prompts for the total number of customers.
It iterates through each customer:
Gathers the customer's name and phone number.

Menu and Ordering Process
Displays a menu featuring 7 items along with their prices.
Takes user input for the chosen item and its quantity.
Utilizes a switch statement to identify the price of the selected item.
Calls totalbill() to calculate the bill and updates the totalSales variable.
Records the number of times each item is sold in the salesCount array.
Inquires if the customer wishes to order additional items.

Bill Calculation and Report Generation
Once the order is complete, it shows the total bill.
Asks if the user wants to generate a weekly or monthly sales report using generateReport().
Displays the total earnings and the sales count for each item.

Handling Multiple Customers
If there are more customers, the loop continues (enter 8 for more customers).
If there are no more customers (enter 9), the program ends.

4. Key Features
Supports multiple customers.
Allows multiple item orders per customer.
Tracks total sales and item-wise sales counts.
Generates weekly and monthly sales reports.
Efficiently manages multiple customers using a loop
