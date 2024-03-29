# DEVELOPER FOR MICROSOFT AZURE NANODEGREE SECOND PART

## This repository contains the solutions of the lessons and quizzes of the Developer for Microsoft Azure Nanodegree Program.

## The first part corresponds to the material provided during the first phase of the scholarship.

# II. AZURE APPLICATIONS

# LESSON 1 INTRODUCTION TO MICROSOFT AZURE DEVELOPMENT

## Prerequisites:

To succeed in this course, students should have experience in the following areas:

* Python (1-3 years of programming experience preferred), with experience building Flask apps
* SQL Server or MySQL to store and query data (you can get by with other SQL flavors as well)
* Using Git to pull and push code

## Lesson Outline:

This lesson will focus on the following topics under Microsoft Azure Cloud Development:

* Why cloud computing is important, when to use it, and who are the key stakeholders
* History of the cloud
* Microsoft Azure and Azure Portal
* Comparing cloud service types (such as Infrastructure as a Service, Platform as a Service, and Software as a Service)
* Tools and environment set up for the course
* The final course project

## Course Outline:

The course is divided into 3 major sections - Azure Compute Services, Storage Options in Azure, and Security, Monitoring and Logging.

![image](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/1.jpg)

## Introduction to Cloud Development:

The cloud is a collection of servers on the internet that store and manage data, run apps, and deliver content such as email or videos. Cloud computing is the delivery of software and storage over the Internet (i.e. the cloud).

Some of the benefits of using cloud computing are:

* Cost
* Scale
* Reliability
* Security

The three major types of cloud services are Public, Private, and Hybrid cloud. The major differences between these are in where they are deployed, and who manages them. Microsoft OneDrive, Microsoft Azure, and Microsoft Office365 are examples of public cloud options.

Cloud Developers perform some of the following:

* Plan and design cloud based apps
* Monitor, maintain and support cloud applications
* Develop work flows and processes

![image](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/2.jpg)

![image](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/3.jpg)

### Microsoft Learn Resources
* [Cloud Concepts - Principles of cloud computing](https://docs.microsoft.com/en-us/learn/modules/fundamental-azure-concepts/)
* [Foundations of cloud computing for developers](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-computing-overview/?WT.mc_id=udacity_learn-wwl)

## Why Cloud Development Is Important:

You've probably worked with various cloud services before, such as Microsoft OneDrive and Google Docs, and of course, you'll be working with Microsoft Azure in this course.

Some of the advantages of cloud computing are:

* Cost: The cloud provider handles all the upfront costs associated with buying hardware, along with on-going maintenance costs
* Scale: Most are pay-as-you-go depending on demand (elasticity), and can be expanded as needed
* Reliability: Management of backups, disaster recovery, etc. is made easier
* Security: Policies and controls are already in place to protect your data

Some of the disadvantages of cloud computing are:

* It is internet-based, so it can be prone to outages and fluctuations in speed
* Sensitive, private and core data is physically located on someone else's server
* Cloud services will be tailored and customized for your specific cloud instance, potentially making it hard to quickly change providers

![image](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/4.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/5.jpg)

### Microsoft Learn Resources
* [Economics of cloud computing](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-economics/)
* [Predict costs and optimize spending for Azure](https://docs.microsoft.com/en-us/learn/modules/plan-manage-azure-costs/)

## Business Stakeholders:

As a cloud developer, you will interact and engage with numerous stakeholders, each of whom has different priorities. Some of these are:

* Your users.
* Company executives.
* I.T. Department.
* Cloud Service provider.
* Finance Department.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/6.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/7.jpg)

## History of Cloud Development:

The roots of cloud computing go as far back as the 1960s.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/8.jpg)

1969 - JCR Licklider aimed to create a system where information could be accessed anywhere in the world called the “Intergalactic Computer Network”.

1980s - Supercomputing Centers start to form and Commercial Internet Service Providers start to emerge in the late 1980s.

1990 - The internet becomes visible to all when Tim Berners-Lee invents the World Wide Web.

1999 - Salesforce.com launches and becomes a pioneer in delivering enterprise applications over the internet, which is known as Software-as-a-Service(SaaS). This paves the way for other SaaS applications such as Microsoft 365 and Gmail.

2002 - Amazon launches its Amazon Web Services (AWS) platform. AWS is formally launched as a business unit in 2006.

2006 - Amazon launches its Elastic Compute Cloud (EC2), a commercial web service that allowed users to rent computers to run their applications. EC2 paved the way for application delivery over the internet, which allowed web-scaled businesses like Netflix and Spotify to exist.

2007 - Dropbox introduces its file hosting service, and with that cloud storage becomes a commodity.

2008 - Google launches its Google App Engine (GAE) Platform-as-a-Service (PaaS). This service allowed developers to host their web applications on Google’s managed data centers.

2010 - Microsoft launches its cloud computing platform, Azure, after announcing it back in 2008. Azure now covers Software-as-a-Service(SaaS), Platform-as-a-Service(PaaS), and Infrastructure-as-a-Service(IaaS).

2011 - IBM launches SmartCloud, a suite of enterprise-class cloud computing technologies for building private, public, and hybrid clouds.

2013 - Google launches Google Compute Engine (GCE) as an addition to its Google Compute Platform. This is an Infrastructure-as-a-Service (IaaS) component of the platform that allows a user to spin up Virtual Machines (VMs) on demand.

So what’s next? Cloud computing is on the rise in this day and age. As cloud computing continues to become more mainstream, more and more companies are looking to adopt it. Industries such as marketing, education, and healthcare are beginning to increase their use of cloud-based services and platforms.

## Microsoft Azure:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/9.jpg)

Azure is a public computing platform with tremendous value and benefits:

* Scalability: can dynamically handle changes in volume, bandwidth, storage size
* Availability: redundant on a global scale with 99.9%+ uptime (see SLA by service here)
* Security: replicated data helps protect against natural disaster, while authentication strategies help secure access to the data
* Standard delivery pipeline development services, such as:
  * Source control
  * Unit testing
  * Integration testing
  * Delivery
* Live development tools

Azure products span multiple categories, such as Compute, Analytics, Databases, A.I. and Machine Learning.

The Azure products this course will focus on are:

* App Services
* Virtual Machines
* Azure SQL Databases
* Blob Storage
* Azure Active Directory
* Aspects of Azure Monitor, such as logs and alerts

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/10.jpg)

### Microsoft Learn Resources
* [Align requirements with cloud types and service models in Azure](https://docs.microsoft.com/en-us/learn/modules/align-requirements-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Core Cloud Services - Azure architecture and service guarantees](https://docs.microsoft.com/en-us/learn/modules/azure-architecture-fundamentals/)

## The Azure Portal:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/11.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/12.jpg)

### Microsoft Learn Resources
* [Core Cloud Services - Manage services with the Azure portal](https://docs.microsoft.com/en-us/learn/modules/tour-azure-portal/?WT.mc_id=udacity_learn-wwl)

## IaaS, PaaS, and SaaS:

In contrast to on-premises solutions, there are three types of services that Azure offers us:

* Infrastructure as a Service (IaaS) - removes the expense of up-front costs of hardware, software and test environments
* Platform as a Service (PaaS) - handles networking, provides middleware and development & database tools
* Software as a Service (SaaS) - provides end-users access to online cloud solutions

![](https://video.udacity-data.com/topher/2020/July/5f10a86a_azure-service-level-comparison/azure-service-level-comparison.png)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/13.jpg)

## Tools & Environment:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/14.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/15.jpg)

### Microsoft Learn Resources
* [Create an Azure account](https://docs.microsoft.com/en-us/learn/modules/create-an-azure-account/?WT.mc_id=udacity_learn-wwl)
* [Control Azure services with the CLI](https://docs.microsoft.com/en-us/learn/modules/control-azure-services-with-cli/?WT.mc_id=udacity_learn-wwl)
* [Prepare your development environment for Azure development](https://docs.microsoft.com/en-us/learn/modules/prepare-your-dev-environment-for-azure-development/?WT.mc_id=udacity_learn-wwl)
* [Implement a code workflow in your build pipeline by using Git and GitHub](https://docs.microsoft.com/en-us/learn/modules/implement-code-workflow/?WT.mc_id=udacity_learn-wwl)

## Project: Deploy an Article CMS to Azure:

It is exciting to take a look at what we will be creating in our <strong>final course project</strong>. Similar to many such systems that exist in the real world, we will be designing, building, and deploying an Article Content Management System (CMS), which will include the ability to :

* Login and authenticate
* Read posts
* Create and save a post
* Edit and save an existing post

The project looks straightforward from the user interface, but there is a lot going on under the hood of this Flask app. The Sign In page makes use of the Microsoft Authentication Library (MSAL) and Azure Active Directory to log in with a Microsoft account, while data related to article titles, authors and text bodies is stored in an Azure SQL Server. An Azure Storage Account with Blob Storage is used to store the images, and the web app itself can be deployed using either an Azure Virtual Machine or an Azure App Service. All of these resources are likely tied to a single resource group.

All these terms may not make much sense to you yet, but by the end of the course, you'll know each resource involved quite well, and be able to deploy your own Article CMS with Azure!

![](https://video.udacity-data.com/topher/2020/March/5e6f8ed6_article-cms/article-cms.png)

## Lesson Recap:

What did we learn in this introductory lesson on Azure Cloud Development?

* Why cloud computing is important, when to use it, and who are the key stakeholders
* History of the cloud
* Microsoft Azure and Azure Portal
* Comparing cloud service types - IaaS, PaaS and SaaS
* Tools and environment set up for the course
* The final course project

## Glosary:

* <strong>The Cloud</strong>	A collection of servers on the internet that store and manage data, run apps, and deliver content such as email or videos.
* <strong>Cloud Computing</strong>	The delivery of software and storage over the Internet (i.e. the cloud).
* <strong>Public Cloud</strong>	Cloud computing resources shared amongst multiple customers, with applications and data still separate.
* <strong>Private Cloud</strong>	Cloud computing resources that are dedicated to only one entity. This is most similar to how on-premises resources operate, but with the resources still hosted off-site by a third party.
* <strong>Hybrid Cloud</strong>	Utilizing a mix of public and private cloud resources.
* <strong>Cloud Developer</strong>	Developers who build cloud applications or utilize other cloud resources in their applications. They are responsible for ensuring applications run efficiently in the cloud, requiring appropriate authentication to access, and identifying appropriate resources to use.
* <strong>Microsoft Azure</strong>	A public computing platform provided by Microsoft, with many products spanning many categories, such as Compute, Analytics, Databases, A.I. and Machine Learning.
* <strong>Azure Portal</strong>	The browser-based and GUI version of working with Azure resources.
* <strong>Elasticity</strong>	The ability to scale up or down resources to match demand.
* <strong>On-Premises</strong>	The non-cloud option where companies host all their necessary compute, storage and other resources on-site.
* <strong>Infrastructure as a Service (Iaas)</strong>	Removes the expense of up-front costs of hardware, software and test environments, as the cloud provider is instead responsible for providing physical hardware.
* <strong>Platform as a Service (Paas)</strong>	Handles networking, provides middleware and development & database tools, in addition to the physical hardware provided at the IaaS level.
* <strong>Software as a Service (Saas)</strong>	Provides end-users access to online cloud solutions, without the need to build or support the underlying applications themselves.


________________________________________________________________________________________________________________________________________________________________________________



# LESSON 2 AZURE COMPUTE DEVICES

## Introduction:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/17.jpg)

In this lesson, we'll focus on Azure Compute Services:

* First, we'll take a look at some of the various compute options available
* Then, we'll get you set up for success by discussing subscriptions and resource groups
* From there, we'll take a deeper dive into two compute services in Azure: Virtual Machines and App Services
* After comparing and contrasting these two, you'll create both resources and deploy an app to them

![](https://video.udacity-data.com/topher/2020/July/5f10a6cb_course-outline-compute/course-outline-compute.png)

## Big Picture: Compute Services:

There are a lot of compute services available through Azure, each with their own use cases. You can check out a good chart for deciding when to use each (which you'll see more of in later lessons and courses) in the Microsoft documentation. Some of the available options are:

* Virtual Machines
* App Services
* Azure Batch
* Azure Functions
* Container Instances
* Service Fabric
* Azure Kubernetes Service (AKS)

We'll focus on Virtual Machines and App Services in this lesson, although you'll see some of the others in a later course.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/18.jpg)

### Microsoft Learn Resources
* [Core Cloud Services - Azure compute options](https://docs.microsoft.com/en-us/learn/modules/azure-compute-fundamentals/)

## Subscriptions and Resource Groups:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/19.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/20.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/21.jpg)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/22.jpg)

This starts at the top with your <strong>Azure Account</strong>. The next level down is the <strong>Subscription</strong> level; in this course you will likely only work with one subscription, but it's likely in your day-to-day Azure work that you may be working with more than one. For instance, there may be one subscription for development and testing, and another for production systems.

Below the subscription level is where you'll find <strong>Resource Groups</strong>. These help to organize resources you use, such as Virtual Machines and App Services (as well as storage options and other resources we'll discuss in later lessons), in order to make resource management easier. You may have a resource group for a specific project, or because resource groups are tied to a <strong>Region</strong>, you may have resource groups containing similar resources in multiple locations across the world. A region contains at least one data center, but could have multiple data centers that are close by and networked together through a low-latency network. There are over 60 regions available worldwide and available in 140 countries, such as East US and Japan West.

![](https://video.udacity-data.com/topher/2020/July/5f108911_subscription-resource-group-hierarchy/subscription-resource-group-hierarchy.png)

When choosing a region, it's important to consider what you are trying to achieve. For development and testing purposes, you likely want a region close to yourself; for production purposes, you often want resources to be close to your user. Keep the following in mind:

* Service availability - Some services may not be available in a particular region.
* Performance - Latency determines network service performance; are you creating resources for yourself or your end user?
* Cost - Costs of services vary by region. If latency isn’t an issue, you might want to deploy your services in the cheapest region.

### Creating a Resource Group in the Azure Portal

To set up a resource group in the Azure Portal:

* Go to the [Azure Portal homepage](http://portal.azure.com/)
* Click "Create a Resource Group"
* Search for "Resource group" and click "Create"
* You'll need to select the subscription for the resource group, name it, and select a region
* Make sure once you select "Review and create" to actually review the information! While it doesn't take too much time to go back and create a new resource group, you'll want to check for any typos in the name or if the wrong region was selected. When we work out of Azure CLI later, this becomes even more important, as you could cause other scripts to fail if things are named incorrectly or are in an inappropriate region.
* Click "Create" once you are done reviewing.

You'll practice this yourself in the upcoming exercise.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/23.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/24.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/25.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/26.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/27.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/28.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/29.jpg)

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/23.jpg)](https://www.youtube.com/watch?v=_9nHPP0gixc&feature=emb_logo)

### Microsoft Learn Resources
* [Manage resources in Azure](https://docs.microsoft.com/en-us/learn/paths/manage-resources-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Move Azure resources to another resource group](https://docs.microsoft.com/en-us/learn/modules/move-azure-resources-another-resource-group/?WT.mc_id=udacity_learn-wwl)
* [Control and organize Azure resources with Azure Resource Manager](https://docs.microsoft.com/en-us/learn/modules/control-and-organize-with-azure-resource-manager/?WT.mc_id=udacity_learn-wwl)
* [Create ARM templates](https://docs.microsoft.com/en-us/learn/modules/build-azure-vm-templates/?WT.mc_id=udacity_learn-wwl)

## Exercise: Create A Resource Group:

In this exercise, you'll create a resource group in Azure. This is a quick exercise, but will set you up for success through the rest of the course!

* Create a Resource Group named <strong>resource-group-west</strong> in Azure in the <strong>West US</strong> region.

<strong>Note:</strong> We will use this resource group throughout the course, so do not delete it after creation. Resource Groups are fully covered in the Azure free account.

## Solution (Alternative Solution using the CLI):

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=rmWRvxY0Hh8&feature=emb_logo)

### Azure CLI Documentation
You can reference the [Azure CLI documentation](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest&WT.mc_id=udacity_learn-wwl) for further information on other commands.

### Steps to Create a Resource Group using the Azure CLI:

* 1. Log in using az login.
* 2. We'll use the Azure CLI command az group create and pass in two flags:
   * resource group --name
   * --location which is the same as the "region" field on the Azure portal.
* 3. If you want to see a list of all locations, you can run az account list-locations -o table to output the list in table format.
* 4. I want to create my resource group in the West US 2 region:

az group create --name resource-group-west --location westus2

The resource group will be created and a JSON response will be returned with the status.

Alternatively, you can check out the screenshot below for how you might do the same from the Portal (note that the below uses the West US region and not West US 2).

![](https://video.udacity-data.com/topher/2020/July/5f075271_resource-group-solution/resource-group-solution.png)

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://video.udacity-data.com/topher/2020/July/5f075271_resource-group-solution/resource-group-solution.png)](https://www.youtube.com/watch?v=rmWRvxY0Hh8&feature=emb_logo)

## Virtual Machines vs. App Services:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/30.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/31.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/32.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/33.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/34.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/35.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/36.jpg)

### Virtual Machines
<strong>Azure Virtual Machines</strong> (VMs) provide infrastructure as a service (IaaS) by allowing you to create and use virtual machines in the cloud.

Some of the benefits of VMs are:

* VMs allow you full access and control of the VM.
* Lower up-front cost compared to purchasing and maintaining hardware.
* Support of both Linux and Windows VMs.
* Multiple types to choose from, such as compute or memory-optimized VMs, along with varying amounts of CPU, RAM and storage.
* VMs allow for the installation of custom images and are an excellent choice for migrating from an on-premises server to the cloud.
* Multiple VMs can be grouped to provide high availability, scalability, and redundancy. There are two options when it comes to scaling—Virtual Machine Scale Sets and Load Balancers. These will be covered in a different course.

Some of the limitations of VMs are:

* They are more expensive
* They can be more time consuming for the developer than other compute options

### App Service
<strong>Azure App Service</strong> is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. It is a Platform as a Service (PaaS) that allows a developer to focus on the application while Azure takes care of the infrastructure.

Some of the benefits of using an App Service are:

* Support of multiple languages, such as .NET, .NET Core, Java, Ruby, Node.js, PHP, or Python
* High availability, auto-scaling and support of both Linux and Windows environments.
* Continuous deployment model using GitHub, Azure DevOps, or any Git repo.
* Vertical or Horizontal scaling. Vertical scaling increases or decreases resources allocated to our App Service, such as the amount of vCPUs or RAM, by changing the App Service pricing tier. Horizontal scaling increases or decreases the number of Virtual Machine instances our App Service is running.
* You can set the amount of hardware allocated to host your application, and cost varies based on the plan you choose. There are three different tiers - Dev/Test, Production, and Isolated. We’ll be using the free option within Dev/Test for the exercises in this course.

Some of the limitations of an App Service are:

* You have limited access to the host server, so you are unable to control the underlying OS or install software on the server.
* You’re always paying for the service plan, even if your services or application isn’t running.
* There are hardware limitations, such as a maximum of 14GB of memory and 4 vCPU cores per instance
* While they support multiple languages, as noted in the benefits above, they are limited to just using those languages (as of when this course was built).

### Use Cases
Each of these has their own use cases, although sometimes there is still some ambiguity on when to use each. Virtual Machines are usually better when you need control of the underlying operating system or are using custom software to support your needs; an app service is typically better for lightweight applications and services, especially when you don't have the need for high performance compute services. Additionally, you'll need to take into consideration the hardware limitations of App Services, as noted above.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/37.jpg)

## Exercise: Virtual Machines vs. App Services:

### Virtual Machines vs. App Services
For each of the three scenarios below, analyze and determine whether a virtual machine or an app service would be best served for the situation. It's important to note that this involves some level of ambiguity - you should feel free to expand beyond the given scenario and consider any other areas that might be important in making your decision.

### Scenario 1
Your company wants to deploy a series of lightweight APIs as part of their plan to shift to using microservices in the future. The company is very cost-conscious due to the current economic environment, and wants to focus on using the correct services right now, and is less concerned about scaling concerns due to stagnant growth.

### Scenario 1 Scratchpad
You can use this space as a scratchpad of your thoughts on Scenario 1. Note that this will lock after you submit it.

Your reflection
* App Services

### Scenario 2
Your company has recently signed a sizable government contract in which you will deploy various apps for the related government departments to use. The contract was a big win for the company, as it vastly increases the number of users of your apps. Additionally, the contract does contain provisions that require dedicated servers for security reasons to host any of the government department's services and information. Relatedly, some of the different departments' applications are required to be maintained on different servers.

### Scenario 2 Scratchpad
You can use this space as a scratchpad of your thoughts on Scenario 2. Note that this will lock after you submit it.

Your reflection
* Virtual Machines

### Scenario 3
You have been assigned to determine the cloud needs for a new product your company will soon be launching. In the past couple of years, your company has been on a roller coaster ride - some product launches meet massive success, while others flounder pretty quickly out of the gates. As such, the product manager is a bit wary of immediately creating a bunch of resources without knowing for sure what the real demand for this new product will be. The application currently utilizes ~5 GB on 2 CPUs during your stress testing, but is definitely a minimum viable product, and could grow vastly in size and compute resources if successful.

### Scenario 3 Scratchpad
You can use this space as a scratchpad of your thoughts on Scenario 3. Note that this will lock after you submit it.

### Your reflection
* App Services

## Solution: Virtual Machines vs. App Services:

### Scenario 1
>>Your company wants to deploy a series of lightweight APIs as part of their plan to shift to using microservices in the future. The company is very cost-conscious due to the >>current economic environment, and wants to focus on using the correct services right now, and is less concerned about scaling concerns due to stagnant growth.

Some key points that stood out to me were:

* Deploying a series of lightweight APIs
* Less concern about scaling up processing power
* Cost-consciousness

I would choose an <strong>App Service</strong> in this situation. Lightweight APIs tend to be well-suited to App Services over VMs, and won't approach the size limit for App Services very easily. Additionally, App Services cost less than VMs do. Lastly, since the ability to scale quickly is less of a concern, we don't need to factor that into the analysis.

As the company shifts into microservices, Azure Functions would also be a good compute option for them to consider, but that won’t be covered until a later course.

### Scenario 2
>>Your company has recently signed a sizeable government contract in which you will deploy various apps for the related government departments to use. The contract was a big win >>for the company, as it vastly increases the number of users of your apps. Additionally, the contract does contain provisions that require dedicated servers for security >>reasons to host any of the government department's services and information. Relatedly, some of the different departments' applications are required to be maintained on >>different servers.

A couple of key points that stood out to me were:

* A vast increase in the number of users
* The need for dedicated servers for security reasons

This situation is likely best for <strong>Virtual Machines</strong>. Handling the vast increase in the number of users, with separate, dedicated servers, is going to be better achieved this way.

### Scenario 3
>>You have been assigned to determine the cloud needs for a new product your company will soon be launching. In the past couple of years, your company has been on a roller >>coaster ride - some product launches meet massive success, while others flounder pretty quickly out of the gates. As such, the product manager is a bit wary of immediately >>creating a bunch of resources without knowing for sure what the real demand for this new product will be. The application currently utilizes ~5 GB on 2 CPUs during your stress >>testing, but is definitely a minimum viable product, and could grow vastly in size and compute resources if successful.

This is a bit of a tough one - it's important to remember that in real-life situations, there may not always be a clear dividing line on exactly which service is best.

Some key points that stood out to me were:

* The confidence level of this application being a massive success seems low (do we want to assume we'll need a lot of scaling?)
* The application currently utilizes ~5 GB on 2 CPUs during stress testing
* The potential the app will grow in resource needs

The answer here depends greatly on which of the above points you highlight. In the current situation, an App Service likely works fine - it can scale vertically to meet different demand levels, and the compute resources needed are well within App Service limits. However, there's some consideration that Virtual Machines may be necessary in the near future if many more features are added, or demand changes in a way that requires vertical scaling. In fact, I'd argue that the problem so far is a bit ill-defined - I'd want to know what level of control we need over the underlying OS, security requirements we have, etc.

## Creating a Virtual Machine:

Please open the link in a new tab to follow the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=ngD-D9XBPw4&feature=emb_logo)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/39.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/40.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/41.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/42.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/43.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/44.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/45.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/46.jpg)

The steps I took to create a Linux Virtual Machine on Azure were:

* 1. On the homepage, click "Create a resource"
* 2. Click on "Compute" in the left menu
* 3. Click on "Virtual Machine"
* 4. Create a Linux VM with the following details:

* Subscription: This will vary for you. Should default to your subscription.
* Resource Group: "hello-world-rg"
* VM Name: "linux-vm-west"
* Region: West US 2 or a region closest to you that's available
* Availability Options: Default option of "No infrastructure redundancy required" is fine here.
* Image: Ubuntu Server (any version) but I'm going to use the latest version 18.04 LTS
* Azure Spot instance: No
* Size: Click on "Select Size" and select "Standard B1ls"
* Authentication type: Password
* Username: (any username you choose) something other than the default "AzureUser" I used "udacityadmin"
* Password: (any password you choose) "Udacityadmin@123"
* Inbound Port Rules: "Allow Select Ports" and make sure from the drop-down menu, 22 and 80 are selected.

### Connect and deploy an App using the command line:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?time_continue=20&v=Ty_ZR_E6Ukg&feature=emb_logo)

To connect to the created VM, I did the following (note that Windows users should use PowerShell or Bash):

* 1. We'll need our admin username we set when creating the VM - "udacityadmin"
* 2. We'll need the public IP address of our VM. You can use the following command to grab the IPs addresses for a particular VM from the CLI—
```
az vm list-ip-addresses -g <RESOURCE-GROUP> -n <VIRTUAL-MACHINE-NAME>
```
or use Azure portal.
* 3. Next, we're going to copy a basic Flask app from my local machine to the VM. We'll be using the secure copy utility—
```
scp -r <SOURCE-DIR> [ADMIN-NAME]@[PUBLIC-IP]:<TARGET-DIR>
```
In this example, I used—
```
scp -r ./web udacityadmin@IPADDRESS:/home/udacityadmin
```
### NOTE: 
The first time you try connecting to the VM, you'll see a similar message to the one below and should answer 'yes' to permanently add the IP address to the list of known hosts.

>>The authenticity of host '52.191.135.139 (52.191.135.139)' can't be established.
>>ECDSA key fingerprint is SHA256:7bBVTsYNImhXxAn+xscCHm/OkcodHZS615VSKO3GP8c.
>>Are you sure you want to continue connecting (yes/no)?

* 4. Once the files have been copied to the VM, we can connect to the VM using—
```
ssh [ADMIN-NAME]@[PUBLIC-IP]
```

* 5. We can use "ls" to see the web directory we just uploaded

* 6. Python 3 is already installed on the VM. We'll install Python Virtual Environment and NGNIX to use as a reverse proxy
```
sudo apt-get -y update && sudo apt-get -y install nginx python3-venv
```

* 7. Before we run the app, we have to configure Nginx to redirect all incoming connections on port 80 to our app that is running on localhost port 3000

* By default, Nginx has a default page that is displayed. If you visit the public IP address in your browser, you should see this page rendered.
* We'll navigate to the <strong>/etc/nginx/sites-available</strong> directory—
```cd /etc/nginx/sites-available```

* We’ll first unlink the default site using 
```sudo unlink /etc/nginx/sites-enabled/default```

* Then we’ll create a new file <strong>reverse-proxy.conf</strong> in the <strong>/etc/nginx/sites-available</strong>—
<strong>sudo vim reverse-proxy.conf</strong>
* We're going to add the following code to this file:

```
server {
    listen 80;
    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection keep-alive;
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
 }
 
 ```
 
Now we’ll activate the directories by creating a sym link to the /sites-enabled directory 

```sudo ln -s /etc/nginx/sites-available/reverse-proxy.conf /etc/nginx/sites-enabled/reverse-proxy.conf```

* We have to restart nginx so the changes take effect. ```sudo service nginx restart```

* 8. cd to web

* 9. Create venv ```python3 -m venv venv```
* 10. Activate the env ```source venv/bin/activate```
* 11. Upgrade pip in our virtual environment and then Install dependencies ```pip install --upgrade pip``` ```pip install -r requirements.txt```
* 12. We'll run our app ```python application.py```
* 13. In a web browser, we can visit the public IP address of the VM and you should see the application
* 14. Type "exit" to disconnect from the VM

<strong>Note:</strong> Azure free account only allows 750 hours of free hosting. Make sure to delete this VM after creation for any exercises to avoid charges.

<strong>Cleanup</strong>
If we no longer need a resource, we can delete them through the portal.

* 1. From the homepage, click on "Resource Group"
* 2. Click on the resource group you want to manage
* 3. You have two options—"Delete resource group" or if you want to keep the resource group, you can click on the individual or collection of resources you want to delete and click on "Delete"

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/48.jpg)

### QUESTION 2 OF 2
You've gone through all the steps for creating a Virtual Machine and deploying an app to it, and everything appears to be working from within the VM itself. However, when you navigate to the public IP address, it gives a connection error. Which of the following is a likely cause of the issue?

* You need to make sure the VM is listening on port 80

### Microsoft Learn Resources
* [Introduction to Azure virtual machines](https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-virtual-machines/?WT.mc_id=udacity_learn-wwl)
* [Create a Linux virtual machine in Azure](https://docs.microsoft.com/en-us/learn/modules/create-linux-virtual-machine-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Deploy a website with Azure virtual machines](https://docs.microsoft.com/en-us/learn/paths/deploy-a-website-with-azure-virtual-machines/?WT.mc_id=udacity_learn-wwl)

## Exercise: Creating a Virtual Machine:

### Create a Linux Virtual Machine
In this exercise, you'll create and connect to a Linux Virtual Machine in Azure.

<strong>Prerequisite:</strong> If you're using Windows, you’ll need PowerShell or Bash to connect to the VM with ssh. Windows 10 should already have Powershell installed. If you don't have it already installed, here is a guide on how to install it.

* 1. Create a Linux VM called “linux-vm-west” inside “resource-group-west” which was created in a previous exercise. The VM should have the following configurations:
>> * VM Name: "linux-vm-west"
>> * Region: West US or the closest region to you that's available
>> * Availability Options: No infrastructure redundancy required.
>> * Image: Ubuntu Server (any version)
>> * Azure Spot instance: No
>> * Size: Standard B1ls
>> * Authentication type: Password
>> * Username: (any username you choose)
>> * Password: (any password you choose)
>> * Inbound Port Rules: Allow both 22 and 80

* 2. After creating the VM, use <strong>secure copy</strong> to copy the ```web``` directory from [here](https://video.udacity-data.com/topher/2020/July/5f1875e2_create-vm-starter/create-vm-starter.zip) to the VM. ```scp -r ./web <USERNAME>@<IPADDRESS>:/home/<USERNAME>```
* 3. After copying the files to the VM, <strong>connect</strong> to it and run the command ```ls``` to check the ```web``` directory is on the VM.
* 4. Next, install ```python3-env``` and ```nginx``` ```sudo apt-get -y update && sudo apt-get -y install nginx python3-venv```
* 5. Next, configure nginx to listen for incoming traffic on port 80 and set port 3000 as the proxy.
>> * Navigate to ```/etc/nginx/sites-avaiable```
>> * Remove the ```default``` file
>> * Replace it with a file containing:

```server {
  listen 80;
  location / {
      proxy_pass http://localhost:3000;
      proxy_http_version 1.1;
      proxy_set_header Upgrade $http_upgrade;
      proxy_set_header Connection keep-alive;
      proxy_set_header Host $host;
      proxy_cache_bypass $http_upgrade;
  }
}
```

* After saving the file, restart nginx ```sudo service nginx restart```
* 6. Change to the ```web``` directory and create and activate a virtual env
* 7. As a best practice, update pip in a newly created virtual env
* 8. Install dependencies from <strong>requirements.txt</strong>
* 9. Run the application and visit the public IP address in your browser. You should see the application running if done correctly.

### Cleanup
Once you're done with the exercise, be sure to delete the VM and it's resources to avoid incurring unwanted charges.

<strong>Note:</strong> Azure free accounts only allow 750 hours of free hosting. Make sure to delete this VM after completing the exercise to avoid charges.

### Supporting Materials
[create-vm-starter.zip](https://video.udacity-data.com/topher/2020/July/5f1875e2_create-vm-starter/create-vm-starter.zip)

## Solution: Creating a Virtual Machine:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=a5gKkVARnXU&feature=emb_logo)

In this solution video, I showed you an alternative way to create a Linux VM using Azure CLI. Use whichever method you feel more comfortable with moving forward. Connecting to the VM is done the same way in both instances.

* 1. First, we'll login using ```az login```
* 2. Next, we'll create our VM using ```az vm create```. If we don't pass a location, it defaults to the location of the resource group. This would be fine in most cases, but it's worth noting that sometimes a VM size might not be available in the same region as your resource group, so you'd have to pass in a location for a different region.

```
az vm create \
   --resource-group "resource-group-west" \
   --name "linux-vm-west" \
   --location "westus2" \
   --image "UbuntuLTS" \
   --size "Standard_B1ls" \
   --admin-username "udacityadmin" \
   --generate-ssh-keys \
   --verbose
```
   
* 3. Upon success, you will have a JSON response.
* 4. Next we will open port 80 to allow outside traffic to our VM

az vm open-port \
    --port "80" \
    --resource-group "resource-group-west" \
    --name "linux-vm-west"
    
* 5. Upon success, you will receive a JSON response.

Alternatively, you can check the screenshot below for the same approach through the portal.

![](https://video.udacity-data.com/topher/2020/July/5f075463_linux-vm-solution/linux-vm-solution.png)

### Connecting to the VM
* 1. We'll need the admin username we set when creating the VM
* 2. We'll need the public IP address of our VM. You can use the following command to grab the IP address for a particular VM from the CLI.
```az vm list-ip-addresses -g resource-group-west -n linux-vm-west```
* 3. Next we're going to copy a basic Flask app from my local machine to the VM. We'll be using the [secure copy utility](http://www.hypexr.org/linux_scp_help.php) ```scp -r ./web udacityadmin@IPADDRESS:/home/udacityadmin```
* 4. Now we can connect to the VM with “ssh [username]@[IP Address]” <strong>Note:</strong> Since we generated SSH keys, you won't be prompted for a password.
* 5. Run ```ls``` to see the web directory we just uploaded
* 6. Python 3 is already installed on the VM. We'll install Python Virtual Environment and NGNIX to use as a reverse proxy
```sudo apt-get -y update && sudo apt-get -y install nginx python3-venv```
* 7. Before we run the app, we have to configure Nginx to redirect all incoming connections on port 80 to our app that is running on localhost port 3000

>> * By default, Nginx has a default page that is displayed. If you visit the public IP address in your browser, you should see this page rendered.
>> * We'll navigate to the <strong>/etc/nginx/sites-available</strong> directory—
```cd /etc/nginx/sites-available```
>> * We’ll first unlink the default site using ```sudo unlink /etc/nginx/sites-enabled/default```
>> * Then we’ll create a new file <strong>reverse-proxy.conf</strong> in <strong>/etc/nginx/sites-available—</strong>
```sudo vim reverse-proxy.conf```
>> * We're going to add the following code to this file:

```
server {
    listen 80;
    location / {
        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection keep-alive;
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;
    }
 }
 ```
 
* 8. Now we’ll activate the directories by creating a sym link to the <strong>/sites-enabled</strong> directory 
```sudo ln -s /etc/nginx/sites-available/reverse-proxy.conf /etc/nginx/sites-enabled/reverse-proxy.conf```
>> * We have to restart nginx so the changes take effect
```sudo service nginx restart```

### Deploying the App to the VM
This section is the same as the earlier walkthrough, so we'll skip a solution video for it.

To deploy the app on the virtual machine, I did the following:

* 1. CD to ```web```
* 2. Create venv ```python3 -m venv venv```
* 3. Activate the env ```source venv/bin/activate```
* 4. Upgrade pip in our virtual environment and then Install dependencies—
```pip install --upgrade pip pip install -r requirements.txt```
* 5. We'll run our app ```python application.py```
* 6. In a web browser, we can visit the public Ip address
* 7. Type "exit" to disconnect from the VM

### Cleanup
If we no longer need a resource, we can delete them through the portal. The quickest way to do this from the CLI is to delete the resource group. This will delete all resources in that group

```az group delete -n resource-group-west```

## Creating an App Service:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=C4B4Ebchf0U&feature=emb_logo)

I took the following steps to create an App Service Web App using the Azure Portal

* 1. On the homepage, click "Create a resource"
* 2. Search for "Web App"
* 3. Click "Create"
* 4. Select your subscription
* 5. Select your resource group "resource-group-west"
* 6. Enter a name for your web app—This needs to be a unique name and is unique to Azure as a whole and not just your Azure account. I used "hello-world1234" as my unique name.
* 7. For Publish, select "Code"
* 8. For the "Runtime Stack", select "Python 3.7" or greater.
* 9. For the "Operating System" select "Linux"
* 10. Select a region for your app service
* 11. Create a new App Service Plan. You can keep the default name Azure gives you or you can create your own name.
* 12. For SKU and size, select "F1" (Free).
* 13. Click "Review + Create"
* 14. Click "Create"
* 
Then, I clicked on the URL to see the app service, which confirmed the app service was up and running. Now we need to deploy our code.

<strong>Note:</strong> Azure free account only allows 1 Linux App Service of size F1. You will need to delete the App Service Web App along with the App Service Plan after each exercise since we will create other Linux App Services throughout this course.

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/49.jpg)](https://www.youtube.com/watch?time_continue=4&v=bpME7sOhPNg&feature=emb_logo)

To deploy an App Service from a GitHub repository, I did the following:

* 1. Go to Deployment Center
* 2. Choose GitHub
* 3. Choose org and repo
* 4. Go through the prompts; deployment takes a few minutes
* 5. Go to URL of web app and should see the app deployed

### Cleanup
If we no longer need a resource, we can delete them through the portal.

* 1. From the homepage, click on "Resource Group".
* 2. Click on the resource group you want to manage.
* 3. You have two options—"Delete resource group" or if you want to keep the resource group, you can click on the individual or collection of resources you want to delete and click on "Delete".

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/50.jpg)

### Microsoft Learn Resources)
* [Host a web application with Azure App service](https://docs.microsoft.com/en-us/learn/modules/host-a-web-app-with-azure-app-service/?WT.mc_id=udacity_learn-wwl)
* [Manage an App Service plan in Azure](https://docs.microsoft.com/en-us/azure/app-service/app-service-plan-manage?WT.mc_id=udacity_learn-wwl)
* [Deploy a website to Azure with Azure App Service](https:/)/docs.microsoft.com/en-us/learn/paths/deploy-a-website-with-azure-app-service/?WT.mc_id=udacity_learn-wwl)

## Exercise: Creating an App Service:.

### Create and Deploy an App Service Web App
In this exercise, you'll create and deploy an app service web app.

### Prerequisites:

* A GitHub Account. If you don’t have one, create one [here](https://github.com/).

### Create an App Service Web App
Create an App Service Web App with the following configuration:

* Resource-Group: resource-group-west
* Web App Name: unique name
* Publish: Code
* Runtime stack: Python 3.7
* Operating System: Linux
* Region: West US or the closest region to you
* App Service Plan: Default name or Create new with a name of your choice
* SKU and size: F1 (Free)

<strong>Note:</strong> Azure free account only allows one Linux App Service of size F1. You will need to delete the App Service along with the App Service Plan after this exercise since we will create other Linux App Services throughout this course.

### Deploy the App Service Web App
It’s finally time to deploy some code to Azure! Download the web app code provided [here](https://video.udacity-data.com/topher/2020/July/5f18767d_create-app-service-starter/create-app-service-starter.zip).

* 1. Create a new repo and push the web app code to the repo
* 2. On Azure portal in the Deployment Center, deploy the web app from GitHub
* 3. Navigate to the deployed URL

### Supporting Materials
[create-app-service-starter.zip](https://video.udacity-data.com/topher/2020/July/5f18767d_create-app-service-starter/create-app-service-starter.zip)

## Solution: Creating an App Service:

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=GOieycrud0Q&feature=emb_logo)

In this solution video, I showed you an alternative way to create and deploy an Azure App Service Web App using Azure CLI. Use whichever method you feel more comfortable with moving forward.

### Steps to Create and Deploy an App Service Web App from a Directory using Azure CLI:

* 1. Sign in to Azure ```az login```
* 2. cd to ```web``` directory
* 3. Run the following command:

```
az webapp up \
 --resource-group resource-group-west \
 --name hello-world1234 \
 --sku F1 \
 --verbose
 ```
 
* 4. If you visit the URL, you should see your site deployed.
* 5. If you want to update your app, make changes to your code and then run (<strong>Note:</strong> this may not update new requirements you may have added):

```
az webapp up \
 --name hello-world1234 \
 --verbose
 ```
 
 Alternatively, you can create the initial web app from the Portal as shown in the below screenshot (and then deploy code to it separately, as shown in the earlier video).
 
 ![](https://video.udacity-data.com/topher/2020/July/5f07555b_app-service-solution/app-service-solution.png)
 
### Cleanup
If we no longer need a resource, we can delete them through the portal. The quickest way to do this from the CLI is to delete the resource group. This will delete all resources in that group

```az group delete -n resource-group-west```

Alternatively, if you want to just delete the App Service and App Service plan individually, you can do so with the following commands:

### Delete an App Service

```
az webapp delete \
    --name hello-world1234 \
    --resource-group resource-group-west
```

### Delete an App Service plan

```
az appservice plan delete \
    --name [App Service Plan Name] \
    --resource-group resource-group-west
```

### QUIZ QUESTION
You've built a web app, and deployed it with az webapp up, but seem to be getting an ImportError when actually trying to access the application. What change do you need to make to the app for it to work?

* Add the related library to requirements.txt and update the deployed app

## Lesson Conclusion:

In this lesson, we focused on Azure Compute Services:

* We took a look at some of the various compute options available
* Then, we discussed subscriptions and resource groups, and you created your own resource group
* From there, we took a deeper dive into two compute services in Azure: Virtual Machines and App Services
* After comparing and contrasting these two, you created both resources and deployed an app to them

### Glossary 

### Key Term          Definition

<strong>Subscription</strong>	Multiple of these can exist within a single Azure account; often used for billing and other management purposes.

<strong>Resource Group</strong>	Help to organize resources you use, such as Virtual Machines, App Services or storage, in order to make resource management easier. Groups are often set up for different projects or regions.

<strong>Region</strong>	Locations of Azure data centers around the world. The closer the region of app resources is to the end user, the lower the latency experienced.

<strong>ARM Templates</strong>	Created within Azure Resource Manager to more easily spin up a set of given resources multiple times.

<strong>Virtual Machines</strong>	An Azure IaaS option giving you full access to the underlying operating system of a compute resource. These can be either Windows or Linux machines, with great availability, scalability and redundancy. These require more on-going maintenance and up-keep by cloud developers.

<strong>App Service</strong>	An Azure PaaS option allowing developers to focus more on their apps than the underlying infrastructure. It is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. It supports multiple languages and continuous deployment. While they are good for scaling, there is also a limit of up to 14 GB or 4 CPU cores on the highest tier.

<strong>App Service Plan</strong>	Contains certain settings of an App Service, such as region, number of VM instances (App Services still run on VMs, but the developer does not have control of the underlying VM, and the app may share the VM with other apps), size of those instances, and pricing tier.

<strong>Azure Batch</strong>	Used for running large-scale and high-performance compute applications beyond the capabilities of an App Service.

<strong>Azure Functions</strong>	A serverless, event-driven, compute-on-demand platform (covered in a later course).

<strong>Container Instances</strong>	A platform for deploying serverless docker containers (covered in a later course), without the container orchestration provided by AKS (see below).

<strong>Service Fabric</strong>	Microsoft's own distributed systems platform, similar to Kubernetes.

<strong>Azure Kubernetes Service (AKS)</strong> Microsoft's own platform for hosting and managing Kubernetes, including deploying docker containers into clusters (covered in a later course).



________________________________________________________________________________________________________________________________________________________________________________



# LEESON 3 AZURE STORAGE

## Introduction:

In this lesson, you will:

* Take a look at all the different storage options available in Azure and their benefits
* Take a deep dive on Azure SQL Databases and Blob Storage, including creating the related resources and uploading data
* Connect those storage services to your app

![](https://video.udacity-data.com/topher/2020/July/5f10a6f7_course-outline-storage/course-outline-storage.png)

## Big Picture: Storage:

Some of the benefits of using Azure for storage are:

* Automated backup and recovery
* An option to replicate data at multiple data centers worldwide to help prevent outages from unplanned events, such as hardware failure.
* Data analytics support
* Data encryption for added security
* Support for the storage of multiple data types. Azure is designed to hold 3 main types data—relational data, non-relational data or NoSQL data, and unstructured data such as images.
* Scale up or scale out when demand is high and scale back when demand is low.
* Eliminate the expense of having to purchase, install, configure, and maintain on premises hardware.

### Microsoft Learn Resources
* [Core Cloud Services - Azure data storage options](https://docs.microsoft.com/en-us/learn/modules/azure-database-fundamentals/)
* [Choose a data storage approach in Azure](https://docs.microsoft.com/en-us/learn/modules/choose-storage-approach-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Learning Path: Store data in Azure](https://docs.microsoft.com/en-us/learn/paths/store-data-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Learning Path: Architect a data platform in Azure](https://docs.microsoft.com/en-us/learn/paths/architect-data-platform/?WT.mc_id=udacity_learn-wwl)

### Azure Storage Options
Among others, some of the Azure Storage options are:

* Azure SQL Server and SQL Database
* Azure Blob Storage
* Azure CosmosDB
* Disk Storage
* Azure Data Lake Storage
* HPC Cache

We could spend an entire course just on Azure storage, so we’ll focus on two of these services in this lesson—Azure SQL Database and Azure Blob Storage. CosmosDB will be covered in another course.

We also covered the three tiers of blob storage - hot, cool and archive. We'll come back to this later in the section on Azure Blob Storage.

### QUIZ QUESTION
True or False: My app will only ever use one type of storage.

* False

## Azure SQL Databases:

* Azure SQL databases are used for structured, relational data.
* In Azure, you also need to first create a related SQL server to hold the database, although you can create multiple SQL databases under a single SQL server.
* Azure SQL databases do not have a free tier option like we saw with App Services earlier; however, when you sign up for a new free Azure account, you get 12 months of up to 250GB of Azure SQL database storage. The lowest tier is currently ~$5 / month otherwise for a small amount of storage.

### Creating an Azure SQL Database in the Portal

Please watch the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=eZHNDuYasj8&feature=emb_logo)

To create an Azure SQL Database in the Azure Portal:

* 1. Find the "SQL databases" service in Azure.
* 2. Click "Create SQL Database".
* 3. Select the appropriate subscription and resource group (likely “resource-group-west”).
* 4. Enter a database name.
* 5. If you already have a SQL server, you can use it; however, you likely need to click "Create New".
>> * If creating a new SQL server, enter a server name, and then admin and password - make sure you can remember these, or you will not be able to access the server when necessary. The admin name cannot just be "admin".
>> * Set the location to match the resource group.
* 6. Keep SQL elastic pool on the default of "No".
* 7. Under Compute+Storage, click on "Configure Database". While General Purpose won't end up charging you anything for the short time the server is live for these exercises, you might as well press "Looking for basic, standard, premium?", and change it to "Basic".
* 8. Press the "Next: Networking" button, then select "Public Endpoint", and set both of the Firewall rules that appear to "Yes". This will allow us to more easily access the SQL database later on within our app.
* 9. Click "Review + Create" and then "Create" to create the database, then wait for it to deploy.

### QUIZ QUESTION
Azure SQL Databases can be left up on the basic tier for no cost forever.

* False

### Microsoft Learn Resources
* [Work with relational data in Azure](https://docs.microsoft.com/en-us/learn/paths/work-with-relational-data-in-azure/?WT.mc_id=udacity_learn-wwl)
* [Provision an Azure SQL database to store application data](https://docs.microsoft.com/en-us/learn/modules/provision-azure-sql-db/?WT.mc_id=udacity_learn-wwl)
* [Create an Azure Database for PostgreSQL server](https://docs.microsoft.com/en-us/learn/modules/intro-to-postgres/)

## Adding Data to the Database:

Please watch the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=nOqbJ-HTicQ&feature=emb_logo)

To add data to the SQL Database, I performed the following:

* 1. Once the SQL database is deployed, click on its name to access it (you may need to go back to the main "SQL databases" page in Azure).
* 2. Click on the "Query editor" in the left side menu, and then log in with my SQL Server credentials.
* 3. I pasted the query from my ```posts-table-init.sql``` script into the query window, and hit "Run"; you should see ```Query succeeded: Affected rows: 3```.
* 4. On the left side of the query window, I clicked on the "Tables" folder, and double-checked that the ```dbo.POSTS``` table was successfully created with the correct fields.
* 5. I ran a new query with ```SELECT * FROM posts```, to see the three posts listed.

You'll get to practice this yourself in the upcoming exercise.

### QUIZ QUESTION
Which of the following would be appropriate data to store in a SQL database?

* Information about books like author, title, year published, and summary
* Sales invoices, such as id, price, and item quantities

## Exercise: Azure SQL Databases:

### Exercise: Azure SQL Databases
In this exercise, you will create an Azure SQL Database and add data to it. In a later exercise, you will connect an app to the database, so that you can both get and post data from the app into the database.

* 1. Deploy a SQL Database in Azure called “database-west” to the “resource-group-west” resource group (or whichever resource group you have been using in earlier exercises).
* 2. Within the Azure portal, add the data from the script in the sql_scripts directory here to the database. You should be able to run a SELECT query afterward on the animals table to see the example animals populated in your database.

<strong>Note:</strong> Azure free accounts only allow 250GB of free storage using SQL Databases. Once you get to the end of this lesson, you will want to delete the SQL Database and SQL Server to avoid incurring any charges, as you'll create a different SQL Database in the final course project.

### Supporting Materials
[sql-scripts.zip](https://video.udacity-data.com/topher/2020/July/5f075d26_sql-scripts/sql-scripts.zip)

## Solution: Azure SQL Databases:

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=xyfZkpSg2bs&feature=emb_logo)

In this solution video, I showed you an alternative way to create an Azure SQL Database using Azure CLI.

### Create SQL Server

```
az sql server create \
--admin-user udacityadmin \
--admin-password p@ssword1234 \
--name hello-world-server \
--resource-group resource-group-west \
--location westus2 \
--enable-public-network true \
--verbose
```
### Create Firewall rule

Next, we have to create two firewall rules. These are the same two rules we checked as yes when we used the portal.

The first one is to allow Allow Azure services and resources to access the server we just created.

```
az sql server firewall-rule create \
-g resource-group-west \
-s hello-world-server \
-n azureaccess \
--start-ip-address 0.0.0.0 \
--end-ip-address 0.0.0.0 \
--verbose
```
This second rule is to set your computer's public Ip address to the server's firewall. You'll need to find your computer's public ip address for this part.

I'm using macOS, so I used the command ```curl ifconfig.me```; you can use ```ipconfig``` in the command prompt if you are on Windows.

### Create clientIp firewall rule

```
az sql server firewall-rule create \
-g resource-group-west \
-s hello-world-server \
-n clientip \
--start-ip-address <PUBLIC-IP-ADDRESS> \
--end-ip-address <PUBLIC_IP_ADDRESS> \
--verbose
```

### Create SQL Database
Finally, to create the database itself, I used the below command.

```
az sql db create \
--name hello-world-db \
--resource-group resource-group-west \
--server hello-world-server \
--tier Basic \
--verbose
```

### Adding Data
We'll again add data to the database through the portal, as that's the most straightforward method for now (until we connect to an app).


Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=C6nP7JAozDM&feature=emb_logo)

### Cleanup
You can find the CLI commands for cleaning up the SQL resources below.

### Delete DB

```
az sql db delete \
--name hello-world-db \
--resource-group resource-group-west \
--server hello-world-server \
--verbose
```

### Delete SQL Server

```
az sql server delete \
--name hello-world-server \
--resource-group resource-group-west \
--verbose
```
## Blob Storage:

Before discussing Blob Storage Accounts, you may need to know what a <strong>Blob</strong> is in the first place.

A <strong>Binary Large Object</strong> or <strong>Blob</strong> is a data type that can store unstructured (binary) data and is used to store things like images or videos in a database. Blobs are not the go-to choice when it comes to structured data that is queried frequently, such as user profile information. They have higher latency than memory and local disk and don't have the indexing features that make databases efficient at running queries. Blobs are commonly used in combination with databases to store non-queryable data, such as a profile picture for a user's profile. Each user record in the database would include the URL of the blob containing the user's photo.

### Azure Storage Accounts
An Azure storage account can store data objects you create, such as blobs and files. This storage account provides a unique namespace in Azure for your data, and every item that you store has an address that includes your unique account name. It’s worth noting the name of the storage account can contain only lowercase letters and numbers.

In this course, you'll mostly utilize General-purpose v2 storage accounts, which provide support and the latest features for Azure Storage services such as blobs, Data Lake Gen2, Files, Disks, Queues, and Tables. This type of storage account is recommended for most scenarios when using Azure Storage services.

Storage accounts can contain multiple blob containers within them, such as "images" and "movies" containers, to organize different data files. From there, each container can have many blobs inside of them (the files themselves).

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/51.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/52.jpg)

![](https://video.udacity-data.com/topher/2020/July/5f10b31c_blob-storage-hierarchy/blob-storage-hierarchy.png)

### Blob Storage Lifecycle
In an earlier video, we discussed blob storage tiers—hot, cold, and archive. These are set based on how frequently data will be accessed, with hot accessed the most frequently, with relatedly lower latency for requests, but higher costs.

Blob storage offers a rule-based policy you can use to transition your data between these tiers to optimize performance and cost. This is shown again in the below graphic - while your blobs may start in a Hot container, they could be moved to a Cool container if they have not been modified in the past 30 days. From there, if they have not been modified in 90 days, they could be transitioned to Archive storage; you could then perhaps delete them after a year of non-usage.

![](https://video.udacity-data.com/topher/2020/July/5f10b341_blob-storage-lifecycle/blob-storage-lifecycle.png)

### QUESTION 1 OF 2
True or False: Blob Storage and SQL Databases can be used interchangeably.
False

## Creating Blob Storage in the Portal:

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=9-ZCMnrULsk&feature=emb_logo)

To create a blob storage account on Azure Portal, I did the following:

### Create a Storage Account in Azure:

* 1. Click Create a resource
* 2. Search for storage account
* 3. Select the appropriate subscription and resource group (likely “resource-group-west”).
* 4. Enter a storage account name, note—it can only be lowercase letters and numbers. “helloworld1234”
* 5. Set the location to West US 2 to match the resource group.
* 6. Leave "Performance" as Standard, while making sure "Account kind" is StorageV2. This could also be BlobStorage, but StorageV2 is preferred.
* 7. We’ll leave replication on the default setting
* 8. Set "Access tier" to Cool - in a live production app, you may need this to be Hot, but in our case, Cool will work just fine.
* 9. Click "Next: Networking" to confirm that the storage account is using a Public endpoint (all networks)
* 10. Click "Next: Data Protection", "Next: Advanced", then set "Blob public access" to "Enabled".
* 11. Click "Review + Create" and then "Create" to create the database, then wait for it to deploy.

### To add a Blob Container called images:

* 1. Once the Storage account is deployed, click on its name to access it (you may need to go back to the main "Storage accounts" page in Azure).
* 2. Click on the "Containers" button in the storage account's "Overview" page.
* 3. Click "+ Container", then add the name of ```images```.
* 4. Set "Public access level" to Container, and click "Create".

<strong>NOTE:</strong> I had to refresh my page a few times before I could access the container.

### Adding Images to the Container
To add an image to the Blob Container:

* 1. Click on the container named ```images```.
* 2. Click "Upload", and add an image of your choosing.
* 3. Once the image appears within the container view, click on it, and copy the "URL" property.
* 4. Paste the URL into your browser to see if the image appropriately loads.

You can also download the file from here as well.

### QUESTION 2 OF 2
You are trying to pull in some images from blob storage into your app, but have been unsuccessful. Which of the following changes might resolve this?

* Give the blob storage container a public endpoint.
* Add the access key for the blob storage account into the call.

### Microsoft Learn Resources
* [Create an Azure Storage account](https://docs.microsoft.com/en-us/learn/modules/create-azure-storage-account/?WT.mc_id=udacity_learn-wwl)
* [Secure your Azure Storage account](https://docs.microsoft.com/en-us/learn/modules/secure-azure-storage-account/?WT.mc_id=udacity_learn-wwl)
* [Organize Azure storage blobs with properties and metadata](https://docs.microsoft.com/en-us/learn/modules/organize-blobs-properties-metadata/?WT.mc_id=udacity_learn-wwl)
* [Implement data archiving and retention](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers?tabs=azure-portal&WT.mc_id=udacity_learn-wwl)
* [Implement hot, cool, and archive storage (same content as above)](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers?tabs=azure-portal&WT.mc_id=udacity_learn-wwl) (same content as above)
* [Move items in Blob storage between storage accounts or containers](https://docs.microsoft.com/en-us/learn/modules/copy-blobs-from-command-line-and-code/?WT.mc_id=udacity_learn-wwl)
* [Blob Storage lifecycle](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-lifecycle-management-concepts?tabs=azure-portal&WT.mc_id=udacity_learn-wwl)

## Exercise: Blob Storage:

In this exercise, you will create a Storage Account with a Blob Container capable of storing images. In a later exercise, you will connect an app to the container, so that you can both get and post images from the app into the container.

* 1. Deploy a Storage Account in Azure to the “resource-group-west” resource group (or whichever resource group you have been using in earlier exercises).
* 2. Add a Blob Container to the Storage Account named ```images```.
* 3. Upload an image into the container.

<strong>Note:</strong> Azure free accounts only allow 5GB of free blob storage. Once you get to the end of this lesson, you will want to delete the Storage Account to avoid incurring any charges, as you'll create a different Storage Account in the final course project.

### Solution: Blob Storage

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=0fpwGAA0BFw&feature=emb_logo)

In this solution video, I showed you an alternative way to create an Azure Storage Account and a Storage Container using Azure CLI.

First we create our storage account. We use the following command:

```
az storage account create \
 --name helloworld12345 \
 --resource-group resource-group-west \
 --location westus2
 ```

The storage will default to general purpose V2 and the access tier cannot be set, so it will default to hot.
Then we create our container.

```
az storage container create \
 --account-name helloworld12345 \
 --name images \
 --auth-mode login \
 --public-access container
 ```
 
You can go to the portal to check that the storage account and container have been created. You can then upload an image through the portal the same way as in the earlier video; coming up, we'll look at how to connect a Python app so that the app can handle uploading images.

Lastly, I also showed you how to set up a new lifecycle management rule for an alert, which can be found under "Blob Service" within your Storage Account, under "Lifecycle Management".

## Connecting Your App to Storage:

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=4n_L0OlldXc&feature=emb_logo)

To connect an app to the storage we've set up, we need a few things from each storage service.

From the SQL server and database:

* 1. SQL Server server name (the name of the sql server with .database.windows.net appended to it)
* 2. Admin username
* 3. Admin password
* 4. SQL Database name

From blob storage:

* 1. Storage account name
* 2. A storage account access key
* 3. Container name

In our case, we're keeping the management of these values a bit simpler with a config.py file that will be imported into the primary app file.

### Azure Storage Blob Library for Python

Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/53.jpg)](https://www.youtube.com/watch?v=Fra5C7MdRGc&feature=emb_logo)

In order to interact with our Azure blob storage from within the Python web app, we'll need the [Azure Storage Blob Library](https://pypi.org/project/azure-storage-blob/). Note that you can install this with ```pip install azure-storage-blob```, and you'll need to make sure to include the library in your ```requirements.txt``` file in your own apps.

We will largely focus on the ```BlobServiceClient``` class. This class has three methods we’ll use:

* ```get_blob_client``` - creates a blob client using the filename as the name for the blob
* ```upload_blob``` - upload the file to the blob container
* ```delete_blob``` - delete a blob from a blob container

### Uploading a blob
Here is the code I included for uploading a blob.

```
from azure.storage.blob import BlobServiceClient

blob_container = app.config['BLOB_CONTAINER']
storage_url = "https://{}.blob.core.windows.net/".format(app.config['BLOB_ACCOUNT'])
blob_service = BlobServiceClient(account_url=storage_url, credential=app.config['BLOB_STORAGE_KEY'])

blob_client = blob_service.get_blob_client(container=blob_container, blob=filename)
blob_client.upload_blob(file)
```

Note that I am getting the ```BLOB_CONTAINER``` name from the configuration file, which was attached to the Flask app separately. I do a similar procedure for getting the ```BLOB_ACCOUNT``` AND ```BLOB_STORAGE_KEY``` where needed. I then use the aforementioned ```get_blob_client``` and ```upload_blob``` functions to upload a file.

You might notice that there is a ```filename``` and ```file``` used here - these are not the same things! The ```filename``` is just the name of the file, e.g. ```test_image.png```, while the ```file``` is the actual file object. So, the blob client is first called to create a blob with the given ```filename```, and then the ```file``` is uploaded into that ```filename``` blob.

### Deleting a blob
Assuming you've already defined the ```blob_service``` from before, you just need to get a new blob client with ```get_blob_client``` for the related container and ```filename```, then ```delete_blob```.

```
blob_client = blob_service.get_blob_client(container=blob_container, blob=filename)
blob_client.delete_blob()
```
It's important to note here you don't need a file to feed to ```delete_blob``` - by specifying the ```filename``` when you ```get_blob_client```, it already knows what blob you are referring to.

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/54.jpg)

### QUESTION 2 OF 2
You create a book app showing book names, authors and front covers. You successfully connect your app to storage, and can see information queried from a SQL database within the app. When you add images to the app through your blob storage account, you don't see any errors, but they show up as broken images within the app afterward. They do appear in the container in the portal. What went wrong?

* The app may not have any way to associate the book cover image to related query data

### Microsoft Learn Resources
* [Connect an app to Azure Storage](https://docs.microsoft.com/en-us/learn/modules/connect-an-app-to-azure-storage/?WT.mc_id=udacity_learn-wwl)
* [Store application data with Azure Blob storage](https://docs.microsoft.com/en-us/learn/modules/store-app-data-with-azure-blob-storage/?WT.mc_id=udacity_learn-wwl)

## Exercise: Connecting Your App to Storage:

In this exercise, you'll be given an application for a virtual zoo, and asked to add connections to your earlier deployed SQL database and Blob Storage to populate the zoo application.

If you already closed down your database and blob storage, you'll want to go back and re-create them before getting started.

Download the starter code for the app [here](https://video.udacity-data.com/topher/2020/July/5f188996_connect-app-to-storage-starter/connect-app-to-storage-starter.zip).

* 1. First, familiarize yourself at least with the ```views.py``` file in the ```FlaskExercise``` directly, although you may also want to check out the other files. You can see an example screenshot of the deployed application below.

![](https://video.udacity-data.com/topher/2020/July/5f03c0e8_example-connected-app/example-connected-app.png)

* 2. Next, add the necessary environment variables to connect to the SQL database in ```config.py```.
* 3. Then, add the necessary environment variables to connect to the Blob storage container in ```config.py```.
* 4. Add the necessary code in ```models.py``` to work with the ```BlobServiceClient``` to upload new images and delete any images that are replaced.
* 5. Run the app on your local machine, and check that the animals are correctly populated from the SQL database.
* 6. Add some images for each animal. You should be able to check back in your blob container and see that new images were added, and they should populate back to the main page.

While it's not a required part of this exercise, you can also try to deploy the app using either an app service or virtual machine; you shouldn't need any additional changes specific to the storage connections, but other changes may be necessary.

### Troubleshooting
* Mac users may need to install ```unixodbc``` as well as related drivers as shown below:
  ```brew install unixodbc```
 
* Check [here](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/install-microsoft-odbc-driver-sql-server-macos?view=sql-server-ver15&viewFallbackFrom=sql-server-ver15%3FWT.mc_id%3Dudacity_learn-wwl) to add SQL Server drivers for Mac. [This StackOverflow](https://stackoverflow.com/questions/44527452/cant-open-lib-odbc-driver-13-for-sql-server-sym-linking-issue) post may also help resolve certain issues.

### Supporting Materials
[connect-app-to-storage-starter.zip](https://video.udacity-data.com/topher/2020/July/5f188996_connect-app-to-storage-starter/connect-app-to-storage-starter.zip)
  
## Solution: Connecting Your App to Storage:
 
 Please open the video in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=7Wev-BXDovs&feature=emb_logo)
  
Since the steps to test the app locally and deploy it are the same as the previous lesson, I will skip those here, and just focus on connecting the app to storage.

### To connect with the SQL Database:

* 1. Within ```config.py```, fill out the:
>> * ```SQL_SERVER``` with the URL of your SQL Server, e.g. ```{YOUR-SQL_SERVER}.database.windows.net```
>> * ```SQL_DATABASE``` with the name of your SQL Database
>> * ```SQL_USER_NAME``` with the username for your SQL Server
>> * ```SQL_PASSWORD``` with the password for your SQL Server

### To connect to the Blob Storage Container:

* 1. Within ```config.py```, fill out the:
>> ```BLOB_ACCOUNT``` with the name of your storage account (above the container level)
>> ```BLOB_STORAGE_KEY``` with the primary access key for your storage account. From the Azure portal, navigate to the storage account, and then under "Setting", click on "Access keys". Copy and paste the "Key" under "key1", including the double equal signs ("==") at the end.
>> ```BLOB_CONTAINER``` with the name of your blob container, likely ```images```

* 2. Within ```models.py```, you'll need to use the ```BlobServiceClient``` called ```blob_service``` to get a Blob Client using the container name and related filename, and then either upload or delete the blob as follows:
  
```
 try:
     blob_client = blob_service.get_blob_client(container=blob_container, blob=filename)
     blob_client.upload_blob(file)
     if self.image_path: # Get rid of old image, since it's replaced
         blob_client = blob_service.get_blob_client(container=blob_container, blob=self.image_path)
         blob_client.delete_blob()
```
### Why to Use a Random Filename
You might be wondering why a random filename was chosen for our blob upload. Well, let's say you've created an app, and uploaded a ```tiger.png``` file to it. You give access to some of your friends to add more animals to it, and as a joke, they upload a picture of an elephant under the name ```tiger.png``` as well. Your original tiger image would be deleted and replaced.

Even outside of a friendly joke, it's quite likely as your app scales up to thousands (and hopefully millions!) of users, they will be uploading files with the same names as others, if you don't randomize them. With unique, random filenames, you won't have to worry about this issue.

## Lesson Conclusion:

In this lesson, you:

* Took a look at all the different storage options available in Azure and their benefits
* Took a deep dive on Azure SQL Databases and Blob Storage, including creating the related resources and uploading data
* Connected those storage services to your app

## Glossary:

### Key Term                    Definition
<strong>Azure SQL Server</strong>	Azure SQL Databases must first have a SQL Server on which the database will be created. Multiple databases can be created on a single server.

<strong>Azure SQL Database</strong>	Used for storing structured, relational data.

<strong>Blob</strong>	A data type that can store unstructured (binary) data, and is used to store things like images or videos in a database. Blob is short for Binary Large Object.

<strong>Storage Account</strong>	This is the highest level of storage hierarchy for data objects like blobs, files, queues, and tables.

<strong>Container</strong>	A level of the storage hierarchy that helps organize blobs, such as splitting between image and video blobs. There can be multiple containers to one storage account.

<strong>Blob Storage</strong>	Use only for storing blob data.

<strong>Table Storage</strong>	Stores structured, non-relational data.

<strong>File Storage</strong>	Utilized for file sharing storage solutions.

<strong>Disk Storage</strong>	Utilized for disk-based storage, such as hard drive and solid-state memory disks.

<strong>Data Lake Storage</strong>	Utilized for data lakes used in big data analytics.

<strong>Hot Storage</strong>	Used for storing frequently accessed data.

<strong>Cool Storage</strong>	Used for storing infrequently accessed data and stored for at least 30 days.

<strong>Archive Storage</strong>	Used for storing data that will be rarely accessed and stored for at least 180 days. Access time latency may be very high.

<strong>HPC Cache</strong>	A cache used for faster access to certain data used for high performance compute, while leaving the rest of large datasets in other storage options.

<strong>CosmosDB</strong>	Azure's non-relational database service, capable of using different non-relational databases like MongoDB and Cassandra (covered in a later course).

<strong>Retention</strong>	How long to store a given piece of data or file for, such as 30 days.


________________________________________________________________________________________________________________________________________________________________________________



# LESSON 4 SECURITY AND MONITORING BASICS 
 
 ## Introduction:
 
 In this lesson, you'll:

* Differentiate the security responsibilities between cloud developers and the cloud provider
* Discover the various security options available in Azure
* Get hands-on with Azure Active Directory, OAuth 2.0, and the Microsoft Authentication Library (MSAL)
* Add monitoring and logging into your Azure applications, including storing logs and activating alerts

Once again, this could be a course of its own, so we'll also provide a lot of additional materials for other areas to investigate outside of the scope of this lesson.
 
 ![](https://video.udacity-data.com/topher/2020/July/5f10a70f_course-outline-security-monitor/course-outline-security-monitor.png)
 
 ## Security Responsibilities: 
 
Just like we saw early on in the course with technology stack differences between on-premises, IaaS, PaaS and SaaS, security responsibilities also differ among these service types. For the cloud developer, on-premises still puts all security responsibilities onto them. With IaaS, the security of physical hardware shifts to the cloud provider. With PaaS, the operating system security shifts to be the responsibility of the cloud provider, while network, application and identity security are a shared responsibility. With SaaS, the network and application shift responsibility to the cloud provider, but identity stays as a shared responsibility.

It's important to note here that some security responsibilities always stay with the cloud developer:

* Account and access management (E.g. do you give the appropriate people the right access, and revoke access when appropriate?)
* Client endpoints (E.g. do you secure the appropriate endpoints to confidential information?)
* Data Governance and Rights Management (E.g. do you prevent employees from emailing confidential documents to third parties?)
 
 ![](https://video.udacity-data.com/topher/2020/July/5f10b4be_azure-security-responsibilities/azure-security-responsibilities.png)
 
 ![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/55.jpg)
 
### Microsoft Learn Resources
* [Cloud security](https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-security/?WT.mc_id=udacity_learn-wwl)
* [Security, responsibility, and trust in Azure](https://docs.microsoft.com/en-us/learn/modules/protect-against-security-threats-azure/)
* [Use a framework to identify threats and find ways to reduce or eliminate risk](https://docs.microsoft.com/en-us/learn/modules/tm-use-a-framework-to-identify-threats-and-find-ways-to-reduce-or-eliminate-risk/?WT.mc_id=udacity_learn-wwl)
* [Prioritize your issues and apply security controls](https://docs.microsoft.com/en-us/learn/modules/tm-prioritize-your-issues-and-apply-security-controls/?WT.mc_id=udacity_learn-wwl)
 
 ## Security Options in Azure:
 
 ![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/56.jpg)
 
 There are a ton of services and topics to consider in Azure, each with their own respective use cases. While we will focus on Azure Active Directory, OAuth 2.0 with MSAL, and some aspects of Azure Monitor in this lesson, it's still worth noting the basics of the other services and topics.
 
 ![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/57.jpg)
 
* <strong>Azure Active Directory:</strong> Provides single sign-on (SSO) and multi-factor authentication (MFA) capabilities, such as Sign in with Microsoft
* <strong>App Configuration:</strong> Stores application settings in one secure location
* <strong>Key Vault API:</strong> Stores application keys and secrets in one secure location
* <strong>Managed Identities:</strong> A part of Azure Active Directory; This helps streamline providing an app or app user access to other Azure resources
* <strong>Shared Access Signatures:</strong> Give external parties certain limited access (determined by you) to different Azure resources
* <strong>Role-Based Access Controls (RBAC):</strong> Help internally manage who has access to what resources, and what they can do to said resources
* <strong>Azure Monitor:</strong> Provides a wide range of monitoring services such as log analytics, metrics, alerts, and much more
* <strong>Application Insights:</strong> Part of Azure Monitor; This helps monitor performance and other key metrics
 
 ![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/58.jpg)
 
### QUESTION 2 OF 2
Your company is developing a new app on Azure, and developers under the project are under a strict NDA to not discuss project details with others inside the company. Within the app itself, it should be able to authenticate users with their Microsoft logins, as well as log attempts to access the deployed app by non-authorized accounts. Which of the following security options might be used here?

* Azure RBAC
* Azure Active Directory
* Azure Monitor

### Microsoft Learn Resources
* [Learning Path: Manage security operations in Azure](https://docs.microsoft.com/en-us/learn/paths/manage-security-operations/?WT.mc_id=udacity_learn-wwl)

## Case Study: Security Best Practices in Azure:

### Case Study: Security Best Practices

While we'll focus largely on Azure Active Directory and the Microsoft Authentication library in upcoming sections, it's important to also look at the broader contexts of best practices in security for the different deployment types we had earlier in the course - IaaS (with Virtual Machines) and PaaS (with App Services).

Microsoft has put together some great documentation for best practices for both of these, so first spend a few minutes reading each post (or at a minimum, skimming them).

* [IaaS Security Best Practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/iaas)
* [PaaS Security Best Practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-deployments)

You'll use the knowledge from each of these to answer the below quizzes.

### Deep Dive - PaaS
If you want, you can also dive a little deeper on the PaaS side of things with more specific articles around App Services, Azure SQL Database and Azure Storage with the below links, but they aren't required to answer the quiz questions.

* [Deep Dive: App Service Best Practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-app-services)
* [Deep Dive: Azure SQL Database Best Practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-sql)
* [Deep Dive: Azure Storage](https://docs.microsoft.com/en-us/azure/security/fundamentals/paas-applications-using-storage)

### QUESTION 1 OF 5
Which of the following are security best practices related to Virtual Machines?

* Enable encryption on VMs.
* Identify and remediate exposed VMs that allow access from “any” source IP address.
* Install the latest security updates.
* Control VM access.

### QUESTION 2 OF 5
Which of the following are security best practices related to App Services?

* Authenticate through Azure Active Directory.
* Don’t put credentials and other secrets in source code or GitHub.
* Perform security penetration testing.

### QUESTION 3 OF 5
Which of the below describe a difference in best practices between Virtual Machines and App Services?

* App Services do not have best practices around hard disks.

### QUESTION 4 OF 5
You are moved onto a project at work, and given your Azure experience, are asked to identify any security issues. One virtual machine that supports the project was deployed October 30th, 2017. What best practice may have been violated?

* Periodically redeploy your VMs to force a fresh version of the OS.

### QUESTION 5 OF 5
Your app service is running version 0.12.1 of a Python library, while the latest version is 2.1.3. An external party is able to access certain data due to a vulnerability fixed in version 1.5.6. What best practice may have been violated?

* Monitor the security state of your App Service environments.

## Azure Active Directory:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=7jZxyvMsVtI&t=59s)

Azure Active Directory is Microsoft’s solution for single sign-on (SSO) and multi-factor authentication (MFA). We'll be using it in combination with the Microsoft Authentication Library (MSAL) to use "Sign in with Microsoft" buttons in an app, although it can be used more broadly for identity management purposes within an organization. The "tenant" in Azure AD is usually equivalent to an organization.

As you get started with Azure AD, there may be a limit to your access if you are using an enterprise account - for instance, while building this course, I was actually locked out of the main Azure AD tenant for Udacity (for security reasons), and had to use a separate one for building course materials.

### Using Azure Active Directory in the Portal
As usual, you can start things off in the Azure Portal by just searching for "Active Directory". From there, you should already be in a tenant by default, although you can create a new one, if needed, to keep things separate from your main tenant. Again, if you are on an enterprise account that limits your access here, you may need to use another (personal) account.

To register an app in Azure AD (which does not actually need a deployed app for these steps):

* Click on app registrations on the left panel.
* Enter a user-facing display name.
* I allowed the widest set of accounts to access it (Accounts in any organizational directory and personal Microsoft accounts).
>> * When you build your own apps, you may want to be more restrictive, but in this case, it will make it easier for you to allow other users to authenticate with your app. An internal application, for instance, might be limited to a single tenant.
* You can ignore the redirect URI here for now, and revisit that when we get to implementing OAuth 2.0. However, if you already know this for your app, you can enter one here now, and any others necessary later on.
* Once the Application has been registered, you need to copy the Application (client) ID, as it’ll be used later in another exercise.
* Next, under manage on the left here, click on certificates and secrets
* Click on "+ New client secret", then enter a description (you can decide on your own desired expiration time, I chose one year). Copy down the string under "Value", and make sure you store it somewhere safe - <strong>you won't be able to see it again,</strong> and would otherwise have to create a new client secret once again. We’ll use this value and the application client ID when implementing OAuth 2.0.

You'll practice this yourself in the upcoming exercise.

### QUIZ QUESTION
You created a web app and have deployed it as a live website, with a requirement to sign in with a Microsoft account to access it. When you signed on with your own account, the app seems to appropriately log you in, but your friend, who can access the sign in page, said they could not. What might have happened? (You can answer this without seeing the next section on OAuth2!)

* The supported account type in Azure Active Directory may limit their access

### Microsoft Learn Resources
* [Secure Azure Active Directory users with Multi-Factor Authentication](https://docs.microsoft.com/en-us/learn/modules/secure-aad-users-with-mfa/?WT.mc_id=udacity_learn-wwl)
* [Enable secure access to apps for external users with Azure AD B2C](https://docs.microsoft.com/en-us/learn/modules/enable-external-access-with-b2c/?WT.mc_id=udacity_learn-wwl)
* [Monitor and report on security events in Azure AD](https://docs.microsoft.com/en-us/learn/modules/monitor-report-aad-security-events/?WT.mc_id=udacity_learn-wwl)

## Exercise: Azure Active Directory:

This exercise will get you familiar with registering an app in Azure Active Directory, which will set you up for the next exercise to use Microsoft Authentication.

* 1. Navigate to Azure Active Directory in the Azure portal.
>> * If you are using a corporate Microsoft account, you might be restricted from access, in which case you would need to use a personal account for this stage of the exercise.
* 2. You should already have a default tenant to use, but if not, create a new tenant and fill in the required information.
* 3. Create a new app registration, and set it to allow both any organizations and personal accounts.
* 4. You can ignore the Redirect URI for now, as that will be added as part of the next exercise.
* 5. Copy down the "Application (client) ID", which will be used in the next exercise.
* 6. Create and copy down a client secret key, which will be used in the next exercise.

## Solution: Azure Active Directory:

This is the same process as before, so we'll skip the video this time through.

## To register your app and get the necessary app information for the next exercise:

* 1. Navigate to Azure Active Directory in the Azure portal.
>> * If you are using a corporate Microsoft account, you might be restricted from access, in which case you would need to use a personal account for this stage of the exercise.
* 2. You should already have a default tenant to use, but if not, create a new tenant and fill in the required information.
* 3. Navigate to the "App registrations" page, and enter a name for the app, while allowing the widest set of accounts to access it.
>> * Remember, you'll likely want to be more restrictive when creating your own apps.
* 4. You can ignore the Redirect URI for now, as that will be added as part of the next exercise.
* 5. After you click "Register", copy down the "Application (client) ID", as you'll need that for the next exercise.
* 6. Additionally, under "Manage", click "Certificates & secrets", then "+ New client secret", then enter a description (you can decide on your own desired expiration time). Copy down string under "Value", and make sure you store it somewhere safe.

## OAuth2 with MSAL Part 1:

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/59.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/60.jpg)

<strong>Authentication</strong> is the process of checking if the user is who they say they are, and <strong>authorization</strong> is the process of checking if the user is allowed to access data and what they can do with the data.

![](https://video.udacity-data.com/topher/2020/July/5f10b5e8_authentication-vs-authorization/authentication-vs-authorization.png)

OAuth 2.0 is the industry-standard protocol for authorization. Instead of creating apps that each maintain their username and password information, apps can delegate that responsibility to a centralized identity provider.

Azure AD is the centralized identity provider in the cloud that we’ll use to implement OAuth 2.0, or more specifically "Sign in with Microsoft", in our case. The Microsoft Authentication Library (MSAL) is a Python library we’ll use to implement “Sign in with Microsoft” functionality in an app. You may have also heard of or used Active Directory Authentication Library (ADAL) before; this is an older library that does not support personal Microsoft accounts.

![](https://video.udacity-data.com/topher/2020/July/5f10b643_sign-in-with-ms/sign-in-with-ms.svg)

### The MSAL Process

In our simplified workflow, the authorization process with MSAL is as follows:

* First, when the user clicks the “Sign in with Microsoft” button in your app, a function in your app will be activated, which will cause a browser pop-up. The user signing in will request an authorization code, from the ```/oauth/v2.0/authorize``` endpoint.
* The OAuth2 provider, Microsoft in this case, will return an authorization code and will redirect the user based on a URL you have provided within your application’s Python code.
* From here, your app will then need to request an access token. To do so, you’ll need the authorization code you received before, along with information like client ID and client secret, in the case of Azure Active Directory. It’s also likely you will be requesting a certain scope, such as ```USER.READ```, which would allow you to read the user’s profile information (but not make changes to it). This will hit the ```/oauth/v2.0/token``` endpoint.
* This will then return the access token for that user.
* At this point, the access token itself is then used to actually hit some secure endpoint.
* The endpoint must actually validate the token your app sent it, which is outside of your hands. It then will return the requested secure data, if the token is validated.

You'd also need to provide the ability for users to logout.

You can also find the complete workflow in [Microsoft's documentation.](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow)

![](https://video.udacity-data.com/topher/2020/July/5f10b619_msal-oauth-process/msal-oauth-process.png)

## OAuth2 with MSAL Part 2:

### MSAL in Code

There are a few key parts to implement in your code when working with MSAL. Note that the library is just ```msal``` if you install it with ```pip install```.

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=7OS920xtw1A&t=2s)

### Getting the Authorization Code
You'll first need to create a ```ConfidentialClientApplication```:

* First create a ```ConfidentialClientApplication``` object. This class requires a Client ID and Client Secret from Azure AD.
* It also requires an “authority” based on single or multi-tenant access.
>> * For example, [https://login.microsoftonline.com/common](https://login.microsoftonline.com/common) is for multi-tenant access whereas single tenant access would replace /common with a tenant id
* We can also pass in an optional argument for a cached session to avoid re-requesting information.

Once the client is created, you'll use the ```get_authorization_request_url``` function of the client object. This requires:

* A scope, such as ```USER.READ```
* State (UUID in our case, identifying the session)
* Redirect URI
*
Note that you can find more on the MSAL library code in the link further down the page as well.

### Getting the Access Token

After re-creating the ```ConfidentialClientApplication``` object using the ```cache``` value, you then use the ````acquire_token_by_authorization_code``` method. This method requires:

* An authorization code
* A scope

This method also takes other parameters, so this could be a good spot for adding in a ```redirect_uri``` to push a user to a particular endpoint.

### Logging Out

It's also important to make sure your users can log out. This is actually a bit separate from the MSAL library itself, and is more concerned with a particular endpoint:

```
return redirect(Config.AUTHORITY + '/oauth2/v2.0/logout' +
    '?post_logout_redirect_uri=' +
    url_for('login', _external=True))
```

I briefly mentioned the ```/oauth2/v2.0/logout``` endpoint earlier, and that’s what you can redirect to after the user clicks a sign out button. It will start with the authority they signed in with, such as ```https://login.microsoftonline.com/common``` for a multi-tenant app, the OAuth logout endpoint, as well as a post-logout redirect URI.

Here, this assumes the app has some Flask endpoint for “login”, that is external to the original redirect URI (separate from Microsoft). You will also want to enter your redirect URI back in Azure AD, like you did with the redirect URIs for logging in.

### Additional Resources - MSAL

* [Python Documentation for Microsoft Authentication Library](https://msal-python.readthedocs.io/en/latest/)
* [Microsoft Graph permissions levels](https://docs.microsoft.com/en-us/graph/permissions-reference) - such as ```User.Read``` that gives an app permission to read user profile data

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/61.jpg)

### QUESTION 2 OF 2
You've built an app that utilizes the msal library for authentication purposes. The app and its related login/logout flow work fine when running on localhost, but when you deploy the app, the app loads but authentication doesn't work appropriately. What step might you have skipped with the live application?

* The live app's redirect URI needs to be added in Azure AD

### Microsoft Learn Resources - Authentication
While KeyVault API, Managed Identities, Shared Access Signatures, and Role-Based Access Controls (RBAC) are outside the scope of this course, we encourage you to check them out below, especially if you plan to take Microsoft's [AZ-204](https://docs.microsoft.com/en-us/learn/certifications/exams/az-204) exam on Developing Solutions for Microsoft Azure.

* [Secure app configuration data by using the App Configuration and KeyVault API](https://docs.microsoft.com/en-us/learn/modules/configure-and-manage-azure-key-vault/)
* [Manage keys, secrets, and certificates by using the KeyVault API (same content as above)](https://docs.microsoft.com/en-us/learn/modules/configure-and-manage-azure-key-vault)
* [Implement Managed Identities for Azure resources](https://docs.microsoft.com/en-us/learn/modules/authenticate-apps-with-managed-identities/)
* [Create and implement shared access signatures](https://docs.microsoft.com/en-us/learn/modules/control-access-to-azure-storage-with-sas/)
* [Control access to resources by using role-based access controls (RBAC)](https://docs.microsoft.com/en-us/learn/modules/secure-azure-resources-with-rbac/)

## Exercise: OAuth2 with MSAL:

This exercise will help you get familiar with integrating the Microsoft Authentication Library, or ```msal```, into an application. In the previous exercise, you registered an app with Azure Active Directory, and you'll use some of the information from there so that authentication can occur.

First, download the application code [here](https://video.udacity-data.com/topher/2020/July/5f075c1e_oauth-msal-starter/oauth-msal-starter.zip).

<strong>Note:</strong> This app will be served on ```https``` only as Azure AD will block insecure connections for redirect URIs on deployed applications. As such, when testing on ```localhost```, make sure to add ```https``` at the start instead of ```http```, e.g. ```https://localhost:5555```.

* 1. You can launch the app, if desired, to start, but you'll notice that it doesn't yet allow you to log in with your Microsoft account. To start, open up ```config.py```, and enter in both the client secret and application client ID you previously copied down from Azure AD. If your app is no longer registered, go back through the steps in the previous exercise to obtain new values.

* 2. You'll also notice a variable for ```REDIRECT_PATH```. This should start with a ```/```, and then can be whatever else you want it to be (although you should stay away from ```/home```, ```/login``` or ```/logout```, since those are used elsewhere in the app). Once you have this set, go back to Azure AD and enter this as the redirect URI for your app, as well as adding a logout URI.

* 3. Now, you're ready to get started with ```msal```. The app code contained in ```views.py``` currently implements a bit of basic log in and logout with the ```Flask-Login``` library, but you need to implement the TODOs throughout for the "Sign in with Microsoft" button on the app to work appropriately. The suggested order is as follow:

* Implement _build_msal_app to create a confidential client application
* Implement _build_auth_url to get an authorization request URL
* Acquire a token from an msal app within the authorized function
* Add the appropriate logout URL to the logout function

Together, the above four steps should allow you to have a functional "Sign in with Microsoft" button with the Microsoft Authentication Library, as well as to log back out of the related Microsoft account.

* 4. Test your app out in localhost (making sure to use ```https```), or feel free to deploy the app as well.

### Supporting Materials
[oauth-msal-starter.zip](https://video.udacity-data.com/topher/2020/July/5f075c1e_oauth-msal-starter/oauth-msal-starter.zip)

## Solution: OAuth2 with MSAL:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=CFRywEmy-2Q&feature=emb_logo)

This was my approach to the exercise:

### Add necessary variables in ```config.py```

* 1. Fill out ```CLIENT_SECRET``` and ```CLIENT_ID``` by getting the relevant values from the registered app in Azure Active Directory (see previous exercise).
* 2. Add a ```REDIRECT_PATH``` - I used ```"/getAToken"```.
* 3. Note that if we were using a single tenant app, ```AUTHORITY``` would switch from ```https://login.microsoftonline.com/common``` to ending instead with the tenant name (in place of ```common```).

### Add the redirect and logout URIs in Azure AD

* 1. Within your registered app, under "Manage", click on "Authentication", then "+Add a platform".
* 2. Select "Web" under "Web applications" in the new window.
* 3. Enter ```https://localhost:5555/getAToken``` in the redirect URI (replace ```/getAToken``` with your own ```REDIRECT_PATH```).
* 4. Enter ```https://localhost:5555/login``` in the logout URI - we want the user to be redirected back to the login page of this app when they logout. Other apps could potentially just redirect back to a homepage (our homepage is hidden behind the login process).
* Click Configure.

### Adding MSAL functionality

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/62.jpg)

### Implement "Sign in with Microsoft" with MSAL

* 1. In ```_build_msal_app```, you'll want to use a ```ConfidentialClientApplication``` (see documentation [here](https://msal-python.readthedocs.io/en/latest/#confidentialclientapplication)):

```
return msal.ConfidentialClientApplication(
     Config.CLIENT_ID, authority=authority or Config.AUTHORITY,
     client_credential=Config.CLIENT_SECRET, token_cache=cache)
 ```    
     
2. In ```_build_auth_url```, you can use the previous msal app to get an authorization request url (see documentation [here](https://msal-python.readthedocs.io/en/latest/#msal.ClientApplication.get_authorization_request_url)):

```
return _build_msal_app(authority=authority).get_authorization_request_url(
    scopes or [],
    state=state or str(uuid.uuid4()),
    redirect_uri=url_for('authorized', _external=True, _scheme='https'))
```
    
* 3. If we go back to our ```authorized``` function, we'll see a place where we can use our ```_build_msal_app``` function again, this time to acquire a token (see documentation [here](https://msal-python.readthedocs.io/en/latest/#msal.ClientApplication.acquire_token_by_authorization_code)):

```
result = _build_msal_app(cache=cache).acquire_token_by_authorization_code(
     request.args['code'],
     scopes=Config.SCOPE,
     redirect_uri=url_for('authorized', _external=True, _scheme='https'))
```
* 4. At this point, logging a user in with Microsoft should work just fine, but you should also make sure they are able to log out. So, along with making sure you have the correct logout URI in Azure AD, you also need to return the correct redirect in ```logout```:

 ```
 return redirect(
     Config.AUTHORITY + '/oauth2/v2.0/logout' +
     '?post_logout_redirect_uri=' + url_for('login', _external=True))
 ```
 
### Using HTTPS with Your App
You may have noticed the use of ```_scheme='https'``` and ```_external=True``` in the ```url_for()``` functions used in this exercise.

Setting the ```_scheme``` to "https" allows it to be served to the browser, as you may guess, through "https". Now, we don't have a fully secure app, as you may note when you try to open it in your browser; however, in this basic app, it's not super concerning just yet. However, Azure Active Directory will not allow you to use a non-HTTPS website for a live app's redirect URI (localhost can still use HTTP).

In order for this ```_scheme``` setting to work, ```_external``` must also be set to True, which just means an absolute URL will be created, as opposed to a relative URL such as which works with localhost.

### Handle MSAL Exceptions and Errors
This [article](https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-error-handling-dotnet?tabs=python) gives an overview of the different types of errors and recommendations for handling common sign-in errors.

## Monitoring and Logging in Azure:

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=lxTPv7Nte8I&t=88s)

<strong>Note:</strong> I should be using console logs when setting up my alert, not app logs.

### Benefits of Logging
Implementing logging in your applications can help with:

* Troubleshooting problems or preventing potential new ones
* Improving application performance or maintainability
* Automating operations that would otherwise require manual intervention

### Monitoring and Logging in Azure
Azure gives developers the ability to:

* Monitor metrics, such as performance and service quotas
* Use App-based logging
* Send logs to storage
* Create alerts

There are other monitoring and logging options, such as Application Insights and Log Analytics using the Kusto query language, that are outside of the scope of this course. We’ll focus on the built-in monitoring and logging offered to help debug an App Service App.

![](https://video.udacity-data.com/topher/2020/July/5f10b55d_log-solution/log-solution.png)

### Logging Considerations in a Flask App
When building a Flask application, ```print``` statements won’t show up like they usually would in a regular Python application. You’ll need to use the built-in logger Flask has to log events. You’re able to set the minimum severity level of the events you want to capture; for example, you could set the logger to only capture events at a warning level or above.

Check out the documentation in the resources below if you need some more background on how logging works for Flask applications.

### Additional Resources - Flask and Logging
* [Flask Documentation](https://flask.palletsprojects.com/en/1.1.x/)
* [Flask Logging Documentation](https://flask.palletsprojects.com/en/1.1.x/logging/)
* [Standard Python Logging Library](https://docs.python.org/3/library/logging.html) (Flask logging is a logger object from this library)

![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/63.jpg)
![](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/64.jpg)

### Microsoft Learn Resources
* [Analyze your Azure infrastructure by using Azure Monitor logs](https://docs.microsoft.com/es-es/learn/modules/analyze-infrastructure-with-azure-monitor-logs/?WT.mc_id=udacity_learn-wwl)
* [Monitor apps in Azure App Service](https://docs.microsoft.com/es-es/azure/app-service/web-sites-monitor?WT.mc_id=udacity_learn-wwl)
* [Implement code that handles transient faults](https://docs.microsoft.com/es-es/azure/architecture/best-practices/transient-faults?WT.mc_id=udacity_learn-wwl)

## Exercise: Monitoring and Logging in Azure:

### Exercise: Monitoring & Logging

In this exercise, you'll add logging to a web app, check out the logs in the Log stream for the app, create access alerts, and send the logs to a storage account for longer-term storage.

Download the app code [here](https://classroom.udacity.com/nanodegrees/nd081-1/parts/e154e8c5-f0c6-4db4-b647-dadabfdc057b/modules/1cd2c151-9c62-4f63-b605-f6cc14be548f/lessons/b5d9586f-6ad0-4e51-ab92-53c3fea26d68/concepts/421ae6a5-b925-44aa-ac47-6ef818e00503).

If you load the app on its own, you'll notice that this basic app has four buttons, responding to four different logging levels - ```info```, ```warning```, ```error``` and ```critical```. While in a complete app these would of course be triggered through different events occurring, in your case, you simply want to make sure Flask is appropriately logging these button presses.

To complete the exercise:

* 1. You want anything that is a ```warning``` or above to be logged. Make sure the app's logger is configured for this in ```__init__.py```. This means that if the ```info``` button is clicked, the related request will still be made, but both your local console, and later in Azure, should not note anything for ```info``` items.
* 2. Add some logic in ```views.py``` for logging the correct level when a given button is pressed.
* 3. Deploy the app as an app service. It may be easiest if you make a new resource group first, so that any additional services you add in the next steps can be easily deleted.

```
az webapp up \
 --sku F1 \
 --name {YOUR_APP_NAME} \
 --resource-group {YOUR_RESOURCE_GROUP} \
 --location westus2
 ```
 
* 4. While waiting for the app to deploy, create a new storage account in the resource group with your app service. Eventually, the logs will be stored here.

* 5. Once the app has deployed, navigate to the app service in the Azure portal, as well as opening the app URL in a separate window or tab. Navigate to the Log stream for your app, and check whether the logs are appearing appropriately for each button. If not, go back to steps 1 & 2.

* 6. Go the the Diagnostic settings of your app, and add a setting that sends the console logs to the storage account you created in Step 4. This will take around 10 minutes before logs start showing up in the storage account, so continue to the next step.

* 7. In the Alerts section, create a new alert based on the Requests signal for when there are greater than a count of 20 requests in a 15 minute period (set this low so you will be sure to activate it). As part of doing so, create an action group, only including yourself, that will receive an email when the alert is triggered. This may also take roughly 10 minutes to kick in, so go ahead and progress to the next step.

* 8. While you wait for the storage account to begin receiving logs and the alert to activate, go to the "Quotas" section under "App Service plan" in your app. Take note of the limits, which especially on the free tier are fairly low. If your app exceeds these limits, it will be stopped until the next reset, unless you scale up your app (outside the scope of this course). It's important to note here that all of these quota limitations are available for setting alerts - take a few minutes to consider what type of alerts you might consider setting to become aware of a potential upcoming quota issue.

* 9. If it's been 10 minutes, go back to your app website and make sure to hit each of the buttons a few times to create additional logs and potentially activate an email alert. Then, go check if your storage container appropriately contains the logs, and if you have received an email alert.

### Supporting Materials
[monitor-log-starter.zip](https://video.udacity-data.com/topher/2020/July/5f075c72_monitor-log-starter/monitor-log-starter.zip)

## Solution: Monitoring and Logging in Azure:

There's a few parts to this exercise, so let's step through each of them.

### Adding Logging in the Flask App

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/47.jpg)](https://www.youtube.com/watch?v=YLXB7YcQj84&t=37s)

The text below each video is just a text form of the solution video, so feel free to skip if you got all you needed from the video.

* 1. Flask doesn't output regular ```print``` statements as you'd see in other Python apps. However, the logger contained within a Flask app does output to ```sys.stderr```. Flask apps actually have this logger by default, and it uses the ```logging``` library from the Python standard library. As such, since we want to set the logging level to ```warning```, it can be done as follows in ```__init__.py```:

```
app.logger.setLevel(logging.WARNING)
```
We also want to update the stream handler for the logger to only pay attention to warnings and above:

```
streamHandler = logging.StreamHandler()
streamHandler.setLevel(logging.WARNING)
app.logger.addHandler(streamHandler)
```
* 2. There's quite a bit of room for exactly what messages you want to log for each log level in the app, but I did this in the basic fashion below, just stating back which level occurred:

 ```
 if log:
     if log == 'info':
         app.logger.info('No issue.')
     elif log == 'warning':
         app.logger.warning('Warning occurred.')
     elif log == 'error':
         app.logger.error('Error occurred.')
     elif log == 'critical':
         app.logger.critical('Critical error occurred.')
 ```              
* 3. From there, I first confirmed that the logs appeared to be working through the terminal by running on localhost, then I deployed the app as follows:

```
az webapp up \
 --sku F1 \
 --name {YOUR_APP_NAME} \
 --resource-group {YOUR_RESOURCE_GROUP} \
 --location westus2
``` 
 
### Sending Logs to Storage

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=iOe3OsNeziw&t=11s)

<strong>Note:</strong> I should be using console logs when setting up my alert, not app logs.

* 1. To prepare for sending logs to storage, I first went and created a new storage account in the portal. This can just be standard performance, StorageV2, with cool access tier (you would likely be better served with hot access in an app with substantial logging needs). I used the defaults for everything else.

* 2. If the app is deployed, head to the app URL and press a few buttons. Back in the App Service page in the portal, find the "Log stream" under "Monitoring", and confirm that your button presses are in fact showing up in the Log stream.

* 3. Next, click on "Diagnostic settings", also under "Monitoring", then "Add diagnostic setting". Give it a name, then under "log", click "AppServiceConsoleLogs", then under "Destination details", click "Archive to a storage account". You can change the "Retention (days)" that has appeared on the left if you want; the default of "0" will be indefinite retention. Then click "Save". It will take about ten minutes for this to begin populating.

### Adding Alerts

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=aYHVNPTRGVE&t=4s)

* 1. Go back to your App Service, and click on "Alerts" under "Monitoring", then "+ New alert rule". The scope should just be your app.

* 2. Under "Condition", click "Select condition", then find the "Signal name" ```Requests```, and click on it. Scroll down to "Alert logic", and change the "Aggregation Type" to ```Count```, then put ```20``` in the "count" box (this is set low on purpose). Finally, set the "Aggregation granularity" to 15 minutes to make sure you will activate the alert, and click "Done".

* 3. Under "Action group", click "Select action group", and then "+ Create action group". Give it an "Action group name", "Short name", then make sure to select the same Resource group as your app is in for easier deletion later on. Give the "Action name" something descriptive, such as ```20 Requests in 15 minutes```. Then, for "Action Type", select "Email/SMS message/Push/Voice". In the new window, click on "Email" and enter your own email, then click "OK" at the bottom of this side window, then "OK" at the bottom of the main window for adding the action group.

* 4. Lastly, add an alert rule name and description. You can change the severity of the alert if you wish. Make sure the final box for "Enable alert rule upon creation" is checked. Finally, click the "Create alert rule" button. Once again, this will take about 10 minutes to activate.

### Quotas & Checking on Logs and Alerts

Please open the link in a new tab to watch the tutorial:

[![IMAGE ALT TEXT](https://raw.githubusercontent.com/ARBUCHELI/BERTELSMANN-SCHOLARSHIP---INTRODUCTION-TO-AZURE-APPLICATIONS-NANODEGREE-PROGRAM/main/Images/38.jpg)](https://www.youtube.com/watch?v=goNwVw7VRbQ&t=24s)

### Considering quotas:

* 1. While waiting for the previous two stages to be ready, navigate back to your App Service, and find the "App Service plan" header, then click on "Quotas". On mine, under the free tier, I notice I have 60 minutes of CPU time for the day, and 330 MB (I accidentally say 165 MB in the video) of data out (along with one for shorter CPU time, and another for memory usage).

* 2. While not required to add the actual alerts for these, it's important to consider how you might approach doing so. If I go back to Alerts and check out the different conditions, I notice that CPU Time and Data Out are both two other Metrics I could make an alert based on. For CPU Time, perhaps I could consider setting an alert for 15 minutes total used (900 seconds) within a six hour aggregation period. If this is triggered, maintained activity at that level would cause the CPU time quota to be exceeded, leading to the app being stopped.

* 3. There are plenty of more ways to address these quotas through alerts, but that is just one example.

### Checking that log storage and alerts were appropriately created:

* 1. If it's been 10 minutes, first navigate back to your app URL and click the buttons each a handful of times, to make sure you have some new logging information, as well as hitting a decent number of requests to trigger the alert email. You can check the "Metrics" page under "Monitoring" for your App Service, and select the "Requests" metric (it updates once every five minutes) to confirm you are actually sending enough requests, or you could also manually count from the Log stream.

* 2. To check log storage is appropriately configured, go back to the storage account you created earlier, and look at its containers. If it hasn't been ten minutes yet, the logs may not have appeared yet. If a container was created, click on it, then dive down into the directories until you get to the json logs. Download the log, and confirm it shows some of your various logging from the app.

* 3. To check that the alert has appropriately occurred (make sure you have actually met the trigger criteria), just check your email. Note that you will have received a first email just for joining the action group.

![](https://video.udacity-data.com/topher/2020/July/5f075cbd_alert-email/alert-email.png)

## Lesson Conclusion:

In this lesson, you:

* Differentiated the security responsibilities between cloud developers and the cloud provider
* Discovered the various security options available in Azure
* Got hands-on with Azure Active Directory, OAuth 2.0, and the Microsoft Authentication Library (MSAL)
* Added monitoring and logging into your Azure applications, including storing logs and activating alerts

There is a ton to learn in the areas of Security and Monitoring in Azure, so make sure to check out some of the links throughout the lesson if you want to dive even deeper!

## Glossary:

### Key Term          Definition
<strong>Azure Active Directory</strong>	Provides single sign-on and multi-factor authentication capabilities, such as Sign in with Microsoft.

<strong>Tenant</strong>	Typically equivalent to an organization in Azure AD, although you can set up additional tenants as necessary.

<strong>OAuth2</strong>	The industry-standard protocol for authorization. Instead of creating apps that each maintain their username and password information, apps can delegate that responsibility to a centralized identity provider.

<strong>Microsoft Authentication Library</strong>	A Python library used in conjunction with Azure AD to utilize Microsoft single sign-on capabilities in Python apps. Abbreviated as "MSAL".

<strong>App Configuration</strong>	Stores application settings in one secure location.

<strong>KeyVault API</strong>	Stores application keys and secrets in one secure location.

<strong>Managed Identities</strong>	A part of Azure Active Directory; this helps streamline providing an app or app user access to other Azure resources.

<strong>Shared Access Signatures</strong>	Give external parties certain limited access (determined by you) to different Azure resources.

<strong>Role-Based Access Controls (RBAC)</strong>	Help internally manage who has access to what resources, and what they can do to said resources.

<strong>Transient Faults</strong>	The loss of network connectivity, service unavailability, or other timeouts; your cloud applications should appropriately handle these.

<strong>Azure Monitor</strong>	Provides a wide range of monitoring services such as log analytics, metrics, alerts, and much more.

<strong>Application Insights</strong>	Part of Azure Monitor; This helps monitor performance and other key metrics.

<strong>Authentication</strong>	The process of checking if the user is who they say they are.

<strong>Authorization</strong>	The process of checking if the user is allowed to access data, and what they can do with that data.

## Course Recap:

Congratulations on reaching the end of this course on Azure Applications! You should be proud of all of the skills you've built these past few weeks:

* Creating and deploying virtual machines and app services
* Setting up cloud storage services, such as Azure SQL Databases and Blob Storage, and connecting them to an app
* Adding OAuth 2.0 capabilities with the Microsoft Authentication Library and Azure Active Directory to your app
* Implementing monitoring and logging solutions

Next up, you'll combine all of these new skills into your final course project - building and deploying an Article CMS with Azure. Best of luck, and have fun!

![](https://video.udacity-data.com/topher/2020/July/5f04bb0d_azure-dev-c1-course-outline/azure-dev-c1-course-outline.png)


________________________________________________________________________________________________________________________________________________________________________________


# LESSON 5 PROJECT (OPTIONAL): DEPLOY AND ARTICLE CMS TO AZURE

## Project Overview:

In this project, you'll be given a simple Content Management System (CMS) for articles, where a user can log in, view published articles, and publish new articles. An article consists of a title, author, and body of text (to be stored in an Azure SQL Server) along with an image (to be stored in Azure Blob Storage).

The CMS includes the following components:

* A webapp using Python with the Flask framework.
* A SQL database that contains a user table and an article table for the webapp to query.
* A Blob Storage container where images are stored.

It will be up to you to create and manage the resources necessary to fully deploy both the necessary storage and compute resources for the app to Azure. As part of the project, you'll also need to analyze which resource best fits for app deployment between a VM or App Service. Lastly, you'll add in an authentication option to Sign in with Microsoft, as well as logging for successful and unsuccessful logins.

### App Example
Below is a screenshot from the Python Web Application, viewing an article that was created successfully.

![](https://video.udacity-data.com/topher/2020/March/5e6f8ed6_article-cms/article-cms.png)

## Instructions:

### Project Instructions

First, take a look at the [project rubric](https://review.udacity.com/#!/rubrics/2850/view), which will be used to grade your submission. Then, get the starter code from [this repository](https://github.com/udacity/nd081-c1-provisioning-microsoft-azure-vms-project-starter).

You are expected to do the following to complete this project:

* 1. Create a Resource Group in Azure.

* 2. Create an SQL Database in Azure that contains a user table, an article table, and data in each table (populated with the scripts provided in the SQL Scripts folder).

>> * Provide a screenshot of the populated tables as detailed further below.

* 3. Create a Storage Container in Azure for ```images``` to be stored in a container.

>> * Provide a screenshot of the storage endpoint URL as detailed further below.

* 4. Add functionality to the Sign In With Microsoft button.

>> * This will require completing TODOs in ```views.py``` with the ```msal``` library, along with appropriate registration in Azure Active Directory.

* 5. Choose to use either a VM or App Service to deploy the FlaskWebProject to Azure. Complete the analysis template in ```WRITEUP.md``` (or include in the README) to compare the two options, as well as detail your reasoning behind choosing one or the other. Once you have made your choice, go through with deployment.

* 6. Add logging for whether users successfully or unsuccessfully logged in.

>> * This will require completing TODOs in ```__init__.py```, as well as adding logging where desired in ```views.py```.

* 7. To prove that the application in on Azure and working, go to the URL of your deployed app, log in using the credentials in this README, click the Create button, and create an article with the following data:

>> * Title: "Hello World!"
>> * Author: "Jane Doe"
>> * Body: "My name is Jane Doe and this is my first article!"
>> * Upload an image of your choice. Must be either a .png or .jpg. After saving, click back on the article you created and provide a screenshot proving that it was created successfully. Please also make sure the URL is present in the screenshot.

* 8. Log into the Azure Portal, go to your Resource Group, and provide a screenshot including all of the resources that were created to complete this project. (see sample screenshot in "example_images" folder)

* 9. Take a screenshot of the Redirect URIs entered for your registered app, related to the MS Login button.

* 10. Take a screenshot of your logs (can be from the Log stream in Azure) showing logging from an attempt to sign in with an invalid login, as well as a valid login.

![](https://video.udacity-data.com/topher/2020/May/5ed0057a_sample-azure-portal-resource-group/sample-azure-portal-resource-group.png)

### Submission
Your submission must include the following, as according to the [project rubric](https://review.udacity.com/#!/rubrics/2850/view):

* 1. A screenshot of an article created in the Article CMS on Azure. The screenshot must also include the URL. The article should have the following fields set:
>> * Title: "Hello World!"
>> * Author: "Jane Doe"
>> * Body: "My name is Jane Doe and this is my first article!"
>> * An image of your choice. It must be either a .png or .jpg.

* 2. A screenshot of the resource group from the Azure Portal including all of the resources that were created to complete this project. (see sample screenshot above).

* 3. A screenshot showing the created tables and one query of data from the initial scripts in the SQL database (see example in the project repository).

* 4. A screenshot showing an example of blob endpoints for where images are sent for storage (see example in project repository).

* 5. A screenshot of the redirect URIs related to Microsoft authentication (see example in the project repository).

* 6. A screenshot showing one potential form of logging with an "Invalid login attempt" and "admin logged in successfully", taken from the app's Log stream or other logs you create and store (see example in project repository). You can customize your log messages as you see fit for these situations.

* 7. Your application code—most importantly ```__init__.py``` and ```views.py``` since they will contain your updates for Auth and Logging.

* 8. Your ```WRITEUP.md``` file analyzing and explaining your choice between a VM or App Service.

* 9. OPTIONAL: A URL to your Python App Service.

### Cleaning Up
### IMPORTANT:

Please make sure to cleanup your resource group in Azure after receiving your grade for this course to avoid being billed for any running services when your free account with Azure expires.














________________________________________________________________________________________________________________________________________________________________________________
# GLOSSARY 

### Reverse Proxy:
In computer networks such as the internet, a reverse proxy is a common type of proxy server that is accessible from the public network. Large websites and content delivery networks use reverse proxies –together with other techniques– to balance the load between internal servers. Reverse proxies can keep a cache of static content, which further reduces the load on these internal servers and the internal network. It is also common for reverse proxies to add features such as compression or TLS encryption to the communication channel between the client and the reverse proxy.

### Unit Testing:
In computer programming, unit testing is a software testing method by which individual units of source code—sets of one or more computer program modules together with associated control data, usage procedures, and operating procedures—are tested to determine whether they are fit for using.

### Integration Testing: 
Is the phase in software testing in which individual software modules are combined and tested as a group. Integration testing is conducted to evaluate the compliance of a system or component with specified functional requirements.  It occurs after unit testing and before validation testing.

### Content Management System: 
A content management system, often abbreviated as CMS, is software that helps users create, manage, and modify content on a website without the need for specialized technical knowledge.
In simpler language, a content management system is a tool that helps you build a website without needing to write all the code from scratch (or even know how to code at all).
Instead of building your own system for creating web pages, storing images, and other functions, the content management system handles all that basic infrastructure stuff for you so that you can focus on more forward-facing parts of your website.




# Adaptation as a repository: Andrés R. Bucheli.
