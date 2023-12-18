# High Resiliency Application - PHP Website

## Overview

The PHP code included in this repository serves as the backbone for the High Resiliency Application. This PHP application is designed to interact with a MySQL database, handling data input and presentation through a simple web interface.

## PHP Application Code

### File Structure

- **index.php:** Main web page displaying a sample page with basic information.
- **functions.php:** PHP functions for database interactions and table verification.
- **dbinfo.inc:** Configuration file containing database connection details.
- **add_employee.php:** PHP script to handle the addition of employee data.
- **display_employees.php:** PHP script to display employee data in a tabular format.

### Functionality

1. **Database Connection:**
   - The `dbinfo.inc` file contains configuration details for connecting to the MySQL database.

2. **Adding Employee Data:**
   - The `add_employee.php` script allows the addition of employee data through a simple form.

3. **Displaying Employee Data:**
   - The `display_employees.php` script retrieves and displays employee data in a tabular format.

4. **Database Verification:**
   - The `functions.php` file includes functions to verify the existence of the required database table and create it if necessary.

## Deployment

1. Include the PHP files in your web server's document root or hosting environment.
2. Ensure the `dbinfo.inc` file contains accurate database connection details.
3. Access the application through the web server URL.

## Configuration

Adjust the database connection details in the `dbinfo.inc` file to match your MySQL database settings.

```php
<?php
define('DB_SERVER', 'your_database_server');
define('DB_USERNAME', 'your_database_username');
define('DB_PASSWORD', 'your_database_password');
define('DB_DATABASE', 'your_database_name');
?>
```

## Important Note

- Ensure that the web server environment is configured to support PHP.
- Verify that the MySQL database mentioned in the configuration exists and is accessible.
