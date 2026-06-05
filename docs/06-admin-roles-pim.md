# Admin roles and Privileged Identity Management

## Goal

This section documents how privileged access was reviewed and assigned in Microsoft Entra ID.

The goal was to practice least-privilege administration by avoiding unnecessary standing admin access and using Privileged Identity Management where available.

## Scenario

Jordan Lee represents an IT support user who may need limited privileged access for administrative support tasks.

Instead of assigning broad standing administrator access, the lab uses an eligible role assignment through Privileged Identity Management.

## Role assignment

| User | Role | Assignment type | Purpose |
|---|---|---|---|
| Jordan Lee | Privileged Role Administrator | Eligible | Simulate controlled privileged access for role management tasks |

## Why eligible access was used

Eligible access supports just-in-time privileged access.

This reduces the risk of users having permanent access to sensitive administrative roles when the access is only needed for specific tasks.

## IAM concepts demonstrated

- Least-privilege administration
- Privileged access management
- Privileged Identity Management
- Eligible role assignment
- Just-in-time access concept
- Administrative role review
- Audit-friendly privileged access documentation

## Evidence

Screenshots for this section are stored in:

`screenshots/05-admin-roles-pim/`

Included evidence:

- Privileged Role Administrator role reviewed
- Role description reviewed before assignment
- Privileged Identity Management assignments page reviewed
- Jordan Lee assigned eligible Privileged Role Administrator access

Included evidence:

- Privileged Role Administrator role reviewed
- PIM assignment page reviewed
- Jordan Lee assigned eligible privileged role access
