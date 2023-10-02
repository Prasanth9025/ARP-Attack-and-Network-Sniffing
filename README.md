# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/Prasanth9025/ARP-Attack-and-Network-Sniffing/assets/118343686/56b8e3b0-1494-4e6a-85a7-39e77f755a3a)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Prasanth9025/ARP-Attack-and-Network-Sniffing/assets/118343686/0c26420a-cca8-4c9a-9a93-ec622a478102)

dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Prasanth9025/ARP-Attack-and-Network-Sniffing/assets/118343686/2f441822-c440-47d7-ae94-459ab03a42d8)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Prasanth9025/ARP-Attack-and-Network-Sniffing/assets/118343686/bfa2fe33-35a5-4e22-b08e-c627ea01d1e2)
Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Prasanth9025/ARP-Attack-and-Network-Sniffing/assets/118343686/4401464a-7e78-4b3b-9452-760dd97465d9)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
