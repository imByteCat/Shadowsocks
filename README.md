# Shadowsocks Manyuser
_Shadowsocks is a fast tunnel proxy that helps you bypass firewalls._

> This is a backup copy of _[shadowsocks manyuser](https://github.com/shadowsocks/shadowsocks)_(Removed).
> Thanks to _[clowwindy](https://github.com/clowwindy)_.

## Install

### Installing on RPM-based OS
1. Update Packages
```
yum -y update
```

2. Install M2Crypto and pip
```
yum install -y m2crypto python-pip
```

3. Install CyMySQL
```
pip install cymysql
```

4. Clone this repo `shadowsocks-manyuser`
```
git clone https://github.com/imByteCat/shadowsocks-manyuser.git
```

5. Edit the configuration file `Config.py`, for example, I'll use `vim`
```
vim Config.py
```
Then edit the database address, port, user name, password, etc.

6. Run the Shadowsocks Server   
```
python server.py
```

### Installing on Debian-based OS
1. Update Packages
```
apt -y update
```

2. Install `M2Crypto` and `Python Setuptools`
```
apt install -y m2crypto python-pip
```

3. The same as _Installing on RPM-based OS_

**Enjoy!**

> **Note :**  
> You should allow shadowsocks ports ot stop the firewall first.  
> You can use this commond to stop firewall:  
> `service iptables stop`
