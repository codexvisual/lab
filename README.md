# Lab - CodeIgniter Application

A web application built with the **CodeIgniter** PHP framework.

## Requirements

- PHP 7.x
- Apache / Nginx server
- MySQL / MariaDB

## Installation

1. **Clone the repository** into your web root (e.g. `htdocs` or `/var/www/html`):

```bash
git clone <repo-url> lab
```

2. **Create a database** and import the SQL file:

```bash
mysql -u root -p < elitedesignbd_lab.sql
```

3. **Configure database** in `application/config/database.php` with your DB credentials.

4. **Configure base URL** in `application/config/config.php`:

```php
$config['base_url'] = 'http://localhost/lab/';
```

5. Open the application in your browser:

```
http://localhost/lab
```

## Features

- CodeIgniter MVC structure
- Uploads management
- User/admin panel

## Notes

- Uploaded files are stored in the `uploads/` directory.