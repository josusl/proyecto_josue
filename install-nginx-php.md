~~~
root@server-nginx:/home/ubuntu# sudo apt install php7.4 php7.4-fpm php7.4-mysql php-common php7.4-cli php7.4-common php7.4-json php7.4-opcache php7.4-readline php7.4-mbstring php7.4-xml php7.4-gd php7.4-curl
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  libonig5
Suggested packages:
  php-pear
The following NEW packages will be installed:
  libonig5 php-common php7.4 php7.4-cli php7.4-common php7.4-curl php7.4-fpm php7.4-gd php7.4-json php7.4-mbstring php7.4-mysql php7.4-opcache
  php7.4-readline php7.4-xml
0 upgraded, 14 newly installed, 0 to remove and 0 not upgraded.
Need to get 4577 kB of archives.
After this operation, 20.5 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/universe arm64 libonig5 arm64 6.9.4-1 [134 kB]
Get:2 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 php-common all 2:75 [11.9 kB]
Get:3 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-common arm64 7.4.3-4ubuntu2.15 [959 kB]
Get:4 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-json arm64 7.4.3-4ubuntu2.15 [17.9 kB]
Get:5 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-opcache arm64 7.4.3-4ubuntu2.15 [179 kB]
Get:6 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-readline arm64 7.4.3-4ubuntu2.15 [11.8 kB]
Get:7 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-cli arm64 7.4.3-4ubuntu2.15 [1301 kB]
Get:8 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/universe arm64 php7.4-fpm arm64 7.4.3-4ubuntu2.15 [1308 kB]
Get:9 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4 all 7.4.3-4ubuntu2.15 [9232 B]
Get:10 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-curl arm64 7.4.3-4ubuntu2.15 [29.0 kB]
Get:11 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-gd arm64 7.4.3-4ubuntu2.15 [26.8 kB]
Get:12 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/universe arm64 php7.4-mbstring arm64 7.4.3-4ubuntu2.15 [388 kB]
Get:13 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-mysql arm64 7.4.3-4ubuntu2.15 [111 kB]
Get:14 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 php7.4-xml arm64 7.4.3-4ubuntu2.15 [89.5 kB]
Fetched 4577 kB in 0s (16.8 MB/s)
Selecting previously unselected package libonig5:arm64.
(Reading database ... 94642 files and directories currently installed.)
Preparing to unpack .../00-libonig5_6.9.4-1_arm64.deb ...
Unpacking libonig5:arm64 (6.9.4-1) ...
Selecting previously unselected package php-common.
Preparing to unpack .../01-php-common_2%3a75_all.deb ...
Unpacking php-common (2:75) ...
Selecting previously unselected package php7.4-common.
Preparing to unpack .../02-php7.4-common_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-common (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-json.
Preparing to unpack .../03-php7.4-json_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-json (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-opcache.
Preparing to unpack .../04-php7.4-opcache_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-opcache (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-readline.
Preparing to unpack .../05-php7.4-readline_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-readline (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-cli.
Preparing to unpack .../06-php7.4-cli_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-cli (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-fpm.
Preparing to unpack .../07-php7.4-fpm_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-fpm (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4.
Preparing to unpack .../08-php7.4_7.4.3-4ubuntu2.15_all.deb ...
Unpacking php7.4 (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-curl.
Preparing to unpack .../09-php7.4-curl_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-curl (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-gd.
Preparing to unpack .../10-php7.4-gd_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-gd (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-mbstring.
Preparing to unpack .../11-php7.4-mbstring_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-mbstring (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-mysql.
Preparing to unpack .../12-php7.4-mysql_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-mysql (7.4.3-4ubuntu2.15) ...
Selecting previously unselected package php7.4-xml.
Preparing to unpack .../13-php7.4-xml_7.4.3-4ubuntu2.15_arm64.deb ...
Unpacking php7.4-xml (7.4.3-4ubuntu2.15) ...
Setting up php-common (2:75) ...
Created symlink /etc/systemd/system/timers.target.wants/phpsessionclean.timer → /lib/systemd/system/phpsessionclean.timer.
Setting up php7.4-common (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/calendar.ini with new version

Creating config file /etc/php/7.4/mods-available/ctype.ini with new version

Creating config file /etc/php/7.4/mods-available/exif.ini with new version

Creating config file /etc/php/7.4/mods-available/fileinfo.ini with new version

Creating config file /etc/php/7.4/mods-available/ffi.ini with new version

Creating config file /etc/php/7.4/mods-available/ftp.ini with new version

Creating config file /etc/php/7.4/mods-available/gettext.ini with new version

Creating config file /etc/php/7.4/mods-available/iconv.ini with new version

Creating config file /etc/php/7.4/mods-available/pdo.ini with new version

Creating config file /etc/php/7.4/mods-available/phar.ini with new version

Creating config file /etc/php/7.4/mods-available/posix.ini with new version

Creating config file /etc/php/7.4/mods-available/shmop.ini with new version

Creating config file /etc/php/7.4/mods-available/sockets.ini with new version

Creating config file /etc/php/7.4/mods-available/sysvmsg.ini with new version

Creating config file /etc/php/7.4/mods-available/sysvsem.ini with new version

Creating config file /etc/php/7.4/mods-available/sysvshm.ini with new version

Creating config file /etc/php/7.4/mods-available/tokenizer.ini with new version
Setting up php7.4-curl (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/curl.ini with new version
Setting up php7.4-mysql (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/mysqlnd.ini with new version

Creating config file /etc/php/7.4/mods-available/mysqli.ini with new version

Creating config file /etc/php/7.4/mods-available/pdo_mysql.ini with new version
Setting up php7.4-readline (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/readline.ini with new version
Setting up php7.4-opcache (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/opcache.ini with new version
Setting up libonig5:arm64 (6.9.4-1) ...
Setting up php7.4-gd (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/gd.ini with new version
Setting up php7.4-json (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/json.ini with new version
Setting up php7.4-xml (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/dom.ini with new version

Creating config file /etc/php/7.4/mods-available/simplexml.ini with new version

Creating config file /etc/php/7.4/mods-available/xml.ini with new version

Creating config file /etc/php/7.4/mods-available/xmlreader.ini with new version

Creating config file /etc/php/7.4/mods-available/xmlwriter.ini with new version

Creating config file /etc/php/7.4/mods-available/xsl.ini with new version
Setting up php7.4-mbstring (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/mods-available/mbstring.ini with new version
Setting up php7.4-cli (7.4.3-4ubuntu2.15) ...
update-alternatives: using /usr/bin/php7.4 to provide /usr/bin/php (php) in auto mode
update-alternatives: using /usr/bin/phar7.4 to provide /usr/bin/phar (phar) in auto mode
update-alternatives: using /usr/bin/phar.phar7.4 to provide /usr/bin/phar.phar (phar.phar) in auto mode

Creating config file /etc/php/7.4/cli/php.ini with new version
Setting up php7.4-fpm (7.4.3-4ubuntu2.15) ...

Creating config file /etc/php/7.4/fpm/php.ini with new version
Created symlink /etc/systemd/system/multi-user.target.wants/php7.4-fpm.service → /lib/systemd/system/php7.4-fpm.service.
Setting up php7.4 (7.4.3-4ubuntu2.15) ...
Processing triggers for systemd (245.4-4ubuntu3.18) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.9) ...
Processing triggers for php7.4-cli (7.4.3-4ubuntu2.15) ...
Processing triggers for php7.4-fpm (7.4.3-4ubuntu2.15) ...
root@server-nginx:/home/ubuntu#
root@server-nginx:/home/ubuntu# sudo systemctl start php7.4-fpm
root@server-nginx:/home/ubuntu# sudo systemctl enable php7.4-fpm
Synchronizing state of php7.4-fpm.service with SysV service script with /lib/systemd/systemd-sysv-install.
Executing: /lib/systemd/systemd-sysv-install enable php7.4-fpm
root@server-nginx:/home/ubuntu#
~~~