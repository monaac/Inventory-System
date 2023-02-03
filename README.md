# Inventory-System
An SQL data structure for an Inventory System

This data structure includes five tables: products, suppliers, orders, customers, and sales. The products table stores information about products, including their name, description, price, and stock. The suppliers table stores information about suppliers, including their name, address, and phone number. The orders table stores information about orders, including the product ID, supplier ID, order date, and quantity. The customers table stores information about customers, including their name, address, and phone number. The sales table stores information about sales, including the product ID, customer ID, sale date, and quantity.

The relationships between the tables are enforced through foreign key constraints, ensuring that an order or sale is only linked to an existing product and supplier or customer, respectively. The products and suppliers tables also have unique constraints on the name column, ensuring that each product and supplier has a unique name.
