# linux_debugging
Owner: SRIHARI
Debugging using valgrind:
REQUIREMENTS: 1) laptop or a PC with linux os or linux running in virtual box 2)install valgrind by running these two commands in the terminal 1)sudo apt-get update -y 2)sudo apt-get install -y valgrind
CODE:
 the files that consists of _d in their name is the deubbging files and the otherwise is the files that consists of some errors
 there are 5 programs with error and 5 programs that are debugged.
 HOW TO RUN:
 by the following 2 commands in the terminal
 1)gcc -g yourprogramename     ( for eg: gcc -g prg1.c ) 
 2) valgrind --leak-check=yes ./a.out
 
