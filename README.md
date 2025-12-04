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
<img width="1336" height="844" alt="KevTEch AD Lab 1" src="https://github.com/user-attachments/assets/10fb06bc-54a5-4c65-81ef-a389bec3abc9" />


<img width="1350" height="841" alt="KevTEch AD Lab 2" src="https://github.com/user-attachments/assets/1f8302bb-f03b-4656-ad69-938fee9e629d" />

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
<img width="1333" height="837" alt="KevTEch AD Lab 4" src="https://github.com/user-attachments/assets/be9abcad-4044-47ad-97c8-9156fa543239" />

<img width="1328" height="835" alt="KevTEch AD Lab 6" src="https://github.com/user-attachments/assets/f6eaf819-6c8e-40ac-ac7a-c3d6c09d30bb" />

<img width="1371" height="839" alt="KevTEch AD Lab 7" src="https://github.com/user-attachments/assets/f5a4d9c7-c32c-426f-a484-3ca190fc0922" />

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
<img width="1333" height="845" alt="KevTEch AD Lab 9" src="https://github.com/user-attachments/assets/0611fb50-a3f7-4a13-8c84-04ed4a11944a" />

<img width="1350" height="841" alt="KevTEch AD Lab 11" src="https://github.com/user-attachments/assets/5dbbd286-0eaf-4d48-85de-9f3f6d9aa544" />

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
<img width="1593" height="860" alt="KevTEch AD Lab 12 Install windows 11" src="https://github.com/user-attachments/assets/6cbe7450-4a55-49c2-bbd9-73c628b1e887" />
<img width="1600" height="835" alt="KEvtech ad lab 15 Server network config host only adapter" src="https://github.com/user-attachments/assets/deb142d9-3b70-40b5-be27-29a2ecb87357" />
<img width="1600" height="858" alt="Kevtech ad lab 16 network setting server" src="https://github.com/user-attachments/assets/d6aea81b-00d5-42f1-be1f-2597fea9affb" />
<img width="1599" height="861" alt="Kevtech ad lab 17 windows 11 network settings" src="https://github.com/user-attachments/assets/babd373a-0671-4935-bb98-d129ac9fa673" />
<img width="1600" height="846" alt="ping" src="https://github.com/user-attachments/assets/9fb63988-9296-44cb-a489-f54e980dc338" />
<img width="1596" height="833" alt="Kevtech ad lab 19 connect windows 11 to domain" src="https://github.com/user-attachments/assets/9715af9c-72aa-4388-b65c-e39c341215f7" />
<img width="1599" height="836" alt="kevtech ad lab 20 successfully connecteed to domain" src="https://github.com/user-attachments/assets/8e339d03-872d-43ab-a2e0-c89ca156bd8e" />
<img width="1594" height="823" alt="kevtech ad lab 21 logged in to windows11 as Jeff" src="https://github.com/user-attachments/assets/26668b57-2160-4f0e-a26e-371036942626" />

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
Disabled User
<img width="1600" height="835" alt="Kevtech part 5 disabled jeff" src="https://github.com/user-attachments/assets/3c046c50-f1ba-447b-b925-259b0a9563a6" />
<img width="1600" height="861" alt="Kevtech part 5 jeff disabled" src="https://github.com/user-attachments/assets/47f7837c-abb4-4bc7-adea-e6b01f1adfdc" />

User Account Expired
<img width="1600" height="860" alt="Kevtech part 5 account expired" src="https://github.com/user-attachments/assets/d6b7ec4c-650c-4836-b6f3-2053c2bf38c5" />
<img width="1600" height="859" alt="Kevtech part 5 Jeff account expired" src="https://github.com/user-attachments/assets/8e863271-441c-4f97-8dfa-57b01bc3a7d6" />

Logon Hours Restricted
<img width="1599" height="860" alt="Kevtech part 5 Logon hours for jeff" src="https://github.com/user-attachments/assets/9abf71fc-92cf-4f2f-835f-5fc97f1b5f6f" />
<img width="1600" height="860" alt="Kevtech part 5 Logon hour jeff restricted" src="https://github.com/user-attachments/assets/7736483a-9003-4cc0-98de-0c171298abab" />

Account Lockout Policy

<img width="1599" height="861" alt="Kevtech part 5 Group Policy management account lockout and password" src="https://github.com/user-attachments/assets/1eb25299-4f22-4cd3-93a7-bf3e6440b4c0" />
<img width="1600" height="860" alt="Kevtech part 5 Jeff incorrect password locked out" src="https://github.com/user-attachments/assets/d7c8264b-21af-44e7-8832-4715e70f3c51" />
<img width="1599" height="861" alt="KEvtech part 5 Jeff unlock account" src="https://github.com/user-attachments/assets/54ae54dc-365b-43a5-b72b-bd6415ebe785" />

</details>

---

### Notes
- Screenshots are placeholders; replace with actual images from your lab.
- Each mini-project is self-contained, making it easy to add new parts as you progress through the KevTech labs.
