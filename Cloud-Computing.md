## Cloud Computing – Key Points
- On-demand delivery of IT resources over the internet
- Pay-as-you-go pricing model
- No need to manage physical servers
- Faster innovation and scalability

## Interview Angle
Q: Why companies move from traditional IT to cloud?\
A: To reduce CapEx, increase scalability, improve availability, and reduce operational overhead.

## Certification Angle

AWS will ask who manages what

Pay attention to:
- “Customer responsibility”
- “AWS responsibility”
- Keywords like fully managed, shared, abstracted

--------------------------------------------------------------------------------------------------

## What is Cloud Computing?
Cloud computing is on-demand delivery of computing resources (servers, storage, databases, networking) over the internet with pay-as-you-use pricing.

## Traditional vs Cloud
| Traditional |	Cloud |
| --- | --- | --- |
| Buy hardware |	Rent resources |
| High upfront cost |	Pay only for usage |
| Slow scaling |	Instant scalability |
| Manual maintenance |	Managed by provider |

## Types of Cloud Deployment Models

1. Public Cloud
- Owned by cloud providers (AWS, Azure, GCP)
- Example: AWS EC2

2. Private Cloud
- Dedicated infrastructure
- More control, less scalability

3. Hybrid Cloud
- Combination of public + private
- Common in enterprises

## Types of Cloud Service Models

IaaS (Infrastructure as a Service)
- Virtual machines, storage, networking
- Example: EC2

PaaS (Platform as a Service)
- Runtime + OS managed
- Example: Elastic Beanstalk

SaaS (Software as a Service)
- Fully managed applications
- Example: Gmail, Salesforce

👉 AWS mostly provides IaaS & PaaS

## Benefits of AWS Cloud
- No upfront investment
- High availability
- Auto scaling
- Global infrastructure
- Security & compliance

## AWS Global Infrastructure (Very Important)

Regions
- Geographical locations
- Example: ap-south-1 (Mumbai)

Availability Zones (AZs)
- Isolated data centers inside a region
- Used for high availability

Edge Locations
- Used by CloudFront (CDN)
- Faster content delivery

👉 Best practice: Deploy across multiple AZs

## Shared Responsibility Model

AWS Responsibility:
- Physical data centers
- Hardware
- Networking
- Underlying infrastructure

Customer Responsibility:
- OS patching
- IAM users & permissions
- Data security
- Application configuration

👉 Very common interview + exam question

## Core AWS Services (High-Level)

- Compute: EC2, Lambda
- Storage: S3, EBS
- Networking: VPC, Route53, Load Balancer
- Security: IAM, CloudTrail, GuardDuty

## AWS Pricing Model
- Pay-as-you-go
- Pay less with:
- Reserved Instances
- Savings Plans
- No termination charges

## AWS Use Cases in DevOps
- CI/CD pipelines
- Infrastructure as Code
- Monitoring & logging
- Secure cloud environments
- Scalable deployments

## Interview Questions (Day-1 Ready)

Q1: What is cloud computing?\
A: On-demand IT resources over the internet with pay-as-you-use pricing.

Q2: Difference between region and AZ?\
A: Region is a location; AZs are isolated data centers inside a region.

Q3: Explain Shared Responsibility Model.\
A: AWS secures infrastructure; customers secure OS, data, and access.

## Certification Focus (Cloud Practitioner)

Clearly understand and focus on:
- Cloud basics
- Pricing
- Shared responsibility
- Global infrastructure

🔑 Key Takeaways (Revision)
- Cloud = scalable + cost-effective
- AWS is global & secure

Responsibility is shared

Foundation for DevOps & Architect roles
