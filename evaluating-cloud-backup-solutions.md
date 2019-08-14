# Evaluating Cloud Backup Solutions (AWS vs. Azure vs. Google Cloud)
![aws vs. azure vs. google backup](https://cdn.pixabay.com/photo/2018/04/19/16/47/cloud-3333628_1280.png)

When an attack happens, the most important thing is to restore the systems as soon as possible. The staggering costs of a data breach are driving organizations to choose backup and recovery solutions to ensure they can bounce back after an attack. 

There are several solutions for backup and recovery, some on-premises and others cloud-based. Although they provide similar core services, each platform has its own strengths and weaknesses. 

In this article, we will cover what is a cloud backup and recovery solution, why it is important and will analyze the three top vendors, [Google](https://cloud.google.com/storage/archival/), [Azure](https://azure.microsoft.com/en-us/services/backup/) and [Amazon Web Services](https://aws.amazon.com/backup-restore/). We aim to highlight their key features, pricing, and support to help you choose the right solution for your organization.  
## What Is a Cloud Backup and Recovery Solution?
Cloud Backup automates the backing up and storing your data from your servers to a secure private or public cloud service. Backup and recovery solutions allow you to restore the critical systems of your environment in the event of a disaster such as a data breach. Let’s take a look at the differences between having your backup on-premises or on the cloud.
 
The key differences between the two systems lie in the recovery time and the security they offer. 
* **Recovery time**—On-premise backups usually take longer, from hours to weeks to recover and upload the data. This will depend on the type of storage chosen and its location. On the other hand, cloud backups are much faster, taking from minutes to hours to fully recover. Since it is already stored in the cloud there is no retrieving and uploading time.  
* **Security**—The public or private cloud hosting the backup leverages from security solutions such as threat intelligence systems that monitor the environment and prevent threats. 
*Top Three Cloud-Based Recovery Solutions Compared
There are several could vendors that offer an array of features and disaster recovery solutions. The top three cloud platforms are Google, Azure and Amazon Web Services (AWS). Let’s have a look at what they have to offer. 
## Amazon Web Services
The oldest of the three platforms, AWS is an Infrastructure-As-A-Service (IaaS) cloud services platform. The platform offers over 140 services, among them security features such as data encryption, access control, and a firewall system. AWS leverages from Amazon’s shopping platform data center regions’ network, allowing users to select a region close to their traffic origin. This enables for fast transfers of data from and to the cloud, speeding recovery in case of disaster. 
*Features*
* **Data durability**—copies of all data uploaded to AWS S3 are stored on three devices in a single AWS region. 
* **Flexibility and scalability**—scales up backup resources in minutes. 
* **Cost-efficient**—with pay-as-you-go pricing. It provides a range of storage classes,  (Object Storage Classes)  so you can choose the right storage for your use cases and adjust your costs accordingly.
* **Support for all data types**—offers backup for all data types. Includes storage services for blocks, files and objects. 
* **Security and compliance**— AWS security platform use built-in network firewalls to control access to applications and instances. The system keeps its customers data secure by automatically encrypting all traffic. It also manages compliance programs in its infrastructure, providing compliance reports. 
*Pricing*
The platform offers a pricing scheme on a per-hour payment basis. Provides a free plan with limited storage and computing capability that is useful for start-ups or individuals. The on-demand pricing model allows paying monthly for per-hour billed usage.   
*Support*
Amazon S3 offers 24/7 free support for basic troubleshooting. General inquiries usually are answered within 24 hrs. However, the platform charges monthly for more advanced technical support, with response times varying according to the chosen plan, from twelve hours on the developer plan to fifteen minutes on the enterprise plan. Several features such as third-party software support are available only for the business and enterprise plan. 
*Benefits of AWS Backup*
* **Centrally manages backups**—from a central console allowing to backup and restore data. 
* **Automates backup processes**—provides automated backup schedules. The system is easy to implement. You can apply backup policies by tagging your AWS resources.
## Microsoft Azure
A hybrid cloud platform that focuses on the Internet of Things (IoT) DevOps and app development. Azure offers Platform-As-A-Service (PaaS) resources such as [Azure backup](https://cloud.netapp.com/blog/5-considerations-before-you-backup-on-azure) and Azure Site Recovery (ASR). The platform allows for data encryption and offsite storage.  
*Features*
* **Security and Availability**—Azure backup stores the data in three separated servers at the primary data center and another three copies in an alternative location. Provides data encryption across all traffic and while at rest. 
* **Efficient Bandwidth Utilization**—The platform generates an initial full backup that is updated periodically on a schedule. This minimizes bandwidth consumption. 
* **Integration with Data Protection Manager (DPM)**—allows Microsoft users to create a hybrid backup service.
* **Virtual Machines replication automation**—using ASR, allowing to replicate even on-premises virtual machines and physical servers to Azure. 
* **Varied operating systems support**—from Windows to Linux based, ASR supports a variety of applications and operating systems. 

Additional features include:
* Automatic Storage Management
* Unlimited Scaling
* Unlimited Data Transfer
* Long-Term Retention
*Pricing*
The solution offers pre-paid or monthly payment options. Azure rates are calculated factoring the amount of storage provisioned, the geographical location, the usage frequency and the type of data redundancy you choose. The price is calculated per minute of usage. While it seems complicated at first, the platform’s pricing model helps users to manage costs when appropriately managed. 
*Support*
Azure offers free, basic support, with three paid tiers for advanced support.  Response times range from business hours for the Developer tier to 24/7 for the Standard and Professional Direct tiers. For critical issues, the response time goes from up to eight hours to up to one hour. 

Account management and advisory services are only available for the top layer. In addition, there is a ‘Premier Support’ layer boasting a response time of up to 15 minutes besides account management and advisory services. 
*Benefits of Azure Backup and Recovery*
* High performance
* High computing capability 
* Integration with the other Microsoft services 
## Google Cloud
Google Cloud Storage is a service within the Google Cloud Platform (GCP), enabling unified object storage and archived data. Like AWS, the platform offers users the option to choose the geographical region to store their data. For backup and recovery services, Google relies on third-party service providers that integrate seamlessly with the platform.
*Features*
* **Third-party providers**—allow users to choose what backup service fits best their needs. For example, Coldline and Nearline manage cold and warm storage, respectively, and are available for all GCP regions. 
* **Guaranteed 99.99% SLA**—that means that downtime is kept to a minimum. 
* **High scalability**—to exabytes of data.
* **Automatic backup scheduling**—several providers offer automated backup scheduling, retention and storage tiering. 

Additional features include:
* Persistent storage for snapshots
* Regional storage for backups 
* Nearline/Coldline storage for archives. 
*Pricing*
Pay-as-you-go billed per-minute or per-second of usage. Several partners offer a 1 cent per GB/month for warm data storage and 0.7 cents per GB/month for cold data storage. 
*Support*
Google Cloud Storage features a free tutorial support center, with an active community that can help solve most basic troubleshooting. It provides three paid tiers of advanced support with a monthly cost. For critical issues, the time goes from four business hours to 15 min for the top tier. Consultations and technical account management are available only for the top tiers. 
*Benefits of Google Backup*
Better prices than other providers
Excellent networking speed
Fastest recovery times.
Providers integrate with Google Cloud Storage. 
## Which One Should You Choose? 
Although it is not an easy feat to choose the best cloud backup service provider for your organization, we aimed to provide you with the information to make a choice. Different types of companies will match with different cloud vendors. 

For example, if your organization already uses a lot of Microsoft products, Azure can be a natural choice. If your company is a small startup looking for cost-effective pricing and fast scalability, you can consider Google Cloud Platform. Companies looking for a wide catalog of services and multi-region scope can look into AWS. It will depend on your company’s needs to check which provider addresses them best. 
