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
![image](https://github.com/LakshmanAdhireddy/ARP-Attack-and-Network-Sniffing/assets/118707265/f4a96972-71f8-476e-8571-cb60f505e57b)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/LakshmanAdhireddy/ARP-Attack-and-Network-Sniffing/assets/118707265/b186f92b-4057-4ae3-995b-e8a7d88ff515)

 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
 
## OUTPUT:
![image](https://github.com/LakshmanAdhireddy/ARP-Attack-and-Network-Sniffing/assets/118707265/cff485d0-ed0b-40c0-b627-b7d8f9626a4b)


In Kali issue the following commands:
sudo dsnifff

## OUTPUT:
![image](https://github.com/LakshmanAdhireddy/ARP-Attack-and-Network-Sniffing/assets/118707265/07aed121-5439-4014-8285-82fe22cc6192)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/LakshmanAdhireddy/ARP-Attack-and-Network-Sniffing/assets/118707265/9baab712-04ab-4071-8a21-e96b7d899f1d)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
