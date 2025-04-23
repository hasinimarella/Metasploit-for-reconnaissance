# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system

## OUTPUT:
![alt text](image.png)

Invoke msfconsole:

## OUTPUT:

![alt text](msfconsole.png)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.

## OUTPUT:

![alt text](help.png)

Port Scanning:
Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000).

![alt text](image-4.png)

use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.
![alt text](image-13.png) 

![alt text](image-5.png)


Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to Metasploit's auxiliary modules and list all the scanner modules.

![alt text](image-6.png)

Search is a powerful command in Metasploit that you can use to find what you want to locate.

![alt text](image-7.png)

search type:auxiliary mysql

![alt text](image-8.png)

![alt text](image-9.png)

![alt text](image-10.png)

![alt text](image-11.png)

## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
