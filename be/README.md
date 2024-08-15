# 🌟 Page Generator Engine for Administration Website 🌟

[![Framework: Sails.js](https://img.shields.io/badge/Framework-Sails.js-blue.svg?style=for-the-badge&logo=sails.js)](https://sailsjs.com/)
[![Database: MySQL](https://img.shields.io/badge/Database-MySQL-green.svg?style=for-the-badge&logo=mysql)](https://www.mysql.com/)

## 📝 Overview

**Page Generator Engine for Administration Website** is an open-source project designed to streamline the process of creating and managing administrative pages. Built with **JavaScript** and leveraging the **Sails.js** framework, this engine offers a flexible and scalable solution for developing robust administration websites. **MySQL** is used as the database to ensure reliable data management.

## 🚀 Features

- 🛠️ **Dynamic Page Generation**: Easily create and customize admin pages without repetitive coding.
- 🔒 **Role-Based Access Control**: Manage user permissions and access levels effectively.
- 💾 **MySQL Integration**: Robust data handling with MySQL for efficient storage and retrieval.
- 📦 **Extensible and Modular**: Designed for easy integration and extension to fit different use cases.

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- 🟢 **Node.js** (>= 14.x)
- 🔵 **npm** (Node Package Manager)
- 🟢 **MySQL** (>= 8.x)

## ⚙️ Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/vuvu15202/PGEA.git
    cd PGEA
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Configure MySQL Database**:

   - **Set Up MySQL Native Password**:
   
     Run the following SQL scripts one by one in your MySQL command line or MySQL Workbench to set up the native password and grant all privileges:
   
    ```sql
    ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'your_password';
    GRANT ALL PRIVILEGES ON *.* TO 'root'@'localhost' WITH GRANT OPTION;
    FLUSH PRIVILEGES;
    ```

   - **Create a MySQL database**:
   
     After setting up the password, create a database for the project.
   
   - **Update Configuration**:
   
     Update the `config/datastores.js` file in the project with your database credentials.

4. **Run the Application**:
    ```bash
    sails lift
    ```

Your application should now be running on `http://localhost:1337`.

## 🛠️ Usage

- **Admin Panel**: Log in as an admin to manage users, pages, and content.
- **API Endpoints**: Access various API endpoints for user management, page generation, and more.

## 🤝 Contribution

We welcome contributions from the community! To get started:

1. 🍴 **Fork the Repository** on GitHub.
2. 🌿 **Create a New Branch** for your feature or bugfix.
3. 📝 **Submit a Pull Request** with a detailed description of your changes.

## 🛡️ Support

If you have any questions or need assistance, feel free to open an issue on GitHub.

## 🙏 Acknowledgements

- **Sails.js** - The powerful MVC framework for Node.js
- **MySQL** - The world's most popular open-source database
