# AWS Cloud Technical Essentials
The AWS Cloud Technical Essentials course is designed for individuals who are new to Amazon Web Services (AWS) and want to establish a solid understanding of the core principles and services offered by AWS. This foundational course provides an introduction to cloud computing concepts and walks participants through key AWS services, enabling them to comprehend the fundamental building blocks of cloud solutions. By covering essential concepts, services, and best practices, the course sets the groundwork for further exploration and utilization of AWS cloud solutions.
<br/><br/>

## Skills Covered
* Develop a comprehensive understanding of AWS cloud services, including compute, networking, storage, and databases
* Gain hands-on experience with provisioning, configuring, and managing AWS resources using the AWS Management Console
* Learn best practices for designing secure, scalable, and cost-effective cloud architectures on AWS
* Acquire practical skills in monitoring, optimizing, and troubleshooting AWS environments to ensure optimal performance and cost efficiency
* Learn about serverless computing concepts and services, including AWS Lambda and Amazon API Gateway
<br/><br/>

## Module 01: Introduction to Amazon Web Services
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
<br/>

**AWS Global Infrastructure** - 
* AWS Region - separate geographic area
* AWS Availability Zone - Availability Zone as data center. A availability zone may have multiple data center but because the are close together, they counted as 1 Availability Zone.
<br/>

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

**Amazon EC2 Instance Lifecycle**<br/>
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
### Understanding the Network in AWS Services
* **Amazon Virtual Private Cloud (VPC)** - VPC is a logically isolated section of the AWS Cloud where you can launch AWS resources.
* **VPC Subnets** - VPC Subnets are divisions within a VPC that allow you to organize resources. They are associated with a specific availability zone (AZ) in a region.
* **Route Tables** - Route Tables contains a set of rules, called routes, that are used to determine where network traffic is directed.
* **Internet Gateway** - Internet Gateway enables communication between instances in your VPC and the internet. It serves as a horizontally scaled, redundant component.
* **Amazon Route 53** - Route 53 is a scalable and highly available domain name system (DNS) web service. It translates user-friendly domain names into IP addresses.
* **Virtual Private Network (VPN) and Direct Connect** - VPN and Direct Connect services provide secure and dedicated network connections between your on-premises data center and your VPC.
* **Security Group and Network ACL** - Security Group act as virtual firewalls for your instances, controlling inbound and outbound traffic. Network ACL are stateless and operate at the subnet level.
<br/>

### Introduction to Amazon Virtual Private Cloud (Amazon VPC)
**Amazon Virtual Private Cloud (VPC)** gives you full control over your virtual networking environment, including resource placement, connectivity, and security. Get started by setting up your VPC in the AWS service console.
* Selection of your own IP address range
* Creation of subnets
* Configuration of route tables and network gateways
![Amazon Virtual Private Cloud](Images/Amazon_VPC.png)

### Amazon VPC Routing
**Amazon VPC routing** is a crucial aspect of networking within AWS. It involves configuring the rules that determine how traffic flows between different components within the VPC, such as subnets, instances, and the internet.

### Amazon VPC Security
**Amazon VPC Security** is a critical aspect of AWS networking, focusing on safeguarding resources within the VPC and controlling access to and from external networks.
<br/><br/>















<br/><br/><br/><br/><br/><br/><br/><br/>
## AWS Keywords
* AWS Region - separate geographic area
* AWS Availability Zone - Availability Zone as data center. A availability zone may have multiple data center but because the are close together, they counted as 1 Availability Zone.
* AWS CloudFront -> Cache provides, CDN services
* AWS Edge Location -> Location of CloudFront
* AWS EC2 - Amazon Elastic Compute Cloud (EC2)

