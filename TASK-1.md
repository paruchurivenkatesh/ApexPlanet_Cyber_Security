# Task 1 – Foundations of Cybersecurity

**Internship:** Cybersecurity & Ethical Hacking Internship  
**Organization:** ApexPlanet Software Pvt. Ltd.  
**Task 1:** Foundations of Cybersecurity

---

# Objective

Build a strong foundation in cybersecurity by learning networking, Linux, cryptography, and security tools while setting up a professional ethical hacking lab.

---

# Lab Environment

## Attacker Machine

| Machine | OS | IP Address |
|----------|----|------------|
| Kali Linux | Kali Linux | 192.168.56.101 |

## Target Machine

| Machine | OS | IP Address |
|----------|----|------------|
| Metasploitable2 | Ubuntu Linux | 192.168.56.103 |

Network Type:

Host-Only Adapter

---

# Connectivity Test

Ping from Kali Linux

```bash
ping 192.168.56.103
```

Expected Output

```
64 bytes from 192.168.56.103
icmp_seq=1 ttl=64 time=0.5 ms
```

Ping from Metasploitable2

```bash
ping 192.168.56.101
```

---

# Cybersecurity Basics

## CIA Triad

### Confidentiality

Ensures information is only accessible by authorized users.

Examples

- Encryption
- Passwords
- Access Control

---

### Integrity

Ensures data remains accurate and unmodified.

Examples

- SHA256
- Digital Signatures
- Checksums

---

### Availability

Ensures systems remain available to legitimate users.

Examples

- Backups
- Redundant Servers
- Disaster Recovery

---

# Common Cyber Threats

## Phishing

Fake emails or websites designed to steal credentials.

## Malware

Malicious software including viruses, worms, spyware, and trojans.

## DDoS

Distributed Denial of Service attack that floods a server with traffic.

## SQL Injection

Injection of malicious SQL commands into web applications.

## Brute Force Attack

Repeated password guessing attempts.

## Ransomware

Encrypts victim files and demands payment.

---

# Attack Vectors

- Social Engineering
- Insider Threats
- Wireless Attacks
- Weak Passwords
- Vulnerable Applications
- Misconfigured Systems

---

# Linux Fundamentals

## File Navigation

Current Directory

```bash
pwd
```

List Files

```bash
ls
```

Change Directory

```bash
cd
```

Create Folder

```bash
mkdir cybersecurity
```

Create File

```bash
touch notes.txt
```

Copy File

```bash
cp file1.txt file2.txt
```

Move File

```bash
mv file1.txt Documents/
```

Delete File

```bash
rm file.txt
```

Delete Folder

```bash
rm -r folder
```

---

# File Permissions

View Permissions

```bash
ls -l
```

Change Permissions

```bash
chmod 755 file.sh
```

Change Owner

```bash
sudo chown kali:kali file.txt
```

---

# Package Management

Update Packages

```bash
sudo apt update
```

Upgrade Packages

```bash
sudo apt upgrade
```

Install Package

```bash
sudo apt install nmap
```

Remove Package

```bash
sudo apt remove nmap
```

---

# Networking Commands

Check IP Address

```bash
ifconfig
```

or

```bash
ip addr
```

Ping Host

```bash
ping 192.168.56.103
```

View Network Connections

```bash
netstat -tulnp
```

Traceroute

```bash
traceroute google.com
```

DNS Lookup

```bash
nslookup google.com
```

---

# Networking Basics

## OSI Model

1. Physical
2. Data Link
3. Network
4. Transport
5. Session
6. Presentation
7. Application

---

## TCP/IP Model

Application

Transport

Internet

Network Access

---

## Common Protocols

HTTP

Port 80

HTTPS

Port 443

DNS

Port 53

FTP

Port 21

SSH

Port 22

SMTP

Port 25

---

# IP Addressing

Kali Linux

192.168.56.101

Metasploitable2

192.168.56.103

Subnet Mask

255.255.255.0

Network

192.168.56.0/24

---

# NAT

Network Address Translation allows private IP addresses to communicate with external networks through a public IP.

---

# Cryptography Basics

## Symmetric Encryption

One key is used for encryption and decryption.

Example

AES

---

## Asymmetric Encryption

Uses a public key and a private key.

Examples

RSA

ECC

---

## Hashing

MD5

```bash
echo "Cybersecurity" | md5sum
```

SHA256

```bash
echo "Cybersecurity" | sha256sum
```

---

# OpenSSL Demo

Encrypt

```bash
openssl enc -aes-256-cbc -salt -in message.txt -out encrypted.enc
```

Decrypt

```bash
openssl enc -aes-256-cbc -d -in encrypted.enc -out decrypted.txt
```

---

# Security Tools

## Wireshark

Purpose

Packet Capture

Example

Capture ICMP traffic during ping.

---

## Nmap

Purpose

Network Scanner

Example

```bash
nmap 192.168.56.103
```

---

## Burp Suite

Purpose

Intercept and analyze HTTP requests.

---

## Netcat

Purpose

Network Debugging

Listener

```bash
nc -lvnp 4444
```

Connect

```bash
nc 192.168.56.103 4444
```

---

# Linux Cheat Sheet

```
pwd
ls
cd
mkdir
touch
cp
mv
rm
chmod
chown
apt
ifconfig
ip addr
ping
netstat
traceroute
nslookup
```

---

# Learning Outcomes

- Understood cybersecurity fundamentals.
- Learned the CIA Triad.
- Studied common cyber threats.
- Built a cybersecurity lab using Kali Linux and Metasploitable2.
- Practiced Linux commands.
- Learned networking fundamentals.
- Explored cryptography concepts.
- Used Wireshark, Nmap, Burp Suite, and Netcat.
- Verified communication between Kali and Metasploitable2.

---

# Author

**Paruchuri Venkatesh**

Cybersecurity & Ethical Hacking Intern

ApexPlanet Software Pvt. Ltd.