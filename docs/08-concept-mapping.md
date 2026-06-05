# Concept mapping: Okta and SailPoint

## Goal

This section maps the Microsoft Entra ID lab concepts to similar identity and access management concepts in Okta and SailPoint.

Okta and SailPoint were not configured or integrated in this lab. These mappings are included only to show how IAM concepts may translate across different identity platforms.

## Platform scope

| Platform           | Scope in this lab                   |
| ------------------ | ----------------------------------- |
| Microsoft Entra ID | Hands-on configuration and evidence |
| Okta               | Conceptual comparison only          |
| SailPoint          | Conceptual comparison only          |

## Concept mapping

| IAM concept               | Microsoft Entra ID lab example                                   | Okta concept                               | SailPoint concept                                        |
| ------------------------- | ---------------------------------------------------------------- | ------------------------------------------ | -------------------------------------------------------- |
| User identity             | Test users such as Ava Patel, Marcus Chen, and Jordan Lee        | Users                                      | Identities                                               |
| Group-based access        | Security groups such as SG-All-Employees and SG-Finance-Analysts | Groups and app assignments                 | Entitlements, access profiles, or roles                  |
| Role-based access control | Department-based group assignments                               | Group-based app access                     | Role or access profile assignment                        |
| MFA enforcement           | Conditional Access policy requiring MFA                          | Sign-on policy or MFA policy               | Access governance control concept                        |
| Joiner workflow           | User profile created and baseline group access assigned          | Lifecycle automation or group assignment   | Identity lifecycle event and birthright access           |
| Mover workflow            | User profile updated and group membership changed                | Profile/group updates                      | Access change based on identity attribute or role change |
| Leaver workflow           | Account disabled and group access removed                        | User deactivation and app access removal   | Identity termination and access revocation               |
| Privileged access         | PIM eligible role assignment                                     | Admin role assignment concept              | Privileged access governance concept                     |
| Access review             | Manual group membership review                                   | Group or application access review concept | Certification campaign or access review                  |

## Key takeaway

The hands-on work in this lab was completed in Microsoft Entra ID.

The Okta and SailPoint mappings are included to show broader IAM understanding, but they are not presented as live configuration evidence.
