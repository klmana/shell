Shell, init files, variables and expansions
Resources
*man or help:
printenv
set
unset
export
alias
unalias
.
source
printf

*Read or watch:
Expansions
	http://linuxcommand.org/lc3_lts0080.php
Shell Arithmetic
      https://www.gnu.org/software/bash/manual/html_node/Shell-Arithmetic.html
     
Variables
	https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_02.html
Shell initialization files
      https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_03_01.html
     
The alias Command
    http://www.linfo.org/alias.html
Technical Writing
	  https://holbertonintranet.s3.amazonaws.com/uploads/misc/2021/6/9112669886fd446a2aa3113c31319d1f468dc160.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220527%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220527T004055Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b6fbfbd119873c673ca0805a51e67d675303347767b77c7eb0d84a9a882f0e79



Requirements
General
Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use &&, || or ;
You are not allowed to use bc, sed or awk
All your files must be executable
More Info
Read your /etc/profile, /etc/inputrc and ~/.bashrc files.

Look at some files in the /etc/profile.d directory.

Note: You do not have to learn about awk, tar, bzip2, date, scp, ulimit, umask, or shell scripting, yet.

Repo:
GitHub repository: shell
Directory: init_files_variables_and_expansions

1. Hello you
mandatory
Create a script that prints hello user, where user is the current Linux user.

2. The path to success is to take massive, determined action
mandatory
Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

3. If the path be beautiful, let us not ask where it leads
mandatory
Create a script that counts the number of directories in the PATH.


4. Global variables
mandatory
Create a script that lists environment variables.


5. Local variables
mandatory
Create a script that lists all local variables and environment variables, and functions.


6. Local variable
mandatory
Create a script that creates a new local variable.

Name: BEST
Value: School


7. Global variable
mandatory
Create a script that creates a new global variable.


8. Every addition to true knowledge is an addition to human power
mandatory
Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.


9. Divide and rule
mandatory
Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.


10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
mandatory
Write a script that displays the result of BREATH to the power LOVE


11. There are 10 types of people in the world -- Those who understand binary, and those who don't
mandatory
Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line


11. There are 10 types of people in the world -- Those who understand binary, and those who don't
mandatory
Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line

13. Floats
mandatory
Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.

14. Decimal to Hexadecimal
mandatory
Write a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable DECIMAL
The script should display the number in base 16, followed by a new line


15. Everyone is a proponent of strong encryption
mandatory
Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

16. The eggs of the brood need to be an odd number
mandatory
Write a script that prints every other line from the input, starting with the first line.

17. I'm an instant star. Just add water and stir.
mandatory
Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.

WATER is in base water
STIR is in base stir.
The result should be in base bestchol


