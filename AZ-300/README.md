# Microsoft Azure Architect Technologies <!-- omit in toc -->
The study guide to Exams *AZ-300: Microsoft Azure Architect Technologies*. Below is a Table of Contents that has links to all different parts of this Exam. Everything on the [official site for the AZ-300 exam](https://www.microsoft.com/en-us/learning/exam-AZ-300.aspx) is found here verbatim. The detailed breakdown of the individual components are presented in an outline style with links to documentation on each Azure resource in the exams. Enjoy!

### TABLE OF CONTENTS <!-- omit in toc -->
- [Deploy and Configure Infrastructure (25-30 %)](#deploy-and-configure-infrastructure-25-30)
  - [Analyze resource utilization and consumption](#analyze-resource-utilization-and-consumption)
  - [Create and configure storage accounts](#create-and-configure-storage-accounts)
  - [Create and configure a Virtual Machine (VM) for Windows and Linux](#create-and-configure-a-virtual-machine-vm-for-windows-and-linux)
  - [Automate deployment of Virtual Machines (VMs)](#automate-deployment-of-virtual-machines-vms)
  - [Create connectivity between virtual networks](#create-connectivity-between-virtual-networks)
  - [Implement and manage virtual networking](#implement-and-manage-virtual-networking)
  - [Manage Azure Active Directory (AD)](#manage-azure-active-directory-ad)
  - [Implement and manage hybrid identities](#implement-and-manage-hybrid-identities)
- [Implement Workloads and Security (20-25 %)](#implement-workloads-and-security-20-25)
  - [Migrate servers to Azure](#migrate-servers-to-azure)
  - [Configure serverless computing](#configure-serverless-computing)
  - [Implement application load balancing](#implement-application-load-balancing)
  - [Integrate on-premises network with Azure virtual network](#integrate-on-premises-network-with-azure-virtual-network)
  - [Manage role-based access control (RBAC)](#manage-role-based-access-control-rbac)
  - [Implement Multi-Factor Authentication (MFA)](#implement-multi-factor-authentication-mfa)
- [Architect Cloud Technology Solutions (5-10 %)](#architect-cloud-technology-solutions-5-10)
  - [Select an appropriate compute solution](#select-an-appropriate-compute-solution)
  - [Select an appropriate integration solution](#select-an-appropriate-integration-solution)
  - [Select an appropriate storage solution](#select-an-appropriate-storage-solution)
- [Create and Deploy Apps (5-10 %)](#create-and-deploy-apps-5-10)
  - [Create web applications by using PaaS](#create-web-applications-by-using-paas)
  - [Create app or service that runs on Service Fabric](#create-app-or-service-that-runs-on-service-fabric)
  - [Design and develop applications that run in containers](#design-and-develop-applications-that-run-in-containers)
- [Implement Authentication and Secure Data (5-10 %)](#implement-authentication-and-secure-data-5-10)
  - [Implement authentication](#implement-authentication)
  - [Implement secure data solutions](#implement-secure-data-solutions)
- [Develop for the Cloud (20-25 %)](#develop-for-the-cloud-20-25)
  - [Develop long-running tasks](#develop-long-running-tasks)
  - [Configure a message-based integration architecture](#configure-a-message-based-integration-architecture)
  - [Develop for asynchronous processing](#develop-for-asynchronous-processing)
  - [Develop for autoscaling](#develop-for-autoscaling)
  - [Implement distributed transactions](#implement-distributed-transactions)
  - [Develop advanced cloud workloads](#develop-advanced-cloud-workloads)

## Deploy and Configure Infrastructure (25-30 %)
### Analyze resource utilization and consumption
* configure diagnostic settings on resources
* create baseline for resources
* create and rest alerts
* analyze alerts across subscription
* analyze metrics across subscription
* create action groups
* monitor for unused resources
* monitor spend
* report on spend
* utilize Log Search query functions
* view alerts in Log Analytics
### Create and configure storage accounts
* configure network access to the storage account
* create and configure storage account
* generate shared access signature
* install and use Azure Storage Explorer
* manage access keys
* monitor activity log by using Log Analytics
* implement Azure storage replication
### Create and configure a Virtual Machine (VM) for Windows and Linux 
* configure high availability
* configure monitoring, networking, storage, and virtual machine size
* deploy and configure scale sets
### Automate deployment of Virtual Machines (VMs)
* modify Azure Resource Manager (ARM) template
* configure location of new VMs
* configure VHD template
* deploy from template
* save a deployment as an ARM template
* deploy Windows and Linux VMs
### Create connectivity between virtual networks
* create and configure VNET peering
* create and configure VNET to VNET
* verify virtual network connectivity
* create virtual network gateway
### Implement and manage virtual networking
* configure private and public IP addresses, network routes, network interface, subnets, and virtual network
### Manage Azure Active Directory (AD)
* add custom domains
* configure Azure AD Identity Protection, Azure AD Join, and Enterprise State Roaming
* configure self-service password reset
* implement conditional access policies
* manage multiple directories
* perform an access review
### Implement and manage hybrid identities
* install and configure Azure AD Connect
* configure federation and single sign-on
* manage Azure AD Connect
* manage password sync and writeback

## Implement Workloads and Security (20-25 %)
### Migrate servers to Azure
* migrate by using Azure Site Recovery (ASR)
* migrate using P2V
* configure storage
* create a backup vault
* prepare source and target environments
* backup and restore data
* deploy Azure Site Recovery (ASR) agent
* prepare virtual network
### Configure serverless computing
* create and manage objects
* manage a Logic App resource
* manage Azure Function app settings
* manage Event Grid
* manage Service Bus
### Implement application load balancing
* configure application gateway and load balancing rules
* implement front end IP configurations
* manage application load balancing
### Integrate on-premises network with Azure virtual network
* create and configure Azure VPN Gateway
* create and configure site to site VPN
* configure Express Route
* verify on-premises connectivity
* manage on-premises connectivity with Azure
### Manage role-based access control (RBAC)
* create a custom role
* configure access to Azure resources by assigning roles
* configure management access to Azure
* troubleshoot RBAC
* implement RBAC policies
* assign RBAC roles
### Implement Multi-Factor Authentication (MFA)
* enable MFA for an Azure tenant
* configure user accounts for MFA
* configure fraud alerts
* configure bypass options
* configure trusted IPs
* configure verification methods
* manage role-based access control (RBAC)
* implement RBAC policies
* assign RBAC Roles
* create a custom role
* configure access to Azure resources by assigning roles
* configure management access to Azure

## Architect Cloud Technology Solutions (5-10 %)
### Select an appropriate compute solution
* leverage appropriate design patterns
* select appropriate network connectivity options
* design for hybrid topologies
### Select an appropriate integration solution
* address computational bottlenecks, state management, and OS requirements
* provide for web hosting if applicable
* evaluate minimum number of nodes
### Select an appropriate storage solution
* validate data storage technology capacity limitations
* address durability of data
* provide for appropriate throughput of data access
* evaluate structure of data storage
* provide for data archiving, retention, and compliance

## Create and Deploy Apps (5-10 %)
### Create web applications by using PaaS
* create an Azure app service web app by using Azure CLI, PowerShell, and other tools
* create documentation for the API by using open source and other tools
* create an App Service Web App for containers
* create an App Service background task by using WebJobs
### Create app or service that runs on Service Fabric
* develop a stateful Reliable Service and a stateless Reliable Service
* develop an actor-based Reliable Service
* write code to consume Reliable Collections in your service
### Design and develop applications that run in containers
* configure diagnostic settings on resources
* create a container image by using a Docker file
* create an Azure Container Service (ACS/AKS) cluster by using the Azure CLI and Azure Portal
* publish an image to the Azure Container Registry
* implement an application that runs on an Azure Container Instance
* implement container instances by using Azure Container Service (ACS/AKS), Azure Service Fabric, and other tools
* manage container settings by using code

## Implement Authentication and Secure Data (5-10 %)
### Implement authentication
* implement authentication by using certificates, forms-based authentication, tokens, Windows-integrated authentication
* implement multi-factor authentication by using Azure AD options
### Implement secure data solutions
* encrypt and decrypt data at rest
* encrypt data with Always Encrypted
* implement Azure Confidential Compute and SSL/TLS communications
* manage cryptographic keys in the Azure Key Vault

## Develop for the Cloud (20-25 %)
### Develop long-running tasks
* implement large-scale, parallel, and high-performance apps by using batches
* implement resilient apps by using queues
* implement code to address application events by using web hooks
* address continuous processing tasks by using web jobs
### Configure a message-based integration architecture
* configure an app or service to send emails, Event Grid, and the Azure Relay Service
* create and configure a Notification Hub, an Event Hub, and a Service Bus
* configure queries across multiple products
* configure an app or service with Microsoft Graph
### Develop for asynchronous processing
* implement parallelism, multithreading, processing, durable functions, Azure logic apps, interfaces with storage, interfaces to data access, and appropriate asynchronous compute models
### Develop for autoscaling
* implement autoscaling rules and patterns (schedule, operational/system metrics, code that addresses singleton application instances, and code that addresses transient state
### Implement distributed transactions
* identify tools to implement distributed transactions (e.g., ADO.NET, elastic transactions, multi-database transactions)
* manage transaction scope
* manage transactions across multiple databases and servers
### Develop advanced cloud workloads
* develop solutions by using intelligent algorithms that identify items from images and videos
* develop solutions by using intelligent algorithms related to speech, natural language processing, Bing Search, and recommendations and decision making
* create and integrate bots
* integrate machine learning solutions in an app
* create and implement IoT solutions
