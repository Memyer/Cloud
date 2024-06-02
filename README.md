# API Documentation
## Base URL

## Endpoints

### 1. User Registration
- **URL**: `/api/register`
- **Method**: `POST`
- **Description**: Registers a new user.
- **Request Body**:
  ```json
  {
    "username": "string",
    "password": "string"
  }
- **Response**:
  Success:'Status: 201 Created'
  Body:
  ```json
  {
  "message": "User registered successfully."
  }


  
