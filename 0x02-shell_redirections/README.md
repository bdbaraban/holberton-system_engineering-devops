In this project, I learned about manipulating files, redirecting files, and using special characters in the Shell.

* `0-hello_world`: Script that prints "Hello, World" followed by a new line to the standard output.
* `1-confused_smiley`: Script that displays a confused smiley `"(Ôo)'`.
* `2-hellofile`: Script that displays the content of the `/etc/passwd` file.
* `3-twofiles`: Script that displays the content of `etc/passwd` and `/etc/hosts`.
* `4-lastlines`: Script that displays the last 10 lines of `/etc/passwd`.
* `5-firstlines`: Script that displays the first 10 lines of `/etc/passwd`.
* `6-third_line`: Script that displays the third line of the file `iacta`.
* `7-file`: Script that creates a file named exactly `\*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:)` containing the text `Holberton School` ending by a new line.
* `8-cwd_state`: Script that writes into the file `ls_cwd_content` the result of the command `ls -la`.
* `9-duplicate_last_line`: Script that duplicates the last line of the file `iacta`.
* `10-no_more_js`: Script that deletes all the regular files (not directories) with a `.js` extension that are present in the current directory and all its subfolders.
* `11-directories`: Script that counts the number of directories and sub-directories in the current directory, not including the current and parent directories but counting hidden ones.
* `12-newest_files`: Script that displays the 10 newest files in the current directory, one file per line, sorted from newest to oldest.
* `13-unique`: Script that takes a list of words as input and only prints words that appear exactly once, one word per line, sorted.
* `14-findthatword`: Script that displays lines containing the pattern "root" from the file `/etc/passwd`.
* `15-countthatword`: Script that displays the number of lines containing the pattern "bin" in the file `/etc/passwd`.
* `16-whatsnext`: Script that displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`.
* `17-hidethisword`: Script that displays all lines in the file `/etc/passwd` that do not contain the pattern "bin".
* `18-letteronly`: Script that displays all lines of the file `/etc/ssh/sshd_config` starting with a letter, including capital letters.
* `19-AZ`: Script that replaces all characters `A` and `c` from input to `Z` and `e` respectively.
* `20-hiago`: Script that removes all letters `c` and `C` from input.
* `21-reverse`: Script that reverses its input.
* `22-users_and_homes`: Script that displays all users and their home directories, sorted by users, based on the `/etc/passwd` file.
* `100-empty_casks`: Script that finds all empty files and directories in the current directory and all sub-directories as follows:

  * Only the names of the files and directories are displayed.
  * Hidden files included.
  * One file name per line.

* `101-gifs`: Script that lists all the files with a `.gif` extension in the current directory and all its sub-directories as follows:

  * Hidden files included.
  * Only regular files (not directories) listed.
  * File names displayed without extensions.
  * Files sorted by byte values, but case insensitive.
  * One file name per line.

* `102-acrostic`: Script that decodes acrostics that use the first letter of each line.
* `103-the_biggest_fan`: Script that parses web server logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Ordered by number of requests, with most active hosts or IP's at the top.
