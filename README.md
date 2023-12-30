# API Documentation
This repository contains the PHP files representing the backend APIs for our Newspaper App project. These APIs play a crucial role in handling user registration, mobile number verification, and login functionalities.

## API Endpoints
1. **User Registration API:**
   - **Endpoint:** `/api/register.php`
   - **Method:** `POST`
   - **Parameters:** `email`, `password`
   - **Description:** Handles user registration by receiving email and password.

2. **Mobile Number Verification API:**
   - **Endpoint:** `/api/verify-mobile.php`
   - **Method:** `POST`
   - **Parameters:** `mobile_number`
   - **Description:** Validates and verifies user identity using mobile number.

3. **Login API:**
   - **Endpoint:** `/api/login.php`
   - **Method:** `POST`
   - **Parameters:** `email_or_mobile`, `password`
   - **Description:** Manages user login by accepting email or mobile number along with the password.

## How to Use
1. Clone or download the repository.
2. Ensure a PHP environment is set up on your server.
3. Configure database credentials in the API files.
4. Host the PHP files on your server.
5. Update the app's codebase with the live API endpoints.

## Configuration
- **Database Configuration:**
  - Locate the database configuration section in each PHP file.
  - Update `host`, `username`, `password`, and `database` according to your server.

## Contribution Guidelines
Contributions to the API are welcome. Follow standard GitHub Fork and Pull Request workflow. Ensure that your code adheres to existing coding standards.

## Issues and Bug Reports
If you encounter any issues or would like to report a bug, please use the GitHub issue tracker.
