# DNS and DHCP Troubleshooting – IT Support Home Lab

## 1. Project Overview

This exercise covers basic DNS and DHCP concepts and troubleshooting techniques in a Windows Server 2022 environment.

DNS and DHCP are important network services used in corporate IT infrastructure.

## 2. Lab Environment

| Component | Details |
|---|---|
| Virtualization | VMware |
| Server OS | Windows Server 2022 |
| Client OS | Windows 10/11 |
| Network Services | DNS and DHCP |
| Directory Service | Active Directory |

## 3. Understanding DNS

Domain Name System (DNS) translates domain names into IP addresses.

DNS is essential in Active Directory because domain-joined computers use DNS to locate Domain Controllers and other domain services.

### DNS Troubleshooting Commands

Check network configuration:

```cmd
ipconfig /all
```

Test connectivity to the Domain Controller:

```cmd
ping <Domain-Controller-IP>
```

Check DNS resolution:

```cmd
nslookup <domain-name>
```

Display DNS cache:

```cmd
ipconfig /displaydns
```

Clear DNS cache:

```cmd
ipconfig /flushdns
```

## 4. Understanding DHCP

Dynamic Host Configuration Protocol (DHCP) automatically assigns network configuration to client devices.

DHCP can provide:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server Address

### DHCP Troubleshooting Commands

Release the current DHCP lease:

```cmd
ipconfig /release
```

Request a new DHCP lease:

```cmd
ipconfig /renew
```

Check assigned network configuration:

```cmd
ipconfig /all
```

These commands should be used only when the client is configured for DHCP.

## 5. Common Network Issues

| Issue | Possible Cause | Troubleshooting |
|---|---|---|
| No network connectivity | Incorrect IP configuration | Check ipconfig /all |
| Domain cannot be located | DNS configuration issue | Check nslookup |
| APIPA address | DHCP server unavailable | Check DHCP connectivity |
| DNS resolution failure | Incorrect DNS settings | Flush DNS and test resolution |
| Cannot reach server | Network connectivity issue | Test ping and routing |

## 6. IT Support Troubleshooting Process

1. Identify the user's network problem.
2. Check the computer's IP configuration.
3. Verify the default gateway and DNS server.
4. Test connectivity to the Domain Controller.
5. Perform DNS resolution tests.
6. Check DHCP configuration if applicable.
7. Identify the root cause.
8. Apply the appropriate resolution.
9. Verify connectivity.
10. Document the incident and resolution.

## 7. Skills Practiced

- DNS Fundamentals
- DHCP Fundamentals
- IP Configuration
- Network Connectivity Troubleshooting
- Command Prompt Administration
- Windows Server 2022
- IT Service Desk Troubleshooting

## 8. Learning Outcome

Developed an understanding of DNS and DHCP services and learned basic command-line techniques for investigating network connectivity and name resolution issues.

## 9. Screenshots

Screenshots from the VMware home lab will be added after completing the practical exercises.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Server | Active Directory | Networking

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical configuration and troubleshooting results to be verified.
