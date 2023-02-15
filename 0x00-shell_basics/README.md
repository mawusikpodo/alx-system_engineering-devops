## The commands used:
- Task 0: Write a script that prints the absolute path name of the current working directory. ```pwd``` <br>
- Task 1: Display the contents list of your current directory. ```ls``` <br>
- Task 2: Write a script that changes the working directory to the user’s home directory. ```cd ~ ```<br>
- Task 3: Display current directory contents in a long format ```ls -l``` <br>
- Task 4: Display current directory contents, including hidden files (starting with .). Use the long format. ```ls -la``` <br>
- Task 5: Display current directory contents.
 --Long format
 --with user and group IDs displayed numerically
 --And hidden files (starting with .) ```ls -lna``` <br>
- Task 6: Create a script that creates a directory named my_first_directory in the /tmp/ directory. ```mkdir /tmp/my_first_directory``` <br>
- Task 7: Move the file betty from /tmp/ to /tmp/my_first_directory. ```mv /tmp/betty /tmp/my_first_directory``` <br>
- Task 8: Delete the file betty.
 --The file betty is in /tmp/my_first_directory```rm /tmp/my_first_directory/betty ```<br>
- Task 9: Delete the directory my_first_directory that is in the /tmp directory. ```rm -r /tmp/my_first_directory``` <br>
- Task 10: Write a script that changes the working directory to the previous one. ```cd -``` <br>
- Task 11: Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the     parent of the working directory and the /boot directory (in this order), in long format. ```ls -a . .. /boot``` <br>
- Task 12: Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script. ```file /tmp/iamafile``` <br>
- Task 13: Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. ```ln -s /bin/ls __ls__``` <br>
- Task 14: Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that all HTML files have the extension .html ```cp -u *.html ../``` <br>
- Task 15: Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
You can assume that the directory /tmp/u will exist when we will run your script ```mv [[:upper:]]* /tmp/u``` <br>
- Task 16: Create a script that deletes all files in the current working directory that end with the character ~. ```rm *~``` <br>
- Task 17: Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
You are only allowed to use two spaces (and lines) in your script, not more  ```mkdir -p welcome/to/school``` <br>
- Task 18: Write a command that lists all the files and directories of the current directory, separated by commas (,). ```ls -amvp``` <br>
