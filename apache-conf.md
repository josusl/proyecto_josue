## Archivo de configuración  /etc/apache2/sites-available/music.jpenalba.es.conf

~~~
<VirtualHost *:80>
        ServerAdmin josupema@hotmail.com
        ServerName  music.jpenalba.es

        # Indexes + Directory Root.
        DirectoryIndex index.html index.php
        DocumentRoot /var/www/wordpress/

        <Directory /var/www/wordpress/>
          AllowOverride All
          Options FollowSymLinks
          Order allow,deny
          Allow from all
        </Directory>

        LogLevel warn
        CustomLog /var/log/apache2/wordpress-access.log combined
        ErrorLog /var/log/apache2/wordpress-error.log
</VirtualHost>

~~~
