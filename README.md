# IT350_Project

## Setup local machine
Open the terminal in Ubuntu.
Install Apache2
* sudo apt-get install apache2

Install PHP
* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install php5.6
* sudo apt-get install libapache2-mod-php

Install SQLite3
* sudo apt-get install sqlite3

Install Git
* sudo apt-get install git-all

Download GitHub Desktop if you wish
Create a GitHub Account

Download repository
* Go to /var/www and use the command: sudo git clone https://github.com/acook8/IT350_Project.git

Change default page
* sudo nano /etc/apache2/sites-available/000-default.conf
change “DocumentRoot /var/www/html” to “DocumentRoot /var/www/IT350_Project/codeigniter”

Database
* Because Git doesn't support database files, it is best to keep the database out of the repository. On the server the database is called imf and is located in the /var/www folder. Make sure to create a database there on your local machine.

## Wiki
Look at the Wiki for some information about how to use GitHub

## Issues
Bugs and tasks go under issues. Create an Issue for these so everyone knows what they are, and so we can work on them together
