# Group Policy Security Baseline Lab (Microsoft Azure)
A lab that creates two Group Policy objects for common security settings and links them to an Organizational Unit, using PowerShell on a Windows Server 2022 VM in Microsoft Azure.

## Project Architecture
Scripted deployment

## Core Policy Baselines Deployed
* **Ransomware Mitigation (`SEC-Ransomware-Mitigations`):** Disabled Windows Script Host through Group Policy to block .vbs and .js email attachments from running.
* **Data Privacy Protection (`SEC-System-Privacy-Hardening`):** Configured a BitLocker drive encryption policy using 256-bit AES.
* **Targeted Allocation:** Linked both GPOs to a dedicated Organizational Unit for test endpoints.

## Skills Demonstrated
* Security Configuration Management
* Group Policy (GPO) creation and linking
* PowerShell Scripting
