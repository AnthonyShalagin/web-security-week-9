# WebsiteSecurity_Week9
CodePath Facebook Website Security Week 9 Assignment
# Project 9 - Honey Pot

Time spent: **10** hours spent in total

> Objective: Setting up a honeypot using Google Cloud Platform and intercept some attempted attacks in the wild.

## Background: 
A **honeypot** is a decoy application, server, or other networked resource that intentionally exposes insecure features which, when exploited by an attacker, will reveal information about the methods, tools, and possibly even the identity of that attacker. Honeypots are commonly used by security researchers to understand the threat landscape facing developers and system administrators, collecting data that might include:

* Information about sources of malicious network traffic such as IP addresses, geographic origin, targeted ports, etc.
* Information used to harden resources against email spammers
* Malware samples
* DB vulnerabilities such as SQLI techniques

### Summary of the Attacks

| Top 5 Attacker IPs        | Number of Attacks          |
| ------------- |:-------------:|
| 134.74.251.204      | 547 |
| 200.85.93.196      | 3      |
| 85.93.20.248 | 3      |
| 129.157.228.96 | 3      |
| 61.27.18.125 | 1      |

| Top 5 Attacker Ports        | Number of Attacks          |
| ------------- |:-------------:|
| 23      | 14 |
| 3389      | 3      |
| 2323 | 3      |
| 1433 | 3      |
| 8000 | 2      |

### Which Honeypot(s) you deployed
Honeypot Dionaea with HTTP

### Any issues you encountered
Ran into issues run Ubuntu Trusty and Gcloud
