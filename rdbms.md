# Week 6 
<br>1 . Week 5 Answers:
```
mysql -t -u student employees < /home/share/rdbms/wk5answers.sql
vim /home/share/rdbms/wk5answers.sql
```
<br>2 . [Joins](http://www.w3schools.com/sql/sql_join.asp)
<br>3 . [Elliot uses Vim](https://drive.google.com/open?id=0B-CFaefA1v4RSC1XQTF5TVIyZHc)
<br>4 . [Exiting Vim 1](https://drive.google.com/open?id=0B-CFaefA1v4RY1h5VjM2c3BZUGs)
<br>5 . [Exiting Vim 2](https://drive.google.com/open?id=0B-CFaefA1v4RaHZrdVdlZEpPNUk)
<br>6 . [Vim Cheat Sheet](https://vim.rtorr.com/)
<br>7 . [Codecademy - Learn SQL ](https://www.codecademy.com/learn/learn-sql)

## Exercises

<br>1 . Count the number of employees in the employees database.
<br>2 . Count the number of female employees that were born in the 50s.
<br>3 . What is the employee id of the person with the highest salary?
<br>4 . Find the employee details (name DOB etc) of the person with the highest salary (you will need to join the salaries and employees tables).
<br>5 . Find the employee details of the person with the lowest salary.
<br>6 . List all the salaries of Berni Sanella DOB 29/8/61 - order the query by to_date;
<br>7 . Bernie contributed 10% of her  salary to her pension. How much per annum did she pay into her pension for each of her  salaries? Create a query to output the pension contributions for each of her salaries.
<br>8 . Create an alias for the pension column in Q5 called “Pension”.
<br>9 . How much was Bernie paid in the month of October 1997 ( salary / 12 )?


# Week 5

<br>1 . [Select](http://www.w3schools.com/sql/sql_select.asp)
<br>2 . [Where](http://www.w3schools.com/sql/sql_where.asp)
<br>3 . [Order By](http://www.w3schools.com/sql/sql_orderby.asp)
<br>4 . [Count](https://www.w3schools.com/sql/sql_count_avg_sum.asp)
<br>5 . [And & Or](http://www.w3schools.com/sql/sql_and_or.asp)
<br>6 . [Dates](http://www.w3schools.com/sql/sql_dates.asp)

## Exercises

1 . Create an SQL script in your sqlexercises folder called wk5.sql and write a SELECT statement that outputs a list of the first 10 female employees (use LIMIT 10). Append the following exercises to your wk5.sql script: 
<br>2 . A list of female employees that have a last name of “Gils”
<br>3 . Use the SQL created in Exercise 2 to create a list showing only the first name, last name and DOB.
<br>4 . Sort the output in 3 by first name.
<br>5 . Sort the output in 3 by DOB.
<br>6 . List all employees whose DOB is 18/1/1962 (dates can be referenced as strings - WHERE birth_date = '1961-08-29')
<br>7 . Who is the oldest employee?
<br>8 . Who is the newest (most recently hired) employee?
<br>9 . List all female employees that were born in the 60s.
<br>10 . List all male employees that were hired in the 80s.
<br>11 . Add a file called yourname_sqlchallenges.md to the [Fife College blue](https://github.com/Fife-College/blue) private repository with an SQL challenge for your fellow students. Make sure you have a solution to the challenge and if the challenge requires any other knowledge other than that presented in class, you must indicate what else is required in your challenge.
<br>12 . Create a directory on Ygritte called "sqlchallenges" and place the answer to your challenge in this directory in a file named answer.sql. Attempt some of the challenges posed by other students and put your answers in the sqlchallenges directory in the format nameofchallenger_answer.sql. 


# Week 4

1 . [GitHub Is Your New CV](http://code.dblock.org/2011/07/14/github-is-your-new-resume.html)
<br>2 . [GitHub Home](https://github.com/)
<br>3 . [Example Profile](https://github.com/marijnh)
<br>4 . [GitHub CV Generator](http://resume.github.io/)
<br>5 . [Mineplex Project Contributions](https://drive.google.com/file/d/0B7l9n3yk5ob0b0JCWXU5ZjY4dUk/view?ts=58170cea)

## Exercises

1 . Complete these [GitHub Exercises](https://docs.google.com/document/d/1CWRBnj2pL_RIDAdgzoiZjm_fWHf_yznotVnGvG21lyk/edit?usp=sharing)
<!--
<br>2 . Add a file called yourname_sqlchallenges.md to the [Fife College blue](https://github.com/Fife-College/blue) private repository with an SQL challenge for your fellow students. Make sure you have a solution to the challenge and if the challenge requires any other knowledge other than that presented in class, you must indicate what else is required in your challenge.
<br>3 . Create a directory on Ygritte called "sqlchallenges" and place the answer to your challenge in this directory in a file named answer.sql. Attempt some of the challenges posed by other students and put your answers in the sqlchallenges directory in the format nameofchallenger_answer.sql. 
-->

# Week 3

<br>1 . Using MySql on Ygritte interactively:
```
you@ygritte:~$ mysql -u student employees
mysql> select * from employees limit 10;
```
<br>2 . Using MySql using a script

```
mkdir sqlexercises
cd sqlexercises
gedit test.sql
select * from employees limit 10;
you@ygritte:~$ mysql -t -u student employees < test.sql
```

<br>4 . [Select](http://www.w3schools.com/sql/sql_select.asp)
<br>5 . [Where](http://www.w3schools.com/sql/sql_where.asp)
<br>6 . [Order By](http://www.w3schools.com/sql/sql_orderby.asp)
<br>7 . [Count](https://www.w3schools.com/sql/sql_count_avg_sum.asp)
<br>8 . [And & Or](http://www.w3schools.com/sql/sql_and_or.asp)
<br>9 . [Joins](http://www.w3schools.com/sql/sql_join.asp)

# Week 2
<br> 1 . [MySQL Example Employee Database](https://dev.mysql.com/doc/employee/en/sakila-structure.html)
<br> 2 . Complete this tutorial: [The Art Of The Command Line](https://github.com/jlevy/the-art-of-command-line)

## Exercises 

<br>1 . Complete this tutorial: [Learning the Command Line on Codecademy](https://www.codecademy.com/learn/learn-the-command-line)
<br>2 . In groups - study the [MySQL Example Employee Database](https://dev.mysql.com/doc/employee/en/sakila-structure.html) and identify what information you can derive from the database e.g. the oldest employee etc. Document you findings on Ygritte in a file called employees.txt. You can use gedit to edit the file:
```
gedit employees.txt
```

# Week 1 
<br> 1 . [Unit Descriptor](http://www.sqa.org.uk/files/hn/H16W35.pdf)
<br> 2 . [Corners Game](https://docs.google.com/document/d/1f8YCnRpKR5dgO-aP77ZXJg5SU6BWLMkiLsc99n1WZe4/pub)
<br> 3 . [Netcraft Survey](http://news.netcraft.com/archives/2015/10/16/october-2015-web-server-survey.html)
<br> 4 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br> 5 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br> 6 . [Learning the Command Line on Codecademy](https://www.codecademy.com/learn/learn-the-command-line)
<br> 7 . Ygritte FAQ.
```
cat /home/share/misc/ygrittefaq.txt | more
```

## Exercises
<br>1 . Make sure you change your password using the following command:
```
passwd
```
<br>2 . Complete this tutorial: [Learning the Command Line on Codecademy](https://www.codecademy.com/learn/learn-the-command-line)
