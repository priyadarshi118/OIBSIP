Task 1: Basic Network Scanning with Nmap
#Objective
The objective of this task is to perform a basic network scan using Nmap on a local system using Kali Linux. This scan helps identify open ports and running services on the system.

#Tools Used
Nmap
Kali Linux (VirtualBox)

#Commands Used
Check Nmap installation:

nmap --version

Perform a basic scan on localhost:

nmap localhost

Perform a service version scan on localhost:

nmap -sV localhost

Save the scan output to a file:

nmap -sV localhost > nmap_scan_results.txt
Results

The scan was successfully performed on localhost (127.0.0.1).

The host is up and reachable.

The scan checked the default 1000 TCP ports.

Most of the ports were closed and no unnecessary services were running.

The results were saved in a file named nmap_scan_results.txt for documentation.

#Security Explanation
Network scanning is an important step in security analysis. It helps identify open ports and running services on a system. Closed ports indicate that unnecessary services are not exposed, which reduces the risk of attacks. Regular scanning helps maintain system security and detect potential vulnerabilities.
