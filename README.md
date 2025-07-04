                                [ROUTER]
                              /           \
                             /             \
                            /               \
                      [Kali Server]       [Ubuntu Server]
                      (IP: 10.0.2.15)     (IP: 10.0.2.15)
                      -----------------------------------
                                  Nmap Scan
Ubuntu vs Kali Attack Simulation on VirtualBox (Please check screenshots for representation)

\\ Project Overview
This project simulates a network attack scenario between an Ubuntu (victim) and Kali Linux (attacker) machine in a controlled VirtualBox environment. The simulation demonstrates common penetration testing techniques, defensive configurations, and network security principles. This hands-on exercise is valuable for cybersecurity learning as it:
- Shows real-world attack vectors in a safe environment
- Demonstrates both offensive and defensive strategies
- Provides practical experience with security tools
- Highlights the importance of proper system hardening

Setup Instructions

//Virtual Environment
- **VirtualBox Version**: 7.0.12
- **Host System**: Windows 10


### Virtual Machines
| Specification       | Kali Linux               | Ubuntu                   |
|---------------------|--------------------------|--------------------------|
| OS Version          | Kali Linux 2023.4        | Ubuntu 22.04 LTS         |
| RAM Allocation      | 4GB                     | 2GB                      |
| Storage             | 25GB dynamic allocation | 20GB dynamic allocation |
| Network Adapter     | Bridged Adapter          | Bridged Adapter          |

Simulation Steps

1. Virtual Machine Setup
- Downloaded and verified ISO images from official sources
- Created VMs with recommended specifications
- Installed VirtualBox Guest Additions for better integration
- Configured snapshots for easy recovery

 2. Network Configuration
- Configured machines
- Verified connectivity using `ping` and `arp-scan`

 3. Attack Methodologies
**Performed attacks including:**
- Network reconnaissance with `nmap`
- Vulnerability scanning with `nikto` or `openvas`
- Password cracking with `hydra` or `john`

 4. Defensive Measures Implemented
On the Ubuntu machine:
- Configured firewall rules with `ufw`
- Implemented fail2ban for SSH protection
- Hardened SSH configuration
- Set up intrusion detection with `aide`

 5. Results Observed
- Successfully compromised ubuntu using tools from Kali
- Detected attack 
- Learned about attack patterns 

//Key Learnings
This project helped me develop:
- Practical penetration testing skills
- Network configuration and troubleshooting
- System hardening techniques
- Security tool proficiency (nmap, metasploit, etc.)
- Understanding of attack vectors and defenses
- Incident response fundamentals

//Future Enhancements
Potential improvements for this project:
- Implement a more complex network topology with routers/firewalls
- Add Windows machines to simulate heterogeneous environments
- Incorporate SIEM solutions for centralized logging
- Develop automated attack/defense scripts
- Add vulnerability patching simulations
- Include red team/blue team exercises

  
