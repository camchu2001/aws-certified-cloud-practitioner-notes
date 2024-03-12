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

## 2. Advantages of the Cloud
1. <u>**Trade capital expenses for variable expense** </u>
![capital-variabl-expenses | 500](https://i.imgur.com/dOq6Xor.png)

* **Capital expenses (CapEx)**: **up-front** costs associated with acquiring, improving, maintaining physical assets (e.g.: buildings, machinery, equipment, vehicles, furniture, or computer hardware.) → *you pay for everything in the data center whether you use it or not.*
* **Variable expenses (VarEx)**: costs that fluctuate/change in proportion to a specific business activity or production level. → *you only pay when you consume resources and for the amount that you use.*
2. <u>**Massive economies of scale**</u>
	* Because of aggregate usage from all customers, AWS can achiever higher economies of scale and pass savings onto customer. 
	→ *Using cloud computing can help achieve a **lower variable cost** than what you can get on your own.* 
3. <u>**You can stop guessing capacity**</u>
	* Cloud computing eliminates guessing about your infrastructure capacity needs because you access as much or as little as you need, scaling up and down as required with only a few minutes notice. 
4. <u>**Increase speed and agility**</u>
	* In a cloud computing environment, information technology resources allocation is only a click away. 
	→ reduces the time it takes to make those resources available. 
5. <u>**Stop spending money on running/maintaining data center**</u>
	* Saves you the trouble of having to focus too much on infrastructure, allowing you to focus on software development. 
6. <u>**Go global in minutes**</u>
	* You can easily deploy your application in multiple AWS regions around the world. 
	→ provide lower latency and better experience for user. 