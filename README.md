# E-commerce Product Management System

## Overview
This project demonstrates a simple **E-commerce Product Management System** built in C++ using Object-Oriented Programming (OOP) principles.

## Features
- Base class `Product` with common attributes (ID, name, price, stock).
- Derived class `Electronics` with additional attributes (brand, warranty).
- Abstract class `Discountable` for applying discounts.
- Template class `InventoryList<T>` to manage product inventory.
- `ShoppingCart` class with operator overloading (`+=`, `==`).
- `Order` class to simulate checkout and payment.

## Program Flow
1. Display the inventory of products.
2. Add products to the shopping cart.
3. Handle out-of-stock cases.
4. Show cart contents and calculate the total cost.
5. Apply a discount to products (demo).
6. Confirm an order and finalize payment.

## How to Compile and Run
```bash
g++ main.cpp -o ecommerce
./ecommerce
```

## Output Example
See **Ecommerce_Output.docx** for the sample program run output.

