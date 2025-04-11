# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

### Name : Prathyusha
### Reg.No: 212223240187

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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/0b917ba5-731a-4700-874f-4b1f432640ff)


![image](https://github.com/user-attachments/assets/59661c8f-c14f-4a86-b43a-a7cd900f0fb3)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/660eecb8-3e39-4c61-82c7-6e8a06355985)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/88e796b9-4eeb-4ebf-97e7-6f97e16c0529)


![image](https://github.com/user-attachments/assets/601bc983-0580-4701-86f0-cc4dcd12f659)




Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
