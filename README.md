# IAM Access Governance Lab | Microsoft Entra ID

## Overview

This project is a hands-on IAM access governance lab built in Microsoft Entra ID.

The lab documents how I created a small identity environment with fictional users, role-based groups, MFA enforcement, Conditional Access, privileged access management, joiner/mover/leaver workflows, and access review simulation.

The goal of this project is to practice common IAM Analyst tasks in a controlled lab environment and document the work clearly with screenshots and written explanations.

## Project status

In progress.

This lab is being built step by step, with documentation and screenshots added as each section is completed.

## Lab environment

The lab uses a Microsoft Entra ID tenant named **Northstar Identity Lab**.

The environment includes fictional users, departments, and security groups to model realistic access governance scenarios across HR, Finance, IT, Conditional Access, privileged access, and access review workflows.

## Skills demonstrated

- Microsoft Entra ID tenant setup
- User provisioning
- Security group creation
- Role-based access control
- Least-privilege access assignment
- MFA and Conditional Access policy configuration
- Joiner, mover, and leaver workflow simulation
- Privileged Identity Management
- Access review simulation
- IAM documentation and evidence collection

## Planned sections

| Section | Description |
|---|---|
| Lab overview | Defines the project purpose, scope, and lab environment |
| Users and groups | Documents test users, security groups, and RBAC assignments |
| Conditional Access | Documents MFA policy configuration and pilot testing |
| JML workflows | Simulates joiner, mover, and leaver lifecycle workflows |
| Admin roles and PIM | Documents privileged access management using PIM |
| Access review simulation | Reviews group membership and validates access cleanup |
| Concept mapping | Maps the Entra ID lab concepts to Okta and SailPoint at a high level |

## Repository structure

```text
docs/
screenshots/
artifacts/
README.md
```

## Documentation

- [Lab overview](docs/01-lab-overview.md)

Additional documentation will be added as each lab section is completed.

## Important note

This lab is built hands-on in Microsoft Entra ID only.

Okta and SailPoint are not configured or integrated in this project. They may be referenced later only as conceptual comparisons to show how similar IAM concepts appear across different identity platforms.
