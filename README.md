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
![image](https://github.com/user-attachments/assets/e7841b0c-3942-4f80-9bfe-581d18c1f6e7)

![image](https://github.com/user-attachments/assets/33e02eb9-4a7d-451f-a0c0-f36d36358c0e)




 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/25b589c5-2fcf-448f-88ec-259dbd646799)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/072ac50f-4220-4aef-835f-dd2fa8e5e768)

![image](https://github.com/user-attachments/assets/e3cc55e4-d7d1-4ffa-a7b1-3d3a99dc34fc)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
