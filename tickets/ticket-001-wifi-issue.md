# Ticket 001: WiFi Connectivity Issue

## Issue
User reports they cannot connect to WiFi.

## Environment
- Windows 10 laptop
- Home network

## Troubleshooting Steps
1. Checked if WiFi is enabled
2. Verified correct network selected
3. Ran ipconfig to check IP address
4. Renewed IP using ipconfig /release and /renew
5. Restarted router

## Findings
Device was not receiving a valid IP address.

## Resolution
Reset the router and renewed the IP address. Connection restored.

## Key Takeaways
DHCP issues can prevent devices from obtaining valid network connectivity.
