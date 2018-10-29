# Shell, basics
In this project, I learned about what the Shell is, how to navigate directories using `cd`, `pwd`, `ls`, how to look around using `ls`, `less`, and `file`, and how to manipulate files with `cp`, `mv`, `rm`, and `mkdir`. Further, I practiced working with the `type`, `which`, `help`, and `man` commands, implementing wildcards, reading man pages, creating links, and using keyboard shortcuts in Bash.

## Tasks
* **Where am I?**
  * `0-current_working_directory`: Bash script that prints the absolute pathname of the current working directory.

* **What’s in there?**
  * `1-listit`: Bash script that displays the contents list of current directory.

* **There is no place like home**
  * `2-bring_me_home`: Bash script that changes the working directory to the user's home directory.

* **The long format**
  * `3-listfiles`: Bash script that displays current directory contents in long format.

* **Hidden files**
  * `4-listmorefiles`: Bash script that displays current directory contents, including hidden files, using long format.

* **I love numbers**
  * `5-listfilesdigitonly`: Bash script that displays current directory contents, including hidden files, as follows:
    * Long format
    * User and group ID's displayed numerically

* **Welcome holberton**
  * `6-firstdirectory`: Bash script that creates a directory named `holberton` in the `/tmp/` directory.

* **Betty in Holberton**
  * `7-movethatfile`: Bash script that moves the file `betty` from `/tmp/` to `/tmp/holberton`.

* **Bye bye Betty**
  * `8-firstdelete`: Bash script that deletes the file `betty` in `/tmp/holberton`.

* **Bye bye Holberton**
  * `9-firstdirdeletion`: Bash script that deletes the directory `holberton` in the `/tmp` directory.

* **Back to the future**
  * `10-back`: Bash script that changes the working directory to the previous one.

* **Lists**
  * `11-lists`: Bash script that lists all files, including hidden files, in the current directory, parent of the working directory, and `/boot` directory, using long format.

* **File type**
  * `12-file_type`: Bash script that prints the type of the file named `iamafile` located in the `/tmp` directory.

* **We are symbols, and inhabit symbols**
  * `13-symbolic_link`: Bash script that creates a symbolic link to `/bin/ls`, named `__ls__`.

* **Copy HTML files**
  * `14-copy_html`: Bash script that copies all HTML files from the current working directory to the parent of the working directory, but only those that did not exist in the parent directory or were newer than the versions in the parent working directory.

* **Let’s move**
  * `15-lets_move`: Bash script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

* **Clean Emacs**
  * `16-clean_emacs`: Bash script that deletes all files in the current working directory that end with the character `~`.

* **Tree**
  * `17-tree`: Bash script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/holberton` in the current directory.

* **Life is a series of commas, not periods**
  * `18-commas`: Bash script that lists all files and directories of the current directory, including hidden ones, as follows:
    * Separated by commas (`,`).
    * Directory names end with a slash (`/`).
    * Alpha-ordered, except for the directories `.` and `..` which are listed at the beginning.
    * Only digits and letters are used to sort - digits come first.

* **File type: Holberton**
  * `holberton.mgc`: A magic file that can be used with the command `file` to detect `Holberton` data files.
