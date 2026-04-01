# Ticket 004: DNS Resolution Issue

## Issue
User reports that they are unable to access websites using domain names, but can successfully access sites using IP addresses.

## Environment
- Windows 10 desktop
- Home network
- Wired Ethernet connection

## Troubleshooting Steps
1. Verified network connectivity by pinging a known IP address (8.8.8.8)
2. Attempted to ping a domain name (google.com) and observed failure
3. Used nslookup to test DNS resolution
4. Flushed DNS cache using ipconfig /flushdns
5. Restarted the DNS Client service
6. Changed DNS server settings to a public DNS (8.8.8.8 and 8.8.4.4)
7. Restarted the computer to apply changes

## Findings
The system was unable to resolve domain names due to a misconfigured or unresponsive DNS server.

## Resolution
Updated the DNS server settings to a reliable public DNS server. DNS resolution was restored and websites loaded normally.

## Key Takeaways
DNS issues can prevent access to websites even when network connectivity is functional. Verifying IP connectivity helps isolate DNS problems quickly.

## Customer Communication
Explained the issue in simple terms, clarifying that the internet connection was working but the system could not translate website names into IP addresses.

## Additional Commands Used
- ipconfig /all
- nslookup google.com
- ping 8.8.8.8
