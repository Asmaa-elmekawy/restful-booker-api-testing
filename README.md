# Restful Booker API Testing

## Project Overview

A Postman API testing project for the Restful Booker API, focused on validating authentication, booking operations, negative scenarios, and API response behavior.

## Tools & Technologies

* Postman
* REST API
* JavaScript (Postman test scripts)
* Git & GitHub

## Test Coverage

### 1. Authentication

* Generate an authentication token.
* Validate requests using a valid token.
* Test invalid and missing authentication.

### 2. Booking Operations

* Retrieve booking details.
* Create a new booking.
* Partially update booking details.
* Delete a booking.

### 3. Negative Testing

* Invalid booking ID.
* Invalid authentication token.
* Missing required fields.
* Invalid data types.
  
### 4. Data Validation

* Response schema validation.
* Required field validation.
* HTTP status code assertions.
* Response time validation.

## How to Run

1. Download or clone this repository.
2. Open Postman and import the collection JSON file.
3. Configure the `baseUrl` variable with the API base URL.
4. Run the authentication request to generate a valid token.
5. Ensure the token and booking ID variables are configured correctly.
6. Execute the requests individually or run the collection using Collection Runner.

## Notes

* This project uses the public Restful Booker practice API.
* The API may reset its data or behave inconsistently because it is a shared practice environment.
* Some booking operations may modify temporary test data.

## Author

Asmaa Elmekawy
