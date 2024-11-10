# AWS Cloud Technical Essentials
The AWS Cloud Technical Essentials course is designed for individuals who are new to Amazon Web Services (AWS) and want to establish a solid understanding of the core principles and services offered by AWS. This foundational course provides an introduction to cloud computing concepts and walks participants through key AWS services, enabling them to comprehend the fundamental building blocks of cloud solutions. By covering essential concepts, services, and best practices, the course sets the groundwork for further exploration and utilization of AWS cloud solutions.

## Skills Covered
* Develop a comprehensive understanding of AWS cloud services, including compute, networking, storage, and databases
* Gain hands-on experience with provisioning, configuring, and managing AWS resources using the AWS Management Console
* Learn best practices for designing secure, scalable, and cost-effective cloud architectures on AWS
* Acquire practical skills in monitoring, optimizing, and troubleshooting AWS environments to ensure optimal performance and cost efficiency
* Learn about serverless computing concepts and services, including AWS Lambda and Amazon API Gateway
<br/><br/>

## Module 01: Introduction to Amazon Web Services
### Learning Outcomes
* Define Amazon Web Services (AWS) and its role in the cloud computing industry
* Understand the global infrastructure of AWS, including regions and availability zones
* Recognize fundamental concepts that underpin AWS Cloud
* Articulate the importance of AWS IAM in managing secure access to AWS resources
* Explain essential IAM concepts, such as users, groups, roles, policies, and permissions
* Understand the purpose and advantages of IAM groups for effective user management
* Grasp the concept of IAM roles and their application in delegating permissions
* Apply IAM knowledge to enhance security and access control within the AWS service
* Apply theoretical knowledge gained in the IAM module through practical, hands-on lab exercises.
* Develop confidence in utilizing IAM for secure access control within AWS

**Definition of Cloud Computing** - Cloud model comprises five essential chrematistics, three services, and four deployment models.

**Essential Chrematistics** 
* Broad Network Access
* Rapid Elasticity
* Measured Service (For pay-as-you-go basis)
* On-Demand Self-Service
* Resource Pooling

**Service Models**
* Software as a Service (SaaS)
* Platform as a Service (PaaS)
* Infrastructure as a Service (IaaS)

**Deployment Models** 
* Public
* Private
* Hybrid
* Community
<br/><br/>

**AWS Global Infrastructure** - 
* AWS Region - separate geographic area
* AWS Availability Zone - Availability Zone as data center. A availability zone may have multiple data center but because the are close together, they counted as 1 Availability Zone.
<br/><br/>

**AWS Identity Access Management (IAM)** -
* Access Management
* User Group
    * One user can assigned multiple group
    * Sub-group not allow
* Users
    * Create User
    * Change Password: Security Credentials -> Update Console Password
    * Set MFA (Multi-factory Authenticator)
* Roles
    * Use to communicate each other between different services or same service with different regions
* Policies
    * Policies can be set per User or User Group
    * Direct Managed: A huge pre-defined policies available
    * Customer Managed: Can create custom policy
* Dentity Providers
* Account Setting
    * Change Password Policy
<br/><br/>

## Module 02: AWS Compute
### Learning Outcomes
* Define Amazon EC2 and understand its significance in AWS computing
* Comprehend the lifecycle of an Amazon EC2 instance, including launching stopping, and terminating
* Define serverless computing and identify its advantages and use cases
* Explore AWS Lambda as a serverless computing service and its event-driven architecture
* Evaluate and choose the appropriate AWS computing service based on specific requirements
* Apply theoretical knowledge in a practical setting by launching a sample application on Amazon EC2
* Gain hands-on proficiency in setting up and managing computing resources on AWS


### Introduction to Amazon Elastic Compute Cloud (EC2)
**AWS EC2** - is a web service that provides resizable compute capacity in the cloud. In other words virtual machine in the AWS Cloud environment. It reduces the time required to obtain and start the new server in a minute.

**Benefites of AWS EC2**
* Scalability
* Flexibility and Variety
* Elasticity
* Reliability
* Security
* Cost Efficiency
* Security Group
    * Inbound Rule
    * Outbound Rule

**Pricing Options of AWS EC2**
* On-Demand - Pay by the hour or second basis
* Reserved - Time limit 1 or 3 years contracts up to 70% discount
* Spot - Price based on bargading of up to 90% discount
* Dedicated Host - physical EC2 server is dedicated for our use. Most expensive option.

**Amazon EC2 Instance Lifecycle**

![Amazon EC2 Instance Lifecycle](Images/Lifecycle.png)
<br/><br/>

### What is Serverless?
**Serverless** architecture is a way to build and run applications and services without having to manage infrastructure. Your application still runs on servers, but all the server management is done by AWS

**Benefites of Serverless**
* Fully managed service
* Scale Flexiby
* Only pay for resources you use
* Enhance Developer productivity
* Seamless Connections
* Develop Intelligent applications

**Example of Serverless Services**
* AWS Lambda - Enables you to run code without provisioning or managing servers.
* AWS App Runner - Makes it easy to build, deploy, and scale web applications quickly.
* AWS Fargate - Allows you to run containers without having to manage the underlying infrastructure
<br/><br/>

### Introduction to AWS Lambda
**Where to Use** - You can run code for virtually any type of application or backend service. This includes:
* Data Processing
* Real-time Stream Processing
* Machine Learning
* WebSocket
* IoT Backends
* Mobile Backends
* Web Applications

**How AWS Lambda works** - There are options for configuring Lambda functions using the Lambda console, Lambda API, AWS CloudFormation, or AWS Serverless Application Model (AWS SAM).
* Function
* Tigger
* Event
* Application Environment
* Deployment Packages
* Runtime
<br/><br/>

## Module 03: AWS Networking
### Learning Outcomes
* Develop a foundational understanding of networking principles in the AWS environment
* Master the concepts of Amazon VPC, including its components and use cases
* Gain proficiency in configuring routing within an Amazon VPC
* Acquire knowledge of security features and best practices for securing an Amazon VPC
* Apply theoretical knowledge in a practical setting through the hands-on lab, reinforcing the ability to create and manage VPCs, launch EC2 instances, and deploy applications

### Understanding the Network in AWS Services
* **Amazon Virtual Private Cloud (VPC)** - VPC is a logically isolated section of the AWS Cloud where you can launch AWS resources.
* **VPC Subnets** - VPC Subnets are divisions within a VPC that allow you to organize resources. They are associated with a specific availability zone (AZ) in a region.
* **Route Tables** - Route Tables contains a set of rules, called routes, that are used to determine where network traffic is directed.








<br/><br/><br/><br/><br/><br/><br/><br/>
## AWS Keywords
* AWS Region - separate geographic area
* AWS Availability Zone - Availability Zone as data center. A availability zone may have multiple data center but because the are close together, they counted as 1 Availability Zone.
* AWS CloudFront -> Cache provides, CDN services
* AWS Edge Location -> Location of CloudFront
* AWS EC2 - Amazon Elastic Compute Cloud (EC2)

