# OpenVas-Vulnerability-Management

This project will consist of setting up an OpenVas Vulnerability Management Server in the Microsoft Azure environment. An insecure with very outdated software Windows 10 virtual machine will be set up as the target for vulnerability scans.  

## Objectives
The main objective of this project is to learn how to perform an unauthenticated scan, credentialed scan against a vulnerable virtual machine, and learn how to remediate found vulnerabilities.  
The main objective of this project is to perform an unauthenticated scan, credentialed scan against a vulnerable virtual machine, and learn how to remediate found vulnerabilities.  

## Technologies and Software Employed:
- OpenVas
- Windows 10 Pro Virtual Machine
- VNet
- Old Version of Adobe Reader: 10.0_AdbeRdr1000_en_US_1
- Old Version of VLC Player: vlc-1.1.7-win32
- Old Version of FireFox: Firefox Setup 97.0b5
## Performing an Unauthenticated Scan 
![Unauthenticate Scan](https://i.imgur.com/6ho7ibY.jpg)
![Unauthenticate Scan Results](https://i.imgur.com/oJM1Ide.jpg)
![Unauthenticate Scan Ports](https://i.imgur.com/iSXUuhU.jpg)
## Configure to allow Credentialed Scans
Disable Windows Firewall 
![Windows Firewall](https://i.imgur.com/Op7uq0d.jpg)
Enable Remote Registry 
![Windows Firewall](https://i.imgur.com/jNUf6kq.jpg)
Create LocalAccountTokenFilterPolicy in registry
![Windows Firewall](https://i.imgur.com/QWMBYBp.jpg)
## Performing a Credentialed Scan
![Credentialed Scan](https://i.imgur.com/vR5m6eb.jpg)
![Credentialed Scan Results](https://i.imgur.com/oBNmblr.jpg)
## Redmediation
OpenVas provided a very detailed description and recommended solution for each vulnerability.  I remediated some vulnerabilities according to the suggested solutions.  
![Solutions](https://i.imgur.com/fJJlxm1.jpg)
## Verification
I performed another credentialed to verify the vulnerabilities has been resolved after implemented solutions.  There is a downward trend icon indicating that there are less vulnerabilities compared to the first credentialed scan.  
![Verification Scan](https://i.imgur.com/5YR1dk8.jpg)
![Verification Scan](https://i.imgur.com/NBAx3wd.jpg)
## Conclusion
In the lab, I established a secure Azure network featuring the OpenVAS Vulnerability Management Scanner VM. I conducted both unauthenticated and credentialed scans using OpenVAS and effectively addressed the identified vulnerabilities.
