# Gap Analysis: Väst Vindpark - Baiar Yusuf

| Gap # | Devices | IEC-62443 Control | Description | Risk Rating | What to do (Implementation) | Priority |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | AD, SCADA, RDS | SR 2.1 Authorization | We do not use "Role-Based Access". This makes it easy for an attacker to move around. | 25 | Create roles for Operators and Admins. Only give them the access they need. | 1 |
| 2 | AD, SCADA, RDS | SR 1.1 MFA | We do not use Multi-Factor Authentication. Passwords alone are not safe. | 25 | Make it mandatory to use MFA for all users logging into the system. | 2 |
| 3 | Firewalls, Router | SR 5.1 Segmentation | The IT and OT networks are not separated properly. | 25 | Configure firewalls to block unnecessary traffic between IT and the turbines. | 3 |
| 4 | OT-Firewall | SR 6.1 Logging | We do not save logs in one central place. It is hard to investigate problems. | 25 | Start sending all security logs to a central server so we can check them. | 4 |
| 5 | SCADA, Network | SR 6.2 Monitoring | We are not watching the network traffic for attacks. | 20 | Use a monitoring tool (IDS) to find and alert us about strange traffic. | 5 |