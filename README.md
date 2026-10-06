# Python Ordering System

A simple command-line ordering system built in Python. It lets a user pick items from a cafe menu, then calculates the subtotal, tax, and final total.

## Features

- Displays a menu of 5 items with prices
- Takes 3 menu selections from the user
- Calculates the order subtotal
- Adds 15% tax
- Prints an order summary with item names and the total

## Concepts Used

- Functions and docstrings
- Dictionaries and lists
- Loops and user input
- List comprehensions
- f-strings and rounding

## Sample Output
------- Menu -------
1. espresso  |  1.99
2. coffee    |   2.5
3. cake      |  2.79
4. soup      |   4.5
5. sandwich  |  4.99

Select menu item number 1 (from 1 to 5): 4
Select menu item number 2 (from 1 to 5): 5
Select menu item number 3 (from 1 to 5): 1
You have ordered 3 items
['soup', 'sandwich', 'espresso']
Calculating bill subtotal...
Subtotal for the order is: 11.48
Calculating tax from subtotal...
Tax for the order is: 1.72
Calculating bill subtotal...
Calculating tax from subtotal...
Order summary: Items: ['soup', 'sandwich', 'espresso'], Total: 13.2
```

## Project Structure

```
py-ordering-system/
├── ordering_system.py
└── README.md
```

## Future Improvements

- Let the user choose how many items to order
- Handle invalid input (non-numbers, items outside 1-5)
- Add item quantities