Requirement for this projects

Allowed editors: vi, vim, emacs
All your scripts will be tested on Ubuntu 20.04 LTS
All your scripts should be exactly two lines long ($ wc -l file should print 2)
All your files should end with a new line (why?)
The first line of all your files should be exactly #!/bin/bash
A README.md file, at the root of the folder of the project, describing what each script is doing
You are not allowed to use backticks, &&, || or ;
All your files must be executable

**Note: The project is written on emacs editor
Tasks in this project

0. Create a script that switches the current user to the user betty.
1. Write a script that prints the effective username of the current user.
2. Write a script that prints all the groups the current user is part of.
3. Write a script that changes the owner of the file hello to the user betty.
4. Write a script that creates an empty file called hello.
5. Write a script that adds execute permission to the owner of the file hello.
6. Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7. Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
8. Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
The file hello will be in the working directory You are not allowed to use commas for this script
9. Write a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
10. Write a script that sets the mode of the file hello the same as s mode.

The file hello will be in the working directory
The file olleh will be in the working directory
11. Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12. Create a script that creates a directory called my_dir with permissions 751 in the working directory.
13. Write a script that changes the group owner to school for the file hello

The file hello will be in the working directory
14. Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15. Write a script that changes the owner and the group owner of _hello to vincent and staff respectively.

The file _hello is in the working directory
The file _hello is a symbolic link
16. Write a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

The file hello will be in the working directory
17. Write a script that will play the StarWars IV episode in the terminal.