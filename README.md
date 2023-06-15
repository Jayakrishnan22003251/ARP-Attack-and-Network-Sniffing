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

![1 (2)](https://github.com/praveenst13/ARP-Attack-and-Network-Sniffing/assets/118787793/6d5faf03-5344-44ab-ac2c-fd763111f491)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![2 (2)](https://github.com/praveenst13/ARP-Attack-and-Network-Sniffing/assets/118787793/a70b28b6-7f35-43b5-92d7-840f43f1bf82)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![3 (2)](https://github.com/praveenst13/ARP-Attack-and-Network-Sniffing/assets/118787793/e985ae01-13fa-42f1-8155-94b04deddecb)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![4 (2)](https://github.com/praveenst13/ARP-Attack-and-Network-Sniffing/assets/118787793/b683d8ad-117e-44c7-b03c-bdd0b0f7e4c0)


Invoke the wireshark and examine the various menus  and controls of the tool:

![5 (2)](https://github.com/praveenst13/ARP-Attack-and-Network-Sniffing/assets/118787793/e9461986-63fa-4577-8c66-ccb63a3c56bf)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
