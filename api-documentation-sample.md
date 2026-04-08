# API Documentation: User Service

## Base URL

---

## Authentication

All requests require an API key:

---

## Endpoint: Get User

### Request

### Parameters

| Name | Type | Description |
|------|------|-------------|
| id   | string | Unique user ID |

---

### Response

```json
{
  "id": "12345",
  "name": "John Doe",
  "email": "john@example.com"
}
