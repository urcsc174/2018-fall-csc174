# Lab 11: Login System

*Due: Wednesday, November 14, 2018 (today - in-class)* 

The purpose of this lab assignment is to practice building a PHP/MySQL login system for a website.

- Start your MAMP or WAMP server
- [ ] On your localhost, create a database, database user/password, and assign privileges to the user.<br> Remember: in phpMyAdmin you can do all three things all at once: 

    1. Create the user account
    2. Change the host name to "localhost"
    3. Click the checkbox, "Create database with same name and grant all privileges"

## Follow online tutorial to build the system

The goal here is to *not* blindly copy and paste the code from the tutorial, but actually read and understand how the pieces and parts work together.  You don't have to know exactly what each line of code does (most of it is error handling) but you do need to know what each snippet does from a high level.

- Go to: the [Tutorial Republic: PHP MySQL Login System tutorial](https://www.tutorialrepublic.com/php-tutorial/php-mysql-login-system.php) and follow the instructions
- Test your login system. 

## Add a new webpage to your demo

When your login system works as-is from the tutorial, make these changes:

- [ ] **Rename welcome.php** to **index.php**.  (You'll also need to find any reference to "welcome.php" in the code and change that as well.)
- [ ] **Create a new webpage** in your login system website - add some content, any content, just so it looks different than the Index page.
- [ ] **Link the new webpage** to the index.php page and vice versa so you can go back and forth between the two pages (in effect, a simple navigation menu)
- [ ] **Make the new webpage inaccessible** unless the user is logged-in
  - If the user goes to the new page directly (by URL) it should automatically re-route the user to the login page
- [ ] **Add a button, "Sign Out of Your Account"** to the the new webpage - same as the button on the index.php page

## Demonstrate Your Login System Website

- Show the TA or Professor your functioning login system for *participation* credit.
  1. Demonstrate: go to index.php -- should redirect to the login page.
  2. Click to go to the registration page
  3. Create a new account -- should redirect to the login page
  4. Login -- should redirect to index.php
  5. Go to your second protected webpage
  6. Logout -- should redirect to the login page