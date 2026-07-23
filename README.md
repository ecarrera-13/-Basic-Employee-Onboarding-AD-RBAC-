# Basic-Employee-Onboarding-AD-RBAC-
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
A rapidly growing company, Northstar Medical Group, previously used an MSP to manage user provisioning. The MSP mismanaged users and lacked an appropriate structure to ensure adequate regulatory compliance. There were clear HIPAA violations because patient medical information was accessible to users who should not have had access to the sensitive information. The principle of least privilege was not instituted to create any barriers of access to this information. This posed serious regulatory issues for NMG. They were outside of regulatory compliance and needed to quickly solve the issues caused by the MSP using manual provisioning for users in the domain.  

## Solution Overview
To address the issues at Northstar Medical Group, role-based access controls needed to be implemented, and users needed to be appropriately provisioned into their designated security groups. Organizational units needed to be instituted to create the necessary division among access to shared drives and other network resources. This methodology ensures that patient information remains confidential and inaccessible to users who do not need access. The ultimate goal was to ensure that confidentiality and integrity existed for all patient records.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Demonstrated adequate usage of access controls by implementing RBAC with security groups mapped to each department.
* Provisioned 20 user accounts with consistent naming conventions and attribute standards.
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis
* Gained hands-on experience with the tools and methodology I have learned about in theory throughout certification courses.
* Completed my first IAM/security project
