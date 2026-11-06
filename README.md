# Group Policy Security Baseline Lab (Microsoft Azure)
A lab that creates two Group Policy objects for common security settings and links them to an Organizational Unit, using PowerShell on a Windows Server 2022 VM in Microsoft Azure.

## Project Architecture
A PowerShell script creates the two GPOs and the Organizational Unit and links them together. The screenshot below shows the script, its output, and the result in Group Policy Management.
<img width="1341" height="762" alt="gpo_hardening_matrix" src="https://github.com/user-attachments/assets/3352f599-b8f3-4a07-91e9-8d2565d98555" />


## Core Policy Baselines Deployed
* **Ransomware Mitigation (`SEC-Ransomware-Mitigations`):** Disabled Windows Script Host through Group Policy to block .vbs and .js email attachments from running.
* **Data Privacy Protection (`SEC-System-Privacy-Hardening`):** Configured a BitLocker drive encryption policy using 256-bit AES.
* **Linked To an OU:** Linked both GPOs to a dedicated Organizational Unit for test endpoints.

## Skills Demonstrated
* Security Configuration Management
* Group Policy (GPO) creation and linking
* PowerShell Scripting
