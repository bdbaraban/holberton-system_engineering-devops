# Web server

In this project, I learned about how web servers work.

## Tasks
* **0. Transfer a file to your server**
  * `0-transfer_file`: Bash script that transfers a file from Holberton's
client to a server.
  * Accepts four arguments:
    * The path of the file to be transferred.
    * The IP of the server to transfer the file to.
    * The username that `scp` connects with.
    * The path of the SSH privtae key that `scp` uses.
  * `scp` transfers the file to the user home directory `~/`.

* **1. Install nginx web server**
  * `1-install_nginx_web_server`: Bash script that configures a new
Ubuntu machine with Nginx.
  * Nginx listens on port 80.
  * When querying Nginx at its root `/` with a `curl` GET request,
it returns a page containing the string `Holberton School`.

* **2. Setup a domain name**
  * `2-setup_a_domain_name`

* **3. Redirection**
  * `3-redirection`

* **4. Not found page 404**
  * `4-not_found_page_404`

* **5. Design a beautiful 404 page**
  * `5-design_a_beautiful_404_page`

* **6. Deploy fast, deploy well**
  * `fabfile.py`
