# This is a practice project to show my knowledge of SQL tables and queries

### Overview:
This project is a relational database designed to manage sales data for a business. It utilizes MySQL to store and organize information about products, categories, customers, and transactions.

### Database Structure:
It consists of 4 main tables and are as follows;
  1. Categories: Stores information about product categories.
     * category_id: Unique identifier for each category.
     * category_name: Name of the category.

  2. Products: Stores information about products.
     *  product_id: Unique identifier for each product.
     *  product_name: Name of the product.
     *  price: Price of the product.
     *  quantity_in_stock: Quantity of the product in stock.
     *  category_id: Foreign key referencing the category table, indicating the product's category.

  3. Customers: Stores information about customers.
     * customer_id: Unique identifier for each customer.
     * first_name: First name of the customer.
     * last_name: Last name of the customer.
     * email: Email address of the customer.
     * location: Location of the customer ('Altered' after initial creation).

  4. Orders: Stores information about sales transactions.
     * order_id: Unique identifier for each order.
     * customer_id: Foreign key referencing the customers table, indicating the customer who placed the order.
     * product_id: Foreign key referencing the products table, indicating the product purchased.
     * order_date: Date the order was placed.
     * total_amount: Total amount of the order.

![DB Table](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2001.png)
