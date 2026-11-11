# Active Directory Group Policy Management

## 1. Project Overview

This exercise demonstrates Group Policy Management in a Windows Server 2022 Active Directory environment.

Group Policy allows administrators to centrally configure and manage user and computer settings across domain-joined systems.

## 2. Lab Environment

| Component | Details |
|---|---|
| Operating System | Windows Server 2022 |
| Virtualization | VMware |
| Directory Service | Active Directory Domain Services |
| Management Tool | Group Policy Management Console |
| Organizational Unit | IT-Department |

## 3. Scenario

The IT department needs to apply a standardized desktop configuration to users in the IT-Department OU.

The administrator creates and links a Group Policy Object to the relevant Organizational Unit.

## 4. Practical Tasks

### Task 1: Open Group Policy Management

1. Open Server Manager.
2. Navigate to Tools.
3. Select Group Policy Management.
4. Expand Forest and Domains.
5. Locate the required domain.

### Task 2: Create a Group Policy Object

1. Locate the IT-Department OU.
2. Right-click the OU.
3. Select Create a GPO in this domain, and Link it here.
4. Enter the GPO name: IT-Department-Desktop-Policy.
5. Click OK.

### Task 3: Configure a Desktop Policy

1. Right-click the newly created GPO.
2. Select Edit.
3. Navigate to User Configuration.
4. Open Policies.
5. Select Administrative Templates.
6. Navigate to Desktop settings.
7. Configure the Desktop Wallpaper policy.
8. Apply the configuration.

### Task 4: Update Group Policy

On a domain-joined Windows client, open Command Prompt and run:

```cmd
gpupdate /force
```

### Task 5: Verify Group Policy

Run:

```cmd
gpresult /r
```

Review the applied Group Policy Objects and verify that the intended policy is listed.

## 5. Expected Result

The Group Policy Object should be created and linked to the intended Organizational Unit.

The configured policy should apply to eligible domain users or computers according to its configuration and scope.

## 6. IT Support Best Practices

- Test policies in a dedicated lab OU before production deployment.
- Apply policies only to intended users and computers.
- Understand the difference between User Configuration and Computer Configuration.
- Verify policy application using gpresult.
- Document policy changes.
- Avoid applying restrictive policies to production systems without authorization.

## 7. Skills Practiced

- Group Policy Management
- Group Policy Object Creation
- Organizational Unit Management
- Windows Server Administration
- Domain Policy Troubleshooting
- Command-Line Administration

## 8. Learning Outcome

Learned the fundamentals of creating, linking, configuring, updating, and verifying Group Policy Objects in an Active Directory environment.

## 9. Screenshots

Screenshots from the VMware home lab will be uploaded after completing the practical exercises.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Server | Active Directory

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical configuration and verification to be confirmed.
