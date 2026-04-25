\# Nmap Security Scanning Project


\# Team details- Anshuman Kanade 16010123050 



\## Objective

The objective of this project is to perform network scanning and basic vulnerability assessment using Nmap. The project focuses on identifying open ports, detecting running services, analyzing system characteristics, and understanding potential security risks.



---



\## Tool Used

\- Nmap (Network Mapper)



---



\## About Nmap

Nmap is a widely used open-source tool for network discovery and security auditing. It allows users to identify open ports, detect services and their versions, attempt operating system detection, and perform vulnerability analysis using scripts.



---



\## Target Used

All scans were performed on:

\- scanme.nmap.org (official Nmap test server)



This ensures safe and ethical usage of scanning techniques.



---



\## Commands Used



\### Basic Scan

nmap scanme.nmap.org



Performs a default scan to identify open ports on the target system.



---



\### Service Version Detection

nmap -sV scanme.nmap.org



Detects services running on open ports along with their version information.



---



\### Aggressive Scan

nmap -A scanme.nmap.org



Performs an advanced scan that includes:

\- Service detection  

\- Operating system detection  

\- Script scanning  

\- Traceroute  



---



\### Port Range Scan

nmap -p 1-1000 scanme.nmap.org



Scans the first 1000 ports to identify additional open ports beyond the default scan.



---



\### Vulnerability Scan

nmap --script vuln scanme.nmap.org



Uses the Nmap Scripting Engine (NSE) to check for known vulnerabilities.



---



\## Types of Scans Performed



\- TCP Connect Scan  

\- Service Version Detection (-sV)  

\- Aggressive Scan (-A)  

\- Port Range Scan (-p 1-1000)  

\- Vulnerability Scan using NSE (--script vuln)  



---



\## Procedure



1\. Installed Nmap on the system.  

2\. Opened Command Prompt and navigated to the project folder.  

3\. Executed multiple scan commands from basic to advanced levels.  

4\. Saved outputs using Nmap output options.  

5\. Captured screenshots of scan results.  

6\. Organized files and uploaded them to a GitHub repository.  



---



\## Results and Observations



\- Identified open ports such as:

&nbsp; - Port 22 (SSH)  

&nbsp; - Port 80 (HTTP)  



\- Service detection revealed information about running applications.



\- Aggressive scan provided deeper insights including OS detection attempts.



\- Port range scanning expanded the scope to additional ports.



\- Vulnerability scanning attempted to detect known weaknesses using scripts.



---



\## Output Files



\- scan\_output.txt – Service detection scan results  

\- detailed\_scan.txt – Port range scan results  

\- aggressive\_scan.txt – Aggressive scan output  

\- vuln\_output.txt – Vulnerability scan output  


---



\## Screenshots Folder



\- cmd1.png - basic scan  

\- cmd2.png - service version detection

\- cmd3.1.png & cmd3.2.png - agressive scan

\- cmd4.png - port scan

\- cmd5.1.png & cmd5.2.png – Vulnerability scan


---



\## Automation Script



A batch script (scan.bat) is included to automate the scanning process. It runs multiple Nmap commands sequentially and saves the outputs into respective files.



---



\## Conclusion



This project demonstrates how Nmap can be used as a powerful tool for network scanning and basic security analysis. By performing different types of scans, valuable information about a system can be gathered, including open ports, running services, and potential vulnerabilities. This helps in understanding and improving system security.



---



\## Future Scope



\- Perform scans on local networks  

\- Explore advanced Nmap scripting  

\- Automate repeated scans  

\- Conduct deeper vulnerability analysis  



---

