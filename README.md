#  Active Directory Home Lab

A hands-on home lab project simulating a small enterprise IT environment using Windows Server and Active Directory. Built as a portfolio project for IT Support, Help Desk, and SysAdmin roles.

**[📄 View Full Proof of Completion (PDF)](./AD_Lab_Proof_of_Completion.pdf)**

---

##  What Was Built

| Component | Details |
|-----------|---------|
| Domain Controller | Windows Server 2025 — `WIN-G0QNGSVRO70` |
| Domain | `corp.local` |
| Client Machine | Windows 11 — `PC01` |
| Hypervisor | VMware |
| Roles Installed | AD DS, DNS, File and Storage Services |

---

##  Skills Demonstrated

- Windows Server 2025 installation and configuration
- Active Directory Domain Services (AD DS) setup and domain controller promotion
- DNS Server role installation integrated with AD
- Organizational Unit (OU) design — IT, HR, Finance, Sales, Workstations
- Domain user account creation and management
- Security Group creation (Global scope) with user membership assignment
- Shared folder creation with custom NTFS permission assignments per department
- Windows 11 client domain join and network share access verification

---

##  Lab Screenshots

All screenshots are documented in the [proof of completion PDF](./AD_Lab_Proof_of_Completion.pdf).

| # | What It Shows |
|---|---------------|
| 1 | Shared folder permissions — Finance_Users with Full Control |
| 2 | Server Manager dashboard — AD DS, DNS, File Services all online |
| 3 | Active Directory Users & Computers — OU structure under corp.local |
| 4 | IT_Users security group — members jsmith and tlee assigned |
| 5 | DNS Server role — online at 192.168.117.129 |
| 6 | PC01 (Windows 11) — domain joined, browsing network share |



## 🔗 References

- [Tutorial followed](./Active_Directory_Home_Lab_Tutorial_Resume_Project.pdf)
