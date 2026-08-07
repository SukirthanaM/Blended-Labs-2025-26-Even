# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1600" height="961" alt="image" src="https://github.com/user-attachments/assets/d7509467-d435-41fd-aa24-d4a92053db11" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1600" height="963" alt="image" src="https://github.com/user-attachments/assets/940aaf72-bbfb-4f56-98ce-172d12d006c6" />
<img width="1600" height="961" alt="image" src="https://github.com/user-attachments/assets/54f9bdc0-0cc0-4341-a024-191e2cfda9eb" />
<img width="1600" height="961" alt="image" src="https://github.com/user-attachments/assets/1494f88d-7637-4446-9bee-895b10898421" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1600" height="999" alt="image" src="https://github.com/user-attachments/assets/26a6fe8f-5543-4bb8-91ae-93d249dea150" />
<img width="1600" height="1005" alt="image" src="https://github.com/user-attachments/assets/e9908762-7063-418d-9037-cc91324a6371" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Sukirthana.M
**Reg No:** 212224220112
**Course:** Introduction to Cloud Computing  

