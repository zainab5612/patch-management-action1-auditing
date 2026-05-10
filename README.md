# Patch Management & Vulnerability Reporting with Action1

> A hands-on endpoint management project focused on patch deployment, vulnerability remediation, reporting, and audit evidence.

![Windows Server](https://img.shields.io/badge/Windows%20Server-2022-6E9FC1?style=flat-square)
![Action1](https://img.shields.io/badge/Action1-Patch%20Management-7BAE9D?style=flat-square)
![Security](https://img.shields.io/badge/Focus-Vulnerability%20Remediation-B89BC8?style=flat-square)
![Audit](https://img.shields.io/badge/Reports-Audit%20Evidence-D9A76C?style=flat-square)

---

## Project Summary

I created this project to practice patch management, vulnerability remediation, and audit reporting using Action1.

The goal was to understand how IT teams identify missing updates, deploy patches, confirm that remediation was successful, and generate reports that can be used for audits or compliance reviews.

This project helped me see that patch management is more than just installing updates. It also involves planning, timing, reboot handling, user impact, reporting, and proof that the issue was actually fixed.

---

## What I Worked On

| Area | What I Practiced |
|---|---|
| Patch Management | Found missing updates and deployed them |
| Vulnerability Remediation | Reviewed vulnerabilities and remediation actions |
| Reporting | Exported reports for installed software, antivirus status, and vulnerabilities |
| Audit Evidence | Reviewed audit trails and activity history |
| Access Control | Practiced roles, permissions, and least privilege |
| Endpoint Management | Managed a Windows Server 2022 endpoint through Action1 |

---



| Item | Details |
|---|---|
| Tool | Action1 |
| Endpoint | Windows Server 2022 |
| Domain | homelab.com |
| Main Focus | Patch management and reporting |
| Related Skills | Endpoint security, audit reporting, vulnerability remediation |

---

## Patch Management Workflow

The main workflow I practiced was:

```text
Find missing update → Deploy update → Monitor deployment → Verify installation → Export report
```

I found a missing Microsoft Edge security update, deployed it through Action1, monitored the deployment process, and confirmed the update completed successfully.

This was important because it showed me how IT teams track the full remediation process instead of only assuming the update worked.

---

## Security Update Remediation

During testing, I deployed a Microsoft Edge security update to the endpoint.

The deployment process showed several steps:

- starting the automation
- checking deployment requirements
- downloading the update package
- installing the update
- completing successfully

After the deployment completed, I exported an installed software report to confirm the updated Microsoft Edge version was installed.

---

## Update Scheduling and Reboots

I also reviewed update scheduling and reboot options.

Action1 allowed me to:

- deploy updates immediately
- schedule updates for later
- automatically reboot if required
- show users a warning message before reboot
- give users time to save work before restart

This helped me understand why updates should be planned carefully in a real company. If updates are pushed to everyone at once, it can create many support tickets if something breaks.

---

## Audit and Compliance Reporting

I explored built-in reports that could support audit or compliance reviews.

Reports included:

- vulnerability summary
- antivirus status
- installed software
- missing updates
- endpoint status
- hardware/software inventory

These reports are useful because they provide evidence of what was found, what was fixed, and what still needs attention.

---

## Audit Trail

I reviewed Action1 audit trails to see recorded activity inside the platform.

This matters because audit trails show:

- who performed an action
- what action was performed
- when it happened
- what endpoint or object was affected

This connects to accountability, security, and compliance.

---

## Role-Based Access Control

I also explored roles and permissions.

I practiced creating a limited role to better understand least privilege. The purpose is to make sure users only have the access they actually need.

For example, someone may need permission to view reports or run approved scripts, but they should not automatically have full admin access.

---

## What I Learned

This project helped me better understand:

- patch management
- vulnerability remediation
- endpoint reporting
- audit evidence
- antivirus status reporting
- update scheduling
- reboot planning
- audit trails
- role-based access control
- least privilege
- compliance basics

---

## Screenshots

### Endpoint Dashboard

<img width="1339" height="1011" alt="Screenshot 2026-05-09 001431" src="https://github.com/user-attachments/assets/7896a5f7-3eb3-4748-9e64-db97a89fa28e" />


This shows the managed endpoint inside Action1 and gives an overview of missing updates, vulnerabilities, and endpoint status.

---

### Missing Update Found

<img width="1497" height="845" alt="Screenshot 2026-05-09 222315" src="https://github.com/user-attachments/assets/945958e0-f337-49cc-bdf9-c6d2dab731d4" />

This shows the missing updates that needed to be deployed.

---

### Successful Update Deployment

<img width="1432" height="603" alt="Screenshot 2026-05-09 222753" src="https://github.com/user-attachments/assets/be788460-94f0-4a4e-a3ba-505104efed24" />

This shows the Microsoft Edge update deployment completing successfully.

---

### Installed Software Report

<img width="1809" height="495" alt="Screenshot 2026-05-09 223628" src="https://github.com/user-attachments/assets/1ae1b9d6-73c5-4a1f-bd70-57a9472860f0" />

This exported report confirms that Microsoft Edge was installed with the updated version after remediation.

---

### Vulnerability Summary Report
<img width="1478" height="449" alt="Screenshot 2026-05-09 221151" src="https://github.com/user-attachments/assets/3f785ba0-c08f-41e4-bb16-775bf22595ce" />


This report shows vulnerability information that can be used for review or audit documentation.

---

### Antivirus Status Report
<img width="1243" height="565" alt="Screenshot 2026-05-09 001819" src="https://github.com/user-attachments/assets/1fbc97f7-f01a-4f1d-ac62-919d1657b83f" />


This report shows endpoint antivirus status and protection information.

---

### Audit Trail

<img width="1487" height="854" alt="Screenshot 2026-05-09 215933" src="https://github.com/user-attachments/assets/44098ad8-083f-4e93-8e03-fc948c605daa" />

This shows recorded administrative actions inside Action1.

---

### Role-Based Access Control
<img width="1493" height="561" alt="Screenshot 2026-05-09 220035" src="https://github.com/user-attachments/assets/b54b8884-bd4f-45b2-a6b4-1bafe202c9b9" />
<img width="1317" height="680" alt="Screenshot 2026-05-09 221036" src="https://github.com/user-attachments/assets/e0c87990-fa50-4737-bfd1-e8b2db1107b8" />

This shows role permissions and scope settings used to practice least privilege.

---

## Additional Notes

I kept additional notes while working through patch management, vulnerability reporting, audit reports, and access control.

Additional notes can be added in the `/notes` folder.
