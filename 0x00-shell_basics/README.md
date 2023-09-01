# 0x00-shell_basics
## 0-current_working_directory
Write a script that prints teha bsolute path name of the current working directory.
## 1-list_it
Display all the contents list of your current directory.
## 2-bring_me_home
Write a script that changes the working directory to the user's home directory.
- You are not allowed to use any shell variable.
## 3-listfiles
Display current directory contents in a long format.
## 4-list_more_files
Display current directory contents, including hidden files(starting with ``` . ```). Use the long format.
## 5-listfilesdigitonly
Display current directory contents.
- Long format
- with user and group IDs displayed numerically
- And hidden file(starting with.)
## 6-firstdirectory
Create a script that creates a director named ``` my_first_directory ``` in the ``` /tmp/ ``` directory.
## 7-movethatfile
Move the file ``` betty ``` from ``` /tmp/ ``` to ```/tmp/my_first_directory ```.
## 8-firstdelete
Delete the file ``` betty ```.
- The file ``` betty ``` is in ``` /tmp/my_first_directory ```.   
## 9-firstdirdeletion
Delete the directory ``` my_first_directory ``` that is in the ``` /tmp ``` directory.
## 10-back
Write a script that changes the working directory to the previous one.
## 11-lists
Write a script that lists all files(even ones with names beginning with a period charachter, which are normally hidden) in the current directory and the parent of the working directory and the ``` boot ``` directory (in this order), in long format.
## 12-file_type
Write a script that prints the type of the file named ``` iamfile ```. The file ``` iamafile ``` will be in the ``` /tmp/ directory when we will run your script.
## 13-symbolic_link
Create a symblolic link to ``` /bin/ls ```, named ``` __ls__ ```. The symbolic link should be created in the current working directory.
## 14-copy_html
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
You can consider that HTML files have the extension. ``` .html ```.
## 100-lets_move
Create a script that moves all files beginning with an uppercase letter to the directory ``` /tmp/u ```.
You can assume that the directory ``` /tmp/u ``` will exist when we will run your script. 
## 101-clean_emacs
Create a script that deletes all files in the current working directory that end with the character ``` ~ ```.
## 102-tree
Create a script that creates the directories ``` welcome ``` , ``` welcome/to/ ``` and 	``` welcome/to/school ``` in the current directory.
You are only allowed to use two spaces(and lines)in your script, not more.
## 103-commas
Write a command that lists all the files and directories of the current directory, separated by commas ```(,) ```.
- Directory names should end with a slash ``` (/) ```.
- Files and directories starting with a dot ``` (.) ``` should be listed.
- The listing should be alpha ordered, except for the directories the directories ``` . ``` and ``` .. ``` which should be listed ate the very beginning.
- Only digits and letters are used to sort; Digits should come first.
- You can assume that all the files we will test with will have at least one letter or one digit.
- The listing should end with a new line
