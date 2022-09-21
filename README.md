# connect_to_html_form_to_mysql_with_php


## 1. firstly, install and run xampp on your windows pc or laptop.

// you can download here https://www.apachefriends.org/index.html

then run it as soon after installing.

### note: Minimize XAMPP. Don’t close it.

![](https://www.webcodzing.com/uploads/2021/10/Run-Apache-and-MySQL-on-XAMPP.jpg)

## 2. Create MySQL Database to Connect to HTML Form

// type localhost/PHPMyAdmin in your browser’s search bar and press enter. As show in the image below.

// This will take you to the PHPMyAdmin page. 

![](https://www.webcodzing.com/uploadzvs/2021/10/open-phpmyadmin-page.jpg)

// In the image as below, on the left side, all databases are listed. Just click on the New button to add a new database.

![](https://www.webcodzing.com/uploads/2021/10/MySQL-Database.jpg)

// On the next page, you will choose the name of your database. After that click on Create button. You can give any name to your database. You can use the ‘_’ underscore sign in your name. As shown in the image below. 

![](https://www.webcodzing.com/uploads/2021/10/Create-New-MySQL-Database-for-HTML-form.jpg)

// Now the database has been created successfully. On the next page, you will create a table in your database. Don’t close the page. Let’s see the third step of this lesson.

## 3. Create a Table in MySQL Database to Save HTML Form Entries

// After creating a MySQL database for the HTML form, you will be redirected to the tables page. Just see the image below.

Give a table name. Then, enter how many columns should be in the table.

![](https://www.webcodzing.com/uploads/2021/10/Create-a-Table-in-MySQL-database.jpg)

// In case if you have three input fields like Name, Email, and Message. Then there will be four columns in the database table like Id, Name, Email, and Message.

// After entering the table name and number of columns, click the Go button to create a table.

![](https://www.webcodzing.com/uploads/2021/10/Enter-name-of-columns.jpg)

// See it will look like this in the image below. Remain the other fields as it is. Only fill in the details for Name, Type, Length, and Null Index for only id.

![](https://www.webcodzing.com/uploads/2021/10/Column-details-in-MySQL-Database.jpg)

// Then click the Save button located at the bottom to save.

## 4. Create a User of this MySQL Database and Assign Privileges

// To create a user, go to the Privileges tab as shown in the image below.

### Note: Just make sure your database is selected otherwise you’ll not see the ‘Privileges’ option.

![](https://www.webcodzing.com/uploads/2021/10/Priviliages-in-database.jpg)

// In the Privileges tab, we will create a user for this database. And these details will be needed during the connection of the database using PHP.

![](https://www.webcodzing.com/uploads/2021/10/Add-New-User-for-MySQL-Database.jpg)

// After clicking on Add user account, provide these details.

![](https://www.webcodzing.com/uploads/2021/10/create-a-user-and-assign-all-privileges.jpg)

// Now, click the check to assign all privileges to this user. And then scroll down to the end of the page. And click the Go button to save.

![](https://www.webcodzing.com/uploads/2021/10/create-a-user-and-assign-all-privileges-2.jpg)

// Now the database part is done.

### Before going to the fourth step. We have to create a folder with the name testsite in htdocs folder located inside the XAMPP folder. In that folder, we will place our code files.

## 5. Create a Folder in htdocs and Name it ‘testsite’

// To do this, open the XAMPP folder where you installed it. In the XAMPP folder, find a folder named docs. This is the folder where we place our website files on the local server.

![](https://www.webcodzing.com/uploads/2021/10/htdocs-folder.jpg)

// Open it and create a folder and name it testsite. In this folder, we’ll place our HTML form, CSS stylesheet, and a PHP file. So that we can access them on our PC.

![](https://www.webcodzing.com/uploads/2021/10/testsite-folder.jpg)

## 6. Create HTML Form

// The HTML form will look like this on your PC.

![](https://www.webcodzing.com/uploads/2021/10/HTML-form-to-connect-to-mysql-database.jpg)

### please refer to the uploaded sample code. 
### make sure xampp now is still running.

// now you can access this form by typing localhost/testsite.  

## 7. Create a PHP file to Get HTML Form Entries

// create a PHP file in your text editor with the name form.php in the C:\xampp\htdocs\testsite

### note: please refer to the uploaded sample code.

## 8. Create a Connection to Save HTML Form Entries in MySQL Database

### note: please refer to the uploaded sample code form.php.

// tutorial source: https://www.webcodzing.com/connect-html-form-to-mysql-database-using-php/


