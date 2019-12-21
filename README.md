# smartsacco Microfinance Management

smart Microfinance Management is a lightweight, yet powerful software solution for small microfinance institutions. It uses web technologies like PHP, MySQL, JavaScript (with jQuery), and CSS. 

smartsacco was initially developed for Taifa SACCO (Savings and Credit Cooperative) of kenya. Typically, customers of such SACCOs will have to buy shares to become members of the society. These members will then hold both a savings and a loans account with the financial institution.


## Features
- Customer management
- Share account management
- Savings account management
- Loan management
- Employee management
- Reporting
- Accounting

## Installation
As Smartsacco is fully based on web technology, it requires a PHP-capable webserver and a MySQL database. For testing purposes, using XAMPP is recommended.

To connect to the test database included in this repository (smartsacco.sql), the required configuration is as follows.
Server: 127.0.0.1 /
Database user: root /
Database password: '' (empty password).
These are the current default settings included in ./config/config.php. They should only be used for test installations. Make sure to change database user and password for any productive environment! It is also highly recommended to change the password pepper in each new installation by editing ./config/pepper.php.

The default login for the program GUI is:
Username: admin
Password: password

## Licence
Copyright 3GPL