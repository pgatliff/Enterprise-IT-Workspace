# Enterprise-IT-Workspace
Production sandbox environment modeling enterprise infrastructure, network isolation, and defensive security operations.

# Hybrid Enterprise IT Portfolio Workspace

## Architectural Overview
This portfolio chronicles the design, deployment, and security auditing of a modern hybrid enterprise network sandbox. The ecosystem utilizes a centralized Windows identity platform coupled with scalable Linux infrastructure nodes.

## Network Topology Baseline (Parkland Coursework Integration)
* **Internal Domain:** `gatliff.local`
* **Network Boundary:** `10.10.10.0/24` (Isolated via Hyper-V Internal Virtual Switch)
* **Chapter 8 Homework Focus:** Implementing logical network segmentation and access rules across distinct guest operating systems.

## Provisioned Hybrid Assets

| Host Name  | Operating System     | Core System Function                | Target IP    | Hardware Profile      |
| :---       | :---                 | :---                                | :---         | :---                  |
| CORP-DC01  | Windows Server 2022  | Identity Broker (Active Directory/DNS) | 10.10.10.10  | 4GB RAM / 60GB Storage|
| CORP-SRV01 | Ubuntu Server 24.04  | Enterprise Infrastructure Asset     | 10.10.10.20  | 2GB RAM / 40GB Storage|
