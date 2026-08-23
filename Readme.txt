How to run Project
1. Download and Unzip the file on your local system copy carrental .
2. Put carrental folder inside root directory (for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

Database Configuration

Open phpmyadmin
Create Database carrental
Import database carrental.sql (available SQL File Folder inside zip package)

For User
Open Your browser put inside browser “http://localhost/carrental”
Login Details for user:
Username : test@gmail.com
Password: Test@123

For Admin Panel
Open Your browser put inside browser “http://localhost/carrental/admin”
Login Details for admin :
Username: admin
Password: Test@12345



NOTE: update few things before hosting in LAMP server.
edit the file "/var/www/html/includes/config.php" and add your database password. eg: define('DB_PASS','Root@123');

Also load the content from "./SQL FILE/carrental.sql" to your database
eg: mysql -u root -p carrental < "/home/sangeetha/php-project/SQL File/carrental.sql"
before executing this command, make sure you databse has 'carrental' db created in it.
