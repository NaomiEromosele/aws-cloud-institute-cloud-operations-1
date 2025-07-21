# aws-cloud-institute-cloud-operations-1
Labs and scripts for the Cloud Operations 1 course. Covers Linux, Bash/PowerShell scripting, monitoring with CloudWatch, and DevOps principles with IaC
--- 

## Course Description
This course develops systems management and DevOps skills. It covers the Linux OS, scripting with Bash and PowerShell, monitoring with CloudWatch and CloudTrail, and Infrastructure as Code (IaC) with CloudFormation and the AWS CDK.

---

## Key Skills & Concepts Learned
- Navigating the Linux command line, managing filesystems, and configuring permissions.
- Writing and troubleshooting shell scripts in Bash and PowerShell to automate tasks.
- Using the AWS CLI to interact with and manage AWS resources.
- Monitoring resources and creating alerts with Amazon CloudWatch and CloudTrail.
- Decoupling services and automating responses to events with Amazon EventBridge.
- Managing fleets of instances and automating operational tasks with AWS Systems Manager.
- Implementing version control with Git and AWS CodeCommit.
- Defining and deploying infrastructure as code (IaC) using AWS CloudFormation and the AWS Cloud Development Kit (CDK).

---

## Labs & Projects

### Lab: Using the AWS CLI and Bash to Automate Linux
* **Description:** Wrote Bash scripts that used the AWS CLI to automate the creation and management of AWS services from a Linux environment.
* **Source Code:** `./lab-bash-automation`

### Lab: Using AWS CloudFormation
* **Description:** Modified an existing CloudFormation template to deploy a custom VPC with a public subnet and an EC2 web server, using change sets to manage updates.
* **Source Code:** `./lab-cloudformation`

### Lab: Configuring the AWS CDK Credentials
* **Description:** Used the AWS Cloud Development Kit (CDK) with Python to programmatically define and deploy a VPC and an EC2 instance.
* **Source Code:** `./lab-aws-cdk`
