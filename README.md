# Sitarabucks
# Sitarabucks - PHP Web Application

Sitarabucks is a PHP-based web application that simulates the experience of an online coffee shop. The application allows users to browse, add items to a cart, and proceed with an order, all while focusing on user-friendly design and functionality. This project showcases fundamental PHP concepts and web development practices.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributors](#contributors)
- [License](#license)

---

## Features

- **Dynamic Menu:** Displays a list of coffee and other products fetched dynamically from the database.
- **Cart Functionality:** Users can add, update, or remove items in the cart.
- **Order Summary:** Provides a detailed summary of the user's order, including total cost.
- **Responsive Design:** Ensures the website is accessible on various devices.
- **Backend Integration:** Connects with a MySQL database to manage products, orders, and user data.

---

## Tech Stack

### Frontend:
- HTML5, CSS3
- JavaScript (for interactivity)

### Backend:
- PHP
- MySQL (Database Management)

---

## Installation and Setup

Follow these steps to set up the project locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Shadab-2604/Sitarabucks-PHP.git
   cd Sitarabucks-PHP
   ```

2. **Set Up the Database**
   - Import the `sitarabucks.sql` file (provided in the repository) into your MySQL database.
   - Update the database connection details in `config.php`:
     ```php
     <?php
     $servername = "localhost";
     $username = "root";
     $password = "yourpassword";
     $dbname = "sitarabucks";
     ?>
     ```

3. **Run the Application**
   - Ensure your PHP server (e.g., XAMPP or WAMP) is running.
   - Place the project folder in the `htdocs` directory (if using XAMPP).
   - Open your browser and navigate to `http://localhost/Sitarabucks-PHP`.

---

## Usage

1. Open the website in your browser.
2. Browse through the available products.
3. Add items to the cart and proceed to checkout.
4. View the order summary and complete the order.

---

## File Structure

```
Sitarabucks-PHP/
|-- assets/
|   |-- css/           # Stylesheets
|   |-- js/            # JavaScript files
|   |-- images/        # Images used in the app
|
|-- includes/
|   |-- header.php     # Common header file
|   |-- footer.php     # Common footer file
|
|-- config.php         # Database connection
|-- index.php          # Homepage
|-- cart.php           # Cart management
|-- checkout.php       # Checkout page
|-- sitarabucks.sql    # Database dump
|
|-- README.md          # Project documentation
```

---

## Contributors

- **Shadab** - Backend Development, Database Integration

If you'd like to contribute to this project, feel free to open a pull request!

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Screenshots

_Add screenshots of your project here to help others visualize the app!_

