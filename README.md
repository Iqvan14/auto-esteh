# Comand 
1. UPDATE
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
2. Install AutoSSH
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://github.com/Iqvan14/auto-esteh/blob/master/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh
