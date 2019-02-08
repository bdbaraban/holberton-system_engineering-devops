# Shell, permissions
In this project, I learned about using the `chmod`, `sudo`, `su`, `chown`, and 
`chgrp` commands to represent and change Linux file permissions and change users 
in the Shell.

## Tasks
* **My name is Betty**
  * `0-iam_betty`: Bash script that changes the user ID to `betty`.

* **Who am I**
  * `1-who_am_i`: Bash script that prints the effective userid of the current user.

* **Groups**
  * `2-groups`: Bash script that prints all the groups the current user is a 
part of.

* **New owner**
  * `3-new_owner`: Bash script that changes the owner of the file `hello` to 
the user `betty`.

* **Empty!**
  * `4-empty`: Bash script that creates an empty file called `hello`.

* **Execute**
  * `5-execute`: Bash script that adds execute permissions to the owner of the 
file `hello`.

* **Multiple permissions**
  * `6-multiple_permissions`: Bash script that adds execute permission to the 
owner and the group owner, and read permission to other users, for the file 
`hello`.

* **Everybody!**
  * `7-everybody`: Bash script that adds execution permission to the owner, the 
group owner and the other users, for the file `hello`.

* **James Bond**
  * `8-James_Bond`: Bash script that sets the permission for the file `hello` as 
follows:
    * Owner - no permission at all
    * Group - no permission at all
    * Other users - all permissoins

* **John Doe**
  * `9-John_Doe`: Bash script that sets the mode of the file `hello` to 
-rwxr-x-wx.

* **Look in the mirror**
  * `10-mirror_permissions`: Bash script that sets the mode of the file `hello` 
the same as the file `olleh`.

* **Directories**
  * `11-directories_permissions`: Bash script that adds execute permission to 
all subdirectories of the current directory for the owner, the group owner and 
all other users. Regular files are not changed.

* **More directories**
  * `12-directory_permissions`: Bash script that creates a directory 
`dir_holberton` with permissions 751 in the working directory.

* **Change group**
  * `13-change_group`: Bash script that changes the group owner to `holberton` 
for the file `hello`.

* **Owner and group**
  * `14-change_owner_and_group`: Bash script that changes the owner to `betty` 
and the group owner to `holberton` for all the files and directories in the 
working directory.

* **Symbolic links**
  * `15-symbolic_link_permissions`: Bash script that changes the owner and the 
group owner of the file `hello` to `betty` and `holberton`, respectively.

* **If only**
  * `16-if_only`: Bash script that changes the owner of the file `hello` to 
`betty` only if it is owned by the user `guillaume`.

* **Star Wars**
  * `100-Star_Wars`: Bash script that plays Star Wars Episode IV in the terminal.

* **RTFM**
  * `101-man_holberton`: A man page.
