# Changing Hostname 

viewing the hostname 

```Bash
hostname 
hostnamectl 
```

Currently was nameOfHost

```Bash
sudo hostnamectl set-hostname desired_name
```

Lastly, edit the /etc/hosts file to reflect the change. For example:
Change this:

```Bash
127.0.0.1 localhost
127.0.1.1 nameOfHost
```

To this:

```Bash
127.0.0.1 localhost
127.0.1.1 desired_name
```


or

```Bash
nano /etc/hostname
```

