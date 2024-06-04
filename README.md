Chocolate Factory Inventory System

Description:
You are tasked with creating a Java application for managing the inventory of a chocolate factory. The application should utilize inheritance and SQL to model and store information about different types of chocolate products.

Requirements:
1. Create a base `Chocolate` class with the following properties:
   - `id` (Long)
   - `name` (String)
   - `price` (BigDecimal)
   - `weight` (double)

2. Implement a `ChocolateRepository` class that handles the interaction with the relational database (e.g., MySQL or PostgreSQL). The `ChocolateRepository` should have methods for:
   - Establishing a database connection
   - Creating the necessary tables based on the chocolate class hierarchy
   - Inserting chocolate product records into the database
   - Retrieving chocolate product records from the database
   - Updating chocolate product records in the database
   - Deleting chocolate product records from the database

3. Implement a simple command-line interface (CLI) that allows users to interact with the chocolate factory inventory system. The CLI should provide options for:
   - Adding a new chocolate product
   - Retrieving a chocolate product by ID
   - Retrieving all chocolate products
   - Updating a chocolate product
   - Deleting a chocolate product

   The CLI should directly call the methods of the `ChocolateRepository` to perform these operations.

4. Write unit tests for the `ChocolateRepository` class to ensure the correctness of the implemented functionality.





