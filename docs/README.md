# My API

This is a RESTful API for managing users.

## Endpoints

### `GET /users`

Returns a list of all users.

#### Query Parameters

- `page` (optional): The page number to retrieve. Defaults to 1.
- `limit` (optional): The number of items to retrieve per page. Defaults to 10.

#### Response

```json
[
  {
    "id": 1,
    "name": "John Doe",
    "email": "john.doe@example.com"
  },
  {
    "id": 2,
    "name": "Jane Doe",
    "email": "jane.doe@example.com"
  }
]