# autossh
# install autossh
## sudo apt-get update
## sudo apt-get install autossh -y
## create service
nano /etc/systemd/system/autossh-tunnel.service
sudo  systemctl enable   autossh-tunnel.service
sudo  systemctl start   autossh-tunnel.service
sudo  systemctl status   autossh-tunnel.service
