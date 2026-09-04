# Jira Service Management Help Desk Lab

## Overview

This project demonstrates practical **IT Help Desk / Service Desk ticket management** using **Jira Service Management**.

The lab simulates common Level 1 / Level 2 support incidents from ticket creation through troubleshooting, documentation, escalation, verification, and resolution.

The goal of this project is to show how I would handle real-world support tickets in a structured, professional, and SLA-focused environment.

---

## Skills Demonstrated

- Jira Service Management ticket handling
- Incident triage and prioritization
- Internal troubleshooting notes
- Ticket status management and resolution
- User communication and verification
- Escalation to appropriate support teams
- Active Directory account troubleshooting
- DNS and DHCP troubleshooting
- Outlook / password troubleshooting
- Printer queue and spooler troubleshooting
- Shared folder and NTFS permission troubleshooting
- Network outage incident handling
- Documentation of troubleshooting steps

---

## Ticket Scenarios

### 1. Account Lockout
**Issue:** User could not sign in because the account was locked.

**Workflow demonstrated:**
- Created the support ticket
- Investigated the user account
- Added an internal troubleshooting note
- Resolved the lockout issue
- Verified access with the user
- Closed the ticket

Evidence:
- `01-Jira-Ticket-Created-Account-Lockout`
- `02-Jira-Internal-Note-Account-Lockout-Troubleshooting`
- `03-Jira-Resolved-Account-Lockout-Ticket`

---

### 2. DNS Troubleshooting
**Issue:** User experienced a network/name-resolution problem.

**Workflow demonstrated:**
- Investigated DNS configuration
- Documented troubleshooting in an internal note
- Corrected the DNS-related issue
- Verified connectivity/name resolution
- Resolved the ticket

Evidence:
- `04-Jira-DNS-Troubleshooting-Internal-Note`
- `05-Jira-Resolved-DNS-Troubleshooting-Ticket`

---

### 3. Outlook Password Change
**Issue:** User could not access Outlook after a password change.

**Workflow demonstrated:**
- Created the incident
- Reviewed authentication/password-related causes
- Added troubleshooting notes
- Verified Outlook access
- Resolved the ticket

Evidence:
- `06-Jira-Outlook-Password-Change-Ticket-Created`
- `07-Jira-Outlook-Troubleshooting-Internal-Note`
- `08-Jira-Resolved-Outlook-Password-Change-Ticket`

---

### 4. Printer Queue / Spooler Issue
**Issue:** User could not print because of a print queue/spooler problem.

**Workflow demonstrated:**
- Created the ticket
- Checked printer status and queue
- Troubleshot the Print Spooler service
- Verified printing functionality
- Resolved the incident

Evidence:
- `09-Jira-Printer-Queue-Ticket-Created`
- `10-Jira-Printer-Spooler-Troubleshooting-Internal-Note`
- `11-Jira-Resolved-Printer-Spooler-Ticket`

---

### 5. Shared Folder Permissions
**Priority:** High

**Issue:** User could not access a required shared folder.

**Workflow demonstrated:**
- Created a high-priority support ticket
- Reviewed share and NTFS permissions
- Documented troubleshooting steps
- Restored appropriate access
- Verified access with the user
- Resolved the ticket

Evidence:
- `12-Jira-High-Priority-Shared-Folder-Access-Ticket-Created`
- `13-Jira-Shared-Folder-Permissions-Troubleshooting-Internal-Note`
- `14-Jira-Resolved-Shared-Folder-Permissions-Ticket`

---

### 6. Critical DHCP / Network Outage
**Priority:** Critical / Highest

**Issue:** Multiple users were affected by a DHCP-related network outage.

**Workflow demonstrated:**
- Created a critical incident
- Investigated DHCP/network symptoms
- Documented troubleshooting findings
- Escalated the incident to the network team
- Verified service restoration
- Resolved the outage ticket

Evidence:
- `15-Jira-Critical-DHCP-Network-Outage-Ticket-Created`
- `16-Jira-Critical-DHCP-Outage-Troubleshooting-Internal-Note`
- `17-Jira-Critical-DHCP-Outage-Escalated-to-Network-Team`
- `18-Jira-DHCP-Outage-Post-Escalation-Verification`
- `19-Jira-Resolved-Critical-DHCP-Network-Outage`

---

## Support Workflow Used

For each incident, I followed a consistent troubleshooting process:

**Understand → Check → Test → Fix → Verify → Document**

1. Understand the user-reported issue and impact
2. Check the most likely causes
3. Test the environment and reproduce or isolate the issue
4. Apply the appropriate fix
5. Verify the solution with the user or system
6. Document the work clearly in Jira
7. Escalate when the issue requires another support team

---

## Repository Structure

```text
Jira-Service-Management-Help-Desk-Lab/
│
├── README.md
│
└── screenshots/
    ├── 01-Jira-Ticket-Created-Account-Lockout.png
    ├── 02-Jira-Internal-Note-Account-Lockout-Troubleshooting.png
    ├── 03-Jira-Resolved-Account-Lockout-Ticket.png
    ├── 04-Jira-DNS-Troubleshooting-Internal-Note.png
    ├── 05-Jira-Resolved-DNS-Troubleshooting-Ticket.png
    ├── 06-Jira-Outlook-Password-Change-Ticket-Created.png
    ├── 07-Jira-Outlook-Troubleshooting-Internal-Note.png
    ├── 08-Jira-Resolved-Outlook-Password-Change-Ticket.png
    ├── 09-Jira-Printer-Queue-Ticket-Created.png
    ├── 10-Jira-Printer-Spooler-Troubleshooting-Internal-Note.png
    ├── 11-Jira-Resolved-Printer-Spooler-Ticket.png
    ├── 12-Jira-High-Priority-Shared-Folder-Access-Ticket-Created.png
    ├── 13-Jira-Shared-Folder-Permissions-Troubleshooting-Internal-Note.png
    ├── 14-Jira-Resolved-Shared-Folder-Permissions-Ticket.png
    ├── 15-Jira-Critical-DHCP-Network-Outage-Ticket-Created.png
    ├── 16-Jira-Critical-DHCP-Outage-Troubleshooting-Internal-Note.png
    ├── 17-Jira-Critical-DHCP-Outage-Escalated-to-Network-Team.png
    ├── 18-Jira-DHCP-Outage-Post-Escalation-Verification.png
    └── 19-Jira-Resolved-Critical-DHCP-Network-Outage.png
```

---

## Tools and Technologies

- Jira Service Management
- Windows 10 / 11
- Windows Server / Active Directory
- DNS
- DHCP
- Microsoft Outlook / Microsoft 365
- Windows Print Spooler
- Windows file sharing and NTFS permissions
- TCP/IP troubleshooting concepts

---

## What This Project Shows

This lab demonstrates my ability to:

- Handle support incidents from intake through closure
- Prioritize tickets based on urgency and business impact
- Write clear internal notes for other technicians
- Troubleshoot common desktop, identity, printing, file access, and network issues
- Escalate critical incidents appropriately
- Verify service restoration before closing tickets
- Maintain professional and organized support documentation

---

## Related IT Support Projects

- Active Directory Help Desk Lab
- DNS / DHCP / Network Troubleshooting Lab
- Microsoft 365 / Entra ID / Intune Lab

These projects together demonstrate hands-on experience with common technologies used in modern Help Desk and IT Support environments.

---

## Career Focus

I am building practical experience for roles such as:

- Help Desk Technician
- IT Support Specialist
- Service Desk Analyst
- Desktop Support Technician
- Technical Support Specialist
