# Week 2

<br>1 . [Oracle Certified Associate Java 7 Programmer 1](http://education.oracle.com/pls/web_prod-plq-dad/db_pages.getpage?page_id=5001&get_params=p_exam_id:1Z0-803&p_org_id=&lang=)
<br>2 . [OCA Java 7 Book](http://www.amazon.co.uk/OCA-Java-Programmer-Certification-Guide/dp/1617291048)
<br>3 . Linux editors [vim](http://vim.rtorr.com/), [nano](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/) and [gedit](https://en.wikipedia.org/wiki/Gedit)
<br>4 . [Oracle OO Tutorial](https://docs.oracle.com/javase/tutorial/java/concepts/index.html)
<!--
Computer Science Principles Lab: Java - 4
-->
<br>5 . Setting up screen.
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
<br> 6 . Answer to Exercise 2:
```
cp /home/share/java/exercises/warmup/ex2/Exercises.java ~/workspace/examples/src
```
<br> 7 . Console input example:
```
cp /home/share/java/exercises/input/Controller.java ~/workspace/examples/src
```
<br> 8 . [String comparison](https://stackoverflow.com/questions/513832/how-do-i-compare-strings-in-java)

## Exercises
<br>1 . Continue with the warm up exercises from Week 1.
<br>2 . Start the Java Foundations course in [Oracle Academy](http://ilearning.oracle.com/ilearn/en/learner/jsp/login.jsp?site=OracleAcad)
<br>3 . In your groups create a 10 minute presentation that answers the following questions:
<br>What is OOP?
<br>What are the advantages of OOP?
<br>Explain the term "Instantiating an object in Java" -  provide a code example.
<br>4 . Modify the Controller.java to check for the username "admin" and password "password". Output a successful login message if the user enters the correct username/password combination.
<br>5 . Once logged in prompt for the name and age of the user and display the information as a welcome message.
<br>6 . Create a menu that allows the user to execute each of the warmup exercises.

# Week 1
<br> 1 . [Corners Game](https://docs.google.com/document/d/1f8YCnRpKR5dgO-aP77ZXJg5SU6BWLMkiLsc99n1WZe4/pub)
<br> 2 . [Netcraft Survey](http://news.netcraft.com/archives/2015/10/16/october-2015-web-server-survey.html)
<br> 3 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br> 4 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br> 5 . Ygritte FAQ.
```
cat /home/share/misc/ygrittefaq.txt | more
```
<br> 6 . [The Art Of The Command Line](https://github.com/jlevy/the-art-of-command-line)
<br> 7 . [GitHub Is Your New CV](http://code.dblock.org/2011/07/14/github-is-your-new-resume.html)
<br> 8 . [GitHub Home](https://github.com/)
<br> 9 . [Example Profile](https://github.com/marijnh)
<br> 10 . [Mineplex Project Contributions](https://drive.google.com/file/d/0B7l9n3yk5ob0b0JCWXU5ZjY4dUk/view?ts=58170cea)
<br> 11 . [The mind behind Linux | Linus Torvalds](https://www.youtube.com/watch?v=o8NPllzkFhE)
<br> 12 . Unit Descriptors: [H17135](http://www.sqa.org.uk/files/hn/H17135.pdf), [H17235](http://www.sqa.org.uk/files/hn/H17235.pdf) and [HL9X35](https://www.sqa.org.uk/files/hn/HL9X35.pdf)
<br> 13 . [Oracle Java Tutorial](https://docs.oracle.com/javase/tutorial/)
<br> 14 . [Java Introduction](https://docs.google.com/presentation/d/1dsZd2c00zmYxtRmyCM6NK-2RxiIFhm7JzrNebpi7v5A/edit?usp=drivesdk)
<br> 15 . Answer to Exercise 1:
```
cp /home/share/java/exercises/warmup/ex1/Exercises.java ~/workspace/warmup/src
```

## Exercises
<br>1 . Complete this tutorial: [The Art Of The Command Line](https://github.com/jlevy/the-art-of-command-line)
<br>2 . Complete these [GitHub Exercises](https://docs.google.com/document/d/1CWRBnj2pL_RIDAdgzoiZjm_fWHf_yznotVnGvG21lyk/edit?usp=sharing)
<br>3 . Use this [tutorial](https://docs.oracle.com/javase/tutorial/getStarted/cupojava/unix.html) to create a java program using the Linux command line. Don't put the file in the /temp directory, put it in a folder under your home directory. You can use gedit instead of pico as your editor if you prefer.
<br>4 . Run eclipse from the command line. Familiarise yourself with the IDE using the help menus: Help->Help Contents->Workbench User Guide. Create the HelloWorld program using Eclipse. 
<br>5 . Create a project called "warmup" in Eclipse on Ygritte and complete the following [exercises.](https://docs.google.com/document/d/1zcppr0POAaVqlQIxyX2rl1E50z53ZFqc4E88hB9IQFQ/edit?usp=drive_web)



