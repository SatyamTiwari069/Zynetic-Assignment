# API for the Bookstore Management System 
This project offers a RESTful API for bookstore management, enabling users to add, retrieve, update, and remove book information, among other tasks. 

## Features -
**Database Schema**: Stores book information such as title, author, ISBN, price, and quantity in a MySQL database. -
**API Endpoints**: Offers endpoints for carrying out CRUD operations on books: - Adding a new book - Getting every book back Finding a specific book using its ISBN Revising book information Eliminating a book
**Authentication**: Uses simple authentication to limit access to specific endpoints. 
**Documentation**: Provides clear documentation of API endpoints and usage using Swagger. 
**Testing**: Offers unit tests for the API endpoints to guarantee functionality and efficiently manage errors and edge cases.

## Technology Employed Flask is a Python web framework used to create RESTful APIs.

## Setup 1. Install dependencies: ```bashpip install -r requirements.txt ```
2. Configure the database: Set up the URI for the MySQL database in app.py. Make sure the required table book is included when creating the database.
 3. Launch the program: Open the application folder and execute the file as follows: ```bash python app.py ```

## API Documentation
Running the application and going to the Swagger UI endpoint (/apidocs) in a web browser will provide access to the Swagger API documentation.

## Examining To guarantee the accuracy and dependability of the API endpoints, unit tests are incorporated.
Use the following command to execute the tests: ```bash Python test_app.py `` 

## Postman Screenshots:

![postman-getbookbyisbn](https://github.com/user-attachments/assets/33285d75-0738-4de7-8ffe-0521650e7c05)
![postman-getbook](https://github.com/user-attachments/assets/3c267848-5c74-4a4f-825a-c6985267f48c)
![postman-addbook](https://github.com/user-attachments/assets/81275e0d-9306-4e2f-8bc4-d79b6f06cacc)

