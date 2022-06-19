# Shell 01  <img src="pics/bash.png" width="64" height="30" />

- Exercise 01 - print_groups.sh
  - Write a command line that will display the list of groups for which the login, contained int the environment variable FT_USER, is a member. Separated by commas without spaces.
  - Examples :
    - for FT_USER=nours, the result is "god,root,admin,master,nours,bocal" (without quotation marks)
    ![Image1](pics/exercise_01_1.png)
    - for FT_USER=daemon, the result is "daemon,bin" (without quotation marks)


- Exercise 02 - find_sh
  - Write a command line that searches for all file names that end with ".sh" (without quotation marks) in the current directory and all its sub-directories. It should display only the file name without the .sh.
  - Example of output :
  
- Exercise 03 - count_files.sh
  - Write a command line that counts and dislays the number of regular files and directories in the current directory and all its sub-directories. It should include ".", the starting directory
  - Example of output :

- Exercise 04 - MAC.sh
  - Write a command line that displays your machine's MAC addresses. Each address must be followed by a line break.

- Exercise 05 - Can you create it ?
  - Create a file containing only "42", and NOTHING else.
  - Its name will be :
  
  - Example :

- Exercise 06 - Skip
  - Write a command line that displays every other line for the command ```$> ls -l```, starting from the first line

- Exercise 07 - r_dwssap.sh
  - Write a command line that displays the output of a cat /etc/passwd command, removing comments, every other line starting from the second line, reversing each login, sorted in reverse alphabetical order, and keeping only logins between FT_LINE1 and FT_LINE2 included, and they must separated by ", " (without quotation marks), and the output must end with a ".".
  - Example: Between lines 7 and 15, the result should be something like this : 
