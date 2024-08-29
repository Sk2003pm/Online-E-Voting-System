# Voting System

This project is a web-based voting system that allows users to register, log in, and vote in elections. It also includes an admin panel for managing nominees, users, and viewing results.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Database](#database)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Registration and Login
- Voting for registered users
- Admin Panel for managing nominees and users
- Viewing election results for both users and admins
- Secure login and logout functionality

## Installation

### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](http://www.wampserver.com/en/) for setting up a local server
- Basic knowledge of PHP and MySQL

### Steps

1. Clone this repository:
    ```bash
    git clone https://github.com/sk2003pm/Online-E-Voting-System.git
    ```
2. Copy the project files to your web server's root directory (e.g., `htdocs` in XAMPP).
3. Import the database:
    - Open `phpMyAdmin`.
    - Create a new database named `voting_system`.
    - Import the SQL file located in the `SQL` folder (`voting_system.sql`).
4. Update the database connection details in the `Login.php` and `adminPanel.php` files as needed.

## Usage

### User Side

1. Register an account.
2. Log in with your credentials.
3. Cast your vote for your preferred candidate.
4. View results after voting.

### Admin Side

1. Log in to the admin panel (`adminPanel.php`).
2. Manage users and nominees.
3. View voting results.


## Database

The project uses a MySQL database. The database structure can be found in the `SQL/voting_system.sql` file. Import this file to set up the database.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features, fixes, or enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
