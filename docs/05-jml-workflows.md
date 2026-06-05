# Joiner, mover, and leaver workflows

## Goal

This section documents a simulated joiner, mover, and leaver workflow in Microsoft Entra ID.

The goal was to practice common identity lifecycle tasks that IAM teams support when users join the organization, change roles, or leave the organization.

## Workflow scenarios

| Workflow | Scenario | IAM action |
|---|---|---|
| Joiner | A new user needs baseline and role-based access | Create or validate user profile and assign appropriate groups |
| Mover | A user changes departments or job role | Update user attributes and adjust group membership |
| Leaver | A user leaves the organization | Disable the account and remove group-based access |

## Joiner workflow

The joiner workflow validates that a user has the correct profile details and group memberships for their role.

Expected access:

- Baseline employee access through `SG-All-Employees`
- Department-specific access based on job role

## Mover workflow

The mover workflow simulates a role or department change.

The user profile is updated to reflect the new role, and group membership is changed so access aligns with the new job function.

## Leaver workflow

The leaver workflow simulates access cleanup after a user leaves the organization.

The account is disabled and group memberships are removed to reduce the risk of orphaned access.

## IAM concepts demonstrated

- Identity lifecycle management
- Joiner, mover, and leaver workflows
- User attribute updates
- Group-based access changes
- Least-privilege access cleanup
- Disabled account validation
- Audit-friendly lifecycle documentation

## Evidence

Screenshots for this section are stored in:

`screenshots/04-jml-workflows/`

Included evidence:

- Jordan Lee joiner profile reviewed with IT role and department details
- Jordan Lee joiner group access reviewed
- Jordan Lee mover profile updated from IT to Finance
- Jordan Lee mover group access updated from IT support access to Finance analyst access
- Ava Patel leaver account disabled
- Ava Patel group-based access removed
- Leaver group access removed
