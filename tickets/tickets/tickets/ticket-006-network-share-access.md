# Ticket 006: Unable to Access Network Shared Folder

## Issue
User reports they are unable to access a shared network folder. An error appears when attempting to open the shared drive.

## Environment
- Windows 10 workstation
- Corporate network
- Shared folder hosted on file server

## Troubleshooting Steps
1. Verified network connectivity by pinging the file server
2. Confirmed the shared folder path was correct
3. Checked user permissions for the shared folder
4. Attempted access using the server IP address instead of hostname
5. Verified user credentials and login status
6. Restarted the workstation to clear cached sessions
7. Tested access from another user account

## Findings
User account did not have the correct permissions to access the shared folder.

## Resolution
Updated the user’s permissions on the shared folder. Access was restored successfully.

## Key Takeaways
Access issues are often related to permissions or authentication rather than network connectivity. Verifying access rights is a critical troubleshooting step.

## Customer Communication
Explained that access was restricted due to permissions and confirmed that the issue was resolved after updating access rights.
