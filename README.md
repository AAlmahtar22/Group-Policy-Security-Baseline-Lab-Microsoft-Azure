# Group Policy Security Baseline Lab (Microsoft Azure)
A lab that creates two Group Policy objects for common security settings and links them to an Organizational Unit, using PowerShell on a Windows Server 2022 VM in Microsoft Azure.

## Project Architecture
Scripted deployment

## Core Policy Baselines Deployed
* **Ransomware Mitigation (`SEC-Ransomware-Mitigations`):** Programmatically disabled Windows Script Host (WSH) registry endpoints to block email-borne script payloads (.vbs, .js) from executing.
* **Data Privacy Protection (`SEC-System-Privacy-Hardening`):** Enforced enterprise-grade BitLocker volume encryption parameters utilizing advanced 256-bit AES algorithms.
* **Targeted Allocation:** Mapped security configurations directly to an isolated Organizational Unit (OU) layer hosting production production assets.

## Skills Demonstrated
* Security Configuration Management
* Windows Registry Hardening
* Group Policy Architecture & Policy Linking
* PowerShell Automation & Infrastructure as Code (IaC)
