~~~
ubuntu@server-nginx:~$ sudo su
root@server-nginx:/home/ubuntu# curl -Ls https://download.newrelic.com/install/newrelic-cli/scripts/install.sh | bash && sudo NEW_RELIC_API_KEY=NRAK-TX5IIFY0PZ31G10SZNZPO61LVWW NEW_RELIC_ACCOUNT_ID=3643161 NEW_RELIC_REGION=EU /usr/local/bin/newrelic install
Starting installation.
Installing New Relic CLI v0.60.2
Installing to /usr/local/bin

 _   _                 ____      _ _
| \ | | _____      __ |  _ \ ___| (_) ___
|  \| |/ _ \ \ /\ / / | |_) / _ | | |/ __|
| |\  |  __/\ V  V /  |  _ |  __| | | (__
|_| \_|\___| \_/\_/   |_| \_\___|_|_|\___|

Welcome to New Relic. Let's set up full stack observability for your environment.

✔ Connecting to New Relic Platform
   Connected


Installing New Relic

==> Installing Infrastructure Agent
Hit:1 http://ports.ubuntu.com/ubuntu-ports focal-security InRelease
Hit:2 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal InRelease
Hit:3 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates InRelease
Hit:4 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-backports InRelease
Reading package lists...
Warning: apt-key output should not be parsed (stdout is not a terminal)
OK
Hit:1 http://ports.ubuntu.com/ubuntu-ports focal-security InRelease
Hit:2 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal InRelease
Hit:3 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-updates InRelease
Get:4 https://download.newrelic.com/infrastructure_agent/linux/apt focal InRelease [10.8 kB]
Hit:5 http://eu-marseille-1-ad-1.clouds.ports.ubuntu.com/ubuntu-ports focal-backports InRelease
Get:6 https://download.newrelic.com/infrastructure_agent/linux/apt focal/main arm64 Packages [36.8 kB]
Fetched 47.6 kB in 0s (98.0 kB/s)
Reading package lists...
Selecting previously unselected package libpq5:arm64.
(Reading database ... 125924 files and directories currently installed.)
Preparing to unpack .../libpq5_12.12-0ubuntu0.20.04.1_arm64.deb ...
Unpacking libpq5:arm64 (12.12-0ubuntu0.20.04.1) ...
Selecting previously unselected package td-agent-bit.
Preparing to unpack .../td-agent-bit_1.9.3_arm64.deb ...
Unpacking td-agent-bit (1.9.3) ...
Selecting previously unselected package newrelic-infra.
Preparing to unpack .../newrelic-infra_1.33.2_arm64.deb ...
Unpacking newrelic-infra (1.33.2) ...
Setting up libpq5:arm64 (12.12-0ubuntu0.20.04.1) ...
Setting up newrelic-infra (1.33.2) ...
Created symlink /etc/systemd/system/multi-user.target.wants/newrelic-infra.service → /etc/systemd/system/newrelic-infra.service.
Setting up td-agent-bit (1.9.3) ...
Processing triggers for libc-bin (2.31-0ubuntu9.9) ...
Running agent status check attempt...
Agent status check ok.
✔ Installing Infrastructure Agent
   Installed

==> Installing Logs Integration
✔ Installing Logs Integration
   Installed

  New Relic installation complete

  --------------------
  Installation Summary

  ✔  Infrastructure Agent  (installed)
  ✔  Logs Integration  (installed)

  View your data at the link below:
  ⮕  https://onenr.io/0qQa3G0l0R1

  View your logs at the link below:
  ⮕  https://onenr.io/0EjOg3ydpj6

  --------------------
root@server-nginx:/home/ubuntu#
~~~