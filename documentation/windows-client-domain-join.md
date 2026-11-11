# Windows Client Domain Join – Active Directory Home Lab

## 1. Project Overview

This exercise demonstrates how to join a Windows 10/11 client computer to an Active Directory domain managed by Windows Server 2022.

Domain joining allows centralized authentication, user management, and Group Policy administration.

## 2. Lab Environment

| Component | Details |
|---|---|
| Virtualization | VMware |
| Server Operating System | Windows Server 2022 |
| Client Operating System | Windows 10/11 |
| Directory Service | Active Directory Domain Services |
| Network | VMware Lab Network |
| DNS Server | Domain Controller IP Address |

## 3. Scenario

A new employee receives a Windows workstation and needs access to the organization's Active Directory environment.

The IT Support Engineer prepares the workstation and joins it to the corporate domain.

## 4. Practical Tasks

### Task 1: Prepare the Network

1. Confirm that the Domain Controller is running.
2. Identify the server's IPv4 address.
3. Connect the Windows client to the appropriate VMware network.
4. Configure the Domain Controller IP as the client's preferred DNS server.
5. Verify network connectivity and DNS resolution.

### Task 2: Join the Windows Client to the Domain

1. Open Windows Settings.
2. Navigate to System → About.
3. Open the domain membership settings.
4. Select the Domain option.
5. Enter the actual Active Directory domain name.
6. Provide authorized domain credentials.
7. Confirm successful domain joining.
8. Restart the Windows client.

### Task 3: Verify Domain Membership

Open Command Prompt and execute:

```cmd
whoami
```

Execute:

```cmd
systeminfo
```

Execute:

```cmd
echo %logonserver%
```

Review the output to verify the logged-in account and domain authentication details.

## 5. Expected Result

The Windows client should successfully join the Active Directory domain and communicate with the Domain Controller.

An authorized domain user should be able to sign in, provided the account and workstation permissions are configured correctly.

## 6. Common Domain Join Issues

| Issue | Possible Cause |
|---|---|
| Domain not found | Incorrect DNS configuration |
| Access denied | Insufficient domain permissions |
| Cannot contact domain | Network connectivity issue |
| Authentication failure | Incorrect credentials |
| Time synchronization error | Client and server time mismatch |

## 7. IT Support Best Practices

- Verify DNS configuration before domain joining.
- Confirm network connectivity.
- Use authorized domain credentials.
- Follow company workstation naming standards.
- Verify domain membership after restarting.
- Document the configuration and resolution.

## 8. Skills Practiced

- Windows Client Administration
- Active Directory Domain Join
- DNS Configuration
- Network Troubleshooting
- Domain Authentication
- Windows 10/11 Support
- VMware Virtualization

## 9. Learning Outcome

Learned the fundamentals of preparing a Windows client, configuring DNS, joining an Active Directory domain, and verifying domain authentication.

## 10. Screenshots

Screenshots from the VMware home lab will be added after completing the practical exercises.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Server | Active Directory

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical domain join and verification to be confirmed.
