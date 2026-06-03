# Users and groups

## Goal

This section documents the fictional users and role-based security groups created in Microsoft Entra ID.

The goal was to model a small organization where users receive access through group membership instead of direct one-off assignments.

## Test users

| User | Department | Role |
|---|---|---|
| Ava Patel | Human Resources | HR Analyst |
| Marcus Chen | Finance | Finance Analyst |
| Jordan Lee | IT | IT Support Specialist |

## Security groups

| Group | Purpose |
|---|---|
| SG-All-Employees | Baseline employee access |
| SG-HR-Analysts | HR role-based access |
| SG-Finance-Analysts | Finance role-based access |
| SG-IT-Support | IT support role-based access |

## Access model

The lab uses group-based access assignment to support least privilege.

Users are assigned to a baseline employee group and a department-specific group based on their role. This makes access easier to review, update, and remove during joiner, mover, and leaver workflows.

## IAM concepts demonstrated

- User provisioning
- Security group creation
- Role-based access control
- Group-based access assignment
- Least-privilege access model
- Department-based access design
- Audit-friendly access documentation

## Evidence

Screenshots for this section are stored in:

`screenshots/02-users-and-groups/`

Included evidence:

- Role-based security groups created
- Test users created
- Baseline group membership assigned
- Department-specific group membership assigned
