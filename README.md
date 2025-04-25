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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-04-07 052033](https://github.com/user-attachments/assets/114503ba-627b-43f0-9c4f-b2e22db552e6)
From kali linux issue the command : sudo arpspoof -i eth0 -t
## OUTPUT:
![image](https://github.com/user-attachments/assets/b963d825-b39f-4e48-a029-4ba623d56b1b)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/790e707c-bf92-4be2-a14c-3ef40509306a)
In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/45a86887-dd2f-40bb-8055-de72092e6d71)

Invoke the wireshark and examine the various menus and controls of the tool:

## OUTPUT:
![image](https://github.com/user-attachments/assets/4c959f0e-1d8f-4882-81e7-1a9c61040598)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
