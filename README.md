# SIEM Internship – Phase 1

## 📌 Overview

This repository documents **Phase 1** of my SIEM (Security Information and Event Management) internship project. The goal of this phase is to set up a basic virtual lab environment to simulate a Windows target machine and a SIEM/log collection system, and to enable basic log forwarding using **Sysmon** and **Winlogbeat** (or equivalent tools).

---

## 🧪 Lab Architecture

```plaintext
[Windows Machine (Target)] ---> [SIEM/Log Collector (e.g., Splunk)]
            |                                |
         Sysmon                      Winlogbeat/Log Forwarder
