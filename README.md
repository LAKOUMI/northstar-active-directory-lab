# northstar-active-directory-lab
Active Directory infrastructure and I am lab demonstrating OU design, RBAC, user provisioning, and identity troubleshooting.

## Project  
This project documents the design, implementation, and troubleshooting of an active Directory environment for *Northstar Medical Group (NMG)*, a healthcare organization with more than 200 employees. The goal was to rebuild and organize an identity infrastructure that previously relied on inconsistent manual user management. The project focuses on Active Directory administration, I dentity and Acess Management (IAM), Role-Based Access Control (RBAC), user provisioning, and troubleshooting.

## The problem
Northstar Medical Group's identity environment lacked a consistent organizational structure and standardized access-management process.
key issues included:
- Inconconsistent user account organization
- Lack of clear Organisational (OU) structure
- Inconsistent security group membership
- Manual user provisioning
- Increased risk of users receiving incorrect access
- Identity-management practices that could create security and compliance concerns.
The objective was to create a more structured and manageable Active Directory environment.

## solution
I built and configured an Activite Directory environment using the *NMG.com* domain.
the solution inclued:
- Designing department-based Organisational Units (OUs)
- Creating and managing Active Directory user acconts
- Implementing security groups (RBAC) principales
- Standardizing user account attributes and naming
- Troubleshooting an incident
- Documenting the investigation, root cause, remediation, and verification

  ## Technologies & Skills
  - Windowa Server
  - Active Directory Domain Service (AD DS)
  - Active Directory Users and Computers (ADUC)
  - Identity and Access Management (IAM)
  - Role-Based Access Control (RBAC)
  - Organizational Units (OUs)
  - Security Group
  - User Provisioning
  - Access Troubleshooting
  - Incident Documentation
 
    ## Projet Timeline

    ### Phase 1 _ Active Directory Infrastructure
    Built the NMG.com Active Directory domain and established the foundation for centralized identity management.
    ### Phase 2 _ Organizational Structure
    Created Organizational Units to logically organize users based on business departments and administrative requirements.
    ### Phase 3 _ Identity & Access Management
    Created user accounts and security groups and implemented RBAC principles to align access with department responsibilities.
    ### Phase 4 _ Indcident Ivestigation & Resolution
    Investigation a user access issue by reviewing the affected account's OU placement and security group memberships. The investigation identified multiple
    configuration issues affecting the user's access. The account configuration was corrected and verified after remediation.
    ### Phase _ Documentation & Portfolio
    Documented the infrastructure, troubleshooting methodology, finfinds, remediation steps, and results in a professional GitHub portfolio.

    ## Key Accomplisments
    - Built an Active Directory domain environment from the group up
    - Designed a structured OU hierachy
    - Provisioned and organized multiple user accounts
    - Implemented department-based security groups
    - Applied RBAC concepts to identity management
    - Investigated ann Active Directory access incident
    - Identified incorrect identify configuration
    - Corrected OU placement and security group membership
    - Verified the user's configuration after remediation
    - Documented the project using preofessional technical documentation
   
    ## Troubleshooting Methodology
    For the identity-related inciden, I followed a structured troubleshooting process:

        * Investigate-> Compare-> Identify Root Cause-> Remediate-> Verify-> Document*
    
     Rather than immediately changing the affected account, I first examined its configuration and compared it with the expected configuration for users    performing the same role.
    This approach helped identify the underlying causes before remediation.


    ____

    ## Repository Structure

  '''text
  northstar-active-directory-lab/
  |----- README.md
  |----- documentation/
    |--- incident-resolution-report.md
  |
  |---- screenshots/
    |--- domain-overview.png
    |--- ou-structure.png
    |--- security-groups.png
    |--- users.png
    |--- incident-before'png
    |--- incident-after.png

    
  
