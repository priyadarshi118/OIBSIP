Web Vulnerability Scan using Nikto
Project Description

This project demonstrates how to perform a web vulnerability scan using Nikto in Kali Linux. Nikto is an open-source web server scanner that checks websites for vulnerabilities, outdated software, and security misconfigurations.

The target website used for this scan is http://testphp.vulnweb.com
, which is a vulnerable test site used for security practice.

Tools Used

Kali Linux

Nikto

Oracle VirtualBox

Terminal

Commands Used

1. Install Nikto

sudo apt install nikto

2. Run Web Scan

nikto -h http://testphp.vulnweb.com

3. Save Scan Output

nikto -h http://testphp.vulnweb.com -o nikto_scan_results.txt

4. View Saved Results

cat nikto_scan_results.txt
Scan Results

The Nikto scan detected several issues:

Server running nginx/1.19.0

PHP 5.6.40 version detected

X-Frame-Options header missing (possible clickjacking risk)

X-Content-Type-Options header not set

These issues indicate potential security weaknesses in the web server configuration.

Output File

The scan results were saved in:

nikto_scan_results.txt
Conclusion
Nikto helps identify vulnerabilities and misconfigurations in web servers. This scan demonstrates how security tools can be used to detect potential risks and improve web application security
