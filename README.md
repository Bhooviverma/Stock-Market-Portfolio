# 📈 Stock Portfolio Manager (C Project)

A simple console-based **Stock Portfolio Manager** developed in **C Programming Language**. This project allows users to buy stocks, view their portfolio, update market prices, calculate profit/loss, and sell stocks through a menu-driven interface.

---

## 🚀 Features

### 1. Buy New Stocks

* Choose from a predefined list of 10 popular stocks.
* Enter your purchase price.
* Stock is added to the portfolio.

### 2. View Portfolio

* Displays all purchased stocks in a formatted table.
* Shows:

  * Stock Name
  * Purchase Price
  * Current Market Price
  * Profit/Loss
* Calculates total portfolio value and overall profit/loss.

### 3. Update Market Prices

* Allows users to update the current market price of each stock.
* Profit/Loss is recalculated automatically.

### 4. Sell Stocks

* Sell any stock from the portfolio.
* Displays realized profit/loss before removal.
* Updates portfolio after selling.

### 5. User-Friendly Interface

* Menu-driven navigation.
* Input validation to prevent invalid entries.
* Colored output using ANSI escape codes:

  * 🟢 Green = Profit
  * 🔴 Red = Loss
  * 🔵 Blue = Headings

---

## 📋 Available Stocks

| Stock Name          | Current Price (₹) |
| ------------------- | ----------------- |
| Reliance Industries | 2850.50           |
| Tata Motors         | 890.75            |
| Infosys             | 1630.25           |
| HDFC Bank           | 1655.00           |
| ITC Limited         | 452.10            |
| Bharti Airtel       | 975.40            |
| State Bank of India | 742.20            |
| Hindustan Unilever  | 2600.00           |
| Wipro               | 490.60            |
| Adani Enterprises   | 3200.80           |

---

## 🛠️ Technologies Used

* C Programming Language
* Standard Libraries:

  * `stdio.h`
  * `stdlib.h`
  * `string.h`

---

## 📂 Project Structure

```text
Stock-Portfolio-Manager/
│
├── stock_portfolio_manager.c
├── README.md
```

---

## 🔒 Input Validation

The program validates:

* Menu choices
* Stock selection
* Purchase prices
* Current market prices
* Sell operations

Invalid inputs are handled gracefully without crashing the program.

---

## 🎯 Learning Concepts Demonstrated

This project demonstrates:

* Arrays and 2D Arrays
* Functions
* Function Prototypes
* Conditional Statements
* Loops
* String Handling (`strcpy`)
* Input Validation
* ANSI Escape Sequences
* Portfolio Management Logic
* Data Organization Using Parallel Arrays

---

## 📸 Sample Menu

```text
==========================================
         Stock Portfolio Manager
==========================================
1. Buy New Stock
2. View Portfolio
3. Sell Stock
4. Exit
------------------------------------------
```

---
