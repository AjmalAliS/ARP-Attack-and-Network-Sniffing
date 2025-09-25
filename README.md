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

<img width="704" height="494" alt="491621693-8a7834ad-6ae0-45c3-9303-359d90fd3447" src="https://github.com/user-attachments/assets/807dd5ad-8bac-4c2e-8dc6-9e0b508818cc" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="689" height="270" alt="491621914-806cf959-07bc-4d9f-99c9-c7a621590055" src="https://github.com/user-attachments/assets/e87b45ed-ee6d-45aa-8acb-53c50ad8c111" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="622" height="601" alt="491622142-a0b2644e-cee6-49ea-bbbb-487f9e3ae99d" src="https://github.com/user-attachments/assets/f292e453-2fe2-4328-92b7-d87f3a274ea6" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1918" height="871" alt="491622301-5fed5878-0cb2-4275-9225-2a55bd63017b" src="https://github.com/user-attachments/assets/a4b56ea0-c4a8-4a8d-b065-07add9515951" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
