# Incident Report

## Incident Summary

Multiple failed login attempts were detected against a Windows workstation.

---

## Timeline

| Time | Event |
|------|------|
| 10:00 | Failed Login |
| 10:01 | Failed Login |
| 10:03 | Successful Login |

---

## Evidence

- Windows Event ID 4625
- Windows Event ID 4624

---

## Findings

Unauthorized login attempts originated from the attacker system.

---

## Recommendation

- Reset password
- Disable account
- Enable MFA
- Continue monitoring
