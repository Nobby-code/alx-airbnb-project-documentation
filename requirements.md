# Airbnb Clone - Backend Feature Requirements

## 1. User Authentication

### Description
Enables users to register, log in, and manage their session securely.

### API Endpoints
- **POST** `/api/auth/register`
- **POST** `/api/auth/login`
- **GET** `/api/auth/logout`
- **GET** `/api/users/profile`

### Input/Output Specifications
#### Register
**Input:**
```json
{
  "first_name": "Norbert",
  "last_name": "Guda",
  "email": "jane@example.com",
  "password": "SecureP@ss123"
}


