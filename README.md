# Comand 
1. UPDATE

apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

2. Install AutoSSH

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/Iqvan14/auto-esteh/master/setup.sh && chmod +x setup.sh && ./setup.sh
