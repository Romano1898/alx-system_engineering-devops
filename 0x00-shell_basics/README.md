0-current_working_directory shows the command for current working directory
1-listit displays content of current directory
2-bring_me_home changes working directory to home directory
3-listfiles displays current directory in long format
4-listmorefiles displays current directory contents including hidden files
5-listfilesdigitonly displays current directory in long format, including hidden files and user and group  IDs
6-firstdirectory creates a directory named my_first_directory in /tmp
7-movethatfile moves the file "betty" from /tmp to /tmp/my_first_directory
8-firstdelete deletes the file "betty" in the tmp folder
9-firstdirdeletion deletes my_first_directory in /tmp
10-back changes the working directory to the previous one.
11-lists Writes a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type Writes a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link Creates a symbolic link to /bin/ls, named __ls__ in the working directory
14-copy_html Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

100-lets_move Creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs Creates a script that deletes all files in the current working directory that end with the character ~.
102-tree Creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas Is a command that lists all the files and directories of the current directory, separated by commas (,).

    Directory names end with a slash (/)
    Files and directories start with a dot (.)
    The listing is alpha ordered, except for the directories . and .. which are listed at the very beginning
    Only digits and letters are used to sort; Digits come first

The listing ends with a new line
school.mgc is a magic file that uses the file command to detect School data files.
