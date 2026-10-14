# DummyJSON API Testing Project

## Project Overview
This project demonstrates API testing with Postman against the public DummyJSON practice API. It covers authentication, product endpoints, and cart operations, using JavaScript assertions to validate response status codes, response structure, data types, and selected consistency rules.

## Objectives
- Validate successful and unsuccessful API requests.
- Test login and token-based access.
- Verify product retrieval, search, filtering, sorting, pagination, and field selection.
- Test cart retrieval, creation, updating, and deletion.
- Validate response structures, data types, and cart quantity consistency.
- Practise automated assertions and collection execution in Postman.

## Tools
- Postman
- JavaScript (Post-response scripts)
- DummyJSON public practice API
- Git and GitHub

## Test Coverage

### Authentication
- Login with valid credentials
- Login with invalid credentials
- Login with a missing password
- Retrieve profile using a valid token
- Reject invalid and missing tokens

### Products
- Retrieve all products and a single product
- Handle a nonexistent product
- Search products and validate search results
- Filter products by category
- Validate empty search results
- Validate pagination
- Sort by price ascending and descending
- Select specific response fields

### Shopping Carts
- Retrieve a cart
- Add products to a cart
- Update a cart
- Delete a cart
- Handle a nonexistent cart
- Validate cart quantity consistency

## Test Execution Results
The user-reported final collection run contained **122 assertions: 122 passed and 0 failed**.

These results reflect the collection run reported during project development. Run the collection again before publishing if you want to report a newly verified final result.

## How to Run
1. Install Postman.
2. Import the Postman collection JSON file.
3. Select the correct environment if your requests use environment variables.
4. Run the valid-login request first when a fresh access token is needed.
5. Run the collection with Postman's Collection Runner.
6. Review failures and investigate the actual response before changing assertions.

## Limitations
DummyJSON is a practice API, not a production e-commerce application. Some write operations simulate creation, updates, and deletion rather than permanently changing stored data. Passing assertions confirms only that the observed responses met the checks defined in this collection; it does not guarantee that all possible API behaviour is defect-free.

## Learning Outcomes
- HTTP methods and status codes
- Request bodies and response validation
- Bearer-token authentication
- Postman environment variables
- JavaScript assertions
- Positive and negative test scenarios
- Collection Runner execution
- Response and data-consistency checks

## Repository Contents
- `README.md` — project overview and instructions
- `reports/TEST-EXECUTION-REPORT.md` — test execution record
- `reports/TEST-SUMMARY-REPORT.md` — scope and summary of results
- `docs/TEST-PLAN.md` — scope, approach, and test areas
- `docs/TEST-CASE-INVENTORY.md` — high-level test-case inventory

## Favour Akpan
QA portfolio project demonstrating API testing practice with Postman and DummyJSON.
