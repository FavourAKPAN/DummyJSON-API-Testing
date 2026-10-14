# Test Summary Report

## Overview
This project used Postman to practise API testing against DummyJSON, a public practice API. The collection covers authentication, product endpoints, and cart operations, with automated post-response assertions.

## Scope
**In scope**
- HTTP status-code validation
- Response body and required-field validation
- Data-type and basic value checks
- Authentication success and failure scenarios
- Product search, filtering, pagination, sorting, and field selection
- Cart CRUD-style endpoints and quantity consistency
- JSON Content-Type validation

**Out of scope**
- Production e-commerce workflows
- Real payment processing
- Persistent database verification
- Load, stress, security, or penetration testing
- Guarantees about behaviour beyond the endpoints and assertions exercised

## Reported Results
- **Assertions:** 117
- **Passed:** 117
- **Failed:** 0
- **Reported pass rate:** 100%

## Conclusion
The reported run indicates that the assertions in the collection passed against the responses returned by DummyJSON. The project demonstrates practical use of Postman, JavaScript assertions, environment variables, authentication headers, and collection execution.

The result should be described as a practice API test run, not as evidence that a production shopping application is defect-free. Since the API may simulate write operations, a successful create, update, or delete response does not establish persistent state changes.

## Recommended Next Steps
1. Rerun the collection and capture the final result screen.
2. Add the exported Postman collection JSON separately.
3. Ensure no live tokens or sensitive environment values are committed.
4. Upload the project files to GitHub.
