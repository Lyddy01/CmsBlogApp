# CMS Blog App README

This Content Management System (CMS) provides bloggers with an intuitive and user-friendly interface for creating, editing, and publishing their content. The app was developed using procedural PHP programming. This README will guide you through the setup and usage of the application.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Configuration](#configuration)
6. [Usage](#usage)
   

## 1. Introduction

The CMS Blog App is a web application that enables bloggers to easily manage their blog posts, categories, and user accounts. It was constructed using procedural PHP, making it well-suited for those who prefer a straightforward code structure.

## 2. Features

- User-friendly and intuitive interface.
- User authentication and role-based access control (Admin and Author roles).
- Create, edit, and delete blog posts.
- Organize blog posts into categories.
- Upload and manage media files.
- Comment system for engaging with readers.
- Search functionality to locate specific blog posts.
- Responsive design for both mobile and desktop.

## 3. Requirements

Before you commence, ensure you have the following prerequisites:

- Web server (e.g., Apache, Nginx)
- PHP (version 7.0 or higher)
- MySQL or MariaDB
- A text editor or code editor for configuration

## 4. Installation

To install the CMS Blog App developed in procedural PHP, follow these steps:

1. Clone this repository to your web server:

   ```
   git clone <repository_url> cms-blog-app
   ```

2. Create a MySQL or MariaDB database for the application.

3. Import the included SQL file (`database.sql`) into your database to create the necessary tables.

4. Configure the database connection by editing the `db.php` file and updating the database hostname, username, password, and database name.

5. Ensure that the web server has write permissions for the `uploads` directory to manage media file uploads.

## 5. Configuration

In the `db.php` file, you can configure various settings such as the database connection details, etc. 

## 6. Usage

1. Access the CMS Blog App developed in procedural PHP through your web browser.
2. Register as an administrator or author, depending on your role.
3. Log in to the application.
4. Start creating and managing your blog posts, categories, and media files.

---

Thank you for choosing the CMS Blog App developed in procedural PHP! If you encounter any issues or have questions, please do not hesitate to open an issue on the GitHub repository. Enjoy your blogging experience!
