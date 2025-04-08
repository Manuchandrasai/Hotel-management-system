# Hotel Management System in PHP


## Description


This is a simple Hotel Management System implemented in PHP. It allows you to manage rooms, book rooms, and list available rooms.


## Requirements


- PHP 7.0 or higher
- A web server (e.g., Apache, Nginx)


## Setup


1.  **Install PHP**:


 Make sure you have PHP installed on your system. You can download it from the official PHP website or use a package manager like apt, yum, or brew.


2.  **Set up a web server**:


 If you don't have one already, install a web server such as Apache or Nginx.


3.  **Create a project directory**:


 Create a directory where you will place the PHP files. For example, `hotel_management`.


4.  **Place the PHP code**:


 Save the provided PHP code into a file, for example, `index.php`, and place it in your project directory.


5.  **Configure the web server**:


 Configure your web server to serve the PHP file. For Apache, you might need to create a VirtualHost. Here’s an example:


 ```apache
 <VirtualHost *:80>
 ServerName localhost
 DocumentRoot /path/to/your/hotel_management_system
 <Directory /path/to/your/hotel_management_system>
 AllowOverride All
 Require all granted
 </Directory>
 </VirtualHost>
