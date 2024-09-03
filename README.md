# Coffee Machine

**Coffee Machine** is a simple program that simulates a coffee vending machine with three options: Espresso, Latte, and Cappuccino. Each coffee type has a specific cost and requires certain ingredients. The machine checks for sufficient ingredients before making the coffee and provides a warning if ingredients are insufficient.

## Menu

- **Espresso**: ₹90
  - Ingredients: 50ml water, 18g coffee
  
- **Latte**: ₹120
  - Ingredients: 200ml water, 150ml milk, 24g coffee
  
- **Cappuccino**: ₹160
  - Ingredients: 250ml water, 100ml milk, 24g coffee

## Features

- **Three Coffee Options**: Choose between Espresso, Latte, and Cappuccino.
- **Ingredient Check**: The machine checks if there are enough ingredients before making the coffee.
- **Warning System**: If there are not enough ingredients for the selected coffee, the machine will display a warning and not dispense the coffee.
- **Payment System**: After placing an order, the machine asks you to insert notes (₹500, ₹100, ₹50, and ₹10).
- **Change Dispensing**: If the inserted amount exceeds the coffee cost, the machine will dispense the change along with the coffee.
- **Insufficient Funds Warning**: If the inserted notes are not enough to cover the coffee cost, the machine will display a "Not enough money" message and return the inserted notes.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Udaya-P/Coffee_Machine.git
    ```
2. Navigate to the project directory:
    ```bash
    cd coffee_machine
    ```
3. Run the program
   ```bash
    python3 main.py
    ```
## Usage

1. Run the coffee machine program.
2. Select the desired coffee option by entering `espresso`, `latte`, or `cappuccino`.
3. Insert the required notes (₹500, ₹100, ₹50, ₹10) as prompted by the machine.
4. If the notes cover the cost:
   - The machine will prepare your coffee.
   - It will also dispense any change owed.
5. If the notes are insufficient:
   - The machine will display a "Not enough money" message.
   - Your notes will be returned, and the coffee will not be dispensed.

