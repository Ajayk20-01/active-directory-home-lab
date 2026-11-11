# Active Directory Account Unlock

## 1. Project Overview

This exercise covers the process of unlocking a locked user account using Active Directory Users and Computers (ADUC) in Windows Server 2022.

Account lockouts can occur when users enter incorrect passwords multiple times or when applications and devices continue using outdated credentials.

## 2. Lab Environment

| Component | Details |
|---|---|
| Operating System | Windows Server 2022 |
| Virtualization | VMware |
| Directory Service | Active Directory Domain Services |
| Management Tool | Active Directory Users and Computers |
| Test Account | Lab Test User |

## 3. Scenario

A user contacts the IT Service Desk and reports:

"My Windows account is locked, and I cannot log in."

The IT Support Engineer investigates the issue and unlocks the account after verifying the user's identity.

## 4. Account Unlock Procedure

1. Logged in to Windows Server 2022.
2. Opened Server Manager.
3. Navigated to Tools.
4. Opened Active Directory Users and Computers.
5. Expanded the domain.
6. Located the IT-Department Organizational Unit.
7. Right-clicked the affected test user.
8. Selected Properties.
9. Opened the Account tab.
10. Selected Unlock account, when the account was locked.
11. Clicked Apply and OK.

## 5. Expected Result

The user account should be unlocked successfully.

The user can then attempt to sign in again, provided there are no other account or authentication issues.

## 6. IT Support Best Practices

- Verify the user's identity before unlocking an account.
- Check the reason for repeated account lockouts.
- Investigate outdated saved credentials where appropriate.
- Follow company security policies.
- Document the resolution in the service desk ticket.

## 7. Skills Practiced

- Active Directory Administration
- User Account Management
- Account Lockout Troubleshooting
- Windows Server 2022
- Service Desk Support

## 8. Learning Outcome

Understood how to identify and unlock locked Active Directory user accounts and learned the importance of investigating recurring account lockouts.

## Author

**Ajay Kammari**

GitHub: https://github.com/Ajayk20-01

---

Note: Update this documentation with your actual lab results after completing the exercise.
