# KevTech 2025 – Help Desk & Active Directory Lab

**Description:**  
This repository documents my hands-on work through the KevTech Help Desk Lab (2025), building skills in Active Directory, Group Policy, user management, and Windows administration. Each lab section is treated as a mini-project demonstrating key tasks and configurations.

---

<details>
<summary>Mini-Project 1: Server Installation (Part 1)</summary>

**Objective:** Set up a virtual lab environment using VirtualBox.

**Steps Taken:**
1. Installed Windows Server on VirtualBox.
2. Configured initial server settings and network connection.

**Skills Demonstrated:**
- Virtualization setup
- Server environment preparation

**Screenshot:**  
![Server Installation Screenshot](path-to-your-screenshot.png)

</details>

<details>
<summary>Mini-Project 2: Active Directory Installation (Part 2)</summary>

**Objective:** Install and configure Active Directory Domain Services on the server.

**Steps Taken:**
1. Installed Active Directory Domain Services (AD DS) role on the server.
2. Promoted the server to a Domain Controller.

**Skills Demonstrated:**
- Active Directory installation
- Domain Controller configuration

**Screenshot:**  
![AD Installation Screenshot](path-to-your-screenshot.png)

</details>

<details>
<summary>Mini-Project 3: Account Creation & Guest Additions (Part 3)</summary>

**Objective:** Configure VirtualBox Guest Additions and create user accounts in Active Directory.

**Steps Taken:**
1. Installed VirtualBox Guest Additions on the server.
2. Created a test user account, `Jeff`, in Active Directory Users and Computers.

**Skills Demonstrated:**
- User account creation and management
- VirtualBox enhancements (Guest Additions)

**Screenshot:**  
![User Creation Screenshot](path-to-your-screenshot.png)

</details>

<details>
<summary>Mini-Project 4: Client Setup & Domain Join (Part 4)</summary>

**Objective:** Install a client machine and join it to the domain.

**Steps Taken:**
1. Installed Windows 11 on a separate VirtualBox VM.
2. Joined the Windows 11 machine to the domain.
3. Logged in with the AD user account `Jeff` to verify domain connectivity.

**Skills Demonstrated:**
- Domain joining
- AD user authentication on client machines

**Screenshot:**  
![Domain Join Screenshot](path-to-your-screenshot.png)

</details>

<details>
<summary>Mini-Project 5: Group Policy & Account Policies (Part 5)</summary>

**Objective:** Configure password, account lockout, and login policies using Group Policy and Active Directory.

**Steps Taken:**
1. Disabled and expired the `Jeff` account in Active Directory Users and Computers.
2. Adjusted login hours for the account.
3. Opened **Group Policy Management** via Server Manager → Tools.
4. Edited **Default Domain Policy**:
   - Navigated to Windows → Security Settings → Account Policies → Password Policy & Account Lockout Policy
   - Configured password requirements, account lockout thresholds, and durations.

**Skills Demonstrated:**
- Group Policy configuration
- AD account management and security
- Policy enforcement on domain users

**Screenshots:**  
![AD Account Disabled Screenshot](path-to-your-screenshot.png)  
![Group Policy Screenshot](path-to-your-screenshot.png)  
![Failed Login Screenshot](path-to-your-screenshot.png)

</details>

---

### Notes
- Screenshots are placeholders; replace with actual images from your lab.
- Each mini-project is self-contained, making it easy to add new parts as you progress through the KevTech labs.
