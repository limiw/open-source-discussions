# Open Source Disaster Recovery? An Overview of Free and Open Source DR
![](https://cdn.pixabay.com/photo/2017/02/08/14/31/computer-2049019_1280.jpg)

### Overview 

Disaster recovery (DR) involves the use of tools, processes, and policy-based rules to quickly restore a company’s most important IT infrastructure in the event of an unplanned outage. These outages or disasters could be as a result of natural causes ( e.g. hurricanes knocking out power grids) or human influences (an employee accidentally deleting a database).

You can view DR as a subset of business continuity in which the emphasis is on restoring mission-critical systems, data, and applications. The broader context of business continuity deals with planning, preparation, strategies, and tools to recover normal operations after a disaster. 

Failure to adequately implement a disaster recovery plan can wreak havoc on a business or organization. The longer your mission-critical systems remain offline, the higher the costs associated with a disaster. [Gartner](https://blogs.gartner.com/andrew-lerner/2014/07/16/the-cost-of-downtime/) estimates the cost of downtime to be in the region of $5,600 per minute for the average business, which suggests just how important it is to have the necessary processes and tools in place for quick recovery. 

Speaking of tools, disaster recovery is an area in which the open source model has again shown its worth in making a range of high-quality tools freely available to the public. Some companies or individuals might not have the budget to afford enterprise-level proprietary tools. However, open source tools can assist with getting mission-critical systems back online or restoring your most important data swiftly following an outage. This article discusses five excellent and free DR tools. 

### Open Source DR Tools

**Clonezilla**

This disk cloning and data recovery program comes in both a single-desktop Live edition and an SE server edition. The server edition can be deployed on 40 machines at the same time. Clonezilla is particularly good for disasters that result in the loss of important data. You can completely clone the contents of an individual hard disk drive to an external drive. 

Clonezilla falls under the category of bare metal backup and recovery options, which means that you can use this tool to easily rebuild failed systems from scratch after they suffer some sort of failure.

**Amanda**

This open source backup and recovery software protects more than a million servers and desktops worldwide. The software protects computers and services running various operating systems, including Windows, Linux, and Mac OS-X. 

Amanda dramatically simplifies DR by letting administrators set up a single server which backs up multiple networked clients to a variety of storage options, such as tape storage, Amazon S3 cloud storage, or disk storage. 

**Relax and Recover**

Relax and Recover is another open source disaster recovery tool that falls under the category of bare metal recovery. The tool uses a set-and-forget approach, allowing you to easily set up a data backup option for later recovery without any ongoing maintenance. 

Individual users can recover home systems from a bootable USB stick while organizations can collect ISO images on a central backup server. Relax and Recover is a Linux tool. 


**Bacula**

Bacula provides enterprise-level open source data backup and recovery software. What’s great about this tool is that it helps to automate laborious processes that typically require the input of a system administrator or user. 

Bacula works on networks featuring many different kinds of computer systems and it has client-server communication over TCP/IP, client-side compression, and data encryption features. You also have the option to store your backed up data in a secondary off-site location. 

**Disaster Recovery Linux Manager**

Disaster Recovery Linux Manager (DRLM) provides open source centralized management of disaster recovery implementations that use relax and recover. As the size of the infrastructure grows from a couple of machines to tens of machines or even hundreds, it becomes essential to use a management tool for more efficient management of DR backups and lower costs. 

DRLM lets you create, modify, and delete relax and recover clients and networks using simple commands. You can also restore specific clients with just one command, and you can start rear backups remotely.

### Additional DR Tools

The value of paid tools is that they typically come with better customer support and more features than their open source counterparts, although this is not always strictly true. Some examples of premium DR tools include:

* Azure Site Recovery—this cloud-based disaster recovery service uses the [Microsoft Azure](https://azure.microsoft.com/en-us/services/site-recovery/) cloud to deliver mission-critical IT infrastructure while promising rapid recovery times. Helpfully, you can use this service for free to start out. 
* IBM Resiliency Services—[IBM’s Disaster Recovery as a Service (DRaaS)](https://www.ibm.com/us-en/marketplace/disaster-recovery-as-a-service) option continuously replicates critical data and infrastructure to the cloud for rapid recovery during the all-important post-outage phase. 
* N2WS—this [AWS disaster recovery service](https://n2ws.com/product/aws-disaster-recovery) protects organizations dependant on AWS from AWS outages by replicating cloud instances and storage volumes to different regions. 

### Wrap Up

Disaster recovery doesn’t have to be prohibitively expensive, and these open source tools show that you can achieve a good level of protection without spending a dime. If you have the budget and your organization is large, you might consider some of the enterprise-level options.
