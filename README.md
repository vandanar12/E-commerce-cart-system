# Simple-E-Commerce-Cart-System
This is a simple E-commerce cart system implemented in Python. Users can add products to their cart, update quantities, and view the total bill. The code also includes product discount functionality.

# Features:
1. Product class for representing products with name, price, and availability.
2. DiscountedProduct class as a subclass for products with a percentage discount.
3. ShoppingCart class for managing the shopping cart with add, update, and remove functions.
4. Calculation of the total bill for items in the cart.

# Code explanation:

The provided code is a Python implementation of a simple E-commerce cart system that allows users to manage a shopping cart, add products, update quantities, and calculate the total bill. It also incorporates features such as product discounts and a subclass for discounted products. Here's a brief description of the key components and functionality of the code:

Product Class:

The Product class represents a basic product and has attributes for name, price, and availability.
It includes a calculate_discount method, which returns a default discount of 0% for regular products.
The __str__ method provides a string representation of the product, displaying the name and price.

DiscountedProduct Class:

DiscountedProduct is a subclass of Product and extends it to include an additional attribute, discount_percentage.
The calculate_discount method in this class calculates the discount amount based on the given percentage.

ShoppingCart Class:

The ShoppingCart class manages the user's shopping cart, allowing them to add, update quantities, and remove items.
It maintains a list of items in the cart, where each item is a dictionary containing the product and its quantity.
Methods include add_to_cart, update_quantity, remove_from_cart, and calculate_total_bill to interact with the cart and perform calculations.

Example Usage:

At the end of the script, there is an example usage section demonstrating how to create products, add them to the cart, update quantities, and calculate the total bill.
It showcases the creation of a laptop and a headphones product, adding them to the cart, updating the quantity of the laptop, and then removing the headphones from the cart.
Finally, it calculates the total bill for the items in the cart and displays the results.
This code provides a basic foundation for an E-commerce cart system with the ability to handle different types of products, including those with discounts, and allows users to perform typical cart operations. It can serve as a starting point for building a more comprehensive E-commerce system with additional features and a user interface.
