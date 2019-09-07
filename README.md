# Shadowsocks Manyuser
_Shadowsocks is a fast tunnel proxy that helps you bypass firewalls._

> This is a backup copy of _[shadowsocks manyuser](https://github.com/shadowsocks/shadowsocks)_ (Removed) .   
> Thanks to _[clowwindy](https://github.com/clowwindy)_ .

## Install

### Installing on RPM-based OS
1. Update Packages   
`yum -y update`

2. Install `M2Crypto` and `Python Setuptools`    
`yum install -y m2crypto python-setuptools`

3. Install `pip`   
`easy_install pip`

4. Install `CyMySQL`   
`pip install cymysql`

5. Clone `Shadowsocks-manyuser` with HTTPS
`git clone https://github.com/imByteCat/Shadowsocks-manyuser.git`   
**_Note: You should install `git` first !_   
`yum -y install git`**

6. Change the directory to `Shadowsocks-manyuser`   
For example : `cd /root/Shadowsocks-manyuser`

7. Edit the configuration file `Config.py`   
`vi Config.py`   
Then edit the database address, port, user name, password, etc.

8. Run the Shadowsocks Server   
`python server.py`

### Installing on Debian-based OS
1. Update Packages   
`apt-get -y update`

2. Install `M2Crypto` and `Python Setuptools`    
`apt-get install -y m2crypto python-setuptools`

3. The same as _Installing on RPM-based OS_

**Enjoy!**

> **Note :**   
> You should **STOP the firewall first** !   
> You can use this commond or others what you like :   
> `service iptables stop`
