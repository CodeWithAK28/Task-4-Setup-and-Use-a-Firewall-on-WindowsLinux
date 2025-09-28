Task 4 — Setup and Use a Firewall on Windows/Linux
🎯 Objective

To understand the role of firewalls in system security by setting up and configuring firewall rules.

🛠️ What We Did

Enabled and used UFW (Uncomplicated Firewall) on Kali Linux.

Allowed SSH (port 22) traffic.

Denied Telnet (port 23) traffic.

Listed, verified, and deleted firewall rules as needed.

💻 Commands Used
sudo ufw enable
sudo ufw allow 22/tcp
sudo ufw deny 23/tcp
sudo ufw status numbered
sudo ufw delete <rule_number>

✅ What We Achieved

Controlled access to services using firewall rules.

Secured the system by allowing only necessary traffic (SSH) and blocking insecure services (Telnet).

Learned how to add, verify, and remove UFW rules effectively.
