In this project, I learned about the Shell, including how to navigate it, manipulate files, work with commands, and read man pages.

* `0-current_working_directory`: Prints the absolute pathname of the current working directory.
* `1-listit`: Displays the contents list of current directory.
* `2-bring_me_home`: Changes the working directory to the user's home directory.
* `3-listfiles`: Displays current directory contents in long format.
* `4-listmorefiles`: Displays current directory contents, including hidden files, using long format.
* `5-listfilesdigitonly`: Displays current directory contents, including hidden files, as follows:

   * Long format
   * User and group ID's displayed numerically

* `6-firstdirectory`: Creates a directory named `holberton` in the `/tmp/` directory.
* `7-movethatfile`: Moves the file `betty` from `/tmp/` to `/tmp/holberton`.
* `8-firstdelete`: Deletes the file `betty` in `/tmp/holberton`.
* `9-firstdirdeletion`: Deletes the directory `holberton` in the `/tmp` directory.
* `10-back`: Changes the working directory to the previous one.
* `11-lists`: Lists all files, including hidden files, in the current directory, parent of the working directory, and `/boot` directory, using long format.
* `12-file_type`: Prints the type of the file named `iamafile` located in the `/tmp` directory.
* `13-symbolic_link`: Creates a symbolic link to `/bin/ls`, named `__ls__`.
* `14-copy_html`: Copies all HTML files from the current working directory to the parent of the working directory, but only those that did not exist in the parent directory or were newer than the versions in the parent working directory.
* `15-lets_move`: Moves all files beginning with an uppercase letter to the directory `/tmp/u`.
* `16-clean_emacs`: Deletes all files in the current working directory that end with the character `~`.
* `17-tree`: Creates the directories `welcome/`, `welcome/to/` and `welcome/to/holberton` in the current directory.
* `18-commas`: Lists all files and directories of the current directory, including hidden ones, as follows:

   * Separated by commas (`,`).
   * Directory names end with a slash (`/`).
   * Alpha-ordered, except for the directories `.` and `..` which are listed at the beginning.
   * Only digits and letters are used to sort - digits come first.

* `holberton.mgc`: A magic file that can be used with the command `file` to detect `Holberton` data files.
