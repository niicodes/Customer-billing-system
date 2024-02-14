# Customer-billing-system
## All in One Store Billing System
This is a simple billing system for a store using C++. It creates a list of items with their corresponding IDs and prices, calculates the total price, and generates a bill for the customer.

### Program Functionality
The program first prompts the user to enter their name, address, and the number of items they are purchasing. It then creates an array of list objects, where each object represents an item with an ID, name, and price. The program inserts the items into the array and calculates the total price.

Finally, the program displays the bill using the display function, which takes the array of items, the size of the array, and the customer's name and address as arguments. The bill includes the customer's name and address, the ID, name, and price of each item, and the total price.

### Code Overview
The code defines a list class with three public member variables: id, name, and price.

The display function takes the array of items, the size of the array, and the customer's name and address as arguments. It calculates the total price of the items, displays the bill, and prints a thank-you message.

The main function prompts the user to enter their name, address, and the number of items they are purchasing. It creates an array of list objects, inserts the items into the array, and calculates the total price. Finally, it calls the display function to generate the bill.
