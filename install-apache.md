~~~
root@server-apache:/home/ubuntu# apt install apache2
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  apache2-bin apache2-data apache2-utils libapr1 libaprutil1 libaprutil1-dbd-sqlite3 libaprutil1-ldap libjansson4 liblua5.2-0 ssl-cert
Suggested packages:
  apache2-doc apache2-suexec-pristine | apache2-suexec-custom www-browser openssl-blacklist
The following NEW packages will be installed:
  apache2 apache2-bin apache2-data apache2-utils libapr1 libaprutil1 libaprutil1-dbd-sqlite3 libaprutil1-ldap libjansson4 liblua5.2-0 ssl-cert
0 upgraded, 11 newly installed, 0 to remove and 0 not upgraded.
Need to get 1741 kB of archives.
After this operation, 7314 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 libapr1 arm64 1.6.5-1ubuntu1 [85.4 kB]
Get:2 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 libaprutil1 arm64 1.6.1-4ubuntu2 [82.4 kB]
Get:3 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 libaprutil1-dbd-sqlite3 arm64 1.6.1-4ubuntu2 [10.4 kB]
Get:4 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 libaprutil1-ldap arm64 1.6.1-4ubuntu2 [8572 B]
Get:5 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 libjansson4 arm64 2.12-1build1 [28.5 kB]
Get:6 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 liblua5.2-0 arm64 5.2.4-1.1build3 [96.0 kB]
Get:7 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 apache2-bin arm64 2.4.41-4ubuntu3.12 [1077 kB]
Get:8 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 apache2-data all 2.4.41-4ubuntu3.12 [159 kB]
Get:9 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 apache2-utils arm64 2.4.41-4ubuntu3.12 [81.7 kB]
Get:10 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates/main arm64 apache2 arm64 2.4.41-4ubuntu3.12 [95.6 kB]
Get:11 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal/main arm64 ssl-cert all 1.0.39 [17.0 kB]
Fetched 1741 kB in 0s (6633 kB/s)
Preconfiguring packages ...
Selecting previously unselected package libapr1:arm64.
(Reading database ... 94352 files and directories currently installed.)
Preparing to unpack .../00-libapr1_1.6.5-1ubuntu1_arm64.deb ...
Unpacking libapr1:arm64 (1.6.5-1ubuntu1) ...
Selecting previously unselected package libaprutil1:arm64.
Preparing to unpack .../01-libaprutil1_1.6.1-4ubuntu2_arm64.deb ...
Unpacking libaprutil1:arm64 (1.6.1-4ubuntu2) ...
Selecting previously unselected package libaprutil1-dbd-sqlite3:arm64.
Preparing to unpack .../02-libaprutil1-dbd-sqlite3_1.6.1-4ubuntu2_arm64.deb ...
Unpacking libaprutil1-dbd-sqlite3:arm64 (1.6.1-4ubuntu2) ...
Selecting previously unselected package libaprutil1-ldap:arm64.
Preparing to unpack .../03-libaprutil1-ldap_1.6.1-4ubuntu2_arm64.deb ...
Unpacking libaprutil1-ldap:arm64 (1.6.1-4ubuntu2) ...
Selecting previously unselected package libjansson4:arm64.
Preparing to unpack .../04-libjansson4_2.12-1build1_arm64.deb ...
Unpacking libjansson4:arm64 (2.12-1build1) ...
Selecting previously unselected package liblua5.2-0:arm64.
Preparing to unpack .../05-liblua5.2-0_5.2.4-1.1build3_arm64.deb ...
Unpacking liblua5.2-0:arm64 (5.2.4-1.1build3) ...
Selecting previously unselected package apache2-bin.
Preparing to unpack .../06-apache2-bin_2.4.41-4ubuntu3.12_arm64.deb ...
Unpacking apache2-bin (2.4.41-4ubuntu3.12) ...
Selecting previously unselected package apache2-data.
Preparing to unpack .../07-apache2-data_2.4.41-4ubuntu3.12_all.deb ...
Unpacking apache2-data (2.4.41-4ubuntu3.12) ...
Selecting previously unselected package apache2-utils.
Preparing to unpack .../08-apache2-utils_2.4.41-4ubuntu3.12_arm64.deb ...
Unpacking apache2-utils (2.4.41-4ubuntu3.12) ...
Selecting previously unselected package apache2.
Preparing to unpack .../09-apache2_2.4.41-4ubuntu3.12_arm64.deb ...
Unpacking apache2 (2.4.41-4ubuntu3.12) ...
Selecting previously unselected package ssl-cert.
Preparing to unpack .../10-ssl-cert_1.0.39_all.deb ...
Unpacking ssl-cert (1.0.39) ...
Setting up libapr1:arm64 (1.6.5-1ubuntu1) ...
Setting up libjansson4:arm64 (2.12-1build1) ...
Setting up ssl-cert (1.0.39) ...
Setting up liblua5.2-0:arm64 (5.2.4-1.1build3) ...
Setting up apache2-data (2.4.41-4ubuntu3.12) ...
Setting up libaprutil1:arm64 (1.6.1-4ubuntu2) ...
Setting up libaprutil1-ldap:arm64 (1.6.1-4ubuntu2) ...
Setting up libaprutil1-dbd-sqlite3:arm64 (1.6.1-4ubuntu2) ...
Setting up apache2-utils (2.4.41-4ubuntu3.12) ...
Setting up apache2-bin (2.4.41-4ubuntu3.12) ...
Setting up apache2 (2.4.41-4ubuntu3.12) ...
Enabling module mpm_event.
Enabling module authz_core.
Enabling module authz_host.
Enabling module authn_core.
Enabling module auth_basic.
Enabling module access_compat.
Enabling module authn_file.
Enabling module authz_user.
Enabling module alias.
Enabling module dir.
Enabling module autoindex.
Enabling module env.
Enabling module mime.
Enabling module negotiation.
Enabling module setenvif.
Enabling module filter.
Enabling module deflate.
Enabling module status.
Enabling module reqtimeout.
Enabling conf charset.
Enabling conf localized-error-pages.
Enabling conf other-vhosts-access-log.
Enabling conf security.
Enabling conf serve-cgi-bin.
Enabling site 000-default.
Created symlink /etc/systemd/system/multi-user.target.wants/apache2.service ??? /lib/systemd/system/apache2.service.
Created symlink /etc/systemd/system/multi-user.target.wants/apache-htcacheclean.service ??? /lib/systemd/system/apache-htcacheclean.service.
Processing triggers for ufw (0.36-6ubuntu1) ...
Processing triggers for systemd (245.4-4ubuntu3.18) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for libc-bin (2.31-0ubuntu9.9) ...
~~~