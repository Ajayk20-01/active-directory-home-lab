# Active Directory Password Reset

## 1. Project Overview

This exercise demonstrates how to reset a user's password using Active Directory Users and Computers (ADUC) in Windows Server 2022.

Password resets are one of the common responsibilities of an IT Support and Service Desk Engineer.

## 2. Lab Environment

| Component | Details |
|---|---|
| Operating System | Windows Server 2022 |
| Virtualization | VMware |
| Directory Service | Active Directory Domain Services |
| Management Tool | Active Directory Users and Computers |
| User Account | Lab Test User |

## 3. Scenario

A user contacts the IT Service Desk and reports that they have forgotten their Windows login password and cannot access their account.

The IT Support Engineer needs to reset the user's password through Active Directory.

## 4. Steps Performed

1. Logged in to Windows Server 2022.
2. Opened Server Manager.
3. Navigated to Tools.
4. Opened Active Directory Users and Computers.
5. Expanded the domain.
6. Located the IT-Department Organizational Unit.
7. Selected the test user account.
8. Right-clicked the user account.
9. Selected Reset Password.
10. Entered and confirmed a new temporary lab password.
11. Selected the option requiring the user to change the password at next logon, where appropriate.
12. Confirmed the password reset operation.

## 5. Expected Result

The password reset operation should complete successfully, with a confirmation message displayed by Active Directory Users and Computers.

## 6. IT Support Best Practices

- Verify the user's identity before resetting a password.
- Follow the organization's password policy.
- Never share passwords through insecure channels.
- Use temporary passwords according to company procedures.
- Document the action in the service desk ticket.
- Confirm that the user can access their account.

## 7. Skills Practiced

- Active Directory User Administration
- Password Reset Management
- Windows Server 2022
- Active Directory Users and Computers
- Service Desk Support
- User Account Troubleshooting

## 8. Learning Outcome

Learned the password reset workflow in Active Directory and understood how IT Support Engineers assist users with login and password-related issues.

## Author

**Ajay Kammari**

GitHub: https://github.com/Ajayk20-01

---

*Note: This documentation describes the lab procedure. Mark the exercise as completed only after successfully performing and verifying the password reset.*
