# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## ALGORITHM:

1) Install kali linux either in partition or virtual box or in live mode

2) Investigate on the various categories of tools as follows:

3) Open terminal and try execute some kali linux commands


## METHODS:

### ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a

#### OUTPUT:

![image](https://github.com/Kirupanandhan/ARP-Attack-and-Network-Sniffing/assets/94386222/e6e56ed3-5bdd-455c-a3b9-5f0ce12ceb52)



### From kali linux issue the command : sudo arpspoof -i eth0 -t <target system> <gateway>

#### OUTPUT:

![image](https://github.com/Kirupanandhan/ARP-Attack-and-Network-Sniffing/assets/94386222/cae92cd1-ddb4-47e9-92fb-2e2ba43563e2)



### dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

![image](https://github.com/Kirupanandhan/ARP-Attack-and-Network-Sniffing/assets/94386222/306ceabb-a2ee-424e-a50e-8201bd2b9659)


### In Kali issue the following commands:  sudo dsnifff

#### OUTPUT:

![image](https://github.com/Kirupanandhan/ARP-Attack-and-Network-Sniffing/assets/94386222/fa77176d-db5d-4e89-91b9-6502e56dd12b)


### Invoke the wireshark and examine the various menus and controls of the tool:

![image](https://github.com/Kirupanandhan/ARP-Attack-and-Network-Sniffing/assets/94386222/2dc317ad-5bd1-4104-8772-6adeb2a90151)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
