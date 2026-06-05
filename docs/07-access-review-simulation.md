# Access review simulation

## Goal

This section documents a manual access review simulation in Microsoft Entra ID.

The goal was to practice reviewing group-based access, validating whether access still matched user roles, and documenting cleanup actions after lifecycle changes.

## Scenario

The lab uses security group membership as the access review target.

The review focuses on whether users still have appropriate group access after joiner, mover, and leaver workflow changes.

## Review approach

| Review item | Purpose |
|---|---|
| Group membership | Confirm who has access through each security group |
| User role and department | Validate whether access matches current job function |
| Leaver cleanup | Confirm disabled users no longer retain group-based access |
| Mover cleanup | Confirm users who changed roles no longer retain old department access |

## Review findings

| User | Review result |
|---|---|
| Jordan Lee | Access updated from IT support access to Finance analyst access after mover workflow |
| Ava Patel | Account disabled and group-based access removed after leaver workflow |
| Marcus Chen | Finance access retained based on Finance Analyst role |

## IAM concepts demonstrated

- Manual access review
- Group membership validation
- Least-privilege review
- Access cleanup verification
- Joiner, mover, and leaver validation
- Evidence-based access governance documentation

## Evidence

Screenshots for this section are stored in:

`screenshots/06-access-review-simulation/`

Included evidence:

- Finance group membership reviewed
- Ava Patel access removal validated
