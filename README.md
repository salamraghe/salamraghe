# Abdisalam Abdirahman

I'm working toward IAM Support / IAM Engineer / PAM / Okta IAM roles. Every lab below has screenshots of the real work, what broke, and how I fixed it.

How I see the job: give people the access the ticket asks for, put MFA or an approver in front of it, and take it away when they're done.

Portfolio: https://salamraghe.github.io/

## Labs (proof first)

**Privileged access**
- **[CyberArk PAM 12.6](https://github.com/salamraghe/cyberark-pam-lab)** (Oct 2026): I put a Domain Admin account in a safe with dual control (requester asks with a ticket, approver signs off), had CPM rotate the password, recorded a PSM session, then removed the requester's access.
- **[Entra PIM](https://github.com/salamraghe/entra-pim)** (Oct 2026): I made a user only eligible for User Administrator. To use it they needed MFA, a reason and my approval, and it expired after 1 hour. Every step is in the audit log.

**Cloud identity (Microsoft Entra ID)**
- **[Entra IAM lab](https://github.com/salamraghe/entra-iam-lab)** (Sep 2026): I set up users, groups, P2 licensing, Conditional Access MFA on a group, a leaver offboard, SAML SSO and OIDC.
- **[Entra access review](https://github.com/salamraghe/entra-access-review)** (Oct 2026): I reviewed a group, denied an inactive user with a reason, and auto-apply removed them.
- **[Entra SCIM provisioning](https://github.com/salamraghe/entra-scim-provisioning)** (Oct 2026): I assigned a user in Entra and Entra built their account in a SCIM test app by itself. Leaver step is partial: Entra shows IsActive False, but app-side deactivation isn't shown.
- **[ServiceNow identity tickets](https://github.com/salamraghe/servicenow-identity-tickets)** (Oct 2026): I worked joiner, mover and leaver tickets in ServiceNow, did each change in Entra ID, and closed them with work notes and resolution notes.

**SSO / MFA**
- **[Okta SSO / MFA](https://github.com/salamraghe/okta-sso-mfa)** (Sep 2026): I gave a test user a SAML app through a group, required MFA, proved SSO, then removed the group and the app disappeared.

**On-prem directory**
- **[AD user lifecycle](https://github.com/salamraghe/ad-user-lifecycle)** (Sep–Oct 2026): On a Windows Server 2022 DC, I created users, gave group access, moved a user to a new group, and disabled a leaver.
- **[PowerShell joiner/mover/leaver](https://github.com/salamraghe/powershell-jml)** (Oct 2026): My scripts build, move and disable AD users from CSV files, with every result checked in AD.
- **[LLDAP least privilege](https://github.com/salamraghe/cyberky-lldap-least-privilege)** (Sep 2026): I put an analyst in a read-only group and signed in as him to prove he had no admin rights.

## Contact
Reach me here on GitHub.
