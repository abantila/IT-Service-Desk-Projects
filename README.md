# IT Service Desk Projects

This repository documents IT service desk tickets I completed through ServiceDesk Simulator. Each ticket focuses on a different technical issue and documents how I approached the problem, the troubleshooting steps I performed, and how the issue was resolved.

The purpose of this repository is to document my hands-on practice with IT support, troubleshooting, user account management, hardware, networking, access management, and other common service desk tasks.

---

## Technical Skills & Tools

- **Identity & Access Management:** User account management, authentication troubleshooting, password resets, identity verification, access management

- **Service Desk & Troubleshooting:** Incident troubleshooting and resolution, ticket prioritization, end-user support, technical problem-solving, user communication, resolution verification

> This section will continue to expand as I complete and document more service desk tickets.

---

# Incident Documentation

## Ticket 1: Password Expiration & Login Issue

**Priority:** High  
**Category:** Account Access / Authentication

**Issue:** A user returned from a three-week vacation and was unable to log in to her computer because her password had expired. She was also unable to change the password from the login screen and needed access to her development environment.

**Troubleshooting**
- Located the user's account in the directory and reviewed the authentication settings.
- Initiated identity verification before making changes to the user's account.
- Requested a verification code and received the code from the user through chat.
- Entered the verification code to confirm the user's identity.
- After successfully verifying the user, initiated a password reset.
- Provided the new password to the user through chat.

**Resolution:** Successfully verified the user's identity and reset the expired password. The new password was provided to the user through chat, and the user confirmed that she was able to log in successfully.

### Video Demonstration

🎥 [Watch Complete Ticket Resolution on Loom](https://www.loom.com/share/d00d280188a845998d4b22a76bc5822c)

---

## Ticket 2: Customer Support PC Replacement & Deployment

**Priority:** Critical  
**Category:** Workstation Deployment / Hardware

**Issue:** A Customer Support agent's desktop was completely unresponsive and would not power on. The user had already confirmed that the wall outlet was working, but the workstation showed no lights, fan activity, or other signs of power. Since the agent was unable to take customer calls, a replacement workstation needed to be deployed.

**Troubleshooting**
- Reviewed the deployment documentation to determine the appropriate deployment method and identified Server Imaging as the required method.
- Started the desktop deployment and completed the physical setup by connecting the power, Ethernet, DisplayPort, keyboard, and mouse.
- Accessed the boot menu to begin the Server Imaging process.
- Launched the Task Sequence Wizard and authenticated to the deployment share using the task sequence password provided in the SOP.
- Configured the required task sequence variables by entering the appropriate names and values.
- Completed the imaging process and reached the Windows sign-in screen.
- Signed in using domain credentials to confirm that the workstation was operational.
- Shipped the replacement desktop to the user.

**Resolution:** Successfully deployed and configured a replacement workstation using Server Imaging. The user confirmed through chat that the replacement desktop arrived and was working successfully.

### Video Demonstration

🎥 [Watch Complete Ticket Resolution on Loom](https://www.loom.com/share/bac567009f1c4e0ba738715be945f33f)

---
