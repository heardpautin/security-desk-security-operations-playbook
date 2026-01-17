# MFA Incident Handling – Secure Approach

## Guiding Principle
MFA issues are **identity assurance problems**, not convenience problems.

Disabling MFA is **never a first response**.

---

## Common User Statement
"I can't log in because of MFA."

---

## Analyst Response Logic
1. Confirm identity using approved verification steps
2. Identify the failure mode:
   - device change
   - authenticator app issue
   - network or token desync
3. Review recent access history (if available)
4. Determine if issue is:
   - user error
   - device issue
   - policy enforcement

---

## What the Analyst Does NOT Do
- Disable MFA to “get the user in”
- Bypass security policy
- Make privileged identity changes

---

## Escalation
If MFA reset is required:
- escalate to IAM or security team
- document justification
- ensure approvals are recorded

---

## Security & Compliance Tie-In
This approach supports:
- Zero Trust principles
- IAM governance
- audit defensibility
