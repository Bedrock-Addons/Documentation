---
slug: doc3
title: Installation

---
## Installing on Linux

For this, I will explain how to install on a VPS running Ubuntu 20.04. This requires some understanding of Linux, Apache, and SQL.

1. Start up a server with atleast 500MB of memory, and 8GB of storage.
2. Install a LAMP stack (Linux, Apache, MySQL, and PHP) and configure it.
3. Upload everything except the `Bedrock-Addons.sql` file to the `/var/www/html/` directory on your server.
4. Upload `Bedrock-Addons.sql` to the database, and configure a username and password.
5. Open the `conf.php` file found in `/services/` and change the database credentials to match the ones you set previously.
6. Go to your server IP address and you should see a login page. Login with username `BA2021` and password `BAforMC2021` and change the default credentials.
7. I recommend that you connect a domain and configure SSL for your server, but it is not required for the bare-minimum operation.
8. Congrats! You've got a server running the Universal Addons Project (UAP) data managment software.