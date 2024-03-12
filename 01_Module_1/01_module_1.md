# 1. Module 1 - Cloud Concepts Overview
> ### **Topics**
> * Introduction to cloud computing
> * Advantages to cloud computing 
> * Introduction to Amazon Web Services (AWS)
> * AWS Cloud Adoption Framework (AWS CAF)

> Resources: <br>
> [Types of Cloud Computing](https://aws.amazon.com/types-of-cloud-computing/) <br>
## 1. Introduction to Cloud Computing
### 1. Definition 
**Cloud computing** is the **on-demand** delivery of computer power, database, storage, applications, and other IT *resources* **via the internet** with **pay-as-you-go** pricing.

These *IT resources* run on server computers located in large data centers in numerous locations of the world. 
→ When we use AWS cloud services, we’re using the computers owned by that service provider. 

* In a ***traditional computing model***, you need to manage and maintain the hardware infrastructure for your software, which require spaces, staff, physical security, lots of planning, and money, etc. 
→ This approach can be labor-intensive, expensive and time-consuming.
* ***Clouding computing model*** enables you to think as your infrastructure as software. 
	* It is *flexible*, allowing you to select cloud services that best match your needs. 
	* You only pay for what you use, when you use it, so you can *scale resources* up and down to match your demand. 
→ These IT resources as treated as temporary and disposable, allowing you to implement solutions quickly with low up-front cost. 
### 2. Cloud Service Models
![cloud-service-models | 600](https://i.imgur.com/LEublfp.png)

There are ***three*** main cloud service models:

1. <u> **IaaS - infrastructure as a service**</u>
* **Basic building blocks** for cloud information technology. 
* Provides users with a resource-based service via **virtualization technology** (*creating multiple virtual servers on a single physical server*), offering computing infrastructure, physical or (more often) virtual machines and other resources.
* **Highest level of flexibility** and control over IT resources. 

> You rent a virtual server from AWS, which is a server that exists entirely in the cloud. You configure the virtual server’s operating system, software application, security aspects, etc. 

2. <u>**PaaS - platform as a service**</u>
* Provides environments for **developing**, **testing**, and **managing applications**, it is utilized for software development and **offers a platform** to developers to build applications and services over the internet.
* Removes the need for managing the underlying infrastructure such as **hardware** and **operating system**.
* Has a **higher level of abstraction**, hiding the complexities of server management, allowing you to focus on deployment and management of the application. 

> AWS manages the virtual server and operating system for you. The environments and tools can be pre-configured for specific programming languages and frameworks. You simply upload the application code and the platform takes care of the rest. 

3. <u>**SaaS - software as a service**</u>
* Provides you with a **complete product** that is run and managed by the service provider. 
* In most cases, this refers to end-user applications (designed to be used directly by users who aren't involved in its development or maintenance).
* No need to think/know about how the service is maintained or how the underlying infrastructure is managed. → only **how you will use** the service.
* <u>Example</u>: web-based email application (Gmail, Outlook, iCloud Mail)
### 3. Cloud Computing Deployment Models
![cloud-deployment-models | 600](https://i.imgur.com/BuPaDPy.png)

There are three main cloud computing deployment models, each representing the cloud environment that your applications can be deployed in. 
1. <u>**Cloud (public cloud)**</u>: the **most common** type of cloud computing deployment. 
	* A cloud-based application is **fully deployed in the cloud**, all parts of the application will be running in the cloud 
	* The cloud resources (like servers and storage) are owned and operated by the cloud service provider and delivered over the internet→ we don’t manage any physical infrastructure.
2. <u>**Hybrid**</u>: connect your existing *on-premise* infrastructure and application to *cloud-based resources*. 
	* <u>*Example*</u>: Having your own physical servers and connecting them to AWS services. 
3. <u>**On–premises (private cloud)**</u>:
	* It uses *virtualization* and resource management tools to try and increase resource utilization.
	* While on-premises deployment does not provide many of the benefits of cloud computing, it’s sometimes sought for its ability to provide dedicates resources. 
	* <u>*Example*</u>: Having your own servers that you physically manage within your own facility or through a third-party data center. 
### 4. AWS vs. Traditional IT
![aws-and-traditional-it](https://i.imgur.com/IgcrpbZ.png) 