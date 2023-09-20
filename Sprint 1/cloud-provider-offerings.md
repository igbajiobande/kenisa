# Different Cloud Providers & Their Offerings

*Submission by cohort4-group3 for sprint 1 group story*



## What do Cloud Providers Offer?

These cloud providers offers a broad spectrum of services and features, including infrastructure as a service (IaaS), platform as a service (PaaS), and software as a service (SaaS).  The choice of a cloud provider depends on your specific requirements, such as performance, scalability, geographic presence, and existing technology stack. Pricing is essential for evaluating the offerings and pricing of each provider to determine the best fit for your organization's needs. The list above shows the major cloud providers. They offer a wide range of cloud computing services and solutions. Each provider has its unique strengths and offerings, making them suitable for different use cases and industries. Here are some of the major cloud providers and a brief overview of their offerings:



***

## Amazon Web Services (AWS)

The world's most comprehensive and broadly adopted cloud with over 200 fully featured services from data centres globally [4].  

### Service Level Agreements (SLAs)

Amazon doesn't provide a standardized uptime commitment or service-level agreement (SLA) across the entire AWS cloud, but rather provides SLAs for each individual service. In the case of EC2 -- Amazon's platform for hosting VM instances -- Amazon offers a regional-level SLA of 99.99% and an instance-level SLA of 99.5%. The company provides a tiered system of service credits, where the service credit percentage is tied to the duration of an outage, with longer outages eligible for larger service credits [3].

### Regions & Zones

Amazon currently consists of 27 regions around the globe and has a total of 87 availability zones. [3,7]

### Pricing

Like the competing clouds, Amazon uses a "pay as you go" model for its AWS cloud resources. The formulas used to calculate usage costs are quite complex, but Amazon [offers a pricing calculator](https://calculator.aws/#/?nc2=pr) that can help determine overall costs. Amazon also makes some resources available in a free tier. These free tier resources tend to be helpful to those who want to learn how the various AWS services work without investing a lot of money. [3]

### Overview of Products Offered

| Product Type        | Name of Product/s                                        |
| ------------------- | -------------------------------------------------------- |
| Compute             | AWS Elastic Compute Cloud (EC2), AWS Lambda (serverless) |
| Storage             | Amazon S3 (object storage), Amazon EBS (block storage)   |
| Databases           | Amazon RDS, Amazon DynamoDB, Amazon Aurora               |
| Networking          | Amazon VPC, AWS Direct Connect                           |
| Machine Learning/AI | Amazon SageMaker, AWS AI/ML services                     |
| Analytics           | Amazon Redshift, Amazon EMR                              |
| Developer Tools     | AWS CodeDeploy, AWS CodePipeline                         |
| IoT                 | AWS IoT Core                                             |
| Security            | AWS Identity and Access Management (IAM), AWS WAF        |



***

## Microsoft Azure Cloud Platform (Azure)

Widely considered to be the world's second largest cloud with more than 200 products and cloud services.

### Service Level Agreements (SLAs)

Like AWS, Microsoft has a separate SLA for each individual service within its Azure cloud. Microsoft's uptime guarantee for Azure VMs is very similar to Amazon's SLA. VMs consisting of at least two instances and deployed across two availability zones are guaranteed to have 99.99% availability. That drops to 99.95% availability if the instances are in the same availability zone. The SLA for single-instance VMs varies depending on the hardware configuration, but all VM instances are guaranteed to have at least 95% availability. Like Amazon, Microsoft offers credits when SLAs aren't met.

### Regions & Zones

Microsoft currently offers 27 regions that each support multiple availability zones. In total, there are 60 regions and 116 availability zones.

### Pricing

Microsoft claims "AWS is up to five times more expensive than Azure for Windows Server and SQL Server." Microsoft further states that running Windows VMs on Azure can yield up to a 71% savings over running those VMs on AWS EC2. The company makes similar claims about SQL managed instances and SQL Server VMs with savings of 85% and 45%, respectively. Ultimately, the amount paid depends on several factors. Microsoft provides a pricing calculator to estimate the cost of running various workloads on Azure.

### Overview of Products Offered

| Product Type        | Name of Product/s                                              |
| ------------------- | -------------------------------------------------------------- |
| Compute             | Azure Virtual Machines, Azure Functions (serverless)           |
| Storage             | Azure Blob Storage, Azure Disk Storage                         |
| Databases           | Azure SQL Database, Azure Cosmos DB                            |
| Networking          | Azure Virtual Network, Azure ExpressRoute                      |
| Machine Learning/AI | Azure Machine Learning, Azure Cognitive Services               |
| Analytics           | Azure HDInsight, Azure Data Lake Analytics                     |
| Developer Tools     | Visual Studio Team Services (Azure DevOps), Azure DevTest Labs |
| IoT                 | Azure IoT Hub, Azure IoT Central                               |
| Security            | Azure Active Directory, Azure Security Centre                  |



***

## Google Cloud Platform (GCP)

The third biggest cloud provider with over 150 cutting-edge products.

### Service Level Agreements (SLAs)

Like Microsoft and Amazon, Google ties its SLAs to specific services. In the case of Google's Compute Engine, a single instance is guaranteed to have greater than 99.5% availability. That number increases to 99.99% for instances in multiple zones or for load-balanced instances. Google also offers a financial credit when it fails to meet its SLAs.

### Regions & Zones

Google has an impressive number of data centres in the Asia-Pacific region, North America, South America, Europe and the Middle East. Collectively, these account for the company's 34 regions and 103 availability zones. There are approximately three dozen availability zones in North America alone.

### Pricing

Google [offers the same type of pay-as-you-go pricing as other providers. Those who wish to try out Google Cloud can receive up to $300 in free credits and access to more than 20 products within the Google Cloud. Because cloud pricing tends to be complex, [Google provides a pricing calculator](https://cloud.google.com/products/calculator) that can estimate what it will cost to run various workloads in Google Cloud.

### Overview of Products Offered

| Product Type        | Name of Product/s                                             |
| ------------------- | ------------------------------------------------------------- |
| Compute             | Google Compute Engine, Google Cloud Functions (serverless)    |
| Storage             | Google Cloud Storage, Google Persistent Disk                  |
| Databases           | Google Cloud SQL, Google Cloud Bigtable                       |
| Networking          | Google Virtual Private Cloud (VPC), Google Cloud Interconnect |
| Machine Learning/AI | Google AI Platform, TensorFlow                                |
| Analytics           | BigQuery, Dataflow                                            |
| Developer Tools     | Google Cloud SDK, Cloud Source Repositories                   |
| IoT                 | Google Cloud IoT Core                                         |
| Security            | Identity-Aware Proxy, Google Cloud Security Command Center    |



***

## IBM Cloud

### Overview of Products Offered

| Product Type        | Name of Product/s                                                          |
| ------------------- | -------------------------------------------------------------------------- |
| Compute             | IBM Virtual Servers, IBM Cloud Functions (serverless)                      |
| Storage             | IBM Cloud Object Storage, IBM Cloud Block Storage                          |
| Databases           | IBM Db2, IBM Cloudant                                                      |
| Networking          | IBM Cloud Virtual Private Cloud (VPC), IBM Direct Link                     |
| Machine Learning/AI | IBM Watson, Watson Studio                                                  |
| Analytics           | IBM Cloud CLI, IBM Cloud Code Engine                                       |
| Developer Tools     | IBM Db2 Warehouse, IBM Watson Discovery                                    |
| IoT                 | IBM Watson IoT Platform                                                    |
| Security            | IBM Cloud Identity and Access Management (IAM), IBM Cloud Security Advisor |

## 

***

## Oracle Cloud

### Overview of Products Offered

| Product Type        | Name of Product/s                                                           |
| ------------------- | --------------------------------------------------------------------------- |
| Compute             | Oracle Compute, Oracle Functions (serverless)                               |
| Storage             | Oracle Cloud Object Storage, Oracle Block Volume                            |
| Databases           | Oracle Autonomous Database, Oracle Database Cloud Service                   |
| Networking          | Oracle Virtual Cloud Network (VCN), Oracle FastConnect                      |
| Machine Learning/AI | Oracle Cloud Machine Learning, Oracle AI Platform                           |
| Analytics           | Oracle Analytics Cloud, Oracle Big Data Cloud Service                       |
| Developer Tools     | Oracle Cloud Infrastructure CLI, Oracle Developer Cloud Service             |
| IoT                 | Oracle Internet of Things (IoT) Cloud Service                               |
| Security            | Oracle Identity and Access Management (IAM), Oracle Cloud Security Services |

***

## References

[1] - [Scott Pletcher (Pluralsight) - AWS vs Azure vs GCP: The big 3 cloud providers compared]([AWS vs Azure vs GCP: The big 3 cloud providers compared](https://www.pluralsight.com/resources/blog/cloud/aws-vs-azure-vs-gcp-the-big-3-cloud-providers-compared))

[2] - [Rehnuma Tasnim (DIU Bangladesh) - A Comparative Study on Three Selective Cloud Providers](https://arxiv.org/ftp/arxiv/papers/2208/2208.14482.pdf)

[3] - [Brien Posey (TechTarget) - Top public cloud providers of 2023: A brief comparison]([Top Public Cloud Providers of 2023: A Brief Comparison](https://www.techtarget.com/searchcloudcomputing/tip/Top-public-cloud-providers-A-brief-comparison))

[<div id="four">4</div>] - [Amazon Web Services (AWS) - Cloud computing with AWS]([What is AWS](https://aws.amazon.com/what-is-aws/))

[5] - [What is Azure—Microsoft Cloud Services | Microsoft Azure](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-azure/)

[6] - [Google Cloud (Google) - The new way to cloud starts here](https://cloud.google.com/?hl=en)

[7] - [Amazon Web Services (AWS) - Regions & Availability Zones]([Global Infrastructure Regions &amp; AZs](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/))
