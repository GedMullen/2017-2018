# Week 2.7

<br>1 . [AJAX Introduction](https://www.w3schools.com/xml/ajax_intro.asp)
<br>2 . [AJAX Tutorialspoint](https://www.tutorialspoint.com/ajax/index.htm)

# Week 2.6

<br>1 . [Web Development: Advanced Web Scripting Concepts - Unit Descriptor](https://www.sqa.org.uk/files/hn/HL9W35.pdf)
<br>2 . [JavaScript HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)

## Excercises

Complete the following [tutorial and exercises](https://drive.google.com/file/d/1zsYqZdkLDncrZmyMprgEojoupqDqSFVj/view?usp=sharing)

# Week 2.5

[LO1 Revision Sheet](https://drive.google.com/open?id=0B-CFaefA1v4RaWNYbnRUdXpHSUFZb2g1SXE4M1kyX2k0WTVv)

# Exercise

In your groups create single choice mulitple (4) choice questions on Ygritte in a file called files called phptest.txt.

# Week 2.2

1 . [Tutorialspoint - JSP](https://www.tutorialspoint.com/jsp/)
```
/home/share/java/studentjsp
```

# Week 2.1

```bash
cp -r /home/share/phpcrud/betswithsession/* .
# You will need to modify betged.sql and database.php with your database name 
mysql -t -u student < betged.sql
# Run a PHP server
php -S localhost:8???
firefox localhost:8???
```


# Week 17

```bash
cp -r /home/share/phpcrud/betswithlogin/* .
# You will need to modify betged.sql and database.php with your database name 
mysql -t -u student < betged.sql
# Run a PHP server
php -S localhost:8???
firefox localhost:8???
```

# Week 15

<br>1 . [Sessions Tutorial](http://www.w3schools.com/php/php_sessions.asp) 
<br>2 . [Session Handing - php.net](http://php.net/manual/en/book.session.php)
<br>3 . [User Registration And Login Example](http://www.codingcage.com/2015/01/user-registration-and-login-script-using-php-mysql.html)


## Exercises

<br>1 . In your BetGed application - stop the user from accessing the "customers.php" unless they are logged in as admin (see [Sessions Tutorial](http://www.w3schools.com/php/php_sessions.asp)).
<br>2 . Stop the user from accessing the "read.php" page unless they have logged in as a normal user.


# Week 13

<br>1 . [PHP Login Tutorial](https://docs.google.com/document/d/1DtnOoUNieZOVxIXimgvxUESsfXNqj9evYXAZfAbyRi0/pub)

## Exercises

<br>1 . Add an "admin" user to your BetGed databased. Change index.php to a login screen. If the user logs in with the admin account then direct them to the customer list. If the user logs in using a normal user then direct them to the "Read" page for that customer.  

# Week 10-12

<br>1 . [List Bets](https://drive.google.com/open?id=177-eVrNW-g68ysPJmnHVhyA6v4IKIcQZ) 
<br>2 . [Bootstrap themes](https://bootswatch.com/)
<br>3 . Running Bet Ged (with Bets listed):

```bash
cp -r /home/share/phpcrud/showbets/* .
# You will need to modify betged.sql and database.php with your database name 
mysql -t -u student < betged.sql
# Run a PHP server
php -S localhost:8???
firefox localhost:8???
```


# Week 9
<br> 1 . [List Bets](https://drive.google.com/open?id=177-eVrNW-g68ysPJmnHVhyA6v4IKIcQZ) 
<br> 2 . Resizing gedit
```
gedit -g 200x200+100+100
```
## Exercises

<br> Update Bet Ged to [List Bets](https://drive.google.com/open?id=177-eVrNW-g68ysPJmnHVhyA6v4IKIcQZ) for Customers.

# Week 8

<br>1 . Running Bet Ged:

```bash
mkdir betged
cp -r /home/share/phpcrud/addbets/* betged
cd betged
# You will need to modify betged.sql and database.php with your database name 
mysql -t -u student < betged.sql
# Run a PHP server
php -S localhost:8???
firefox localhost:8???
```
<br>2 . [HTML Select Tag](https://www.w3schools.com/tags/tag_select.asp)
<br>3 . [Error Logging](http://php.net/manual/en/function.error-log.php)
# Week 7

<br> 1 . Running CRUD tutorial on Ygritte:
```bash
cp -r /home/share/phpcrud/tutorial/crud/* .
# You will need to modify customers.sql with your database name 
# You can use sed to do this:
sed 's/!yourdbname/bob11/g' customers.sql > mycustomers.sql 
mysql -t -u student < mycustomers.sql
# Modify database.php with your database name
# Run a PHP server
php -S localhost:8???
firefox localhost:8???
```
<br> 2 . [Learning sed](https://linuxconfig.org/learning-linux-commands-sed)

## Exercises
<br>1 . Continue with Week 6 Exercises

# Week 5 & 6
<br> 1 . [PHP CRUD Tutorial](https://www.startutorial.com/articles/view/php-crud-tutorial-part-1)
<br> 2 . Bootstrap files:
```
cp -r /home/share/bootstrap/* .
```
<br> 3 . Example betged.sql: 
```
cp /home/share/phpcrud/addbets/betged.sql .
```

## Exercises 
<br> 1 . Complete the [PHP CRUD Tutorial](https://www.startutorial.com/articles/view/php-crud-tutorial-part-1) and install and run it on Ygritte. 
<br> 2 . Using the betged.sql script you created in Week 3 you are required to create a "Bet Ged" web application. Implement the following screens:
<br> (a) [Create Customer](https://drive.google.com/open?id=0B-CFaefA1v4RVXV4eVlKSEhySTA)
<br> (b) [Read Customer](https://drive.google.com/open?id=0B-CFaefA1v4RWDhDMTVNNGdOS00)
<br> (c) [Add Bet](https://drive.google.com/open?id=0B-CFaefA1v4RbEFFcTdya0hhSzA)
<br> 3 . Write an SQL script that checks that your bet has been successfully inserted into the database. 


<!-- dealines wk 4 -->
# Week 3 & 4
<br> 1 . [PHP Documentation](http://www.php.net/)
<br> 2 . [PHP Coding Standards](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)
<br> 3 . Creating a database recap:
```sql
DROP DATABASE IF EXISTS <yourusername>;
CREATE DATABASE <yourusername>;
USE <yourusername>;
```
<br> 4 . Useful "sanity check" commands to put at the end of your script:
```sql
SHOW TABLES;
DESCRIBE employees;
SELECT * FROM employees LIMIT 10;
```
<br> 9 . Ygritte Tunnelling.
```
cat /home/share/misc/tunnel.txt 
```
<br>10 . [Introduction To ERM](https://drive.google.com/open?id=0B-CFaefA1v4RZkpXSURLT1ZnSm8)
<br>11 . [Database Design Tutorial](http://en.tekstenuitleg.net/articles/software/database-design-tutorial/intro.html)
<br>12 . [Example ERDs](http://databaseanswers.org/data_models/index.htm)

## Exercises
<br>1 . Create a database based on [this conceptual diagram](https://drive.google.com/file/d/0B-CFaefA1v4RbkpXaG5GSWNrWjQ/view?usp=sharing).
<br>2 . Insert test data into the your database.
<br>3 . Write a PHP script called betged.php that outputs all the bets for all customers. 
<br>4 . Continue with the [PHP Tutorial](http://www.w3schools.com/php/).

# Week 2
<br>1 . Turning off code completion for PHP in Eclipse:
```
Window->Preferences->PHP->Editor->Content Assist->Uncheck Enable Auto Activation
```
<br> 2 . [PHP Tutorial](http://www.w3schools.com/php/) 
<br> 3 . [HTML Forms](http://www.w3schools.com/html/html_forms.asp)
<br> 4 . [HTML Tables](http://www.w3schools.com/html/html_tables.asp)
<br> 5 . [Bootstrap](http://www.w3schools.com/bootstrap/)
<br> 6 . Setting up screen.
```
vim ~/.screen_layout
```
```
split -v
screen -t s1
focus
screen -t s2
split
focus
screen -t s3
focus
```
```
vim ~/.screenrc
```
```
defscrollback 10000
source .screen_layout
layout save def
startup_message off
# switch windows with F3 (prev) and F4 (next)
bindkey "^[OR" prev
bindkey "^[OS" next
# mouse tracking allows to switch region focus by clicking
mousetrack on
```
## Exercises 
<br>1 . Continue the [PHP Tutorial](http://www.w3schools.com/php/default.asp) and run some of the exercises on Ygritte using eclipse. 
<br>2 . Modify [mysqlexample.php](https://gist.github.com/GedMullen/f58ea879c98ada9ca055) to output the name, dob, and salary of the top 10 highest paid employees in the database.

# Week 1
<br> 1 . Unit Descriptors [F6C235](http://www.mysqa.info/files/hn/F6C235.pdf) and [HL9W35](https://www.sqa.org.uk/files/hn/HL9W35.pdf)
<br> 2 . [Dynamically Generated Content](https://docs.google.com/presentation/d/1bWMd9ypXXUJGt-jDpjpRSfh6_2zHMRKjjBcldO0OMeM/pub?start=false&loop=false&delayms=60000&slide=id.p3)
<br> 3 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br> 4 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br> 5 . [mysqlexample.php](https://gist.github.com/GedMullen/f58ea879c98ada9ca055)
<br> 6 . You can start a PHP server on Ygritte by issuing the following command (replace ??? with your unique port number):
```
php -S localhost:8??? 
```
<br> 7 . Linux editors [vim](http://vim.rtorr.com/), [nano](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/) and [gedit](https://en.wikipedia.org/wiki/Gedit)
<br> 8 . [PHP Tutorial](http://www.w3schools.com/php/) 
<br> 9 . Ygritte FAQ.
```
cat /home/share/misc/ygrittefaq.txt | more
```
<br> 10 . [The mind behind Linux | Linus Torvalds](https://www.youtube.com/watch?v=o8NPllzkFhE)
<br> 11 . [The Art Of The Command Line](https://github.com/jlevy/the-art-of-command-line)
## Exercises

<br>1 . Run eclipse from the command line. Familiarise yourself with the IDE using the help menus: Help->Help Contents->Workbench User Guide. Create the HelloWorld program using Eclipse. 
<br>2 . Start this [PHP Tutorial](http://www.w3schools.com/php/default.asp) and run some of the exercises on Ygritte using eclipse. 
