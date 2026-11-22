# Windows Server 2022 Enterprise Active Directory & Network Lab

A hands-on System and Network Administration lab built in **VMware Workstation Pro 17** using **Windows Server 2022**. Each module includes step-by-step GUI walkthroughs with visual verification, architectural rationale, and troubleshooting notes.

---

## Lab Network Architecture

| Hostname | Role | OS | IPv4 Address | Subnet Mask | Default Gateway | DNS Servers |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **`DC-01`** | Primary Domain Controller, DNS, DHCP | Windows Server 2022 Standard | `192.168.198.10` | `255.255.255.0` | `192.168.198.2` | `127.0.0.1`, `8.8.8.8` |

---

## Lab Modules

| Module | Topic | Documentation | Status |
| :--- | :--- | :--- | :--- |
| **Module 01** | VM Provisioning, Static IP & Server Baseline | [01-server-baseline.md](./docs/01-server-baseline.md) | Completed |
| **Module 02** | Active Directory Domain Services (AD DS) & DNS Setup | [02-adds-dns-setup.md](./docs/02-adds-dns-setup.md) | Completed |
| **Module 03** | DHCP Server Configuration & Windows 10 Client Domain Join | `03-dhcp-client-join.md` | In Progress |
| **Module 04** | Organizational Units (OUs), RBAC & User Provisioning | `04-ou-rbac-provisioning.md` | Planned |
| **Module 05** | Group Policy Hardening & File Server Permissions | `05-gpo-file-permissions.md` | Planned |

---

## Repository Structure

```text
Active-Directory-Lab/
├── README.md                  # Lab overview, network table, and module index
├── assets/
│   └── screenshots/           # Step-by-step verification screenshots
└── docs/                      # Detailed Markdown walkthroughs for each module
```