# Microsoft Intune Homelab Project

## Overview

This project demonstrates the deployment and management of Windows devices using Microsoft Intune and Microsoft Entra ID (Azure AD). The lab was built using a Microsoft 365 Business Premium trial tenant and Windows 11 virtual machines.

The goal of this project was to gain hands-on experience with modern endpoint management, cloud identity, application deployment, compliance policies, configuration profiles, and endpoint security.

---

## Technologies Used

* Microsoft Intune
* Microsoft Entra ID (Azure AD)
* Microsoft 365 Business Premium
* Windows 11
* VirtualBox
* Microsoft Defender
* BitLocker
* Microsoft Store Apps
* Win32 Applications

---

## Lab Environment

### Tenant

* Microsoft 365 Business Premium Trial
* Microsoft Entra ID Tenant

### Virtual Machines

#### CLIENT01

* Windows 11
* Local Administrator Account
* Work/School Account Connected
* Intune Managed

#### CLIENT02

* Windows 11
* Microsoft Entra ID Joined
* Intune Managed
* Primary Test Device

---

## User Management

Created and managed users through Microsoft Entra ID.

### Example Users

* Henry Stephens
* Phyo Hein

Tasks performed:

* User creation
* License assignment
* Password management
* Group membership management

---

## Group Management

Created Security Groups for policy and application targeting.

### Example Group

**Intune-Test-Devices**

Purpose:

* Application deployment
* Policy assignment
* Compliance targeting

Tasks performed:

* Security group creation
* Member assignment
* Policy targeting

---

## Device Enrollment

Successfully enrolled Windows 11 devices into Microsoft Intune.

### Enrollment Methods Tested

#### Work Account Registration

* Local Windows account
* Work account connected through "Access work or school"

#### Microsoft Entra ID Join

* Direct sign-in using Microsoft 365 account
* Automatic Intune enrollment
* Preferred enterprise deployment method

---

## Compliance Policies

Created and deployed compliance policies to managed devices.

### Example Policy

Password Compliance Policy

Requirements:

* Password required
* Minimum password standards
* Device compliance monitoring

Tasks performed:

* Policy creation
* Group assignment
* Compliance verification

---

## Configuration Profiles

Created and deployed configuration profiles to managed devices.

### Example Settings

* Device lock configuration
* Password requirements
* Security settings

Tasks performed:

* Profile creation
* Assignment to security groups
* Verification through Intune reporting

---

## Application Deployment

### Microsoft Store Application Deployment

Successfully deployed:

#### Microsoft Whiteboard

Deployment Type:

* Microsoft Store App (New)

Result:

* Automatically installed on enrolled devices

---

### Win32 Application Deployment

Successfully deployed:

#### 7-Zip

Process:

1. Downloaded MSI installer
2. Packaged application using Microsoft Win32 Content Prep Tool
3. Generated .intunewin package
4. Uploaded to Microsoft Intune
5. Configured detection rules
6. Assigned to security groups
7. Verified successful installation

Result:

* Automatic installation on CLIENT02

---

## Endpoint Security

### Microsoft Defender Antivirus Policy

Created and deployed antivirus policy.

Settings configured:

* Real-time protection enabled
* Cloud-delivered protection enabled
* Behavior monitoring enabled

Result:

* Successfully applied to managed devices

---

### Microsoft Defender Firewall Policy

Created and deployed firewall policy.

Settings configured:

* Domain Profile Firewall enabled
* Private Profile Firewall enabled
* Public Profile Firewall enabled

Result:

* Successfully applied to managed devices

---

### BitLocker Disk Encryption

Created and deployed BitLocker policy.

Tasks performed:

* Encryption policy deployment
* Encryption initiation
* Recovery key management

Result:

* Device received BitLocker encryption prompt
* Policy successfully delivered through Intune

---

## Skills Demonstrated

### Microsoft Entra ID

* User management
* Group management
* Device management
* Identity administration

### Microsoft Intune

* Device enrollment
* Compliance policies
* Configuration profiles
* Application deployment
* Endpoint security

### Endpoint Management

* Microsoft Store App deployment
* Win32 App deployment
* Device targeting
* User targeting
* Security policy management

### Security

* Microsoft Defender Antivirus
* Microsoft Defender Firewall
* BitLocker Encryption
* Compliance enforcement

---

## Lessons Learned

* Difference between Microsoft Entra Joined and Work Account Registered devices
* User-based vs Device-based assignments
* Win32 application packaging and deployment
* Compliance policy evaluation
* Endpoint security policy deployment
* Application detection rules
* Intune troubleshooting techniques

---

## Screenshots

### Entra ID

* Users
* Groups
* Licenses

### Intune

* Device Enrollment
* Compliance Policies
* Configuration Profiles

### Application Deployment

* Microsoft Whiteboard
* 7-Zip Win32 Deployment

### Endpoint Security

* Antivirus Policy
* Firewall Policy
* BitLocker Policy

---

## Author

Phyo Si Thu Hein

GitHub:
https://github.com/phyosithu-dev

---

## Project Status

Completed

This project demonstrates practical hands-on experience with Microsoft Intune, Microsoft Entra ID, endpoint security, and modern Windows device management.
