# Tajay-Robb-Point-of-Sale-System
# Point of Sale System – Best Buy Supermarket

#Author: Tajay Robb

Course:
ITT103 - Programming Techniques  

#Date created: April 5, 2025

---

#Project Overview

This Python-based Point of Sale (POS) System simulates a small supermarket checkout system. Built as a major project, it features a functional interface where users can browse products, add/remove from cart, and complete purchases with receipt generation.

---

#Features

- Product Catalog with prices, stock levels, and units  
- Search Functionality by product name or serial number  
- Add to/Remove from Cart with quantity updates  
- View and Clear Cart 
- Checkout with tax and discount calculations  
- Receipt Generation saved as `.txt` file  
= Timestamped Transactions based on Jamaica timezone

---

#Applications used

- Python 3
- `datetime` & `pytz` libraries
  
---

#Files Included

- `robb_tajay_point_of_sale_system.py` – Main Python program
- `receipt_XXXXXX.txt` – Generated receipt files (after checkout)

---

#How to Run

1. Install Python 3 if not already installed.
2. Download the project files.
3. Open a terminal/command prompt.
4. Run the script:

#Assumptions:
1. The user will enter valid product names or serial numbers.
2. All transactions occur in a single session as there is no data saved between runs.
3. Prices are in Jamaican Dollars (JMD).
4. Product quantities are updated in memory only during the current session.
5. The timezone is fixed to Jamaica using the pytz library.
6. Receipts are saved as .txt files in the local directory using a random 6 digit number.
7. Product identification by name is case insensitive.
8. The system is used by one person at a time.

#Limitations:
1. No graphical user interface.
2. No persistent data storage for inventory or transaction history.
3. No user login or authentication system.
4. No duplicate receipt number check; files may be overwritten if numbers repeat.
5. Discount and tax rules are fixed and not configurable.
6. Limited input validation for product names and quantities.


