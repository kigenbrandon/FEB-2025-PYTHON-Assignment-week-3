# PLP python week 3 assignment (Price Discount Calculator)

## Overview

This program calculates the final price of an item after applying a discount, based on the given price and discount percentage. If the discount is 20% or higher, the program applies the discount to the original price. If the discount is lower than 20%, the original price remains unchanged.

## Purpose

The program was created as part of an assignment at PLP Academy to practice working with functions, conditionals, and user input in Python.

## Functionality

- The program prompts the user to input the original price of an item and the discount percentage.
- If the discount percentage is 20% or higher, it calculates the discounted price and displays it.
- If the discount is less than 20%, it simply returns the original price without any changes.
- The program will print either the final price after applying the discount or the original price if no discount was applied.

## Code Walkthrough

### Function: `calculate_discount(price, discount_percent)`

- **Parameters**:
  - `price`: The original price of the item (float).
  - `discount_percent`: The discount percentage to be applied (float).
  
- **Logic**:
  - If the discount percentage is **20% or higher**, it calculates the discount amount and subtracts it from the original price to get the final price.
  - If the discount percentage is **less than 20%**, it returns the original price without applying any discount.

### Main Program

- The program prompts the user to enter the `price` and `discount_percent` using the `input()` function.
- It then calls the `calculate_discount` function to compute the final price.
- The result is printed: either the discounted price if the discount applies, or the original price if no discount is given.

## Example

### Sample Output:

```bash
Enter the original price of the item: $100
Enter the discount percentage: 25
The final price after applying the discount is: $75.00
```

If the user enters a discount percentage below 20%, the output will look like:

```bash
Enter the original price of the item: $100
Enter the discount percentage: 15
No discount applied. The original price is: $100.00
```

## Usage Instructions

1. **Clone or Download the repository** containing this code.
2. **Run the Python script** in your terminal or IDE.
3. **Input the original price** of the item when prompted.
4. **Input the discount percentage**.
5. The program will display the final price after applying the discount, or show the original price if no discount was applied.

## Prerequisites

- Python 3.x installed on your local machine.

## Conclusion

This program demonstrates basic Python programming concepts like functions, conditionals, and user input handling. It allows users to calculate the price of an item after applying a discount if it qualifies, making it a practical tool for scenarios that involve pricing and discounts.
