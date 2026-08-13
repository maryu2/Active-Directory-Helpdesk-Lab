# Active Directory Helpdesk Lab

## Overview

A hands-on Windows Server and Active Directory home lab created to develop and demonstrate practical IT Support, Service Desk, and 1st Line Support skills.

The lab uses a Windows Server virtual machine to build and manage an Active Directory domain in a controlled environment.

The exercises focus on common IT Support tasks involving user accounts, security groups, permissions, shared folders, and user access troubleshooting.

Each lab follows a structured support process:

**Task / Problem → Investigation → Action → Verification → Documentation**

The purpose of this project is to demonstrate practical experience with Active Directory and Windows Server administration, while developing a structured approach to resolving common user and access issues encountered in IT Support environments.

---

## Lab Environment

- **Windows Server**
- **Active Directory Domain Services (AD DS)**
- **Active Directory Users and Computers (ADUC)**
- **Windows PowerShell**
- **Windows Server File Sharing**
- **Security Groups**
- **NTFS Permissions**
- **Share Permissions**
- **Virtual Machine**
- **GitHub**

---

# Active Directory Labs

## Lab 01 — User Account Management

**Status:** Completed 

A series of common IT Support and Service Desk user-account tasks were performed using Active Directory.

The lab covered:

- Creating a domain user
- Resetting a user password
- Unlocking a user account
- Enabling and disabling an account
- Verifying account status
- Configuring and testing account lockout settings

### Skills Demonstrated

- Active Directory user administration
- Domain account management
- Password management
- Account lockout troubleshooting
- User account verification
- Service Desk procedures
- Windows Server administration
- PowerShell administration

### Tools Used

- Windows Server
- Active Directory Users and Computers
- PowerShell

[View Lab 01 — User Account Management](labs/01-user-account-management.md)

---

## Lab 02 — Security Groups & Permissions

**Status:** Completed 

Security groups and permissions were configured to control access to resources within the Windows domain.

The lab covered:

- Creating security groups
- Adding users to groups
- Creating a shared folder
- Configuring NTFS permissions
- Configuring SMB share permissions
- Testing user access
- Troubleshooting SMB share access
- Verifying successful file access

### Skills Demonstrated

- Active Directory security groups
- Group membership management
- NTFS permissions
- Share permissions
- Access control
- File sharing
- Windows administration
- PowerShell administration
- Permission testing
- SMB troubleshooting

### Tools Used

- Windows Server
- Active Directory Users and Computers
- Windows File Explorer
- PowerShell
- Windows Server File Sharing

[View Lab 02 — Security Groups & Permissions](labs/02-security-groups-permissions.md)

---

## Lab 03 — Shared Folder Access Troubleshooting

**Status:** Completed 

A realistic Service Desk troubleshooting scenario was created where a domain user was unable to access a shared folder.

A controlled access problem was introduced by removing the user's membership from the security group responsible for Finance shared-folder access.

The issue was then investigated, the root cause identified, the user's access restored, and the solution verified.

The investigation examined:

- User access
- Security group membership
- NTFS permissions
- Share permissions
- Network access
- Resource configuration
- User session and access verification

### Example Service Desk Scenario

> **User reports:** "I cannot access the Finance shared folder."

The issue was investigated from the perspective of an IT Support technician.

### Troubleshooting Process

**Identify → Investigate → Resolve → Verify → Document**

### Skills Demonstrated

- Service Desk troubleshooting
- Active Directory
- User account investigation
- Security group investigation
- NTFS permissions
- Share permissions
- Access troubleshooting
- Root-cause analysis
- Problem resolution
- Verification and testing
- Technical documentation

### Tools Used

- Windows Server
- Active Directory Users and Computers
- Windows File Explorer
- PowerShell
- Windows Server File Sharing

[View Lab 03 — Shared Folder Access Troubleshooting](labs/03-shared-folder-troubleshooting.md)

---

# Evidence

Each completed lab includes supporting screenshots documenting the work performed.

Evidence includes:

- Active Directory domain configuration
- User account creation
- User account properties
- Password reset
- Account unlock
- Account disable and enable
- Security group configuration
- Group membership
- Shared folder configuration
- NTFS permissions
- Share permissions
- Access testing
- Troubleshooting results
- Final verification

Screenshots are stored in the repository's `screenshots/` directory and referenced from the relevant lab documentation.

---

# Troubleshooting & Administration Method

Each lab follows a consistent approach.

### 1. Task / Problem

Identify the user's request or reported issue.

### 2. Investigation

Gather information using appropriate Active Directory and Windows Server tools.

### 3. Action

Perform the required administrative task or make the necessary configuration change.

### 4. Verification

Test the result and confirm that the requested task or reported issue has been resolved.

### 5. Documentation

Document the process, commands used, configuration changes, results, and supporting evidence.

---

# Skills Developed

Through this project, I developed practical experience in:

- Active Directory
- Windows Server administration
- User account management
- Password management
- Account lockout troubleshooting
- Security groups
- Group membership
- NTFS permissions
- Share permissions
- SMB file sharing
- Access control
- Service Desk troubleshooting
- Root-cause analysis
- Problem resolution
- Verification and testing
- PowerShell administration
- Technical documentation

---

# Project Goal

The goal of this project is to develop practical Active Directory and Windows Server skills relevant to IT Support, Service Desk, and 1st Line Support roles.

The labs focus on realistic tasks that an IT Support technician may encounter when managing user accounts, groups, permissions, and access to shared resources within a Windows domain environment.

Each exercise was performed in a controlled virtual environment and documented as evidence of practical experience.

Rather than only documenting theoretical knowledge, the project focuses on hands-on administration and troubleshooting.

The project demonstrates a structured approach to:

**Identify → Investigate → Resolve → Verify → Document**

---

# Lab Status

**Completed: 3 of 3 labs

- [x] Lab 01 — User Account Management
- [x] Lab 02 — Security Groups & Permissions
- [x] Lab 03 — Shared Folder Access Troubleshooting

All three Active Directory Helpdesk labs have been completed and documented with supporting evidence.
