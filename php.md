# Week 2
<br> 1 . [PHP Tutorial](http://www.w3schools.com/php/) 
<br> 2 . [HTML Forms](http://www.w3schools.com/html/html_forms.asp)
<br> 3 . [HTML Tables](http://www.w3schools.com/html/html_tables.asp)
<br> 4 . [Bootstrap](http://www.w3schools.com/bootstrap/)
<br> 5 . Setting up screen.
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
<br>2 . Continue the [PHP Tutorial](http://www.w3schools.com/php/default.asp) and run some of the exercises on Ygritte using eclipse. 

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
