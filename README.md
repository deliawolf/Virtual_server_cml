# Virtual_server_cml

simple configuration for server in CML
Username and Password is cisco
```
sudo hostname <hostname>
sudo ifconfig <interface> <ip-address> netmask <ip-netmask>
sudo route add -net 0.0.0.0 gw <ip-gateway>
sudo /etc/init.d/services/dhcp stop
```
