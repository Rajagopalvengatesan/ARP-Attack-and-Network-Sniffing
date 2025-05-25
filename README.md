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
![VirtualBox_windows_7_12_10_2023_08_40_45](https://github.com/Raja8334/ARP-Attack-and-Network-Sniffing/assets/120719634/c0305ec6-cb74-458b-b1eb-9d216b843ed2)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Raja8334/ARP-Attack-and-Network-Sniffing/assets/120719634/10bc7697-aca5-427f-a57c-d8cef0a1148f)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Raja8334/ARP-Attack-and-Network-Sniffing/assets/120719634/0eda4258-8810-437d-92ba-5a7601e13855)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Raja8334/ARP-Attack-and-Network-Sniffing/assets/120719634/a475a02e-f62a-45fa-bffe-73330241e67f)



Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Raja8334/ARP-Attack-and-Network-Sniffing/assets/120719634/589e5cb2-a8e2-4e2a-8bbe-ec5e61b6f82d)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
