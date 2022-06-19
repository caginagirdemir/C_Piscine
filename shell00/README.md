# Shell 00       <img src="pics/bash.png" width="64" height="30" />

- Exercise 00 - Only the best know how to display Z
  - Create a file called z that return "Z", followed by a new line, whenever the command cat is used on it.
  ![Image1](pics/only_z.png)

- Exercise 01 - What are attributes anyway?
  - Create a file called testShell00 in your submission directory.
  - Figure out a way for the output to look like this (expect for the "total 1" line)
  ![Image1](pics/only_z.png)
  - Once you have achieved the previous step, execute the following command to create the file to be submitted: ```$> tar -cf testShell00.tar testShell00```
- Exercise 02 - Oh yeah, mooore...
  - Create the following files and directories. Do what's necessary so that when you use the ls -l command in your directory, the output will looks like this:
  ![Image1](pics/only_z.png)
  - Once you have done that, run ```$> tar -cf exo2.tar *``` to create the file to be submitted.

- Exercise 03 - SSH Key
  - Create your own SSH key. Once it is done:
    - Add your public key to your repository, in a file name id_rsa_pub
    - Update your ssh key on the intranet. This will allow you to push the repository to our git server.

- Exercise 04 - midLS
  - In a midLS file, place the command line that will list all files and directories in your current directory (except for hidden files or any file that starts by a dot - yes, that includes double-dots), separated by a comma, by order of modification date. Make sure the directory’s names are followed by a slash character.

- Exercise 05 - GiT commit?
  - Create a shell script that displays the ids of the last 5 commits of your git respository.
![Image1](pics/only_z.png)
  - To test your script, we will use our own enviroment.
