1. Function Definitions
totalbill(int itemprice, int itemquantity):
Multiplies the item price by quantity to compute the total cost for an item.
generateReport(int salesCount[], int totalSales, string reportType):
Displays the number of times each menu item was sold.
Shows total earnings.
Takes a report type parameter ("Weekly" or "Monthly") to generate different reports.
2. struct customer Definition
Defines a structure named customer with:
name: Stores the customer’s name.
phone: Stores the customer's phone number.
3. main() Function Execution
Customer Handling
The program asks for the total number of customers.
Iterates through each customer:
Collects customer name and phone number.
Menu and Ordering Process
Displays a menu with 7 items and their respective prices.
Takes user input for item choice and quantity.
Uses a switch statement to determine the price of the selected item.
Calls totalbill() to compute the bill and updates the totalSales variable.
Stores the number of times each item is sold in the salesCount array.
Asks the customer if they want to order more items.
Bill Calculation and Report Generation
After finishing the order, it displays the total bill.
Asks if the user wants to generate a weekly or monthly sales report using generateReport().
Displays the total earnings and item-wise sales count.
Handling Multiple Customers
If more customers are present, the loop continues (enter 8 for more customers).
If no more customers are there (enter 9), the program terminates.
4. Key Features
Accepts multiple customers.
Allows ordering multiple items per customer.
Tracks total sales and item-wise sales count.
Generates weekly and monthly sales reports.
Uses a loop to handle multiple customers efficiently.
