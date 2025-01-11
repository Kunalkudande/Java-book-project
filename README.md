# 📚 Bookstore Management System

A terminal-based Java application to manage books, track sales, and calculate profits/losses using Object-Oriented Programming (OOP) principles.

## Features
1. **Add Books**: Add book details (name, author, price, quantity) with input validation.
2. **View Books**: Display all available books with details like price and stock.
3. **Purchase Books**: Buy books by ID, update stock, and calculate profit/loss.
4. **Profit/Loss**: Check total profit and loss from all transactions.
5. **Validations**: Ensure correct inputs (e.g., alphabetic names, 10-digit phone numbers).

## OOP Concepts Used
- **Encapsulation**: Book details are stored and managed using private fields with getter and setter methods.
- **Abstraction**: Only relevant details are shown to the user through simple methods, while the internal data is hidden.
- **Inheritance**: In future expansions, new types of books or transactions can be derived from the base class.
- **Polymorphism**: Method overloading for validating different inputs like names, phone numbers, and integers.

## Usage
- Run the Program:
- javac Main.java.
- java Main

## Example Menu:
- 1. Add Book  
- 2. Display Books  
- 3. Purchase Book  
- 4. Check Profit/Loss  
- 5. Exit  
