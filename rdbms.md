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
