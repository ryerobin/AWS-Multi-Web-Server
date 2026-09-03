# Project : My First Multi-Availability Zone Load Balanced Web Infrastructure

## Beginner's Learning Journal
**Current Status:** Studying for AWS Solutions Architect Associate (Day 3)
**Background:** B.S. in Management Information Systems (MIS)

## What I built
I manually created a cloud infrastructure network inside the AWS Console. The goal was to build a system that can handle internet traffic without dropping users.

## Concepts Utilized in the Console
* **Networking** 10.0.0.0/16 VPC was divided into smaller /24 subnets.
* **Security:** Created and attached security group to allow public access on port 80 only, keeping access limited.
*  **Compute & Automation:** Launched 2 EC2 servers.
*  **High Availability:** Attached an Application Load balancer. Tested the browser by watching the traffic alternate between Server 1 and Server 2.

### Next Steps
I plan to continue building projects and while incrementally increase the difficulty with each project, while outlining thought processes and tactics to solve each problem.

### Architecture Design
[Blank.diagram.1 (1).pdf](https://github.com/user-attachments/files/31803103/Blank.diagram.1.1.pdf)

## Load Balancer Site
<img width="1121" height="278" alt="ALB pic" src="https://github.com/user-attachments/assets/7bed03b5-62fa-4e21-bd43-f9e03e72214a" />

## Healthy Targets
<img width="1638" height="371" alt="Healthy Target Group" src="https://github.com/user-attachments/assets/e1b2bc2a-a026-421d-ae7f-d34e2b3b42d9" />

