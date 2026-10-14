# API Test Plan

## Purpose
Define the scope and approach for practising API testing with Postman against DummyJSON.

## System Under Test
DummyJSON public practice API: `https://dummyjson.com`

## Objectives
- Validate expected status codes and response structures.
- Exercise positive and negative authentication scenarios.
- Check product retrieval, search, filtering, pagination, sorting, and field selection.
- Check cart endpoints and selected quantity consistency rules.

## Test Approach
- Send requests from Postman.
- Use post-response JavaScript scripts to assert status codes, headers, fields, data types, and selected business rules.
- Run individual requests while developing tests.
- Run the full collection with Collection Runner.
- Investigate failed assertions against the actual response before changing expectations.

## Test Areas
1. Authentication: valid login, invalid credentials, missing password, valid/invalid/missing token.
2. Products: list, single product, nonexistent product, search, search matching, category filtering, empty results, pagination, sorting, selected fields.
3. Carts: retrieve, add, update, delete, nonexistent cart, quantity consistency.

## Entry Criteria
- Postman is installed.
- The collection is imported and requests are saved.
- The intended environment is selected where required.

## Exit Criteria
- The collection has been run.
- Pass/fail results have been reviewed.
- Failures, if any, are investigated and documented.
- Reports reflect the actual run being reported.

## Risks and Limitations
DummyJSON is a practice API. Write operations may be simulated and should not be treated as proof of persistent production data changes.
