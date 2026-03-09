UFW Firewall Configuration on Kali Linux
Overview

This project demonstrates basic firewall configuration using UFW (Uncomplicated Firewall) on Kali Linux. The firewall is enabled to secure the system by controlling incoming network connections. Specific rules are applied to allow SSH access and block HTTP traffic.

Steps Performed
1. Enable the Firewall

The UFW firewall was activated using the following command:

sudo ufw enable

This enables the firewall and ensures it starts automatically during system startup.

2. Allow SSH Connections

SSH access was allowed so that remote login to the system is possible.

sudo ufw allow ssh

This opens port 22 for incoming SSH connections.

3. Block HTTP Traffic

HTTP traffic was blocked to prevent incoming web requests.

sudo ufw deny http

This blocks port 80 from external connections.

4. Verify Firewall Status

The firewall configuration was verified using:

sudo ufw status verbose

This command displays the firewall status, default policies, and active rules.

Result

Firewall is active and enabled.

SSH (Port 22) is allowed.

HTTP (Port 80) is denied.

Default policy denies incoming connections and allows outgoing traffic.

Conclusion

The firewall was successfully configured using UFW to enhance system security by allowing only necessary services and blocking unwanted network traffic
