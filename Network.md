# Network Forensic Analysis Report

_TODO_ Complete this report as you complete the Network Activity on Day 3 of class.

## Time Thieves 
You must inspect your traffic capture to answer the following questions:

1. What is the domain name of the users' custom site?
   - **frank-n-ted.com**
2. What is the IP address of the Domain Controller (DC) of the AD network?
   - **10.6.12.12**
3. What is the name of the malware downloaded to the 10.6.12.203 machine?
   - Once you have found the file, export it to your Kali machine's desktop.
   - **/files/june11.dll HTTP/1.1**
4. Upload the file to [VirusTotal.com](https://www.virustotal.com/gui/). 
5. What kind of malware is this classified as?
   - **Trojan Malicious Malware**
---

## Vulnerable Windows Machine

1. Find the following information about the infected Windows machine:
    - Host name = **ROTTERDAM-PC**
    - IP address = **172.16.4.205**
    - MAC address = **00:59:07:b0:63:a4**
    
2. What is the username of the Windows user whose computer is infected?
   - `ip.src==172.16.4.205 and kerberos.CNameString`
   - **matthijs.devries**
3. What are the IP addresses used in the actual infection traffic?
   - **185.243.115.84**
      - **green.mattingsolutions.com**
4. As a bonus, retrieve the desktop background of the Windows host.
![](https://github.com/jamesdewhirst/FinalProject/blob/main/Images/empty.gif%253fss%26ss2img.gif)
---

## Illegal Downloads

1. Find the following information about the machine with IP address `10.0.0.201`:
    - MAC address = **00:16:17:18:66:c8**
    - Windows username = **elmer.blanco**
    - OS version = **Mozilla/5.0 (Windows NT 10.0; Win64; x64)**

2. Which torrent file did the user download?
   - **Betty_Boop_Rhythm_on_the_Reservation.avi.torrent**