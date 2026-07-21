# Basic-Employee-Onboarding-AD-RBAC-
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.
User accounts were being created manually without a consistent naming standard, organized OU structure, or reliable group assignments. For a healthcare organization with more than 200 employees, this created security gaps and potential HIPAA compliance risks.

## Solution Overview
Created an Active Directory environment for NMG using a Windows Server 2022 virtual machine and configured the server as the domain controller. Within AD Users and Computers, I created 4 different OUs (Finance, HR, IT and Operations) and Security Groups within those OUs. Added 15 employees to their respective OUs based on their role and job titles. Replaced the flat RBAC model with role-based access by department and secured provisioning through standardized accounts, proper OU placement, and least-privilege group assignments.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server 2022
* Active Directory Domain Services
* VirtualBox
* RBAC (Role Based Access Control)
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Created Organizational Units and Security Group Policies within those OUs
* Added 15 users to the appropriate OU and Group policies based on their roles
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis

## Repository Structure:
Folders created:
Documentation 
  * Domain Config File
  * Security Group Doc
  * User List Documentation
  * RBAC-Structure.md
Screenshots
  * Day 1 Screenshots
  * OUs and Security Grps Screenshots
  * Users and group members list
  * Jane's Incident
Incident-Reports
  * NMG-0047-Resolution.txt
