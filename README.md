# AWS-Multi-Web-Server
Multi server to host my book club landing pages
#Project Overview
This project is a highly available infrastructure deployment on AWS. It directs incoming web traffic onto two separate availability zones and public servers. 

#Architectural Summary
* **Virtual Private Cloud (VPC) :** Custom network built using 10.0.0.0/16 address
*  **High Availability Subnets:** Dual subnets places across separate Availability Zones('us-east-1a' and 'us-east-1b').
*  **Compute Layer:** Two Amazon EC2 instances running start up scripts to deliver data to HTTP servers.
*  **Traffic Balancing:** Application Load Balancer (ALB) implementing Round-Robin routing to balance network loads across the EC2 instances.
*  **Security Control:** Security groups with inbound rule restricting traffic to only port 80 for safe public access.

## Deployment Instructions
1. Initialize directory
2. Preview Changes
3. Provision Architecture
4. Clean up resources
  

### Architecture Design  
[Blank diagram (1).pdf](https://github.com/user-attachments/files/31802701/Blank.diagram.1.pdf)
