# Conditional Access and MFA

## Goal

This section documents how Conditional Access was used to require multifactor authentication for a pilot group in Microsoft Entra ID.

The goal was to practice a common IAM control: requiring MFA for selected users before expanding the policy more broadly.

## Policy approach

The lab uses a pilot group to test MFA enforcement before applying the policy to a larger user population.

| Item | Value |
|---|---|
| Policy name | CA001-Require-MFA-Pilot-Users |
| Pilot group | SG-CA-MFA-Pilot |
| Target resources | All cloud apps |
| Grant control | Require multifactor authentication |
| Initial testing mode | Report-only |
| Final state | On |

## Why a pilot group was used

A pilot group allows an IAM team to test Conditional Access behavior with a small set of users before broader rollout.

This reduces the risk of accidentally locking out users or applying an authentication requirement before it has been validated.

## IAM concepts demonstrated

- Conditional Access policy configuration
- MFA enforcement
- Pilot group testing
- Report-only policy validation
- Group-scoped policy assignment
- Authentication control testing
- Evidence-based IAM documentation

## Evidence

Screenshots for this section are stored in:

`screenshots/03-conditional-access/`

Included evidence:

- MFA pilot group created
- Conditional Access policy scoped to the MFA pilot group
- MFA grant control configured
- Conditional Access policy enabled
- Pilot user MFA sign-in activity reviewed
