# Active Directory – Enable and Disable User Accounts

## 1. Project Overview

This exercise demonstrates how to enable and disable user accounts using Active Directory Users and Computers (ADUC) in a Windows Server 2022 environment.

Managing user account status is an important responsibility of IT Support, Service Desk, and System Administration teams.

## 2. Lab Environment

| Component | Technology |
|---|---|
| Virtualization | VMware Workstation |
| Operating System | Windows Server 2022 |
| Directory Service | Active Directory Domain Services (AD DS) |
| Management Tool | Active Directory Users and Computers |
| Test Environment | IT-Department Organizational Unit |

## 3. Scenario 1 – Disable a User Account

**Business Scenario:**

An employee has left the organization. The HR department submits an approved request to disable the employee's account to prevent further access.

### Procedure

1. Open Server Manager.
2. Navigate to Tools → Active Directory Users and Computers.
3. Expand the domain.
4. Navigate to the IT-Department OU.
5. Locate the test user account.
6. Right-click the account.
7. Select Disable Account.
8. Confirm the operation.
9. Verify that the account is disabled.

### Expected Result

The user account becomes disabled, preventing new Active Directory authentication using that account.

Disabling an account does not necessarily terminate all existing application sessions or revoke cloud authentication tokens.

## 4. Scenario 2 – Enable a User Account

**Business Scenario:**

An employee returns from extended leave, and the IT department receives an approved request to reactivate the account.

### Procedure

1. Open Active Directory Users and Computers.
2. Navigate to the IT-Department OU.
3. Locate the disabled user account.
4. Right-click the account.
5. Select Enable Account.
6. Confirm the operation.
7. Verify that the account is enabled.

### Expected Result

The user account becomes enabled and can authenticate if the credentials, password status, and other access requirements are valid.

## 5. Service Desk Best Practices

- Verify the user's identity and authorization.
- Obtain the required approval before changing account status.
- Follow organizational onboarding and offboarding policies.
- Never disable administrator or production accounts during lab practice.
- Record the account changes in the ITSM ticket.
- Verify the final account status.
- Escalate unexpected authentication problems.

## 6. Example ServiceNow Incident / Service Request

**Ticket Type:** Service Request

**Short Description:** Disable Active Directory user account

**Description:** Authorized request received to disable a user account.

**Category:** User Account Management

**Assignment Group:** IT Service Desk

**Work Notes:**

- Verified the account and request authorization.
- Located the user in Active Directory.
- Disabled the account.
- Confirmed the account status.

**Resolution:** User account disabled successfully.

**Ticket Status:** Resolved

*This is a simulated service request for portfolio demonstration.*

## 7. Skills Demonstrated

- Active Directory User Administration
- User Account Enable and Disable Operations
- Identity and Access Management
- Employee Onboarding and Offboarding
- Service Request Handling
- IT Security Best Practices
- Windows Server 2022 Administration

## 8. Learning Outcome

This exercise explains the process of enabling and disabling Active Directory user accounts and how these operations support secure user access management.

## 9. Screenshots

Screenshots from the VMware home lab will be added after practical verification.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Server | Active Directory

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical results to be confirmed.
