# Windows 10/11 Troubleshooting – IT Support Home Lab

## 1. Project Overview

This project demonstrates common Windows 10/11 troubleshooting techniques used by IT Support and Desktop Support Engineers.

The objective is to identify common operating system problems, investigate possible causes, apply appropriate solutions and verify system functionality.

## 2. Lab Environment

| Component | Details |
|---|---|
| Operating System | Windows 10/11 |
| Virtualization | VMware |
| Troubleshooting Tools | Task Manager, Event Viewer, Command Prompt |
| System Repair Tools | SFC and DISM |
| Network Tools | ipconfig, ping |

## 3. Practical Troubleshooting Exercises

### Task 1: System Information

Command:

```cmd
msinfo32
```

Reviewed Windows version, processor, installed memory and system information.

### Task 2: High CPU and Memory Usage

Opened Task Manager using:

```text
Ctrl + Shift + Esc
```

Checked CPU, Memory and Disk utilization and identified applications consuming system resources.

### Task 3: Windows Update Troubleshooting

Navigated to:

Settings → Windows Update

Checked update status and reviewed available updates and installation errors.

### Task 4: System File Checker

Opened Command Prompt as Administrator and executed:

```cmd
sfc /scannow
```

Scanned protected Windows system files and checked whether file integrity issues required repair.

### Task 5: DISM Image Health Check

Executed:

```cmd
DISM /Online /Cleanup-Image /ScanHealth
```

Checked the Windows component store for corruption.

For repair when required:

```cmd
DISM /Online /Cleanup-Image /RestoreHealth
```

### Task 6: Event Viewer Analysis

Opened Event Viewer:

```cmd
eventvwr.msc
```

Navigated to:

Windows Logs → Application

Reviewed application events and errors to understand troubleshooting information.

### Task 7: Network Troubleshooting

Executed:

```cmd
ipconfig /all
```

Checked IP configuration.

```cmd
ping 8.8.8.8
```

Tested connectivity to an external IP address, where internet access was available.

```cmd
nslookup google.com
```

Tested DNS name resolution.

## 4. Common Windows Issues

| Issue | Troubleshooting Approach |
|---|---|
| Slow computer | Check Task Manager |
| Windows update failure | Review update errors |
| Application crash | Inspect Event Viewer |
| Corrupted system files | Run SFC |
| Windows image corruption | Run DISM |
| Network connectivity issue | Check IP, gateway and DNS |
| Printer not printing | Check printer queue and service |

## 5. IT Support Troubleshooting Methodology

1. Identify the user's issue.
2. Gather information about the problem.
3. Identify possible causes.
4. Perform initial troubleshooting.
5. Apply an appropriate solution.
6. Verify that the issue is resolved.
7. Document troubleshooting steps.
8. Escalate unresolved issues when necessary.

## 6. Skills Practiced

- Windows 10/11 Administration
- Desktop Troubleshooting
- Task Manager
- Event Viewer
- System File Checker
- DISM
- Network Troubleshooting
- IT Service Desk Support

## 7. Learning Outcome

Developed an understanding of common Windows operating system issues and learned how to use built-in troubleshooting tools to investigate and resolve problems.

## 8. Screenshots

Screenshots from the practical exercises will be uploaded after completing the lab activities.

## Author

**Ajay Kammari**

IT Support | Service Desk | Windows Administration

GitHub: https://github.com/Ajayk20-01

---

**Lab Status:** Documentation prepared. Practical exercises and results to be verified.
