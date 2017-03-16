1. AWS S3
  1. S3 Storage Class
  1. S3 Standard

1.1.2.	S3 IA 
1.1.3.	S3 RRS
1.1.4.	Glacier
1.2.	S3 Lifecycle Policies
1.3.	MFA Delete
1.4.	IPv6 Support
1.5.	S3 Transfer Acceleration
1.6.	S3 Multipart Uploads
1.7.	Encryption
1.7.1.	SSE (Server Side Encryption)
1.7.1.1.	SSE-S3 (SSE with S3 Managed Master Key)
1.7.1.2.	SSE-KMS (SSE with AWS KMS Managed Master Key)
1.7.1.3.	SSE-C (SSE with Customer Managed Master Key)
1.7.2.	CSE (Client Side Encryption)
1.7.2.1.	CSE with AWS KMS Managed Customer Master key
1.7.2.2.	CSE with Client Side Master Key
1.8.	S3 Static Web Hosting
1.8.1.	 S3 Supports redirects.
1.9.	S3 Cross Region Replication
Object meta-data, ACL, object certificates.
1.10.	S3 URL Format
1.10.1.1.	static website hosting: bucketName.s3-website-regionName.amazonaws.com

2.	AWS IAM
2.1.	Cross Account Authentication
3.	AWS EC2
3.1.	EC2 Instance Types
3.2.	EC2 Pricing Models
3.2.1.	On Demand Instances
3.2.2.	Spot Instances
3.2.3.	Reserved Instances
3.2.4.	Dedicated Host
3.3.	Types of Virtualization
3.3.1.	PV (Para Virtual)
3.3.2.	HV (Hardware Virtual)
3.4.	Supported OS and Licensing
3.5.	EC2 Container Service
3.6.	EBS (Elastic Block Storage)
3.6.1.	EBS Snapshots
3.6.2.	EBS Snapshots Replication via S3
3.7.	Elastic IPs
3.8.	Cluster Placement Group
3.9.	AWS EC2 Load Balancer
3.9.1.	Types of Load Balancers.
3.9.2.	AWS EC2-Classic Load Balancer
3.9.3.	AWS EC2-VPC Load Balancer
3.9.4.	Protocol Supported by ELB
3.10.	AWS EC2 Auto Scaling
3.11.	Reserved Instance Marketplace
4.	AWS VPC
•	Names of availability zones are randomly applied for each account.
5.	AWS Import/Export
5.1.	AWS SnowMobile
5.2.	AWS SnowBall
5.3.	AWS DirectConnect
6.	AWS Management Tools
6.1.	AWS CloudWatch
7.	AWS Analytics
7.1.	AWS DataPipeline
8.	AWS RDS
8.1.	Cross Region Read Replica
8.2.	RDS Read Replicas
8.3.	RDS Multi-AZ
8.4.	RDS Storage Types 
8.4.1.	General Purpose SSD
8.4.2.	Provisioned IOPS
8.5.	Upgrade RDS Instance
8.6.	RDS Maintenance
8.7.	Database Migration Service
8.8.	 gcdmRDS Import/Export
9.	AWS Storage Gateway
9.1.	File Gateway
9.2.	Volume Gateway
9.2.1.	Cached Volume
9.2.2.	Stored Volume
9.3.	Tape Gateway
10.	AWS ElastiCache
10.1.	Memcached
10.2.	Redis
11.	AWS SQS
12.	AWS SWF
13.	AWS Cloud Formation
14.	Route 53
14.1.	Supports domain registration
15.	AWS Limits
•	S3 minimum file size is 0 Byte.
•	S3 maximum file size 5 TB.
•	All S3 durability eleven 9s except S3 RRS which is 99.99.
•	S3 availability, Standard – 99.99, IA – 99.90, Glacier – 99.00, S3 RRS – 99.99.
•	Max 5 Elastic IPs allowed in a Region.
•	Max 100 buckets allowed per account.
•	EC2 SLA – 99.95.
•	Cloud watch stores metrics for 2 weeks after deleting resources.
•	RDS by default minimum retention period – 1 day, maximum – 35 days.
•	Minimum SSD EBS volume size 1 GB.
•	AWS Cloudwatch minimum time interval granularity for the data that Cloudwatch receives and aggregates – 1 min.
•	EC2 Reserved instances purchase limit: 20 instances / AZ / month.
16.	AWS Best Practices
•	Create Roles instead of storing access keys.
