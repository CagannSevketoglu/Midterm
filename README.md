# Travel Company API

This repository contains the source code for the Travel Company API, a Flask-based web application that allows users to query available houses, book stays, and manage user registrations and logins.


## Design

### Project Structure

The project structure is organized as follows:

- **app/**
  - **\_\_init\_\_.py:** Initialization of Flask app and configuration.
  - **routes.py:** Definition of API routes and resources.
  - **models.py:** SQLAlchemy models for database tables.
  - **static/swagger.json:** Swagger API documentation.
- **config.py:** Configuration settings, including database connection.
- **run.py:** Main script to run the Flask app.
- **README.md:** Documentation for the project.


## Functionality

The API provides the following functionality:

- **QueryHouses:** Retrieve available houses based on date, number of people, and pagination.

- **BookStay:** Allow authenticated users to book stays for specified dates and names.

- **UserRegistration:** Register new users.

- **UserLogin:** Authenticate and log in existing users.

