# Splunk + Active Directory Lab

## Overview

## Network Diagram

## Environment Setup

### System Specification

### Windows Domain Controller (DC)
- Install Windows Server
- Promote to Domain Controller
- Create a test domain (must be 2 level domain e.g. corp.local)
- Create test user accounts for brute force simulation
- Install Sysmon for enhanced event logging
- Install and configure Splunk Universal Forwarder to send logs to the Splunk server

## Windows Client
- Join to the domain (corp.local)
- Install Sysmon
- Install Splunk Universal Forwarder
- Configure Forwarder to send logs to Splunk

## Splunk Server
- Splunk:
  - Download & install Splunk.
  - Enable Receiving
  - Verify Forwarder Connection
  - Create Inputs / Indexes for Windows DC and client victims

## Kali Attacker

- Configure Kali-Attacker:
  - Use tools to simulate attacks and generate telemetry
  - Verify attacks being logged via:
    - Sysmon

## Methodology
### Attack AD from Kali
### Attack Windows client from Kali
### Analyzing Attacks in Splunk
## Evaluation and Improvements
## Conclusion
