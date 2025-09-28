Task 4 — Setup and Use a Firewall on Windows/Linux
🎯 Objective
  Understand the importance of firewalls in system security.
  Learn how to configure and manage firewall rules effectively.

🛠️ What We Did
  Enabled and used UFW (Uncomplicated Firewall) on Kali Linux.
  Allowed SSH (port 22) traffic.
  Denied Telnet (port 23) traffic.
  Listed active firewall rules with numbering.
  Deleted specific rules when no longer needed.

💻 Commands Used
  sudo ufw enable
  sudo ufw allow 22/tcp
  sudo ufw deny 23/tcp
  sudo ufw status numbered
  sudo ufw delete <rule_number>

✅ What We Achieved
  Controlled access to services using firewall rules.
  Secured the system by allowing only necessary traffic (SSH).
  Blocked insecure services (Telnet) to prevent vulnerabilities.
  Gained practical knowledge of adding, verifying, and removing UFW rules.
