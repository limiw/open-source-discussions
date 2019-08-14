# Optimizing Cloud Pricing: AWS vs Azure
![](https://cdn.pixabay.com/photo/2017/01/17/12/45/money-1986779_1280.jpg)

When it comes to cloud computing services, many companies spend more than they need to. For the big vendors like Amazon Web Services and Microsoft Azure, the difficulty resides in the complexity of understanding and estimating the costs. That being said, there are several tools and tips to help you optimize your budget for the cloud. In this article, we explain the pricing scheme for both giants and provide tips for managing your cloud costs effectively. 
## The Dilemma: Reducing Your Cloud Costs Without Affecting Performance
Most companies move to the cloud because they want to take advantage of a flexible IT infrastructure while saving on the costs of computing power and storage space. However, once they’ve moved, the cloud budget often grows to a point where they wonder if it is profitable at all. Many companies pay an average of 35% more on cloud services than they should. 

Tackling the complexity of both AWS and Azure pricing is not for the faint of heart. It is difficult to understand the pricing schemes, which factor in the region, volume, and products utilized. Companies tend to accumulate resources, fearing that minimizing costs can affect their performance.

Without understanding how much you are consuming of which services and how much the platform charges for that usage, is impossible to manage those costs. Both companies have tools and information to help consumers. For instance, Azure has an “[Understanding your bill](https://docs.microsoft.com/en-us/azure/billing/billing-understand-your-bill)” section on their website. A calculator can help estimate the costs for the resources you use.


Screenshot of Azure Pricing Calculator

## What’s in Your Bill? Quick Price Scheme Comparison
Both cloud vendors use a pay-as-you-go pricing model, charging for the actual usage per hour of their virtual machine resources. They also offer a range of subscription-based alternatives, with various combinations of models. These include:
### Pay-as-you-go
**Amazon Web Services**
AWS has 5 main billing categories: 
* **Storage and content delivery*—the category includes services such as Amazon S3, CloudFront, [AWS Elastic Block Store (EBS)](https://cloud.netapp.com/blog/ebs-volumes-5-lesser-known-functions), and Amazon Glacier. 
* **Databases—the platform includes products such as managed relational and NoSQL databases data warehousing and migration services in this category. 
* **Code deployment and management*—including automated code deployment, building, and testing code and continuous delivery of released software
* **Compute and Networking*—this category includes services such as EC2, distributing traffic across virtual servers, automatically scaling servers, and Docker containers. 
* **Application services*—including converting digital media into end-device formats, storing queued data for retrieval, hosting streaming applications and coordinating tasks between them. 

Each category has a different pricing structure. Some are priced per hourly usage, others are calculated per volume in GB, or charged a monthly fee. EC2 computing services, for example, are charged per instance-per-hour. 

**Microsoft Azure**
Each Azure service is priced differently, but the bottom line is that the more resources you use, the more you pay. The platform has pricing tiers for each service, for example, for hosting there are four: Free, Shared, Basic and Standard. 

Each service charges according to the resources used per hour. Databases, for example, allow the user to provision the number, type and generation of instances they will use. 
## Reserve and Subscription Options

**Amazon Web Services**
AWS has another pricing scheme that allows to reserve capacity for particular products. It is called Reserved Instance (RI). A user can reserve capacity on a resource and get discounted hourly rates which can amount to 75% on savings of the total billing costs. Consumers can reserve instances for 1 or 3 years terms.

**Microsoft Azure**
Users can save up to 72% of their billing costs if they subscribe for one- to three-year terms for Linux or Windows Virtual Machines. 
## Useful Tools and Tips to Reduce Costs
Now that you understand the price scheme better, it is time to learn a few tricks to reduce your billing costs. 
### 1. What About a Free Tier?
Both vendors offer free plans. If you are a small company, you can take advantage of these features, and use these tiers until you need to scale up. Let’s take a look at what you can get for free.

**Azure**
There are some products that are free for the first 12 months, and others that are always free. Azure products that offer a 12-month free trial include: 

| Linux Virtual Machines | Windows Virtual Machines | Managed Disks | Blob Storage | File Storage | Azure Cosmos DB | Bandwidth  | SQL Database |
|------------------------|--------------------------|---------------|--------------|--------------|-----------------|------------|--------------|
| 750 hs                 | 750 hs                   | 64 GB X 2     | 5 GB         | 5 GB         | 5 GB            | 15 GB      | 250 GB       |

Other products including artificial intelligence such as Face API and containers such as the Azure Kubernetes Service (AKS) are always free.

**Amazon Web Services**
There are three types of products available for the free tier: Free for 12 months, always free and trials. The products that are free for 12 months include 5 GB of storage, 750 hs of Amazon EC2 and machine learning such as Amazon Comprehend. Security and compliance products such as Amazon Macie are always free up to 1 GB in the free tier. 
### 2. Use a Calculator
Estimating how much you will pay and manage your costs is much easier with a calculator. There are several pricing calculators available for AWS and Azure. Some of them include:
* **Unigma Cloud Calculator*—the solution compares computing costs between AWS and Azure. Provides an estimate based on the number of instances required, the GB provisioned, and average hours per day the instances will run. You can adjust this estimate to a different timeframe to compare costs. 
* **NetApp Azure Calculator*—the app estimates Azure costs providing details and a per-gigabyte cost breakdown. It also shows a comparison with their own service. 
* **Azure Pricing Calculator*—this calculator is featured on the platform website to help consumers estimate and configure features based on their needs. 
* **AWS Pricing Calculator*—this platform calculator helps you generate a cost estimate based on your architecture needs. 
### 3. Set up a “Storage Lifecycle”
Each storage category has a different price level depending on redundancy and speed. Archive storage is the cheapest and database storage the most expensive. Therefore, data that you don’t use can often be moved to a cheaper category. 

For example, object stores and archives store raw data, while block and database storage services contain metadata. Setting up a lifecycle policy that moves automatically old files to a cheaper category is a good strategy to cut costs. This option is available both in AWS and Azure.  
### 4. Use Autoscaling and Serverless Features
You can save costs by adjusting the number of working servers according to the workload. Thus, when the demand is low, the number of servers can scale down automatically, shutting down what is not in use. Another option is to go serverless, which allows functions to run only as needed. Azure offers Kubernetes to allocate resources in a cost-effective way, while AWS provides serverless container platforms such as AWS Fargate. 
### 5. Control Server Utilization
Since server usage is the largest component of your bill, you should use tools and implement strategies to minimize costs. A good rule of thumb is to switch off unused servers and resize the servers you use to support your workload.  

There are tools such as [Azure Cost Advisor](https://docs.microsoft.com/en-us/azure/advisor/advisor-cost-recommendations), or [Cloudyn](https://www.cloudyn.com/), that work with Azure to optimize costs. For AWS you can use tools such as AWS Trusted Advisor. These solutions can detect servers when they become available and recommend that they are turned off. 
### 6. Reserve Instances
Using reserved instances, a company can reduce the cost of servers is going to use long term. Discounts vary from forty to sixty percent according to the time of the commitment. In the instance you want to stop using a committed server, you can replace the commitment with a different type of server or cancel the RI and pay a fine.
## Conclusion
Managing the cost of the cloud can be a hassle even for the most experienced organizations. Whether you are a small startup or a medium-sized company, there are ways to cut costs. You can take advantage of the free tier options or utilize RIs or serverless functions, and you can estimate your workload needs to efficiently manage your cloud costs.
