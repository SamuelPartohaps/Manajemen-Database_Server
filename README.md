# Manajemen-Database-Server
Final Projek
SAMUEL DAYA ANUGERAH 23.83.0955

  # MEMPERBARUI SISTEM PERANGKAT LUNAK
    sudo apt update
    sudo apt upgrade

  # INSTALASI MARIADB
    sudo apt install mariadb-server

  # KONFIGURASI MARIADB
    sudo mysql_secure_installation

  #  INSTALASI WEB SERVER MENGGUNAKAN APACHE  
    sudo apt install apache2
    sudo nano /etc/apache2/sites-available/yourproject.conf

  # MENAMBAHKAN KONFIGURASI PADA FILE APACHE2
    <VirtualHost *:80>
    ServerAdmin admin@yourproject.com
    DocumentRoot /var/www/yourproject
    ServerName yourproject.com
    ErrorLog ${APACHE_LOG_DIR}/error.log
    CustomLog ${APACHE_LOG_DIR}/access.log combined
    </VirtualHost>

  # MENGAKTIFKAN KONFIGURASI APACHE2
    sudo a2ensite yourproject.conf
    sudo systemctl reload apache2

  # LANGKAH INSTALASI PHP :

    sudo apt install php libapache2-mod-php

  #  INSTALL PHP
    php -v

  # LANGKAH INSSTALL PHPMYADMIN :
    sudo apt install phpmyadmin

  # 

