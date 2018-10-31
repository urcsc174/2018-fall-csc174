# Lab 9: Remote Database

*Due: Wednesday, October 31, 2018 (today)* 

In this exercise you will practice setting up a remote database and connecting to it from your localhost.

This is an **individual assignment**.  You will not be working as a team, however you can help each other.

Note: this lab assignment is counted toward your *participation* grade.

## Setup

- Download the [starter-files.zip](starter-files.zip) file and open it on your desktop
- Edit the file: **phonebook.sql** as directed (see the comment on line 1)
- In your localhost, make a copy of the "Four DB Functions" files
  - Hint: put those files in a folder; copy the folder; name the new folder, **phonebook**
- Delete the file, **create-table.sql**; replace it with **phonebook.sql**
- Edit the **testmysql-remote.php** file using the database credentials below:
  - host: **66.147.242.186**
  - database user: **urcscon3_lab09**
  - password: **coffee1N/!**
  - database name: **urcscon3_lab09**
- Test the connection in your localhost
  - If the connection doesn't work, login to Bluehost and jump to the *Check your Access* section, below

## Create a table in the database

- Login to Bluehost: [my.bluehost.com/web-hosting/cplogin](https://my.bluehost.com/web-hosting/cplogin)

  Username: **csc174.org**

  Password: **coffee1N/!**

- Go to the **cPanel**,  **phpMyAdmin**
- Click on the database, **urcscon3_lab09**
- Import or copy & paste your edited **phonebook.sql** file

## Check Your Access

If your localhost connection test script doesn't work:

- While logged-in to Bluehost, go to the **cPanel, Remote MySQL** 
  - Note: may need to use the back button to get out of phpMyAdmin
- Check the first three octets of your IP number.  If it is not in the list, then add your "Class C"
- Recheck your localhost connection test script

## Edit the Phonebook Application

You need to go through each file in the **phonebook** folder; edit as needed to make it work with your table in the Lab 9 database.  Make sure you know the exact field names in the database before you begin.

Here is everything you need to touch to make it work:

- [ ] Edit **connect-db.php**
- [ ] Edit **renderform.php**
    - line 3
    - duplicate and edit lines 21 and 22
- [ ] Edit **index.php**
    - line 13
    - duplicate and edit lines 19 and 20
    - duplicate and edit lines 31 and 32
- [ ] Edit **new.php**:
    - duplicate and edit lines 10 and 11
    - line 17
    - line 22
    - line 26 (be very careful!)
    - line 33
- [ ] Edit **edit.php**
    - duplicate and edit lines 13 and 14
    - line 19
    - line 24
    - line 28 (be very careful! - notice: not the same as new.php)
    - line 42
    - duplicate and edit lines 48 and 49
    - line 54
- [ ] Edit **delete.php**
    - line 11

Then test all four functions - make sure to leave at least one record in the database (it'll be graded)

## Submit the Assignment

- [ ] Go to blackboard, make a submission in "Lab 9: Remote Database"

- [ ] in *Write Submission*, enter:
    - database username
    - database password
    - database name
    - table name

I will view your table and record(s) in the database (pass/fail); also, information in *Write Submission* will be graded!
