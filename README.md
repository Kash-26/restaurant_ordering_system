# Restaurant Ordering System

A **menu-driven Restaurant Ordering System** built in Python using **Object-Oriented Programming (OOP)**. The project demonstrates core Python programming concepts such as classes, objects, constructors, methods, data structures, exception handling, loops, conditional statements, and CSV file handling.

## Features

* Display restaurant menu
* Add food items to cart
* View shopping cart
* Remove items from cart
* Search food items by name
* View available food categories
* Calculate subtotal and GST
* Generate final bill
* Save completed orders to a CSV file
* View previous order history
* Handle invalid user input gracefully
* Automatically create required CSV files

## Technologies Used

* **Language:** Python
* **Concept:** Object-Oriented Programming (OOP)
* **File Handling:** CSV
* **Libraries:** `csv`, `os`, `datetime`

## Python Concepts Demonstrated

| Concept                | Usage                                          |
| ---------------------- | ---------------------------------------------- |
| Variables              | Store food details, prices, quantities, totals |
| Conditional Statements | Menu selection and input validation            |
| Loops                  | Menu system and displaying records             |
| Functions              | Organize program functionality                 |
| Classes                | `Restaurant` class                             |
| Objects                | `Restaurant()` object                          |
| Constructors           | `__init__()`                                   |
| Methods                | Menu, cart, checkout, search, history          |
| Lists                  | Shopping cart                                  |
| Tuples                 | Food categories                                |
| Sets                   | Unique categories                              |
| Dictionaries           | Food/menu information                          |
| Exception Handling     | Handling invalid numeric input                 |
| File Handling          | Reading and writing CSV files                  |

## Main Menu Options

1. Display Menu
2. Add Food to Cart
3. View Cart
4. Remove Item
5. Search Food
6. View Categories
7. Checkout & Generate Bill
8. Order History
9. Exit

## How It Works

### 1. Display Menu

Shows all available food items along with their ID and price.

### 2. Add Food to Cart

The user enters the food ID and quantity. The selected item is added to the cart.

### 3. View Cart

Displays all selected items, quantities, individual subtotals, and the total amount.

### 4. Remove Item

Allows the user to remove an item from the current cart.

### 5. Search Food

Users can search for food items by entering part or all of the food name.

### 6. View Categories

Displays the unique food categories available in the restaurant.

### 7. Checkout

The system:

* Takes the customer's name
* Calculates the subtotal
* Adds 5% GST
* Calculates the final amount
* Displays the bill
* Saves the order in `orders.csv`
* Clears the cart

### 8. Order History

Displays previously completed orders stored in the CSV file.

## File Handling

The project uses CSV files for permanent data storage.

## Exception Handling

The program uses `try-except` to prevent crashes caused by invalid input.
This ensures that the application continues running even when the user enters incorrect data.

## Learning Outcomes

This project provides practical experience with:

* Python OOP
* Classes and objects
* Constructors and methods
* Lists, tuples, sets, and dictionaries
* Functions
* Loops and conditions
* Exception handling
* CSV file handling
* Menu-driven programming
* Basic billing and order management
