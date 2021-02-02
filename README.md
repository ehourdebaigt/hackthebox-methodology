# Hack the Box Methodology

## Table of Contents
* [Initial Recon](#initial-recon)
* [Lateral Movement](#lateral-movement)
* [Privilege Escalation](#privilege-escalation)
* [Tips & Tricks](#tips-&-tricks)
* [Rabbit holes](#rabbit-holes)
* [Resources](#resources)


## Initial Recon
* Scan the ports with nmap
* Use either telnet or netcat to grab the banners of ports
* Enumerate files and folders (if there is a web server)
* Read through the source code of the web pages 
* Enumerate subdomains (make sure to add a domain name to /etc/host on your machine)
* Use Wappalyzer to recon technologies the webite uses
* Use the proper tools to connect to open ports on the box
* Take note of every version number you come across and look up on Internet if there are exploits for these versions
* Take note of usernames, email addresses and names
* Access file sharing systems (SMB, FTP, RSYNC, ...)
* Attempt to exploit most relevant web vulnerabilites depending on the web server (SQL injection, cross-site scripting, local file inclusion, ...)
