# IAM Access Governance Lab | Microsoft Entra ID

## Overview

This project is a hands-on IAM access governance lab built in Microsoft Entra ID.

The lab documents how I created a small identity environment with fictional users, role-based security groups, MFA enforcement, Conditional Access, privileged access management, joiner/mover/leaver workflows, and access review simulation.

The goal of this project is to practice common IAM Analyst tasks in a controlled lab environment and document the work clearly with screenshots and written explanations.

## Project status

Complete.

This lab includes Microsoft Entra tenant setup, test users, role-based security groups, MFA and Conditional Access, joiner/mover/leaver workflows, Privileged Identity Management, access review simulation, and conceptual Okta/SailPoint mapping.

## Lab environment

The lab uses a Microsoft Entra ID tenant named **Northstar Identity Lab**.

The environment includes fictional users, departments, and security groups to model realistic access governance scenarios across HR, Finance, IT, Conditional Access, privileged access, and access review workflows.

## Skills demonstrated

* Microsoft Entra ID tenant setup
* User provisioning
* Security group creation
* Role-based access control
* Least-privilege access assignment
* MFA and Conditional Access policy configuration
* Conditional Access pilot group testing
* Joiner, mover, and leaver workflow simulation
* Privileged Identity Management eligible role assignment
* Manual access review simulation
* IAM documentation and evidence collection
* Conceptual IAM mapping across Entra ID, Okta, and SailPoint

## Project sections

| Section                  | Description                                                                  |
| ------------------------ | ---------------------------------------------------------------------------- |
| Lab overview             | Defines the project purpose, scope, and lab environment                      |
| Tenant setup             | Documents the Microsoft 365 and Microsoft Entra lab environment              |
| Users and groups         | Documents test users, security groups, and RBAC assignments                  |
| Conditional Access       | Documents MFA policy configuration, pilot group scoping, and sign-in testing |
| JML workflows            | Simulates joiner, mover, and leaver lifecycle workflows                      |
| Admin roles and PIM      | Documents privileged access management using PIM                             |
| Access review simulation | Reviews group membership and validates access cleanup                        |
| Concept mapping          | Maps Entra ID lab concepts to Okta and SailPoint at a high level             |

## Repository structure

```text
docs/
screenshots/
artifacts/
README.md
```

## Documentation

* [Lab overview](docs/01-lab-overview.md)
* [Tenant setup](docs/02-tenant-setup.md)
* [Users and groups](docs/03-users-and-groups.md)
* [Conditional Access and MFA](docs/04-conditional-access.md)
* [Joiner, mover, and leaver workflows](docs/05-jml-workflows.md)
* [Admin roles and Privileged Identity Management](docs/06-admin-roles-pim.md)
* [Access review simulation](docs/07-access-review-simulation.md)
* [Concept mapping: Okta and SailPoint](docs/08-concept-mapping.md)

## Evidence

Screenshots are organized by lab section in the `screenshots/` folder.

Evidence includes:

* Microsoft 365 and Microsoft Entra tenant setup
* Role-based security groups
* Test users and group memberships
* Conditional Access MFA policy configuration
* MFA pilot group scoping and sign-in testing
* Joiner, mover, and leaver workflow changes
* PIM eligible role assignment
* Manual access review simulation results

## Important note

This lab is built hands-on in Microsoft Entra ID only.

Okta and SailPoint are not configured or integrated in this project. They are referenced only as conceptual comparisons to show how similar IAM concepts may appear across different identity platforms.
