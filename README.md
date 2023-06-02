# Technical-Assignment---Shopping-Basket
# Shopping Basket Program

This program calculates the total price of items in a shopping basket, taking into account special offers and discounts.

## Installation

1. Ensure that you have Scala and Git installed on your machine.
2. Open your terminal or command prompt.
3. Clone the repository using the following command:

git clone https://github.com/your-username/shopping-basket.git

4. Change to the project directory:

cd shopping-basket

## Usage

1. Open your terminal or command prompt.
2. Change to the project directory if you're not already in it:

cd shopping-basket

3. Run the program with the desired input. For example, to calculate the total price for items "Milk" and "Soup", use the following command:

scala PriceBasket.scala Milk Soup

The program will display the subtotal, any applicable discounts, and the total price.

4. Experiment with different input combinations to test the program's behavior.

## Test Cases

Here are some example test cases you can try:

1. Case: 4 soups and 2 breads (with special offer)

scala PriceBasket.scala Soup Soup Soup Soup Bread Bread

2. Case: 2 soups and 3 apples (with discount on apples)

scala PriceBasket.scala Soup Soup Apples Apples Apples

3. Case: 1 milk, 1 bread, and 1 apple (no offers)

scala PriceBasket.scala Milk Bread Apples


Feel free to modify and add your own test cases to explore the program's functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


