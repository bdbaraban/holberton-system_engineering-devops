In this project, I learned about changing Linux user and file permissions in the Shell.

---

* `0-iam_betty`: Script that changes the user ID to `betty`.
* `1-who_am_i`: Script that prints the effective userid of the current user.
* `2-groups`: Script that prints all the groups the current user is a part of.
* `3-new_owner`: Script that changes the owner of the file `hello` to the user `betty`.
* `4-empty`: Script that creates an empty file called `hello`.
* `5-execute`: Script that adds execute permissions to the owner of the file `hello`.
* `6-multiple_permissions`: Script that adds execute permission to the owner and the group owner, and read permission to other users, for the file `hello`.
* `7-everybody`: Script that adds execution permission to the owner, the group owner and the other users, for the file `hello`.
* `8-James_Bond`: Script that sets the permission for the file `hello` as follows:

   * Owner - no permission at all
   * Group - no permission at all
   * Other users - all permissoins

* `9-John_Doe`: Script that sets the mode of the file `hello` to -rwxr-x-wx.
* `10-mirror_permissions`: Script that sets the mode of the file `hello` the same as the file `olleh`.
* `11-directories_permissions`: Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files are not changed.
* `12-directory_permissions`: Script that creates a directory `dir_holberton` with permissions 751 in the working directory.
* `13-change_group`: Script that changes the group owner to `holberton` for the file `hello`.
* `14-change_owner_and_group`: Script that changes the owner to `betty` and the group owner to `holberton` for all the files and directories in the working directory.
* `15-symbolic_link_permissions`: Script that changes the owner and the group owner of the file `hello` to `betty` and `holberton`, respectively.
* `16-if_only`: Script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.
* `100-Star_Wars`: Script that plays Star Wars Episode IV in the terminal.
* `101-man_holberton`: A man page.
