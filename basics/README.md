sprint 1 Holberton

http://linuxcommand.org/lc3_lts0010.php
http://linuxcommand.org/lc3_lts0020.php
http://linuxcommand.org/lc3_lts0030.php
http://linuxcommand.org/lc3_lts0040.php
http://linuxcommand.org/lc3_lts0050.php
http://linuxcommand.org/lc3_lts0060.php
http://linuxcommand.org/lc3_man_pages/man1.html
https://www.howtogeek.com/howto/ubuntu/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/
https://wiki.ubuntu.com/LTS
https://en.wikipedia.org/wiki/Shebang_%28Unix%29

man or help:

cd
ls
pwd
less
file
ln
cp
mv
rm
mkdir
type
which
help
man

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What does RTFM mean?
What is a Shebang
What is the Shell
What is the shell
What is the difference between a terminal and a shell
What is the shell prompt
How to use the history (the basics)
Navigation
What do the commands or built-ins cd, pwd, ls do
How to navigate the filesystem
What are the . and .. directories
What is the working directory, how to print it and how to change it
What is the root directory
What is the home directory, and how to go there
What is the difference between the root directory and the home directory of the user root
What are the characteristics of hidden files and how to list them
What does the command cd - do
Looking Around
What do the commands ls, less, file do
How do you use options and arguments with commands
Understand the ls long format and how to display it
A Guided Tour
What does the ln command do
What do you find in the most common/important directories
What is a symbolic link
What is a hard link
What is the difference between a hard link and a symbolic link
Manipulating Files
What do the commands cp, mv, rm, mkdir do
What are wildcards and how do they work
How to use wildcards
Working with Commands
What do type, which, help, man commands do
What are the different kinds of commands
What is an alias
When do you use the command help instead of man
Reading Man Pages
How to read a man page
What are man page sections
What are the section numbers for User commands, System calls and Library functions
Keyboard Shortcuts for Bash
Common shortcuts for Bash
LTS
What does LTS mean?
Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file at the root of the repo, containing a description of the repository
A README.md file, at the root of the folder of this project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we???ll learn more about how to utilize this command.


0. Where am I?
Write a script that prints the absolute path name of the current working directory.
1. What???s in there?
Display the contents list of your current directory.
2. There is no place like home
Write a script that changes the working directory to the user???s home directory.
You are not allowed to use any shell variables
3. The long format
Display current directory contents in a long format
4. Hidden files
Display current directory contents, including hidden files (starting with .). Use the long format.
5. I love numbers
Display current directory contents.
Long format
with user and group IDs displayed numerically
And hidden files (starting with .)
6. Welcome
Create a script that creates a directory named my_first_directory in the /tmp/ directory.
7. Betty in my first directory
Move the file betty from /tmp/ to /tmp/my_first_directory.
8. Bye bye Betty
Delete the file betty.
The file betty is in /tmp/my_first_directory
9. Bye bye My first directory
Delete the directory my_first_directory that is in the /tmp directory.
10. Back to the future
Write a script that changes the working directory to the previous one.
11. Lists
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12. File type
Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13. We are symbols, and inhabit symbols
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14. Copy HTML files
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html
15. Let???s move
Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script
16. Clean Emacs
Create a script that deletes all files in the current working directory that end with the character ~.
17. Tree
Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more.


