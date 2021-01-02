Linux Essentials 

**Sudo** : Super User Do

- elevates privileges

**Sudoers**

- /etc/sudoers file controls who chan run commands
- list of users or users groups with permission to execute a subset of commands

**Navigating the File System**
**pwd** : present working directory
**cd** : change directory
**ls** : list contents
**cd ..** : reverse directory
**~/file/** : locate file without having to input the relative path
**mkdir** : make directory
**rmdir** : remove dir
**ls -la** : list hidden folders
**echo "Hi" > test.txt** : write "Hi" in test.txt file
**cat** : capture text in file
**cp** : copy file
**cp file.txt Downloads/** : copy file.txt to downloads folder
**rm Downloads/file.txt** : remove file.txt from downloads folder
**mv file.txt Downloads/** : move file to folder 
**locate** :  find file
**updatedb** : update database 
**passwd**: change password for account
**man + command** : gives you information on command

**grep** : looks for specific term

**User Permission**
3 sections
a.bbb.ccc.ddd
a = - -> file
a = d -> directory
b - file owner
c - group ownership
d - common user
temp folder ususally has full read/write privileges

**Change Access**

- chmod : change mode
- chmod + rwx
- chmod + 777 => full read/write/execute privileges
- example : chmod 777 hello.txt

**Users**
adduser + username

passwd + username

/etc/passwd : file with users

passwords are in the shadow file

/etc/shadow : file with hashed passwords

**Network Commands**

ipconfig / ifconfig
\- display network information about local machine
\- will be deprecated

ip a
\- display network information about local machine

ip n
\- arp table

ip r
\- routing table

iwconfig
\- display network interface parameters

ping

\- detect devices on a network 
\- good for troubleshooting network issues

arp

\- address resolution protocol
\- displays address resolution cache
\- IP address it talks to 
\- associated MAC address
\- associates MAC addresses with IP addresses

netstat
\- lists tcp and udp connections and ports

route
\- prints routing table
\- displays where traffic exits

nmap

\- report for open ports