# IAM Access Governance Lab | Microsoft Entra ID

## Overview

This project is a hands-on IAM access governance lab built in Microsoft Entra ID.

I created a small fictional identity environment called **Northstar Identity Lab** to practice assigning, testing, reviewing, and removing user access in a controlled lab tenant. The lab includes fictional users, department-based security groups, Conditional Access with MFA, joiner/mover/leaver workflow changes, eligible privileged access, and a manual access review simulation.

## Business scenario

Northstar Identity Lab is a fictional organization with HR, Finance, and IT users. Each department needs access to different resources based on job function.

In this lab, I acted as the IAM analyst responsible for setting up baseline group access, enforcing MFA for a pilot group, updating access during user lifecycle changes, limiting privileged access, and reviewing group membership for least privilege.

## Lab environment

The lab uses a Microsoft Entra ID tenant named **Northstar Identity Lab**.

The environment includes fictional users, departments, and security groups to model common access governance scenarios across HR, Finance, IT, Conditional Access, privileged access, and access review workflows.

## IAM concepts practiced

* Microsoft Entra ID tenant setup
* User and security group management
* Group-based access assignment
* Least-privilege access review
* Conditional Access and MFA testing
* Joiner, mover, and leaver workflow simulation
* Privileged Identity Management eligible role assignment
* Manual access review simulation
* IAM documentation and evidence collection
* Conceptual mapping to Okta and SailPoint

## Access governance decisions

This lab includes several access governance decisions that map to common IAM support and review work:

* Using a pilot group before enforcing MFA more broadly
* Assigning access through groups instead of individual one-off assignments
* Updating group membership when a user changes roles
* Removing access during the leaver workflow
* Using eligible privileged access instead of standing privileged access
* Reviewing group membership to confirm whether access still matches the user’s role

## Lab walkthrough

| Section                  | Description                                                                               |
| ------------------------ | ----------------------------------------------------------------------------------------- |
| Lab overview             | Defines the project purpose, scope, and lab environment                                   |
| Tenant setup             | Documents the Microsoft 365 and Microsoft Entra lab environment                           |
| Users and groups         | Documents fictional users, department groups, and group-based access assignments          |
| Conditional Access       | Documents MFA policy configuration, pilot group scoping, and sign-in testing              |
| JML workflows            | Simulates joiner, mover, and leaver lifecycle workflows                                   |
| Admin roles and PIM      | Documents eligible privileged access using Microsoft Entra Privileged Identity Management |
| Access review simulation | Reviews group membership and validates access cleanup                                     |
| Concept mapping          | Maps Entra ID lab concepts to Okta and SailPoint at a high level                          |

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

## Evidence collected

Screenshots are organized by lab section in the `screenshots/` folder.

Evidence includes Microsoft Entra tenant setup, fictional users, department groups, Conditional Access configuration, MFA testing, lifecycle workflow changes, PIM eligible access, and manual access review results.

## Project takeaways

This lab helped reinforce that IAM governance is not only about creating users and assigning groups. Access also needs to be tested, reviewed, adjusted when roles change, and removed when it is no longer needed.

The biggest takeaway from this project was that least privilege is an ongoing process. It applies during onboarding, role changes, offboarding, privileged access assignment, and access reviews.

## Project status

Complete.

This lab includes Microsoft Entra setup, group-based access, Conditional Access testing, lifecycle workflow simulation, eligible privileged access, manual access review documentation, and conceptual Okta/SailPoint mapping.

## Scope notes

This lab was built hands-on in Microsoft Entra ID only. Okta and SailPoint were not configured or integrated.

Okta and SailPoint are referenced only as conceptual comparisons. This lab uses fictional users, groups, and screenshots from a test tenant and does not include production data, automated provisioning, or live third-party IAM integrations.
