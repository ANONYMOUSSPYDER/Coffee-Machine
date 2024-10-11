# Coffee-Machine
# Coffee Machine Simulator

This is a simple Python-based coffee machine simulator that allows users to order different types of coffee, manage resources, and process transactions. The program features a menu of drinks, checks for sufficient ingredients, handles user payments, and provides reports on resource levels and profit.

## Features

- **Drink Selection**: Users can choose from three types of coffee: espresso, latte, and cappuccino.
- **Resource Management**: The simulator tracks available ingredients (water, milk, coffee) and checks if there are enough resources to fulfill orders.
- **Payment Processing**: Users can insert coins and the program will handle transactions, providing change if needed.
- **Reporting**: Users can request a report of current resources and total earnings.

## Functions

- `is_resource_sufficient(order_ingredients)`: Checks if there are enough ingredients for the requested drink.
- `process_coins()`: Calculates the total amount inserted by the user.
- `is_transaction_successful(money_received, drink_cost)`: Validates the payment and updates the profit.
- `make_coffee(drink_name, order_ingredients)`: Deducts the necessary ingredients from the available resources and confirms the order.

## Usage

1. Run the program in a Python environment.
2. Follow the prompts to select a drink or request a report.
3. Enter the number of coins as prompted.
4. The program will either serve the drink or inform you of insufficient resources or funds.

## Requirements

- Python 3.x

Feel free to contribute or suggest enhancements!
