
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
![image](https://github.com/user-attachments/assets/517bf65a-630f-451c-b346-7bc8af8658d4)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/ae6f6245-2f71-4f95-add0-77a384e5c73f)
 dsnif:
![image](https://github.com/user-attachments/assets/d70555c5-a256-49dc-b07f-07575d1f2361)
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/0e41bab5-e797-47cd-a3c3-169e946d6fd0)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/a57ce862-413d-45a0-8915-214e33920f48)
Invoke the wireshark and examine the various menus  and controls of the tool:
## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
