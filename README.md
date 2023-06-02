# Shopping Basket Program

This program calculates the total price of items in a shopping basket, taking into account special offers and discounts.

## Installation

1. Ensure that you have Scala and Git installed on your machine.


   Scala

   1.1. Visit the official Scala website at https://www.scala-lang.org/download/.

   1.2. Scroll down to the "Latest Releases" section and click on the download link for the latest version of Scala for Windows.

   1.3. Choose the installer appropriate for your system (32-bit or 64-bit) and click on the download link.

   1.4. Once the download is complete, run the installer and follow the on-screen instructions.

   1.5. During the installation process, you may be asked to specify the installation directory. Choose a suitable location and proceed with the installation.

   1.6. After the installation is complete, open a new command prompt or terminal window and type scala -version to verify that Scala is installed correctly. You should see the Scala version information printed on the screen.

   Git

   2.1. Visit the official Git website at https://git-scm.com/downloads.

   2.2. Scroll down to the "Downloads" section and click on the download link for the Windows version.

   2.3. The download will start automatically. Once it is complete, run the installer.

   2.4. In the Git Setup wizard, follow the on-screen instructions, leaving the default options selected unless you have specific preferences.

   2.5. On the "Adjusting your PATH environment" screen, select the option "Git from the command line and also from 3rd-party software."

   2.6. Choose the default line ending conversion option (either "Checkout Windows-style, commit Unix-style line endings" or "Checkout as-is, commit Unix-style line endings").

   2.7. Choose the default terminal emulator for Git (either "Use Git Bash only" or "Use Git and optional Unix tools from the Windows Command Prompt").
   
   2.8. Leave the default options selected for configuring extra features and completing the installation.

   2.9. After the installation is complete, open a new command prompt or terminal window and type git --version to verify that Git is installed correctly. You should see the Git version information printed on the screen.

3. Open your terminal or command prompt.
4. Clone the repository using the following command:
   ```shell 
   git clone https://github.com/your-username/shopping-basket.git
4. Change to the project directory:
     ```shell 
     cd shopping-basket

## Usage

1. Open your terminal or command prompt.
2. Change to the project directory if you're not already in it:
      ```shell
      cd shopping-basket

3. Run the program with the desired input. For example, to calculate the total price for items "Milk" and "Soup", use the following command:
      ```shell
      scala PriceBasket.scala Milk Soup

The program will display the subtotal, any applicable discounts, and the total price.

4. Experiment with different input combinations to test the program's behavior.

## Test Cases

Here are some example test cases you can try:

1. Case: 4 soups and 2 breads (with special offer)
      ```shell
      scala PriceBasket.scala Soup Soup Soup Soup Bread Bread

2. Case: 2 soups and 3 apples (with discount on apples)
      ```shell
      scala PriceBasket.scala Soup Soup Apples Apples Apples

3. Case: 1 milk, 1 bread, and 1 apple (no offers)
      ```shell
      scala PriceBasket.scala Milk Bread Apples

Feel free to modify and add your own test cases to explore the program's functionality.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


