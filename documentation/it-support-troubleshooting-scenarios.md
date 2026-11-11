# IT Support – Real-World Troubleshooting Scenarios

## 1. Project Overview

This project documents common IT Support and Service Desk troubleshooting scenarios.

The objective is to understand how to identify user issues, investigate root causes, apply solutions and document incident resolutions.

## 2. Troubleshooting Scenarios

### Scenario 1: User Unable to Log In

**Issue:** User cannot log in to Windows.

**Possible Causes:**
- Incorrect password
- Locked account
- Disabled account
- Network connectivity issue

**Troubleshooting:**
1. Verify user identity.
2. Check account status in Active Directory.
3. Check whether the account is locked.
4. Verify network connectivity.
5. Reset the password if authorized and required.

**Resolution:** Document the actual cause and fix.

### Scenario 2: Account Locked

**Issue:** User reports that their account is locked.

**Possible Causes:**
- Multiple incorrect password attempts
- Outdated saved credentials
- Applications using old passwords

**Troubleshooting:**
1. Verify user identity.
2. Locate the account in Active Directory.
3. Check account lockout status.
4. Investigate possible repeated authentication attempts.
5. Unlock the account if authorized.

**Resolution:** Record the account unlock and any underlying cause identified.

### Scenario 3: Outlook Not Working

**Issue:** User cannot send or receive emails.

**Possible Causes:**
- Network connectivity issue
- Outlook profile problem
- Mailbox storage limitation
- Microsoft 365 service issue

**Troubleshooting:**
1. Check internet connectivity.
2. Review Outlook connection status.
3. Check the Outbox.
4. Review mailbox storage.
5. Investigate Outlook profile configuration.

**Resolution:** Document the actual fix.

### Scenario 4: No Internet Connectivity

**Issue:** User cannot access the internet.

**Possible Causes:**
- Incorrect IP configuration
- DNS failure
- Gateway connectivity issue
- Network adapter problem

**Troubleshooting Commands:**

```cmd
ipconfig /all
ping 8.8.8.8
nslookup google.com
```

**Resolution:** Record the identified network problem and fix.

### Scenario 5: Printer Not Printing

**Issue:** User cannot print documents.

**Possible Causes:**
- Printer offline
- Stuck print queue
- Driver issue
- Print Spooler service issue

**Troubleshooting:**
1. Check printer power and connectivity.
2. Verify the default printer.
3. Inspect the print queue.
4. Check printer drivers.
5. Check the Print Spooler service.

**Resolution:** Document the actual printer issue and fix.

### Scenario 6: Computer Running Slowly

**Issue:** User reports poor computer performance.

**Possible Causes:**
- High CPU utilization
- High memory utilization
- Low disk space
- Too many startup applications

**Troubleshooting:**
1. Open Task Manager.
2. Review CPU and memory usage.
3. Check disk utilization.
4. Identify resource-heavy applications.
5. Review available disk space.

**Resolution:** Record the actual cause and corrective action.

### Scenario 7: DNS Resolution Failure

**Issue:** User cannot access resources using domain names.

**Possible Causes:**
- Incorrect DNS server
- DNS service unavailable
- Incorrect DNS records
- Network connectivity issue

**Troubleshooting Commands:**

```cmd
ipconfig /all
nslookup google.com
ipconfig /flushdns
```

For Active Directory, also verify that the client can resolve the actual domain and locate the Domain Controller.

**Resolution:** Document the actual DNS issue and fix.

### Scenario 8: Cannot Access Shared Folder

**Issue:** User cannot access a shared network folder.

**Possible Causes:**
- Incorrect share permissions
- NTFS permission restrictions
- Network connectivity problem
- Incorrect user group membership

**Troubleshooting:**
1. Verify network connectivity.
2. Check the shared folder path.
3. Review share permissions.
4. Review NTFS permissions.
5. Verify user group membership.
6. Confirm the required access authorization.

**Resolution:** Document the actual permission or connectivity issue and fix.

## 3. Standard IT Support Troubleshooting Method

1. Receive and understand the user's issue.
2. Verify user identity where necessary.
3. Gather relevant information.
4. Identify possible causes.
5. Perform initial troubleshooting.
6. Apply an authorized solution.
7. Verify the result with the user.
8. Document the resolution.
9. Escalate unresolved issues.

## 4. Skills Demonstrated

- Active Directory Troubleshooting
- Windows Desktop Support
- Microsoft Outlook Support
- DNS and Network Troubleshooting
- Printer Troubleshooting
- File and Folder Permissions
- Incident Management
- Customer Communication
- Root Cause Investigation

## 5. Learning Outcome

Developed a structured approach to common IT Support problems and learned how to investigate, troubleshoot and document technical issues.

## 6. Practical Evidence

Screenshots and actual lab results will be added after completing and verifying the practical exercises.

## Author

**Ajay Kammari**

IT Support | Service Desk | Desktop Support

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Scenario documentation prepared. Practical results to be verified.
