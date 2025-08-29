# Cybersecurity-Home-Lab
A repository documenting the architecture, configuration and experiments conducted in my personal cybersecurity home lab


# Cybersecurity Home Lab

## 1. Project Objective

This repository serves as the central documentation hub for my personal cybersecurity home lab. The purpose of this lab is to provide a hands-on, sandboxed environment for practicing defensive and offensive security techniques, analyzing malware, testing vulnerabilities, and mastering industry-standard tools. It is a key component of my ongoing professional development in the cybersecurity field.

---

## 2. Lab Architecture

The lab is built on a virtualized platform, creating an isolated network environment to ensure all experimental traffic is contained.

*   **Virtualization Platform:** [e.g., VirtualBox]
*   **Logical Segments:** The network is segmented into an "Attacker Zone" and a "Target Zone," separated by a virtual firewall [pfSense].
*   **High-Level Diagram:** A detailed network diagram is available in the `01_Architecture` directory.

---

## 3. Core Components

| Role              | Operating System             | Key Software/Purpose                                  |
| ----------------- | --------------------------   | ----------------------------------------------------- |
| **Firewall/Router** | pfSense                    | Network segmentation, traffic logging, IDS/IPS        |
| **Attacker VM**     | Kali Linux                 | Nmap, Metasploit, Burp Suite, Wireshark               |
| **Target VM #1**    | Metasploitable2            | Intentionally vulnerable Linux server for pentesting  |
| **Target VM #2**    | Windows 10                 | Simulates a typical corporate endpoint                |
| **SIEM/Monitoring** | Security Onion             | Centralized logging and threat analysis               |

---

## 4. Repository Structure

This repository is organized into the following directories:

*   **/01_Architecture:** Contains network diagrams and IP schema.
*   **/02_Asset_Configuration:** Detailed build notes and configuration for each VM.
*   **/03_Lab_Experiments:** Step-by-step write-ups of all security exercises performed.
*   **/04_Scripts_and_Automation:** Custom scripts for automating lab tasks.
*   **/05_Reference_Material:** Useful cheatsheets, articles, and external resources.

