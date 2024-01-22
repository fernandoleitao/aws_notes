# AWS Certified Cloud Practioner Essentials

## Cloud Computing

Cloud Computing = on-demand delivery of compute power + database + applications + other IT resources
Pay-as-you-go
Provision exact type and size you need

Private Cloud 

Public Cloud

Hybrid Cloud

5 characteristics of Cloud Computing]

 - On-demand Service
 - Broad Network Service: available over network
 - Multi-tenancy and resource pooling: multiple customers share the same infra and apps / multiple customers serviced from the same physical resources
 - Rapid elasticity and scalability
 - Measured service 

6 advantages of Cloud Computing

 - CAPEX -> OPEX : don´t own hardware
 - Massive economies of scale: reduced prices due to large scale
 - Stop guessing capacity: based on measured usage
 - Increase speed and agility
 - Stop spending money running and maintaing data centers
 - Go global in minutes 

## Types of Cloud Computing

### IaaS (Infra as a Service)

Provide building blocks for cloud IT
Provides network, data storage
Highest level of flexibility
Similar to on premises IT

### PaaS (Platform as a Service)

Removes the need to manage infrastructure
Focus on deployment and management of applications

### SaaS (Software as a Service)

Completed product that is run and managed by the service provider


## Pricing of the Cloud

Compute > Time
Storage > Data stored
Data Transfer OUT 
Data In is FREE

## AWS Cloud Overview

AWS Regions: ex: us-east-1, sa-east-1, etc look for compliance, proximity, avaiable services, pricing
	AWS Availability Zones: ex: sa-east1a/b/c min 3, max 6 / each is one or more data centers with redundant power and network / physically separated from each other
		AWS Edge Locations: used to better latency / over 90+ cities in 40+ countries
		
## Shared Responsibility Model

Customer: Customer Data, Platform, Applications, IAM, Configuration (OS, Network and Firewall), Data Encryption, Data Integrity, Server Side Encryption, Network Traffic Protection
AWS: AWS Software/ AWS Hardware

## IAM

Identity and Access Management > GLOBAL Service
Root account > DON´T USE
Create users!
Users can be grouped / Not mandatory to be in a group / Users can be in more than 1 group

### IAM Permissions

Users can be assigned to policies
Policies define permissions of users
Least privilege principle: don´t give more permissions than a user needs

### IAM Policies

Policies can be attached to groups or inline configured to individual users 
Users that belong to different groups will have different policies attached to

### IAM MFA





## AWS Well Architected Framework





