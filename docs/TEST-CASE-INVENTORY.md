# Test Case Inventory

This is a high-level inventory of test areas covered in the Postman collection. Refer to the exported Postman collection for the exact saved request names and assertion scripts.

| Area | Scenario | Validation focus |
|---|---|---|
| Authentication | Login with valid credentials | Success status, token, user fields, JSON response |
| Authentication | Login with invalid credentials | Rejection status and error response |
| Authentication | Missing password | Validation error response |
| Authentication | Profile with valid token | Successful profile response and field types |
| Authentication | Profile with invalid token | Unauthorized response |
| Authentication | Profile without token | Unauthorized response |
| Products | Get all products | Product array, required fields, pagination metadata |
| Products | Get a single product | ID, title, price, category |
| Products | Nonexistent product | Not-found response |
| Products | Search products | Results array and search response structure |
| Products | Search matching | Result text and IDs |
| Products | Filter by category | Returned categories match requested category |
| Products | No matching search results | Empty array and zero total |
| Products | Pagination | Limit, skip, and page size |
| Products | Price ascending | Price order and data types |
| Products | Price descending | Price order and data types |
| Products | Select fields | Requested fields present and unrequested fields excluded |
| Carts | Get a cart | Cart ID, products, quantities, totals |
| Carts | Add products | User ID, product quantities, total quantity |
| Carts | Update a cart | Updated product quantity and response fields |
| Carts | Delete a cart | Deletion flag and timestamp |
| Carts | Nonexistent cart | Not-found status and error message |
| Carts | Quantity consistency | Sum of item quantities matches cart total quantity |
