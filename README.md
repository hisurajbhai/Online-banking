# Online Banking System

Welcome to the Online Banking System project! This system provides a platform for users to perform various banking activities online.

## Installation

To run the project locally on your machine, follow these steps:

1. **Prerequisites**: Ensure you have XAMPP installed on your system. You can download XAMPP from [here](https://www.apachefriends.org/index.html).

2. **Clone the Repository**: Clone this repository to your local machine using the following command:

git clone https://github.com/hisurajbhai/Online-banking.git

3. **Setup XAMPP**:
- Install XAMPP and start the Apache and MySQL services.
- Navigate to the XAMPP installation directory and find the `htdocs` folder. This is where you will place the project files.

4. **Create Database**:
- Open your web browser and go to `http://localhost/phpmyadmin`.
- Log in to phpMyAdmin.
- Create a new database named `net_banking`.

5. **Import SQL File**:
- Inside the project folder, you will find a file named `database.sql`. Import this file into the `net_banking` database you created earlier. This will set up the necessary tables and data for the project.

6. **Configuration**:
- Navigate to the `config` folder within the project.
- Open `database.php` and update the database configurations according to your local setup (if necessary).

7. **Run the Application**:
- Open your web browser and go to `http://localhost/<project-folder-name>`.
- You should now see the home page of the Online Banking System.

## Usage

- Once the application is running, users can register for an account, log in, and perform various banking activities such as:
- Viewing account balance
- Transferring funds between accounts
- Paying bills
- Managing transactions

