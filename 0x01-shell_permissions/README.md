# 0x01. Shell, permissions
This reaadme file will describe what each script in this directory does

## 0-iam_betty
Create a script that switches the current user to the user ``` betty ```
- You should use exactly 8 characters for your command(+1 charachter for the new line).
- You can assume that the user ``` betty ``` will exist when we run your script.
## 1-who_am_i
Write a script that prints the effective username of the current user.
## 2-goups
Write a script that prints all the groups the current user is part of.
- Note: depending on the user, you will get a different output.
## 3-new_owner
Write a script that changes the owner of the file ``` hello ``` to the user ``` betty ```.
## 4-empty
Write  a script that creates an empty file called ``` hello ```.
## 5-excute
Write a script that adds execute permission to the owner of the file ``` hello ```.
## 6-multiple_permissions
Write a script that adds excute permission ot the owner and the groups owner, and read permission to other users, to the file ``` hello ```.
## 7-everybody
Write a script that adds excution permission to the owner, the group owner and the other users, to the file ``` hello ```.
## 8-james_bond
Write a script taht sets the permission to the file ``` hello ``` as follows: 
- Owner: no permission at all.
- Group: no permission at all.
- Other users: all permissions.
The file ``` hello ``` will be in the working directory You are not allowed to use commas for this script.
## 9-John_Doe
Write a script that sets the mode of the file hello to this:
``` -rxxr-x-wx 1 julien julien 23 sep 20 14:25 hello ```
