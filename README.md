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

![322689343-cd78f9a1-4e19-4686-984a-2cf9c22e3a28](https://github.com/sreekarsh/ARP-Attack-and-Network-Sniffing/assets/139841918/7e210464-cd96-4e4f-98a6-53773c37e3ff)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![img 2](https://github.com/sreekarsh/ARP-Attack-and-Network-Sniffing/assets/139841918/4eaae069-8c29-4da9-91aa-ebb03f9058ef)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![img 3](https://github.com/sreekarsh/ARP-Attack-and-Network-Sniffing/assets/139841918/6fdaf8b1-ee7d-4059-bbe4-871cdce2b1e7)



# In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![img 4](https://github.com/sreekarsh/ARP-Attack-and-Network-Sniffing/assets/139841918/666d469d-88d9-438d-8360-9fe7c00e7df6)



Invoke the wireshark and examine the various menus  and controls of the tool:


![img 5](https://github.com/sreekarsh/ARP-Attack-and-Network-Sniffing/assets/139841918/6c730c68-352c-45e0-96c0-7993708d2577)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
