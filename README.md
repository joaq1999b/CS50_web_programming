# CS50_web_programming
The repository for our course

this is what we have to install today,
don't rush, wait for me so we can check one by one that everything is being properly installed
funny enough I thought half of this stuff would come already installed, but the good news are that is totally trivial to install all these

ROOT ACCESS:
sudo su

PREPARE SYSTEM FOR INSTALLING STUFF:
apt-get update
apt-get upgrade

WEB SERVER:
apt-get install apache2
/etc/init.d/apache2 start
at the browser URL-> localhost

DATABASE SERVER:
apt-get install mysql-server
test before running this one -->apt-get install mysql-client-core-8.0
test:
/etc/init.d/mysql start
mysql


PHP:
test if PHP is running->
cd /var/www/html/
gedit info.php &
-> <?php phpinfo(); ?>
at the browser URL-> localhost/info.php

PYTHON:
Python is already installed, to test it type:
python3
IDEs:
apt-get install spyder
apt-get install atom
