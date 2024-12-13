# This is a practice project to show my knowledge of SQL tables and queries

### Overview:
This project is a relational database designed to manage sales data for a business. It utilizes MySQL to store and organize information about products, categories, customers, and transactions.

### Database Structure:
It consists of 4 main tables and are as follows;
  1. Categories: Stores information about product categories.
     * category_id: Primary key for each category.
     * category_name: Name of the category.

  2. Products: Stores information about products.
     *  product_id: Primary key for each product.
     *  product_name: Name of the product.
     *  price: Price of the product.
     *  quantity_in_stock: Quantity of the product in stock.
     *  category_id: Foreign key referencing the category table, indicating the product's category.

  3. Customers: Stores information about customers.
     * customer_id: Primary key for each customer.
     * first_name: First name of the customer.
     * last_name: Last name of the customer.
     * email: Email address of the customer.
     * location: Location of the customer ('Altered' after initial creation).

  4. Orders: Stores information about sales transactions.
     * order_id: Primary key for each order.
     * customer_id: Foreign key referencing the customers table, indicating the customer who placed the order.
     * product_id: Foreign key referencing the products table, indicating the product purchased.
     * order_date: Date the order was placed.
     * total_amount: Total amount of the order.

![DB Table](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2001.png)
![DB Table cont.](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2002.png)

### Adding data to tables:
Here I have used __INSERT INTO__ to add sample data into rows and columns, along with __SELECT * FROM__ to display the contents of the table.
 
> Disclaimer: The names, emails, and locations used are all sample values and do not represent real-life information.

![Insert 1](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2003.png)
![Insert 2](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2004.png)
![Insert 3](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2005.png)

### Updating table data:
Here I have used a single query to update a row value by using the primary key for referencing the data.
![Update](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2006(Update).png)

### More Queries:
Here I have made use of various conditions and clauses such as __ORDER BY__, __WHERE__, __OR__, __AND__, __IN__, __BETWEEN__, __SUM() AS__, __LIKE__`(image above)` to retrieve certain specific data from different tables.

![Queries 1](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2006(Crop).png)
![Queries 2](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2007.png)
![Queries 3](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2008.png)

### Deleting table data:
Here I added a new row data to the products table and deleted the same to illustrate __DELETE FROM__ with __WHERE__ clause to be careful about deleting all records in the table.

![Delete](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2009.png)

### Various Joins:
Here I have used __INNER JOIN__, __LEFT JOIN__, __RIGHT JOIN__ on the tables to illustrate the relational property of the table using Primary and Foreign keys and in 2 different formats.

![Joins 1](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2010.png)
![Joins 2](https://github.com/deeks02/MySQL-Learning/blob/main/Screenshots/Screenshot%2011.png)


### This is the EOF but it is just the beginning of my SQL journey.
