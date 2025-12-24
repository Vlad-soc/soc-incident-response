# Incident: Brute Force Attack

## Incident Type
Credential Attack (Brute Force)

## Detection
Multiple failed login attempts detected followed by a successful login.

## Investigation
- Analyzed Windows Event ID 4625 (failed logon)
- Reviewed Event ID 4624 (successful logon)
- Checked source IP address and login pattern

## Conclusion
The activity was identified as a brute-force attack.

## Response Actions
- Blocked source IP
- Forced password reset
- Incident documented and escalated
