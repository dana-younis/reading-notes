# AWS: Cloud Servers

## Review, Research, and Discussion
 
1. **Describe the Web-Request-Response-Cycle.**

The request/response cycle is a useful guide to see how all the app’s files and folders fit together.

1. **Explain what a “server” is, as it relates to the WRRC**

A HTTP request is a text string created by the client and delivered to the server that contains the details of the resource the client is requesting. A resource is something that can be accessed over the internet. The HTTP request conveys the resource a client wishes to connect with and how the client wishes to interact with it, as well as certain request-related metadata contained in the header.

1. **What does it mean to “deploy” an application?**

Uploading your app to a web server to make the user able to use it 

## Document the following Vocabulary Terms

* **Server:** is a piece of computer hardware or software (computer program) that performs functions for other programs or devices known as "clients."

* **Pub/Sub:** is a form of asynchronous service-to-service communication used in serverless and microservices architectures.

* **WRRC:** The web is a cycle of requests and responses that flow between clients and servers.

## Preparation Materials

* **Amazon Elastic Compute Cloud (Amazon EC2):** is a cloud-based web service that delivers secure, scalable computing capacity. It is intended to make web-scale cloud computing more accessible to developers. The easy web service interface of Amazon EC2 allows you to get and configure capacity with minimum effort. It gives you total control over your computer resources and allows you to run on Amazon's tried-and-true computing environment.

**Reliable, scalable, infrastructure on demand** 

1. Increase or reduce capacity in minutes rather than hours or days.
1. Amazon EC2 region-specific SLA guarantee of 99.99 percent availability. Each area has at least three availability zones.
1. Gartner has identified the AWS Region/AZ architecture as the optimal approach for operating corporate applications that require high availability.

**Flexible options to optimize cost**
1. With On Demand, you only pay for the compute power you require. With AWS Graviton2-based instances, you can get up to 40% better pricing performance or 10% lower prices with AMD-based instances.
1. Amazon EC2 Spot can decrease costs by up to 90% or accelerate performance for fault-tolerant applications such as large data, containers, web services, and continuous integration and delivery (CI/CD).
1. AWS Savings Plans provide up to 72 percent savings on Amazon EC2 instance usage, independent of instance family, size, operating system, tenancy, or AWS Region.
## Virtual Machine : 
Is a piece of software that allows you to run more than one OS (operating system, which is a piece of software that allows you to manage the hardware) on the same machine!
We utilize virtual machines to try out alternative operating systems, test programs on multiple operating systems, and execute applications that require a different/older operating system.


VM manager, also known as (Hypervisor) --> software that allows us to construct virtual machines.

## Cloud Computing: 
is a server that run the VM for use (the server is more powerful than usual computer) and this server exists in the data center (a physical place for servers). When you use another server to run your app this is Cloud Computing 

## Amazon EC2:
Amazon Elastic Compute Cloud is a cloud computing service that offers secure, resizable compute power. Amazon EC2 has the fastest CPUs available in the cloud and is the only cloud with 400 Gbps ethernet networking. You connect to it through CLI or SSH.

## AMI 
Amazon Machine Image (AMI) is the OS for your cloud computing server (VM).

## AWS EBS
Amazon Elastic Block Storage is an external storage that you may connect to your virtual machine so that data is not lost if the server or VM is shut down.

## AWS BeanStalk :
Service for deploying, managing, and scaling Web Apps, mobile apps, or APIS servers. It scales and manages the app automatically as needed. Elastic BeanStalk is free, and you just pay for the extra AWS resources you use.