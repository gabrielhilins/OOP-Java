# Object Oriented Programming with Java

[Portuguese version of this repository](https://github.com/gabrielhilins/POO-Java)

## About the Repository
- This repository contains several programs using **Object-Oriented Programming** concepts, using the **Java** programming language.

- The project is divided into 2 parts: **Methods** and **Classes and Objects**

- Methods: This folder contains Java programs using methods and constructors.

- Key Programs in this folder:

- 🏦 Simple Digital Bank

    - [AppDigitalBank.java]() and [CheckingAccount.java]()

        - **Requirements**: A **digital bank** wishes to offer its customers a simplified experience through a checking account that allows deposits, withdrawals, transfers, and balance inquiries. To meet this need, the CheckingAccount class was created with the attributes accountNumber (String), balance (double), and accountHolderName (String).
            - Methods:
                - deposit(double amount): increases the balance.
                - withdraw(double amount): decreases the balance if sufficient funds are available.
                - transfer(CheckingAccount destination, double amount): transfers an amount from one account to another.
                - displayBalance(): shows the current account balance.

- 📦 Inventory Manager
    - [AppInventoryControl.java]() and [ProductInventory.java]()

        - **Requirements**: Small warehouses need an **efficient system to manage their product inventory**. The ProductInventory class should allow control of the name (String), quantity (int), and unit price (double) of each product, facilitating the addition and removal of items, as well as allowing price updates and displaying product information.
            - Methods:
                - addToInventory(int quantity): increases the quantity in inventory.
                - removeFromInventory(int quantity): decreases the quantity in inventory if sufficient quantity is available.
                - updatePrice(double newPrice): updates the unit price of the product.
                - displayProduct(): shows the name, quantity, and price of the product.