# Loops, conditions and parsing

In this project, I began working loops and conditionals statemetns in Bash.

## Tasks
* **Create a SSH RSA key pair**
  * `0-RSA_public_key.pub`: A public SSH key uploaded for the purposes of 
Holberton School.

* **For Holberton School loop**
  * `1-for_holberton_school`: Bash script that displays `Holberton School` 
10 times using a `for` loop.

* **While Holberton School loop**
  * `2-while_holberton_school`: Bash script that displays `Holberton School` 
10 times using a `while` loop.

* **Until Holberton School loop**
  * `3-until_holberton_school`: Bash script that displays `Holberton School` 
10 times using an `until` loop.

* **If 9, say Hi!**
  * `4-if_9_say_hi`: Bash script that displays `Holberton School` 10 times 
using a `while` loop.
  * For the 9th iteration, displays `Holberton School` and then `Hi` on a 
new line.
  * Uses an `if` statement.

* **4 bad luck, 8 is your chance**
  * `5-4_bad_luck_8_is_your_chance`: Bash script that loops from 1 to 10 using 
a `while` loop and:
    * Displays `bad luck` on the 4th iteration.
    * Displays `good luck` on the 8th iteration.
    * Displays `Holberton School` for all other iterations.
  * Uses the `if`, `elif`, and `else` statements.

* **Superstitious numbers**
  * `6-superstitious_numbers`: Bash script that displays numbers from `1` to 
`20` using a `while` loop and:
    * Displays `4` and then `bad luck from China` for the 4th iteration.
    * Displays `9` and then `bad luck from Japan` for the 9th iteration.
    * Displays `17` and then `bad luck from Italy` for the 17th iteration.
  * Uses a `case` statement.

* **Clock**
  * `7-clock`: Bash script that displays the time for 12 hours and 59 minutes.
    * Displays hours from `0` to `12`.
    * Displays minutes from `0` to `59`.

* **For ls**
  * `8-for_ls`: Bash script that displays the contents of the current directory 
in list format.
  * Only the part of the name after the first dash is displayed.

* **To file, or not to file**
  * `9-to_file_or_not_to_file`: Bash script that gives information about the 
`holbertonschool` file.
    * If the file exists, displays: `holbertonschool file exists`.
    * If the file does not exist, displays: `holbertonschool file does not exist`.
    * If the file exists and is empty, displays: `holbertonschool file is empty`.
    * If the file exists and is not empty, displays: `holbertonschoolfile is not 
empty`.
    * If the file exists and is a regular file, displays: `holbertonschool file 
is a regular file`.
    * Otherwise, displays nothing.

* **FizzBuzz**
  * `10-fizzbuzz`: Bash script that displays numbers from `1` to `100` in list 
format.
  * Displays `FizzBuzz` when the number is a multiple of 3 and 5.
  * Displays `Fizz` when the number is a multiple of 3.
  * Displays `Buzz` when the number is a multiple of 5.
  * Otherwise, displays the number.

* **Read and cut**
  * `100-read_and_cut`: Bash script that displays the contents of the 
`/etc/passwd` file.
  * Displays only the username, user id, and user home directory path for 
each line.

* **Tell the story of passwd**
  * `101-tell_the_story_of_passwd`: Bash script that tells stories based on 
the contents of the `/etc/passwd` file.
  * Displays content from the file in the format: `The user USERNAME is part of 
the GROUP_ID gang, lives in HOME_DIRECTORY and rides COMMAND/SHELL. USER ID's 
place is protected by the passcode PASSWORD, more info about the user here: 
USER ID INFO`.

* **Let's parse Apache logs**
  * `102-lets_parse_apache_logs`: Bash script that displays the visitor IP 
along with the HTTP status code for logs read from an Apache log access file.
  * Displays content in the format `IP HTTP_CODE`.
  * Uses `awk`.

* **Dig the data**
  * `103-dig_the-data`: Bash script that reads content from an Apace log access 
file and groups visitors by IP and HTTP status code.
  * Displays the grouped number of visitors to an IP address in the format 
`OCCURRENCE_NUMBER IP HTTP_CODE`.
  * Logs are grouped in order of greatest to lowest number of visitors.
  * Uses `awk`.
