# Splunk Lab

## Overview

## Network Diagram

## Environment Setup

### System Specification

### Windows Victim

- Install DVWA:
  - Download and install XAMPP (Apache + MySQL + PHP).
  - Place the DVWA files in the appropriate folder.
  - Start Apache & MySQL.
  - Open in browser and configure the database.
  - Set security level to "low" in DVWA settings.
- Install Sysmon
- Install Winlogbeat
- Install Splunk Universal Forwarder

## Splunk Server
- Splunk:
  - Download & install Splunk Free from Splunk Download.
  - Enable Receiving
  - Verify Forwarder Connection
  - Create Input / Index for Windows victim

## Suricata Server
- Install Suricata
- Configure Suricata
- Edit the default config
- Ensure network interface is correct
- Ensure logging to EVE JSON format is enabled
- Start Suricata
- Verify Suricata detects attacks
- Install Splunk Universal Forwarder on Ubuntu IDS
- Configure Forwarder to Send eve.json to Splunk Server
- On the Splunk Server, open TCP port to receive data
- Verify Forwarder Connection
- Create Input / Index for Suricata Server

## Kali Attacker

- Configure Kali-Attacker:
  - Use tools to simulate attacks on DVWA
  - Verify attacks being logged via:
    - Sysmon
    - Apache logs

## Methodology
### Attack DVWA from Kali
### Analyzing Attacks in Splunk
## Evaluation and Improvements
## Conclusion
