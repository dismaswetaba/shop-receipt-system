# Shop Receipt Program

## Description

The Shop Receipt Program is a simple Python program that calculates the total cost and balance of items purchased from a shop and displays a well formated receipt for the customer

This project was created as a personal programming practice project to strengthen my understanding of Python fundamentals.

## Features

* Collect item details from the customer and store in a list called cart
* Calculates the cost of each item
* Calculates the total purchase cost
* Calcualate balance 
* Display a well formated receipt for the customer
* Save the receipt to a txt file

## Technologies Used

* Python 3
* Git
* GitHub
* Vs code

## Project Structure

```text
shop-receipt/
├── shop-receipt-system.py
└── README.md

```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/dismaswetaba/shop-receipt-system.git
```

2. Enter the project directory:

```bash
cd shop-receipt
```

## Usage

Run the program using:

```basread
Ph
python3 receipt.py
```
First start by authenicating your username by default now is "DISMAS"  , then password which is "####"
Follow the instructions displayed in the terminal and enter the required item details like name, price, quantity or type done if finished.

## Example

```text
__________________________________________________
SHOP RECEIPT PROGRAM
__________________________________________________
Enter username: Dismas
Enter password: ####
Error: username or password is incorrect
Enter username: DISMAS
Enter password: ####
Login successfull.

__________________________________________________
         CUSTOMER DETAILS      
__________________________________________________

Enter customer name: methu
Enter customer phone number: 0704993409

__________________________________________________
         COLLECTING ITEM DETAILS
__________________________________________________
Enter item name (or type 'done' to finish): maize
Enter the price for maize: 120
Enter quantity for maize: 2
Enter item name (or type 'done' to finish): sugar
Enter the price for sugar: 130
Enter quantity for sugar: 3
Enter item name (or type 'done' to finish): salad
Enter the price for salad: 250
Enter quantity for salad: 2.5
Enter item name (or type 'done' to finish): done
The total cost is: Ksh. 1255.0
Eter money paid by the customer: 2000
__________________________________________________
    CUSTOMER RECEIPT   
__________________________________________________
Customer Name: methu 
Phone Number: 0704993409

__________________________________________________
No.  Item Name       Price    QTY    Cost      
__________________________________________________
1    maize           120.00   2.0    240.00    
2    sugar           130.00   3.0    390.00    
3    salad           250.00   2.5    625.00    

__________________________________________________
Total Cost                               : Ksh.1255.00 
Money Paid                               : ksh.2000.00 
Balance                                  : Ksh.745.00

Payment successful. Thank you.
Receipt saved successfully.
Thank you for shopping with us. God bless you.

```

## What I Learned

Through this project, I practiced:
* Security features
* Variables
* Data types
* User input using `input()`
* Type conversion
* Arithmetic operators
* Functions
* Loops
* Defensive programming
* Formatted output
* Input validation
* File handling

## Future Improvements
* Impliment better security features 
* Save the receipt and customer details to a database
* Make the system user friendly and accessible on browsers
* Allow multiple items to be added
* Add discounts
* Add tax calculations
* Add customer information
* Save receipts to a file
* Add date and time to the receipt

## Author

**Dismas Wetaba**

This project was created for learning and practicing Python programming fundermentals.

