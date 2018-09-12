In this project, I learned about manipulating files, redirecting files, and using special characters in the Shell.

* `0-hello_world`: Prints "Hello, World" followed by a new line to the standard output.
* `1-confused_smiley`: Displays a confused smiley `"(Ôo)'`.
* `2-hellofile`: Displays the content of the `/etc/passwd` file.
* `3-twofiles`: Displays the content of `etc/passwd` and `/etc/hosts`.
* `4-lastlines`: Displays the last 10 lines of `/etc/passwd`.
* `5-firstlines`: Displays the first 10 lines of `/etc/passwd`.
* `6-third_line`: Displays the third line of the file `iacta`.
* `7-file`: Creates a file named exactly `\*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:)` containing the text `Holberton School` ending by a new line.
* `8-cwd_state`: Writes into the file `ls_cwd_content` the result of the command `ls -la`.
* `9-duplicate_last_line`: Duplicates the last line of the file `iacta`.
* `10-no_more_js`: Deletes all the regular files (not directories) with a `.js` extension that are present in the current directory and all its subfolders.
* `11-directories`: Counts the number of directories and sub-directories in the current directory, not including the current and parent directories but counting hidden ones.
* `12-newest_files`: Displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.
* `13-unique`: Takes a list of words as input and only prints words that appear exactly once, one word per line, sorted.
* `14-findthatword`: Displays lines containing the pattern "root" from the file `/etc/passwd`.
* `15-countthatword`: Displays the number of lines containing the pattern "bin" in the file `/etc/passwd`.
* `16-whatsnext`: Displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`.
* `17-hidethisword`: Displays all lines in the file `/etc/passwd` that do not contain the pattern "bin".
* `18-letteronly`: Displays all lines of the file `/etc/ssh/sshd_config` starting with a letter, including capital letters.
* `19-AZ`: Replace all characters `A` and `c` from input to `Z` and `e` respectively.
* `20-hiago`: Removes all letters `c` and `C` from input.
* `21-reverse`: Reverses its input.
* `22-users_and_homes`: Displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.
* `100-empty_casks`: Finds all empty files and directories in the current directory and all sub-directories as follows:

  * Only the names of the files and directories are displayed.
  * Hidden files included.
  * One file name per line.

* `101-gifs`: Lists all the files with a `.gif` extension in the current directory and all its sub-directories as follows:

  * Hidden files included.
  * Only regular files (not directories) listed.
  * File names displayed without extensions.
  * Files sorted by byte values, but case insensitive.
  * One file name per line.

* `102-acrostic`: Decodes acrostics that use the first letter of each line.
* `103-the_biggest_fan`: Parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Ordered by number of requests, with most active hosts or IP's at the top.
