# cloud-cyber-lab-aws-red-blue-team
This project is a cloud-native cybersecurity homelab deployed in AWS

# ☁️ Cloud Red/Blue Team Cybersecurity Homelab

This project is designed to simulate real-world Red and Blue Team workflows. I built this to deepen my hands-on experience with threat detection, log correlation, incident response, and infrastructure automation.

## Overview

- Cloud-hosted in AWS (us-east-2 region)
- Infrastructure-as-Code with Terraform
- Simulates Red Team attacks and Blue Team defenses
- Includes:
  - Kali Linux attacker instance
  - Vulnerable Windows Server (victim)
  - Splunk SIEM (log collection & search)
  - Nessus Essentials (vuln scanning)
  - Secure VPC + Subnets + Security Groups

## Tools & Services

| Offensive (Red): Kali Linux, Metasploit, Hydra |
| Defensive (Blue): Splunk, Nessus, Windows Event Logs |
| Infra | AWS EC2, VPC, EBS, CloudWatch |
| Automation | Terraform |

## What I Practiced

- Writing secure Terraform configs
- Configuring Splunk & log forwarding
- Simulating attacks and analyzing alerts
- Managing EC2 access via SSH/XRDP
- Hardening Windows and Linux environments

## Diagrams

![image alt](https://github.com/marsxarts/cloud-cyber-lab-aws-red-blue-team/blob/main/AWS%20cyber%20homelab%20diagram.png?raw=true)

## Documentation



## What I learned 


- End-to-end infrastructure design using IaaC
- Threat simulation techniques (brute-force, log injection)
- Security event correlation and alerting with Splunk
- Log forwarding from Windows to a centralized SIEM

## Resources 
https://medium.com/@kelvinslate50/blue-team-monitoring-homelab-aws-3434f4986959




