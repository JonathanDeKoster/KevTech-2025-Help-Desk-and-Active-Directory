# KevTech Help Desk & Active Directory Lab

**Hands-on Windows administration and Active Directory lab based on the KevTech Help Desk Lab series.**

## Project Overview

This project documents a hands-on Windows and Active Directory environment built in VirtualBox while completing the KevTech Help Desk Lab series.

The lab simulates a small business domain environment and provides practical experience with **Windows Server, Active Directory Domain Services (AD DS), Windows 11 clients, user and account management, domain authentication, Group Policy, and basic security administration**.

The environment is developed progressively, with each mini-project building on the previous configuration.

## Objectives

* Build and configure a virtualized Windows domain environment
* Install and configure Active Directory Domain Services
* Create and manage domain user accounts
* Configure and join Windows client machines to the domain
* Practice domain authentication and account troubleshooting
* Configure and test Group Policy settings
* Apply password and account lockout policies
* Develop practical skills relevant to entry-level IT support and help desk roles

## Lab Environment

| Component          | Configuration                                                 |
| ------------------ | ------------------------------------------------------------- |
| Hypervisor         | Oracle VirtualBox                                             |
| Server             | Windows Server                                                |
| Client             | Windows 11                                                    |
| Directory Services | Active Directory Domain Services (AD DS)                      |
| Management Tools   | Active Directory Users and Computers, Group Policy Management |
| Network            | VirtualBox virtual networking                                 |
| Environment        | Local virtualized test lab                                    |

## Skills Demonstrated

* Windows Server administration
* Active Directory administration
* Domain controller configuration
* User and account management
* Windows domain joining
* Domain authentication
* Group Policy configuration
* Password and account security policies
* Account troubleshooting
* Virtual machine configuration
* Basic Windows networking

---

## Mini-Projects

### Mini-Project 1: Server Installation & Initial Configuration

**Objective:** Build the initial Windows Server environment that serves as the foundation for the Active Directory lab.

**Tasks Performed:**

* Created a Windows Server virtual machine in VirtualBox
* Installed Windows Server
* Completed initial server configuration
* Configured network connectivity in preparation for the domain environment

**Skills Demonstrated:**

* Virtual machine deployment
* Windows Server installation
* Initial server configuration
* Virtual networking

**Result:** Successfully established the Windows Server virtual machine used as the foundation for the Active Directory environment.

---

### Mini-Project 2: Active Directory Domain Services Installation

**Objective:** Install Active Directory Domain Services and configure the server as a domain controller.

**Tasks Performed:**

* Installed the Active Directory Domain Services (AD DS) role
* Configured the server for Active Directory
* Promoted the server to a domain controller
* Verified the Active Directory environment using Windows administrative tools

**Skills Demonstrated:**

* Active Directory Domain Services
* Domain controller deployment
* Active Directory configuration
* Windows Server administration

**Result:** Successfully deployed a functioning Active Directory domain controller for the lab environment.

---

### Mini-Project 3: Active Directory User Creation & Guest Additions

**Objective:** Configure VirtualBox Guest Additions and create a domain user account.

**Tasks Performed:**

* Installed VirtualBox Guest Additions
* Opened Active Directory Users and Computers (ADUC)
* Created the test domain user `Jeff`
* Verified the account within Active Directory

**Skills Demonstrated:**

* Active Directory Users and Computers
* Domain user creation
* User account administration
* VirtualBox Guest Additions

**Result:** Successfully created and managed a domain user account for testing domain authentication.

---

### Mini-Project 4: Windows Client Setup & Domain Join

**Objective:** Deploy a Windows 11 client and connect it to the Active Directory domain.

**Tasks Performed:**

* Created a Windows 11 virtual machine in VirtualBox
* Configured server and client network settings
* Verified connectivity between the Windows Server and Windows 11 client
* Joined the Windows 11 client to the Active Directory domain
* Logged into the client using the domain user account `Jeff`

**Skills Demonstrated:**

* Windows 11 deployment
* Virtual machine networking
* Domain joining
* Active Directory authentication
* Windows client administration
* Basic network troubleshooting

**Result:** Successfully joined the Windows 11 client to the domain and authenticated using an Active Directory user account.

---

### Mini-Project 5: Group Policy & Account Security

**Objective:** Configure and test Active Directory account controls and domain-level security policies.

**Tasks Performed:**

* Disabled the `Jeff` domain account using Active Directory Users and Computers
* Configured account expiration
* Restricted permitted logon hours
* Opened Group Policy Management through Server Manager
* Configured the Default Domain Policy
* Modified password policy settings
* Configured account lockout settings
* Tested account behavior from the Windows 11 domain client
* Unlocked the test account after triggering the account lockout condition

**Skills Demonstrated:**

* Active Directory account administration
* Group Policy Management
* Password policy configuration
* Account lockout policy configuration
* User logon restrictions
* Account troubleshooting
* Domain security administration

**Result:** Successfully configured and tested multiple Active Directory account controls and domain security policies, including account disabling, expiration, logon restrictions, password requirements, and account lockout behavior.

---

## Screenshots

### Mini-Project 1: Server Installation & Initial Configuration

<img width="1336" height="844" alt="Windows Server virtual machine configuration" src="https://github.com/user-attachments/assets/10fb06bc-54a5-4c65-81ef-a389bec3abc9" />

<img width="1350" height="841" alt="Windows Server initial configuration" src="https://github.com/user-attachments/assets/1f8302bb-f03b-4656-ad69-938fee9e629d" />

---

### Mini-Project 2: Active Directory Domain Services Installation

<img width="1333" height="837" alt="Active Directory Domain Services installation" src="https://github.com/user-attachments/assets/be9abcad-4044-47ad-97c8-9156fa543239" />

<img width="1328" height="835" alt="Active Directory domain controller configuration" src="https://github.com/user-attachments/assets/f6eaf819-6c8e-40ac-ac7a-c3d6c09d30bb" />

<img width="1371" height="839" alt="Active Directory management tools" src="https://github.com/user-attachments/assets/f5a4d9c7-c32c-426f-a484-3ca190fc0922" />

---

### Mini-Project 3: Active Directory User Creation & Guest Additions

<img width="1333" height="845" alt="VirtualBox Guest Additions configuration" src="https://github.com/user-attachments/assets/0611fb50-a3f7-4a13-8c84-04ed4a11944a" />

<img width="1350" height="841" alt="Active Directory user account creation" src="https://github.com/user-attachments/assets/5dbbd286-0eaf-4d48-85de-9f3f6d9aa544" />

---

### Mini-Project 4: Windows Client Setup & Domain Join

<img width="1593" height="860" alt="Windows 11 virtual machine installation" src="https://github.com/user-attachments/assets/6cbe7450-4a55-49c2-bbd9-73c628b1e887" />

<img width="1600" height="835" alt="VirtualBox Host-Only Adapter configuration" src="https://github.com/user-attachments/assets/deb142d9-3b70-40b5-be27-29a2ecb87357" />

<img width="1600" height="858" alt="Windows Server network configuration" src="https://github.com/user-attachments/assets/d6aea81b-00d5-42f1-be1f-2597fea9affb" />

<img width="1599" height="861" alt="Windows 11 network configuration" src="https://github.com/user-attachments/assets/babd373a-0671-4935-bb98-d129ac9fa673" />

<img width="1600" height="846" alt="Network connectivity test using ping" src="https://github.com/user-attachments/assets/9fb63988-9296-44cb-a489-f54e980dc338" />

<img width="1596" height="833" alt="Joining Windows 11 client to the Active Directory domain" src="https://github.com/user-attachments/assets/9715af9c-72aa-4388-b65c-e39c341215f7" />

<img width="1599" height="836" alt="Windows 11 successfully joined to the domain" src="https://github.com/user-attachments/assets/8e339d03-872d-43ab-a2e0-c89ca156bd8e" />

<img width="1594" height="823" alt="Windows 11 logged in with Active Directory user Jeff" src="https://github.com/user-attachments/assets/26668b57-2160-4f0e-a26e-371036942626" />

---

### Mini-Project 5: Group Policy & Account Security

**Disabled User Account**

<img width="1600" height="835" alt="Jeff domain account disabled in Active Directory" src="https://github.com/user-attachments/assets/3c046c50-f1ba-447b-b925-259b0a9563a6" />

<img width="1600" height="861" alt="Jeff disabled account verification" src="https://github.com/user-attachments/assets/47f7837c-abb4-4bc7-adea-e6b01f1adfdc" />

**Expired User Account**

<img width="1600" height="860" alt="Domain account expiration configuration" src="https://github.com/user-attachments/assets/d6b7ec4c-650c-4836-b6f3-2053c2bf38c5" />

<img width="1600" height="859" alt="Jeff account expired" src="https://github.com/user-attachments/assets/8e863271-441c-4f97-8dfa-57b01bc3a7d6" />

**Logon Hours Restrictions**

<img width="1599" height="860" alt="Jeff logon hours configuration" src="https://github.com/user-attachments/assets/9abf71fc-92cf-4f2f-835f-5fc97f1b5f6f" />

<img width="1600" height="860" alt="Jeff logon hours restriction" src="https://github.com/user-attachments/assets/7736483a-9003-4cc0-98de-0c171298abab" />

**Password & Account Lockout Policy**

<img width="1599" height="861" alt="Group Policy password and account lockout configuration" src="https://github.com/user-attachments/assets/1eb25299-4f22-4cd3-93a7-bf3e6440b4c0" />

<img width="1600" height="860" alt="Jeff account locked after incorrect password attempts" src="https://github.com/user-attachments/assets/d7c8267c-21af-44e7-8832-4715e70f3c51" />

<img width="1599" height="861" alt="Jeff account unlocked in Active Directory" src="https://github.com/user-attachments/assets/54ae54dc-365b-43a5-b72b-bd6415ebe785" />

---

## Key Takeaways

This project demonstrates hands-on experience building and administering a Windows domain environment from the ground up.

The completed exercises provide practical experience with:

* Windows Server administration
* Active Directory Domain Services
* Domain controllers
* Windows 11 domain clients
* User and account management
* Domain authentication
* Group Policy
* Password and account lockout policies
* Basic Windows networking and troubleshooting

Additional mini-projects will be added as the KevTech Help Desk Lab series is completed.






