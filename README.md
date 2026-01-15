# SOC Incident Response Lab – Minor Project 1

This repository is part of the **HackerHub8 Internship Program**.  
The goal of this project is to build a basic understanding of SOC concepts using hands-on Linux practice and proper documentation.

---

# Tools & Environment
- Oracle VirtualBox  
- Kali Linux  


# Project Structure
- **README.md** – Project overview and daily progress  
- **Screenshots/** – Proof of command execution  
- **Timeline/** – Day-wise activity log  
- **Notes/** – Learning notes and observations  


## Day 1 – Environment Setup
On Day 1, I set up the lab environment required for the SOC project.

# Tasks Completed
- Created the GitHub repository  
- Installed Oracle VirtualBox  
- Installed Kali Linux virtual machine  
- Verified that Kali Linux boots and runs successfully  
This environment will be used for all further SOC practice.

## Day 2 – Linux Basics
On Day 2, I practiced basic Linux commands to understand system navigation and information.

### Commands Practiced
- `pwd` – Checked current directory  
- `ls` – Listed files and folders  
- `cd` – Navigated between directories  
- `uname -a` – Viewed system information  
- `whoami` – Checked logged-in user  
- `sudo apt update` – Updated system packages  

## Day 3 – Network & System Commands
On Day 3, I executed basic system and network monitoring commands in Kali Linux.

### Network Commands
- `ip a` – Checked network interfaces and IP address  
- `ip route` – Viewed routing table  
- `ping 8.8.8.8` – Tested internet connectivity  
- `ss -tuln` – Viewed active listening ports  

### System Commands
- `uptime` – Checked system running time  
- `hostname` – Viewed system hostname  
- `df -h` – Checked disk usage  

Screenshots for these commands are uploaded in the **Screenshots** folder as proof of execution.

## Day 4 – Linux Security Fundamentals

On Day 4, I focused on understanding core Linux security concepts that are important for SOC operations.
I practiced managing file permissions to control access, reviewed user and group information, and checked login activity.

I also monitored running processes and system resource usage to understand how SOC analysts identify abnormal behavior.
Additionally, I explored system and authentication log files to gain basic awareness of how system activities are recorded.
Screenshots of all command executions are uploaded in the **Screenshots** folder as proof of work.

## Day 5 – Authentication Logs, Login Activity & Incident Awareness

On Day 5, I analyzed Linux authentication and system logs to understand how user login activities
and security-related events are recorded. I examined authentication logs to identify successful
and failed login attempts and reviewed login history and active user sessions.

I also explored system logs to observe how errors and warnings are logged.
Based on these observations, I documented a simple incident scenario involving multiple failed
login attempts and understood how early detection helps SOC analysts respond to potential threats.



