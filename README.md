# Abdisalam Abdirahman

I'm working toward IAM Support / IAM Engineer / PAM / Okta IAM roles. I don't just say I know this stuff. Every lab below has screenshots of the actual work, the things that broke, and how I fixed them.

The job, the way I see it: give people the access the ticket asks for, put MFA in front of it, and take it away when they're done.

## Labs (proof first)
- **[CyberArk PAM 12.6](https://github.com/salamraghe/cyberark-pam-lab)**: Onboarded a Domain Admin service account into a safe, had a requester ask and an approver sign off (dual control), had CPM rotate the password, opened a recorded PSM session, then removed the requester's access.
- **[Okta SSO / MFA](https://github.com/salamraghe/okta-sso-mfa)**: Created a test user, put them in an app group, required MFA for the SAML app, proved SSO into a demo SP, then revoked access by removing group membership.
- **[Microsoft Entra ID](https://github.com/salamraghe/entra-iam-lab)**: Users, groups, P2 licensing, Conditional Access MFA on a security group, a leaver offboard, SAML SSO, and OIDC (jwt.ms) in a real tenant.
- **[AD user lifecycle](https://github.com/salamraghe/ad-user-lifecycle)**: On a Windows Server 2022 DC, created users, assigned group access, disabled a leaver, and documented membership.

## Contact
Reach me here on GitHub.
