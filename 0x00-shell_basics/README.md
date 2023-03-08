0-current_working_directory: Prints the absolute path name of the current working directory.
1-listit: Displays the contents list of your current directory.
2-bring_me_home: Script that changes the working directory to the user’s home directory.
3-listfiles: Displays current directory contents in a long format.
4-listmorefiles: Displays current directory contents, including hidden files (starting with .) using long format.
5-listfilesdigitonly: Displays current directory contents in long format, with user and group IDs displayed numerically, and hidden files (starting with .)
6-firstdirectory: Creates a directory named my_first_directory in the /tmp/ directory.
7-movethatfile: Moves the file 'betty' from /tmp/ to /tmp/my_first_directory.
8-firstdelete: Deletes the file 'betty'
9-firstdirdeletion: Deletes the directory my_first_directory that is in the /tmp directory.
10-back: Script that changes the working directory to the previous one.
11-lists: Script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type: Script that prints the type of the file named iamafile.
13-symbolic_link: Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory. 
14-copy_html: Script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move: Script that moves all files beginning with an uppercase letter to the directory /tmp/u.
101-clean_emacs: Script that deletes all files in the current working directory that end with the character ~.
102-tree: Script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
103-commas: Command that lists all the files and directories of the current directory, separated by commas (,).

    Directory names end with a slash (/)
    Files and directories starting with a dot (.) are listed
    The listing is alpha ordered, except for the directories . and .. which are listed at the very beginning
    Only digits and letters are used to sort; Digits come first
    Assume that all the files will have at least one letter or one digit
    Listing ends with a new line
school.mgc: A magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.