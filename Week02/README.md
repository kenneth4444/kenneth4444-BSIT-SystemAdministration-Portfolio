# Week 02 — Enterprise Infrastructure Plan

## Project Overview
This project presents the initial IT infrastructure plan for **ABC Startup Solutions**, a newly established software development company with 20 employees working from one office floor. The plan covers company requirements, hardware and software inventories, network equipment, topology, system administration roles, infrastructure recommendations, and personal reflection.

The design was prepared from the perspective of a **Junior System Administrator**. The main goal is to create an infrastructure that is practical for a small startup, secure enough for business use, manageable by a small IT team, and flexible enough to support future growth.

## Learning Objectives
- Explain the role and responsibilities of a System Administrator.
- Identify hardware, software, and networking requirements for a small business.
- Prepare professional IT inventories and technical documentation.
- Design a logical enterprise network topology.
- Practice infrastructure planning, documentation, and technical communication.

## Company Scenario
**ABC Startup Solutions** is a fictional software development company with 20 employees distributed among Information Technology, Human Resources, Finance, and Sales. The company is starting with no existing computers, server, network, internet infrastructure, or formal security policies.

## Hardware Inventory Summary
The proposed setup includes 20 desktop computers for the standard workstation requirement, 6 business laptops for mobile/backup use, a server, managed network equipment, printers, UPS units, wireless access points, NAS storage, backup drives, and monitors.

| Asset | Qty. | Main Purpose |
|---|---:|---|
| Desktop Computers | 20 | Primary employee workstations |
| Business Laptops | 6 | IT administration, mobility, meetings, contingency |
| Server | 1 | Central services, file sharing, internal applications |
| Managed Switch | 1 | Wired network connectivity and VLAN support |
| Router | 1 | WAN gateway and routing |
| Firewall | 1 | Perimeter security and traffic control |
| Wireless AP | 3 | Business and guest Wi-Fi coverage |
| Network Printers | 2 | Shared printing |
| UPS | 4 | Power protection for server/network equipment |
| NAS | 1 | Local backup and shared storage |
| External Backup Drives | 2 | Offline backup rotation |
| Monitors | 26 | Dual-screen setups for selected roles and laptop docking |

## Software Inventory Summary
Core software includes Windows 11 Pro, Ubuntu Server, Microsoft 365/Office applications, Visual Studio Code, Git, GitHub Desktop, VirtualBox, Google Chrome, Microsoft Defender, AnyDesk, and 7-Zip.

## Embedded Network Diagram
![ABC Network Topology](diagrams/ABC_Network_Topology.png)

The topology uses an Internet → ISP Modem → Router → Firewall → Managed Switch structure. The switch connects the departments, server, printers, and wireless access points. VLANs are recommended so that department traffic can be separated and controlled.

## Technologies Used
- Windows 11 Pro
- Ubuntu Server LTS
- Microsoft 365/Office
- Visual Studio Code
- Git and GitHub
- GitHub Desktop
- VirtualBox
- Google Chrome
- Microsoft Defender
- AnyDesk
- 7-Zip
- Ethernet / CAT6
- VLANs
- Firewall and network segmentation
- NAS and offline backup storage
- Draw.io / diagrams.net
- Markdown
- GitHub

## Challenges Encountered
The main challenge was deciding how much equipment a 20-person company actually needs without making the infrastructure unnecessarily expensive. Another challenge was balancing current requirements with future growth. The plan therefore includes spare network capacity, additional laptops, backup storage, and a VLAN structure that can be expanded later.

## Reflection
This project helped me understand that system administration is not only about installing operating systems or fixing computers. A System Administrator also has to plan resources, document equipment, understand business requirements, protect company information, and think about future growth. The network diagram also showed me how different devices depend on one another. A small mistake in addressing, routing, or security rules can affect several users at the same time.

The most challenging part was designing the infrastructure from zero because there was no existing equipment to use as a reference. I had to think about how many computers, switches, access points, storage devices, and backup devices would be reasonable for 20 employees. I also learned that a professional plan should explain why an item is needed instead of simply listing equipment.

Planning is important before deployment because it prevents unnecessary purchases, reduces configuration problems, and gives the IT team a clear direction. It also makes future troubleshooting easier because the expected structure is already documented. Overall, this activity gave me a better understanding of how a System Administrator connects business requirements with practical technical solutions.

## References
- Microsoft — Windows 11 for Business: https://www.microsoft.com/en-us/windows/business/
- Microsoft — Windows 11 Security: https://www.microsoft.com/en-us/windows/business/windows-11-security
- Ubuntu — Ubuntu Server: https://ubuntu.com/server
- Ubuntu — Ubuntu Server Documentation: https://ubuntu.com/server/docs/
- Visual Studio Code — License: https://code.visualstudio.com/license
- GitHub Desktop: https://github.com/apps/desktop
- GitHub Desktop Documentation: https://docs.github.com/en/desktop/
- diagrams.net: https://www.diagrams.net/
