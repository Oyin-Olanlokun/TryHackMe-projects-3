# TryHackMe-projects-3
Hack into a target Linux system
Date: Sepptember 2024

Objective: Get root access on the target system of IP address 10.10.91.223

Tools used: Nmap

Step by step process: 
- Used Nmap to scan the IP of the target
- Discovered 3 services running - FTP, SSH, and HTTP (add screenshot)
- Connected to the target FTP with ftp 10.10.91.223
- Logged in using anonymous successfully
- Used the command ls to access the list of the filenames available along with thier details (add screenshot)
- Discovered 6 files - 3 txt files, 2 epub files, and 1 sh file
- Discovered the password/content of the file using cat secret.txt (add screenshot)
- Completed control over the target server
- Discovered the content of the flag.txt

Results:
- Gained accessto all the users' files
- Learned that Nmap reports on whether the host is up based on whether it receives any response from it
- Learned that the root account hass full priivileges on a Linux system, meaning that it can read and write any file and install and remove any program
  


