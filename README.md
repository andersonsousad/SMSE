# SMSE - Sales Management System for E-commerce
This project is a sales management system for e-commerce, developed using Flask, SQLAlchemy, and Node.js for some frontend functionalities. The system allows efficient management of products, customers, and orders.

## Technologies Used
- **Flask**: Web framework for the backend.
- **SQLAlchemy**: ORM used for database interaction.
- **PostgreSQL**: Relational database.
- **Node.js**: Used for additional frontend functionalities.

## Features
- CRUD for Products
- CRUD for Customers
- CRUD for Orders

## How to Run
1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/ecommerce.git
    cd ecommerce
    ```

2. **Create a virtual environment and install the dependencies**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

3. **Configure the database in the `config.py` file**

4. **Start the application**
    ```bash
    python run.py
    ```

5. **Testing**
    Use Postman or cURL to make requests to test the routes.
