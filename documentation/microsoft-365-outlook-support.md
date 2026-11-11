# Microsoft 365 and Outlook Troubleshooting

## 1. Project Overview

This project covers common Microsoft 365 and Outlook troubleshooting scenarios encountered by IT Support and Service Desk Engineers.

The objective is to understand email troubleshooting, account access, Outlook configuration, MFA and Microsoft 365 support procedures.

## 2. Technologies Covered

| Technology | Purpose |
|---|---|
| Microsoft 365 | Productivity and collaboration |
| Microsoft Outlook | Email and calendar management |
| Exchange Online | Cloud email service |
| Microsoft Entra ID | Identity and access management |
| MFA | Multi-factor authentication |
| OneDrive | Cloud file storage |
| Microsoft Teams | Communication and collaboration |

## 3. Common Outlook Troubleshooting Scenarios

### Scenario 1: Outlook Not Opening

Troubleshooting steps:

1. Check whether Outlook is already running.
2. Open Task Manager.
3. Check for unresponsive Outlook processes.
4. Close the unresponsive process if appropriate.
5. Press Windows + R.
6. Execute:

```text
outlook.exe /safe
```

7. Check whether Outlook opens in Safe Mode.
8. Investigate add-ins or profile issues if necessary.

### Scenario 2: Outlook Not Sending or Receiving Emails

Troubleshooting steps:

1. Verify internet connectivity.
2. Check Outlook connection status.
3. Inspect the Outbox folder.
4. Check mailbox storage limits.
5. Review email account configuration.
6. Check Microsoft 365 service health if authorized.
7. Test email functionality after troubleshooting.

### Scenario 3: Outlook Profile Issues

Troubleshooting steps:

1. Open Control Panel.
2. Select Mail.
3. Click Show Profiles.
4. Review existing Outlook profiles.
5. Create a new test profile if required.
6. Configure the appropriate email account.
7. Test Outlook functionality.

### Scenario 4: Microsoft 365 Sign-In Problems

Possible causes:

- Incorrect credentials.
- Account lockout.
- MFA verification problems.
- Expired password.
- Account access restrictions.
- Application activation issues.

Troubleshooting steps:

1. Confirm the correct username.
2. Check internet connectivity.
3. Verify account status through authorized administrative tools.
4. Investigate MFA issues according to company policy.
5. Check application activation status.
6. Escalate unresolved authentication problems.

## 4. MFA and Identity Management

Multi-Factor Authentication adds another verification step during account sign-in.

IT Support responsibilities include:

- Assisting users with MFA enrollment.
- Troubleshooting verification issues.
- Helping users understand authentication prompts.
- Following identity verification procedures.
- Escalating authentication problems when required.

Never request a user's MFA code or bypass security controls.

## 5. Example Service Desk Ticket

**Ticket Type:** Incident

**Short Description:** Outlook not sending emails.

**Category:** Software / Email

**Description:** User reports that Outlook messages remain in the Outbox.

**Troubleshooting Performed:**

- Checked internet connectivity.
- Reviewed Outlook connection status.
- Inspected the Outbox folder.
- Checked mailbox configuration.

**Resolution:** Record the actual fix after troubleshooting.

**Status:** Resolved only after user confirmation.

*This is a simulated service desk ticket for portfolio practice.*

## 6. IT Support Best Practices

- Verify user identity before account-related changes.
- Never request passwords or MFA codes.
- Protect confidential email information.
- Follow organizational security policies.
- Document troubleshooting activities.
- Escalate issues requiring administrator access.

## 7. Skills Practiced

- Microsoft 365 Support
- Outlook Troubleshooting
- Email Configuration
- Exchange Online Fundamentals
- Microsoft Entra ID Fundamentals
- MFA Troubleshooting
- Service Desk Incident Management
- User Communication

## 8. Learning Outcome

Developed an understanding of common Microsoft 365 and Outlook support scenarios and learned structured troubleshooting approaches for email and account access issues.

## 9. Screenshots

Screenshots from practical exercises will be added after completing the portfolio activities.

## Author

**Ajay Kammari**

IT Support | Service Desk | Microsoft 365 | Outlook | Active Directory

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical exercises to be completed and verified.
