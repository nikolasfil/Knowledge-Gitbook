# DNS problem with Virtual Machines on eduroam


Virtual Machines with VirtualBox have a dns problem while connected on eduroam networks

Originally the VMs get dns service from the host, the laptop(192.168.1.1)

So we just edit the config file and add another dns server for the machine to access


```Bash
sudo subl /etc/resolv.conf 
```
add

```Bash
nameserver 8.8.8.8
```
