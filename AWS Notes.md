# AWS Well Architected Framework
* Security
* Performance
* Reliability
* Cost Optimized
# AWS EC2
* EC2 Instance Types
* EC2 Pricing Models
  * On Demand Instances
  * Spot Instances
  * Reserved Instances
  * Dedicated Host
* Types of Virtualization
  * PV (Para Virtual)
  * HV (Hardware Virtual)
* Supported OS and Licensing
* EC2 Container Service
* EBS (Elastic Block Storage)
  * EBS Snapshots
  * EBS Snapshots Replication via S3
  * EBS Encryption
* Elastic IPs
* Cluster Placement Group
* AWS EC2 Load Balancer
  * Types of Load Balancers.
  * AWS EC2-Classic Load Balancer
  * AWS EC2-VPC Load Balancer
  * Protocol Supported by ELB
* AWS EC2 Auto Scaling
  * Automatic Time-based Scaling (Cyclic Scaling)
  * Automatic Load-based Scaling
* Reserved Instance Marketplace
* EC2 Bastian Host
* EC2 Launch Config
# AWS VPC
Names of availability zones are randomly applied for each account.
# AWS Import/Export
* AWS SnowMobile
* AWS SnowBall
* AWS DirectConnect
# AWS Management Tools
* AWS CloudWatch
# AWS Analytics
* AWS DataPipeline
# AWS RDS
* Cross Region Read Replica
* RDS Read Replicas
* RDS Multi-AZ
* RDS Storage Types 
  * General Purpose SSD
  * Provisioned IOPS
* Upgrade RDS Instance
* RDS Maintenance
* Database Migration Service
* RDS Import/Export
# AWS Storage Gateway
* File Gateway
* Volume Gateway
  * Cached Volume
  * Stored Volume
* Tape Gateway
# AWS ElastiCache
* Memcached
* Redis
# AWS SQS
* Supports both standard and FIFO queues
* Usage
  * Decoupling the components of an application
  * Configuring individual message delay
  * Dynamically increasing concurrency & througuput at read time
  * Scalling transparently
* Main Features of SQS
  * Redundant Infrastructure
  * Multiple producers and consumers
  * Configurable settings per queue
  * Variable Message Size
  * Access Control
  * Delay Queues
  * PCI Compliance
# AWS SWF
# AWS Cloud Formation
# Route 53
* Supports domain registration
# AWS Best Practices
* Create Roles instead of storing access keys.
# AWS IAM
* Cross Account Authentication
# AWS S3
* S3 Storage Class
  * S3 Standard
  * S3 IA 
  * S3 RRS
  * Glacier
* S3 Lifecycle Policies
* MFA Delete
* S3 Data Consistency Model
* IPv6 Support
* S3 Transfer Acceleration
* S3 Multipart Uploads
* Encryption
  * SSE (Server Side Encryption)
    * SSE-S3 (SSE with S3 Managed Master Key)
    * SSE-KMS (SSE with AWS KMS Managed Master Key)
    * SSE-C (SSE with Customer Managed Master Key)
  * CSE (Client Side Encryption)
    * CSE with AWS KMS Managed Customer Master key
    * CSE with Client Side Master Key
  * S3 Static Web Hosting
    * S3 Supports redirects.
  * S3 URL Format
    * Static website hosting: bucketName.s3-website-regionName.amazonaws.com
  * S3 Cross Region Replication
    * Object meta-data, ACL, object certificates.
    * Versioning Enabled at Source & Destination
# AWS Limits
* S3 minimum file size is 0 Byte.
* S3 maximum file size 5 TB.
* All S3 durability eleven 9s except S3 RRS which is 99.99.
* S3 availability, Standard – 99.99, IA – 99.90, Glacier – 99.00, S3 RRS – 99.99.
* Max 5 Elastic IPs allowed in a Region.
* Max 100 buckets allowed per account.
* EC2 SLA – 99.95.
* Cloud watch stores metrics for 2 weeks after deleting resources.
* RDS by default minimum retention period – 1 day, maximum – 35 days.
* Minimum SSD EBS volume size 1 GB.
* AWS Cloudwatch minimum time interval granularity for the data that Cloudwatch receives and aggregates – 1 min.
* EC2 Reserved instances purchase limit: 20 instances / AZ / month.
* Max #vmwares migrated concurrently : 50
* Max size of general purpose ssd 16 : 16TiB
* Free invalidation paths per month(to remove data from Edge Location) : 1000
* The Root account has total access to all services.
* 1 KB <= SQS Message Size <= 256KB
* SQS Queue Name : 80 Char Limit
* SQS Default Visibility Timeout : 30 Seconds
* SQS Min Visibility Timeout : 0 Seconds
* SQS Max Visibility Timeout : 12 hours
* SQS Default Message Retention Period : 4 days
* SQS Min Message Retention Period : 1 min
* SQS Max Message Retention Period : 14 days
* SQS Min Delivery Delay : 0 Seconds
* SQS Max Delivery Delay : 15 mins
* SQS Min Receive Message Wait Time : 0 Seconds
* SQS Max Receive Message Wait Time : 20 Seconds
* SQS FIFO Queue Transaction Limit : 300 tx/second
* SQS FIFO Queue Naming Convention : must end with ".fifo"
* SQS FIFO does not support timers on individual messages
* SQS FIFO In flight messages storage limit : 120,000
* SQS Max Lenghth Message ID : 100 chars
* SQS Max Lenghth Receipt Handle ID : 1024 chars
* SQS Deadletter queue must reside in the same region than that of original queue
* SQS Queue Names and URLs are case sensitive
* S3 size to support the SQS message : 2 GB
* 
