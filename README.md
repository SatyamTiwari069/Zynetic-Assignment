# Bookstore Management System API

This project provides a RESTful API for managing a bookstore, allowing users to perform operations such as adding, retrieving, updating, and deleting book information.

## Features

- **Database Schema**: Utilizes a MySQL database to store book details, including title, author, ISBN, price, and quantity.
- **API Endpoints**: Provides endpoints for performing CRUD operations on books:
  - Adding a new book
  - Retrieving all books
  - Retrieving a specific book by ISBN
  - Updating book details
  - Deleting a book
- **Authentication**: Implements basic authentication to restrict access to certain endpoints.
- **Documentation**: Includes Swagger for clear documentation of API endpoints and usage.
- **Testing**: Provides unit tests for the API endpoints to ensure functionality and handle edge cases and errors effectively.

## Technologies Used

- Flask: Python web framework for developing the RESTful API.
- Flask-SQLAlchemy: SQLAlchemy integration for database management.
- Flask-HTTPAuth: Library for implementing basic authentication in Flask applications.
- Flask-Swagger: Integration of Swagger/OpenAPI Specification for API documentation.
- MySQL: Relational database management system for storing book details.

## Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Set up the database:
- Configure the MySQL database URI in app.py.
- Ensure the database is created with the necessary table book.
4. Run the application:
   Navigate to application folder and run the file as:
   ```bash
   python app.py
   ```
## API Documentation

The API documentation is available in Swagger and can be accessed by running the application and visiting the Swagger UI endpoint (/apidocs) in a web browser.

## Testing

Unit tests are included to ensure the correctness and reliability of the API endpoints. To run the tests, use the following command:
```bash
python test_app.py
```
## Postman Screenshots:

![addbook](outputs/postman-addbook.png)


![getbook](outputs/postman-getbook.png)


![getbook](outputs/postman-getbookbyisbn.png)

   
