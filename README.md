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
![image](https://github.com/Yogabharathi3/ARP-Attack-and-Network-Sniffing/assets/118899387/fd3d24e1-24ca-4944-8faf-1fc756b67c3b)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Yogabharathi3/ARP-Attack-and-Network-Sniffing/assets/118899387/7bc4dbc7-cf3c-4dcc-84b0-c520055469e9)

dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/Yogabharathi3/ARP-Attack-and-Network-Sniffing/assets/118899387/cc121c39-1cb2-4cbe-b6d4-3ef4ba6582d6)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Yogabharathi3/ARP-Attack-and-Network-Sniffing/assets/118899387/021b8a34-0292-4af1-afeb-b906b6cf6d27)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Yogabharathi3/ARP-Attack-and-Network-Sniffing/assets/118899387/74c67381-6371-4995-9eca-ec213543eb1e)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
