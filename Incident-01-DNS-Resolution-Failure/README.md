# Incident 01 - DNS Resolution Failure

## Scenario
## Baseline Checks

Before introducing the fault, I confirmed that the Windows 11 virtual machine had normal network connectivity and working DNS resolution.

- `ipconfig /all` showed the device had a valid IPv4 address, default gateway and DNS servers.
- `ping 8.8.8.8` confirmed external IP connectivity.
- `nslookup google.com` successfully resolved the hostname using DNS server `1.1.1.1`.
- ![Baseline IP configuration](screenshots/01-baseline-ipconfig.png)
- The baseline configuration showed a valid IPv4 address, default gateway, DHCP configuration and working DNS servers (`1.1.1.1` and `9.9.9.9`).
- ![Baseline DNS resolution](screenshots/02-baseline-dns-resolution.png)
- `nslookup google.com` successfully resolved the domain using DNS server `1.1.1.1`, confirming that DNS resolution was functioning correctly before the fault was introduced.

A Windows 11 user reports that the device appears connected to the network, but websites and other services that rely on domain names are not working.
