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
![image](https://github.com/gokul-sureshkumar/ARP-Attack-and-Network-Sniffing/assets/121148715/a6eb9b47-967f-4f3c-9cb3-8423148e0bd3)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/gokul-sureshkumar/ARP-Attack-and-Network-Sniffing/assets/121148715/3431bd6c-4f9e-4a91-9cf2-1c1ee2ed4665)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/gokul-sureshkumar/ARP-Attack-and-Network-Sniffing/assets/121148715/2b10cb7d-d806-47a5-99d6-995c5daefbab)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/gokul-sureshkumar/ARP-Attack-and-Network-Sniffing/assets/121148715/58f4789f-41ac-4680-8ff7-ac465da8e644)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/gokul-sureshkumar/ARP-Attack-and-Network-Sniffing/assets/121148715/d94514f3-f4af-44a6-a5e7-936ab9e6c44b)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
