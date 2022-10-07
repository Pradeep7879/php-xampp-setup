# php-xampp-setup

Installing apache2
    • sudo apt install apache2
    • sudo systemctl status apache2
    • sudo apt install php7.4 php7.4-mysql php-common php7.4-cli php7.4-json php7.4-common php7.4-opcache libapache2-mod-php7.4
    • php –version
    • sudo systemctl restart apache2
    • touch ~/Templates/"Untitled Document"
    • sudo apt install mysql-server
    • sudo apt-get install curl
    • sudo apt install php-pgsql
    • sudo apt install php-cli
    • sudo apt install php libapache2-mod-php
    • curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add -
    • sudo apt-get update
    • sudo apt install wget curl ca-certificates
    
-------------------------------------------------------------------------------------------
   
    Enable Clean url
    • sudo a2enmod rewrite
    • sudo apache2ctl -M
    • Enable all extentions in php.ini by uncommenting lines
    • cd /etc/apache2
    • sudo gedit apache2.conf
        <Directory "/var/www/html">
        AllowOverride All
        </Directory>

     • sudo gedit /etc/apache2/sites-available/000-default.conf
        <Directory "/var/www/html">
        AllowOverride All
        </Directory>

    • sudo service apache2 restart

-------------------------------------------------------------------------------------------

Installing PHP libraries
    • sudo apt-get install -y php-simplexml
    • sudo apt-get install php-gd
    • sudo apt-get install php-curl
    • sudo apt-get install php-mbstring
    • sudo apt-get install libapache2-mod-php
    • sudo service apache2 restart
    • sudo apt-get install php-zip
    • Enable php mcrypt extension, aes.
    • Enable mysql, sqlserver extensions and also pdo.
