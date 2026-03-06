# 🚗 car-dealership-cms-php - Manage Your Car Listings Easily

[![Download Latest Release](https://img.shields.io/badge/Download-Release-orange?style=for-the-badge)](https://github.com/matopello/car-dealership-cms-php/releases)

## 📋 About

car-dealership-cms-php is a ready-to-use system designed to help you manage car listings on your website. It includes an admin panel where you can add, edit, and delete cars. You can also manage leads and customer reviews, upload images, and use SEO-friendly URLs. This software runs on Windows and uses PHP 8 with a MySQL database.

Key features include:

- Admin panel for easy management  
- Add, update, and remove cars (CRUD)  
- Manage customer leads and reviews  
- Upload and display car images  
- SEO-friendly URLs for better search ranking  
- Built on PHP 8 and MySQL  
- Designed for Apache server with mod_rewrite for URL control  

This project is useful for anyone running a car dealership website or portfolio.

---

## 💻 System Requirements

To run car-dealership-cms-php on Windows, make sure your system meets these requirements:

- Windows 10 or higher  
- Apache server (part of XAMPP or WAMP recommended)  
- PHP 8 installed with required extensions (MySQLi and mod_rewrite enabled)  
- MySQL server (can be local or remote)  
- Minimum 2 GB free RAM  
- At least 100 MB disk space for installation and data  

---

## 🚀 Getting Started

Follow these steps to set up car-dealership-cms-php on your Windows machine. No programming knowledge is needed.

### 1. Visit the Download Page

Go to the release page by clicking the button below. This page has all versions of the app.

[![Download Page](https://img.shields.io/badge/Go_to-Download_Page-blue?style=for-the-badge)](https://github.com/matopello/car-dealership-cms-php/releases)

### 2. Download the Latest Version

On the releases page, find the latest stable version listed near the top. Download the ZIP file marked for Windows or the full package.

### 3. Install a Web Server and Database

If you do not have a web server or database, install one of these all-in-one packages:

- **XAMPP**  
- **WAMP**

These programs include Apache, PHP, and MySQL. Both are free and easy to install on Windows.

### 4. Extract the Files

After downloading the ZIP file, right-click it and choose **Extract Here** or **Extract to folder**. Extract the files into the web server’s root directory:

- For XAMPP: `C:\xampp\htdocs\car-dealership-cms-php`  
- For WAMP: `C:\wamp64\www\car-dealership-cms-php`

### 5. Create a MySQL Database

Open your MySQL management tool. You can use **phpMyAdmin**, which comes with XAMPP and WAMP:

- Open your web browser  
- Go to `http://localhost/phpmyadmin`  
- Click **Databases** tab  
- Create a new database named `car_dealership` (or a name you prefer)  
- Leave collation as `utf8_general_ci`

### 6. Configure the Application

Find the configuration file in the extracted folder, typically named `config.php` or similar.

- Open the file with a text editor like Notepad  
- Enter your MySQL database details:  
  - Database name  
  - Username (usually `root` by default)  
  - Password (may be empty for local servers)  
- Save the changes

### 7. Enable Apache Rewrites (mod_rewrite)

The app uses clean URLs. Make sure Apache’s mod_rewrite module is enabled:

- For XAMPP: Open `httpd.conf` from `C:\xampp\apache\conf\`  
- Search for the line loading mod_rewrite (it looks like `#LoadModule rewrite_module modules/mod_rewrite.so`)  
- Remove the hash (#) at the start to enable it  
- Save and restart Apache from XAMPP control panel  

### 8. Open the App in Your Browser

Type `http://localhost/car-dealership-cms-php` in your browser’s address bar. The home page should load.

---

## ⚙️ Using the Admin Panel

The admin panel allows you to manage all contents, from cars to leads:

- Login by visiting `http://localhost/car-dealership-cms-php/admin`  
- Use default admin credentials found in the documentation or README inside the app folder  
- After login, you can:  
  - Add or edit car records with details like make, model, year, and price  
  - Upload images easily through the form  
  - View and manage customer leads  
  - Review customer feedback  
  - Set SEO-friendly URLs for pages  

---

## 🛠 Troubleshooting Tips

If the app does not work as expected, check the following:

- Confirm Apache and MySQL services are running in XAMPP/WAMP  
- Check the database settings in `config.php` are correct  
- Make sure mod_rewrite is enabled and `.htaccess` file is present  
- Clear your browser cache or try a different browser  
- Look into Apache error logs (`C:\xampp\apache\logs\error.log`) for clues  
- Ensure PHP 8 is being used, not an older version  

---

## 🔗 Helpful Links

- Download releases: https://github.com/matopello/car-dealership-cms-php/releases  
- Apache installation and configuration: https://httpd.apache.org/docs/current/  
- MySQL and phpMyAdmin setup: https://www.phpmyadmin.net/  
- XAMPP download: https://www.apachefriends.org/index.html  
- WAMP download: http://www.wampserver.com/en/

---

## 📥 Download and Setup Summary

- Visit the releases page to get the latest ZIP file  
- Install XAMPP or WAMP for required software  
- Extract files into the server root directory  
- Create a MySQL database using phpMyAdmin  
- Update database settings in the app’s config file  
- Enable mod_rewrite in Apache  
- Open the app in your browser and log in to the admin panel

[![Download Latest Release](https://img.shields.io/badge/Download-Release-orange?style=for-the-badge)](https://github.com/matopello/car-dealership-cms-php/releases)