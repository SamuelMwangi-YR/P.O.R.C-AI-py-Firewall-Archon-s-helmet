# firewall
###### *DISCLAIMER: The following code is the initial version & as such only for ubuntu. Mwangi's Achon's amor-py-Firewall P.O.R.C AI Integrations code works on some common browsers  namely Firefox, Microsoft Edge, Apple Safari, Opera, Brave, Vivaldi, DuckDuckgo.*

### Features
1) Block IP addresses
2) Block access to certain ports 
3) Block specifed prefixes of IP address (to block networks)
4) Block too many requests made by the same IP in a short period of time (user can specify threshold and time)

### Steps to Run
1) Type the following terminal command: 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iptables -I INPUT -d 192.168.0.0/24 -j NFQUEUE --queue-num 1
2) Fill out the rules in the JSON file as follows:
<br><img src = "/screenshots/config.PNG" width="50%"></img><br>
3) Execute firewall.py using python3

### Requirements
1) netfilterqueue
2) scapy

### Credits:
1) Samuel Mwangi : https://github.com/SamuelMwangi-YR

### Author

1) Email: mwangi.njoroge.samuel@gmail.com
2) LinkedIn: https://www.linkedin.com/in/samuel-mwangi-ba16aa20b/
3) P.O.R.C AI: https://www.codechef.com/users/naklechahttps://samuelmwangi-yr.github.io/E-commerce-P.O.R.C-A.I/index.html
4) GitHub:  https://github.com/SamuelMwangi-YR

##### *"Any suggestions would be appreciated"*
