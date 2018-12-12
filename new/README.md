PHP-MySql based Invenotry Manegement System
==========================================================
## Languages, that is used
- PHP
  - Procedural Coding, but for making reusable our code, I used functions(). 
- MySql
- SB Admin 2 (Twitter Bootstrap Template)
- Twitter Bootstrap
- Java Script
- jQuery
- Carbon
  - A special php class for handeling PHP Date and Time Smoothly. 


## Need to Change to use this project
In order to use this project, you need to change few things. Go to **functions/database.php** 
```php
mysql_connect("localhost", "root", "");
mysql_select_db("inventory");
```
Just change **Host Name**, **Host Username **, **Host User Password** & **Database Name**.

Now you need to upload database tables in your database. I already extracted all the tables and data. Go to **db** and upload **inventory.sql**. Hope everything will goes smoothly.

> Username : admin   ,   
> Password: password

**in database, for all users, default password is 'password'**






