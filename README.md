## Title: Python-based Inventory Management System

### Description:
This is a straightforward inventory management system developed in Python. It is designed to provide a simple yet effective way to track products, manage stock levels, and record sales transactions. All inventory and sales data are persisted in JSON files, eliminating the need for a database server. The application features a user-friendly, menu-driven command-line interface.

### Key Features:
~ Product Catalog  : View all available products, including their IDs, names, prices, and quantities.
~ Stock Updates    : Add new products, update the quantity of existing items, and remove items from the inventory.
~ Sales Processing : Simulate sales transactions, which automatically reduces the stock count.
~ Sales Records    : Log all transaction details (e.g., product, quantity, timestamp) for later review.

### Technologies Used:
Python             : The core language for the application logic.
JSON               : Used for handling and persisting data on disk.
Built-in Libraries : Only standard Python libraries are used, such as json and datetime, so no external dependencies are required.
