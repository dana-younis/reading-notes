# AWS: S3 and Lambda

## Review, Research, and Discussion

1. **Describe “The Cloud”**

"The cloud" refers to servers that are accessed over the Internet, and the software and databases that run on those servers. 

1. **What is a container (as it relates to computers and servers)?**

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 

1. **What is auto-scaling?**

Auto Scaling lets you build scaling plans that automate how groups of different resources respond to changes in demand.

1. **What is bandwidth?**

The maximum amount of data transmitted over an internet connection in a given amount of time.

1. **How do cloud providers compute service costs?**

When determining pricing, cloud providers consider the cost of network maintenance. They begin by estimating network hardware, network infrastructure maintenance, and personnel expenses. These costs are totaled and then split by the number of rack units required for an IaaS cloud.

## Document the following Vocabulary Terms

* **Server Instances:** is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based.

* **Containers:** is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 

* **Cloud Services:** a wide range of services delivered on demand to companies and customers over the internet. 

* **Cloud Architecture:** the many components (databases, software capabilities, apps, and so on) designed to utilize the power of cloud resources to address business issues The components of the cloud, as well as the interactions between them, are defined by cloud architecture.
* **AWS:** is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

* **EC2/Beanstalk vs Heroku:** Elastic Beanstalk is one layer of abstraction away from the EC2 layer. Elastic Beanstalk will setup an "environment" for you that can contain a number of EC2 instances, an optional database, as well as a few other AWS components such as a Elastic Load Balancer, Auto-Scaling Group, Security Group.

## Preparation Materials

### AWS S3

* **Amazon Simple Storage Service (Amazon S3):** is an object storage service that offers industry-leading scalability, data availability, security, and performance. 

### AWS Lambda

* **AWS Lambda** is a serverless computing service provided by Amazon Web Services (AWS).

* **How does AWS Lambda work?**

Each Lambda function is executed within its own container. When a function is generated, Lambda wraps it into a new container, which is subsequently executed on an AWS-managed multi-tenant cluster of computers. Each function's container is assigned the required RAM and CPU capacity before the functions begin to operate. When the functions are finished, the RAM allocated at the start is multiplied by the amount of time the function was executing. Customers are then charged depending on the allotted memory and the length of time it takes the function to finish.

#### **When building Serverless applications, AWS Lambda is one of the main candidates for running the application code. Typically, to complete a Serverless stack you’ll need:**

* a computing service.
* a database service. and
* an HTTP gateway service.

#### **What are the most common use cases for AWS Lambda?**

1. individual tasks run for a short time.
1. each task is generally self-contained.
1. there is a large difference between the lowest and highest levels in the workload of the application.

* **Use cases**

1. Real-time file processing
1. Real-time stream processing
1. Machine learning
1. Backends
1. Web applications
1. Mobile backends


### Content Delivery Network (CDN)

* **Content Delivery Network (CDN):** is a geographically dispersed set of servers that collaborate to provide Internet information quickly. A CDN enables the rapid transport of data required for the loading of Internet content such as HTML pages, javascript files, stylesheets, pictures, and videos.
#### CDNs work through servers nearest to the website visitor respond to the request. 

* **What does this mean for an SMB?**
CDNs are more likely to be implemented by larger organizations. The primary reasons why businesses desire to utilize CDNs are to enhance Internet website load times, content delivery speeds, and to minimize the probability of falling victim to and strengthen defenses against Distributed Denial of Service attacks (DDoS).
 

## CDNs 
A Content Delivery Network (CDN) is a geographically distributed set of computers that collaborate to deliver Internet content quickly. A CDN enables the rapid transport of data required for the loading of Internet content such as HTML pages, javascript files, stylesheets, pictures, and videos.

Here's how it works:

When a user requests a webpage from a content delivery network, the CDN will reroute the request from the original site's server to a CDN server nearest to the user and provide the cached material. CDNs will also connect with the source server to provide any previously uncached material.


Benefits of using CDNs:
 1. Increase Speed.
 2. Decrease Load on the server.
 3. Uptime.
 4. Increase server security.

 A smaller company probably doesn’t need to improve website load speeds with a CDN as they typically don’t have an overwhelming amount of traffic.

# 
 Which 3 things had you heard about previously and now have better clarity on?
EC2, Beanstalk and Cloud services

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
Cloud architecture, more AWS services and Server instance.

What are you most excited about trying to implement or see how it works?
AWS S3, Lambda and Lambda functions.

## Cloud Services:
Is a service that allows customers to utilize different distant computers/VM as if they owned it. The benefits of Cloud services include: - Lowering hardware/software expenses.
- Load Distribution.

- Portability.

- Data access and backup

- routine upkeep

- Increased security and speed.

- Cooperation.

Types of Cloud Services:
SaaS --> Software as a service. (google drive, gmail)
Paas --> platform as a service. (GitHub, Heroku, AWS Elastic beanstalk, Netlify)
Iaas --> Infrastructure as a service. (AWS EC2, Azure)