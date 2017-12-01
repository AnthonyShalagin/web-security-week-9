# WebsiteSecurity_Week9
CodePath Facebook Website Security Week 9 Assignment

![A screenshot of the Attack Stat on the MHN Server](https://media.giphy.com/media/26u4hGloP8p0CXp7y/giphy.gif)

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
| 195.154.181.191      | 13 |
| 202.96.50.225      | 6      |
| 139.60.161.43 | 3      |
| 5.9.49.72 | 2      |
| 178.159.37.99 | 2      |


| Top 5 Attacker Ports        | Number of Attacks          |
| ------------- |:-------------:|
| 23      | 17 |
| 5060      | 16      |
| 10050 | 6      |
| 1433 | 3      |
| 8080 | 2      |

### Which Honeypot(s) you deployed
Honeypot Dionaea with HTTP

### Any issues you encountered
Ran into issues run Ubuntu Trusty and Gcloud
