# 🔐 Brute Force Attack Simulation Lab

This project demonstrates brute force attack techniques using Kali Linux and Medusa against vulnerable services in a controlled laboratory environment.

The objective is to understand how weak authentication mechanisms can be exploited and how proper security practices can mitigate these attacks.

---

## 🎯 Objectives

- Simulate brute force attacks against FTP services
- Perform password spraying against SMB
- Test web login brute force against DVWA
- Document the commands used and results obtained
- Identify mitigation strategies for each vulnerability

  ## 🧪 Lab Environment

The laboratory was created using two virtual machines running in VirtualBox.

| Machine | Role | Operating System |
|-------|------|------|
| Kali Linux | Attacker | Kali Linux |
| Metasploitable 2 | Target | Vulnerable Linux |

Both machines were connected using a **Host-Only network** to ensure a safe and isolated testing environment.


## 🌐 Network Topology

Attacker Machine  
Kali Linux  
192.168.56.101  

Host-Only Network  

Target Machine  
Metasploitable 2  
192.168.56.102

## 🔎 Service Enumeration

Before performing any attack, it is necessary to identify active hosts and services in the network.

The following command was used to discover devices in the network:
