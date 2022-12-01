~~~
root@server-nginx:/home/ubuntu# apt install nri-nginx
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following NEW packages will be installed:
  nri-nginx
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 2045 kB of archives.
After this operation, 4874 kB of additional disk space will be used.
Get:1 https://download.newrelic.com/infrastructure_agent/linux/apt focal/main arm64 nri-nginx arm64 3.2.5 [2045 kB]
Fetched 2045 kB in 0s (4207 kB/s)
Selecting previously unselected package nri-nginx.
(Reading database ... 125978 files and directories currently installed.)
Preparing to unpack .../nri-nginx_3.2.5_arm64.deb ...
Unpacking nri-nginx (3.2.5) ...
Setting up nri-nginx (3.2.5) ...
root@server-nginx:/home/ubuntu# cd /etc/newrelic-infra/integrations.d
root@server-nginx:/etc/newrelic-infra/integrations.d# sudo cp nginx-config.yml.sample nginx-config.yml
root@server-nginx:/etc/newrelic-infra/integrations.d# nano nginx-config.yml
root@server-nginx:/etc/newrelic-infra/integrations.d# systemctl restart newrelic-infra
root@server-nginx:/etc/newrelic-infra/integrations.d#
~~~