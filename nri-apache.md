~~~
root@server-apache:/home/ubuntu# apt install nri-apache
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following NEW packages will be installed:
  nri-apache
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 2059 kB of archives.
After this operation, 4939 kB of additional disk space will be used.
Get:1 https://download.newrelic.com/infrastructure_agent/linux/apt focal/main arm64 nri-apache arm64 1.9.1 [2059 kB]
Fetched 2059 kB in 0s (6470 kB/s)
Selecting previously unselected package nri-apache.
(Reading database ... 131492 files and directories currently installed.)
Preparing to unpack .../nri-apache_1.9.1_arm64.deb ...
Unpacking nri-apache (1.9.1) ...
Setting up nri-apache (1.9.1) ...
root@server-apache:/home/ubuntu# cd /etc/newrelic-infra/integrations.d
root@server-apache:/etc/newrelic-infra/integrations.d# ls
apache-config.yml.sample  docker-config.yml
root@server-apache:/etc/newrelic-infra/integrations.d# sudo cp apache-config.yml.sample apache-config.yml
root@server-apache:/etc/newrelic-infra/integrations.d# nano apache-config.yml
root@server-apache:/etc/newrelic-infra/integrations.d# systemctl restart newrelic-infra
root@server-apache:/etc/newrelic-infra/integrations.d# systemctl status  newrelic-infra
● newrelic-infra.service - New Relic Infrastructure Agent
     Loaded: loaded (/etc/systemd/system/newrelic-infra.service; enabled; vendor preset: enabled)
     Active: active (running) since Mon 2022-11-21 18:32:57 UTC; 11s ago
   Main PID: 452869 (newrelic-infra-)
      Tasks: 28 (limit: 4604)
     Memory: 26.9M (limit: 1.0G)
     CGroup: /system.slice/newrelic-infra.service
             ├─452869 /usr/bin/newrelic-infra-service
             ├─452875 /usr/bin/newrelic-infra
             └─452926 /opt/td-agent-bit/bin/td-agent-bit -c /tmp/nr_fb_config4105640284 -e /var/db/newrelic-infra/newrelic-integrations/logging/out_newrelic.so -R /var/db/newrelic-infra/newrelic-integrations/logging>

Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=system/network_interfaces
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=kernel/sysctl
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=kernel/modules
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=services/pidfile
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=config/sshd
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=packages/dpkg
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Agent plugin" plugin=config/selinux
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Integration health check finished with success" component=integrations.runner.Runner env=production integrati>
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="connect got id" agent-guid=MzY0MzE2MXxJTkZSQXxOQXwzNjEzMDM2MTYyNjA2ODg4MTI3 agent-id=3613036162606888127 comp>
Nov 21 18:32:59 server-apache newrelic-infra-service[452875]: time="2022-11-21T18:32:59Z" level=info msg="Integration health check finished with success" component=integrations.runner.Runner env=production integrati>
lines 1-21/21 (END)
^C
root@server-apache:/etc/newrelic-infra/integrations.d#
et
~~~