# Hybrid Active Directory Lab (Azure + Windows Server 2022)

This project is a live, enterprise-style Active Directory lab environment built on Microsoft Azure.  

## Lab Goals

- Deploy a production-style on-prem Active Directory domain on Windows Server 2022 (hosted in Azure).
- Implement a clean OU and security group structure aligned with common enterprise patterns.
- Join Windows 11 clients to the domain for testing and Group Policy application.

## High-Level Architecture (Phase 1)

- **Cloud Provider**: Microsoft Azure
- **Domain Controller**: `DC01` (Windows Server 2022)
- **Domain Name**: `linhlab.local`
- **Virtual Network**: `10.0.0.0/24`
- **Client VM**: Windows 11 joined to `linhlab.local` (later phase)

More phases (Azure AD Connect, Intune, Autopilot, Conditional Access, etc.) will be added as the lab evolves.
