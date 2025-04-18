# Yousef store

## overview
Yousef store is a simple inventory management system built in python. this project was developed as part of assignment 7 for a programming course. the program allows users to manage product in a store by adding, editing, removing, searching, displaying, and buying products. all product data is stored in a text file (`database.txt`) for persistence.

## Features
- **Add product:** add a new product with a unique code, name, price, and count.
- **Edit product:** Edit an existing product's details (name, prise, count) by its code.
- **Remove product:** Remove a product from the inventory by its code.
- **Search product:** Search for a product by its name.
- **show list:** Display all products in the inventory.
- **Buy product:** Buy a specific quantity of a product, updating the inventory accordingly.
- **Discount:** Apply a discount (in percentage) to a product's price.
- **Exit:** Save all changes to the database and exit the program.

## How to Run
1. **Prerequisites:**
   - Python 3.x must be installed on your system.

2. **steps:**
   - clone or download the project files (`store.py` and `database.txt`).
   - Open a terminal and navigate to the project directory.
   -Run the program using the following command:
   ```
   python store.py
   ```
   - Follow the on-screen menu to interact with the program.

## File Structure
- **`store.py:** The main python script containing the program logic.
- **`database.txt`:** A text file that stores product data in the format `code,name,price,count`.
- **`README.md`:** This file, providing documention for the project.

## Usage Example

1. Start the program:
Welcome to Yousef Store loading... Data loaded. 1-Add  2- Edit 3- Remove 4- search 5- show List 6- Buy 7- Discount 8- Exit Enter your choice (1-8):

2. Add a product:
 - choose option `1` to add a product:
 ```
 Enter your choice (1-8): 1
 Enter code: 101
 Enter name: apple
 Enter price: 5000
 Enter count: 10
 product added successfully!
 ```

3. Show the product list:
 - Choose option `5` to display the list:
 ```
 Enter your choice (1-8): 5
 101 Apple 5000
 ```

4. Apply a discount:

 - Choose option `7` to apply a discount to a product:
```
 enter your  choice(1-8): 7 Enter product code to apply
discount: 101 Enter discount percentage (0-100):20 Discount
applied successfully! New price of Apple is 8000.
```

- Check the updated list:
```
enter your choice(1-8): 5
101 Apple 8000
```

 5.Buy a product:
  - Choose option `6` to buy a product:
  ```
  Enter your choice (1-8): 6
  Enter product code to buy: 101
  Enter quantity to buy: 3
  Successfully bought 3 of Apple!
  ```

6. Exit the program:
 - Choose option `7` to exit:
 ```
 Enter your choice (1-8): 7
 mese edam vared kon :')
 ```

 ## Author
 - **Yousef**
 Developed as part of assignment 7 for a programming course.
