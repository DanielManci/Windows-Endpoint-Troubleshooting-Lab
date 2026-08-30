# Windows Endpoint Troubleshooting Lab

A practical Windows 11 IT support lab demonstrating structured diagnosis and resolution of common endpoint, networking, permissions, service and performance issues.

The project was created to practise realistic first-line IT support scenarios and document the troubleshooting process from the initial user-reported symptom through diagnosis, root-cause identification, resolution and verification.

## Lab Environment

- Windows 11 virtual machine
- Oracle VirtualBox
- Windows Command Prompt
- PowerShell
- Task Manager
- Device Manager
- Windows Services
- NTFS file permissions

## Troubleshooting Approach

Each incident follows a structured support process:

1. Identify the user-facing symptom.
2. Establish the current system state.
3. Use appropriate Windows diagnostic tools.
4. Isolate the likely cause.
5. Identify the root cause.
6. Apply a targeted resolution.
7. Verify the result from the user's perspective.
8. Document the incident and evidence.

## Incidents

| Incident | Scenario | Key Skills |
|---|---|---|
| [Incident 01 - DNS Resolution Failure](./Incident-01-DNS-Resolution-Failure) | Windows had IP connectivity but could not resolve domain names | DNS, TCP/IP, `ipconfig`, `ping`, `nslookup` |
| [Incident 02 - Print Spooler Service Failure](./Incident-02-Windows-Service-Failure) | Available printers disappeared because the Print Spooler service was stopped | Windows Services, `sc query`, printing troubleshooting |
| [Incident 03 - System Performance Issue](./Incident-03-System-Performance-Issue) | High CPU utilisation caused degraded Windows performance | Task Manager, PowerShell, process analysis, CPU troubleshooting |
| [Incident 04 - File Permissions Access Issue](./Incident-04-File-Permissions-Issue) | A user could not access a required folder because of incorrect NTFS permissions | User accounts, NTFS permissions, access control, least privilege |
| [Incident 05 - Network Adapter Connectivity Issue](./Incident-05-Network-Adapter-Issue) | Windows lost network connectivity because the network adapter was disabled | Device Manager, network adapters, Device Manager Code 22, `ipconfig` |

## Skills Demonstrated

- Windows 11 endpoint troubleshooting
- Structured fault diagnosis
- Root-cause analysis
- TCP/IP and DNS troubleshooting
- Windows Services management
- Printer troubleshooting
- CPU and process analysis
- PowerShell and Command Prompt
- Device Manager diagnostics
- Local user and NTFS permission management
- Principle of least privilege
- Resolution verification
- Technical incident documentation

## Project Evidence

Each incident contains screenshots showing key stages of the troubleshooting process, including the initial symptom, diagnostic findings, identified root cause and successful resolution.

## Project Context

These incidents were reproduced in a controlled Windows 11 virtual lab environment for practical IT support training. They represent simulated support scenarios rather than incidents handled in a production organisation.
