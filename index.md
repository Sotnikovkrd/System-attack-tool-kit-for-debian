# System attack tool pack for Debian
```
sudo -S apt-get update && cd /root/Downloads && sudo -S apt-get upgrade && sudo -S apt-get dist-upgrade && sudo -S apt-get install netdiscover && sudo -S apt-get install git && sudo -S apt-get install nmap && cd /opt && sudo -S apt-get install wireshark && sudo -S apt-get install python-pip && sudo -S git clone https://github.com/paterva/maltego-trx && sudo -S pip install maltego-trx && sudo -S gem install wirble sqlite3 bundler && cd /opt && sudo -S git clone https://github.com/rapid7/metasploit-framework.git && cd metasploit-framework && sudo -S bundle install
```
## Tools
* Metasploit
* Maltego
* Netdiscover
* wireshark
* Nmap
## Commands for running tools
1) Metasploit
```
msfconsole
```
2) Maltego
```
maltego
```
3) Netdiscover
```
sudo netdiscover
```
4) Wireshark
```
wireshark
```
