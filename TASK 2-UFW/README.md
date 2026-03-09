UFW Firewall Configuration (Kali Linux)

#Overview
This project demonstrates basic firewall configuration using UFW (Uncomplicated Firewall) in Kali Linux. The firewall is enabled, SSH access is allowed, and HTTP traffic is blocked.

#Commands Used
Enable firewall:
sudo ufw enable

Allow SSH access:
sudo ufw allow ssh

Block HTTP traffic:
sudo ufw deny http

Check firewall status:
sudo ufw status verbose

#Result
Firewall is active and enabled on startup.
SSH (Port 22) is allowed for remote access.
HTTP (Port 80) is blocked for incoming connections.

#Conclusion
UFW successfully controls network access by allowing only required services and blocking unnecessary traffic.
