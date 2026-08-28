# Incident 01 - DNS Resolution Failure

## Scenario
## Baseline Checks

Before introducing the fault, I confirmed that the Windows 11 virtual machine had normal network connectivity and working DNS resolution.

- `ipconfig /all` showed the device had a valid IPv4 address, default gateway and DNS servers.
- `ping 8.8.8.8` confirmed external IP connectivity.
- `nslookup google.com` successfully resolved the hostname using DNS server `1.1.1.1`.

A Windows 11 user reports that the device appears connected to the network, but websites and other services that rely on domain names are not working.
