# Microsoft Certified Azure Solutions Architect Expert <!-- omit in toc -->
This project is my study guide to Exams *AZ-300: Microsoft Azure Architect Technologies* and *AZ-301:	Microsoft Azure Architect Design*. Below is a Table of Contents that has links to all different parts of the Exam. Everything on the [official site for the exam](https://www.microsoft.com/en-us/learning/azure-solutions-architect.aspx#skillsandknowledge) is found here verbatim. The detailed breakdown of the individual components are in the respective exam directories and are presented in an outline style with links to documentation on each Azure resource in the exams. Enjoy!

### TABLE OF CONTENTS <!-- omit in toc -->
- [Deploy and Configure Infrastructure](#deploy-and-configure-infrastructure)
  - [Analyze resource utilization and consumption](#analyze-resource-utilization-and-consumption)
  - [Create and configure storage accounts](#create-and-configure-storage-accounts)
  - [Create and configure a Virtual Machine (VM) for Windows and Linux](#create-and-configure-VM-Windows-and-Linux)
  - [Automate deployment of Virtual Machines (VMs)](#automate-deployment-of-virtual-machines)
  - [Create connectivity between virtual networks](#create-connectivity-between-virtual-networks)
  - [Implement and manage virtual networking](#implement-and-manage-virtual-networking)
  - [Manage Azure Active Directory (AD)](#manage-azure-active-directory)
  - [Implement and manage hybrid identities](#implement-and-manage-hybrid-identities)
- [Implement Workloads and Security](#implement-workloads-and-security)
  - [Migrate servers to Azure](#migrate-servers-to-azure)
  - [Configure serverless computing](#configure-serverless-computing)
  - [Implement application load balancing](#implement-application-load-balancing)
  - [Integrate on-premises network with Azure virtual network](#integrate-on-premises-network-with-azure-virtual-network)
  - [Manage role-based access control (RBAC)](#manage-role-based-access-control-RBAC)
  - [Implement Multi-Factor Authentication (MFA)](#implement-multi-factor-authentication)

- [Architect Cloud Technology Solutions](#architect-cloud-technology-solutions)
  - [Select an appropriate compute solution](#select-an-appropriate-compute-solution)
  - [Select an appropriate integration solution](#select-an-appropriate-integration-solution)
  - [Select an appropriate storage solution](#select-an-appropriate-storage-solution)

- [Create and Deploy Apps](#create-and-deploy-apps)
  - [Create web applications by using PaaS](#create-web-applications-by-using-PaaS)
  - [Create app or service that runs on Service Fabric](#create-app-or-service-that-runs-on-Service-Fabric)
  - [Design and develop applications that run in containers](#design-and-develop-applications-that-run-in-containers)
  
- [Implement Authentication and Secure Data](#implement-authentication-and-secure-data)
  - [Implement authentication](#implement-authentication)
  - [Implement secure data solutions](#implement-secure-data-solutions)

- [Develop for the Cloud](#develop-for-the-cloud)
  - [Develop long-running tasks](#develop-long-running-tasks)
  - [Configure a message-based integration architecture](#configure-a-message-based-integration-architecture)
  - [Develop for asynchronous processing](#develop-for-asynchronous-processing)
  - [Develop for autoscaling](#develop-for-autoscaling)
  - [Implement distributed transactions](#implement-distributed-transactions)
  - [Develop advanced cloud workloads](#develop-advanced-cloud-workloads)

- [Determine Workload Requirements](#determine-workload-requirements)
  - [Gather Information and Requirements](#gather-information-and-requirements)
  - [Optimize Consumption Strategy](#optimize-consumption-strategy)
  - [Design an Auditing and Monitoring Strategy](#design-an-Auditing-and-Monitoring-strategy)

- [Design for Identity and Security](#design-for-identity-and-security)
  - [Design Identity Management](#design-identity-management)
  - [Design Authentication](#design-authentication)
  - [Design Authroization](#design-authorization)
  - [Design for Risk Prevention for Identity](#design-for-risk-prevention-for-Identity)
  - [Design a Monitoring Strategy for Identity and Security](#design-a-Monitoring-Strategy-for-Identity-and-Security)

- [Design a Data Platform Solution](#design-a-data-platform-solution)
  - [Design a Data Management Strategy](#design-a-Data-Management-Strategy)
  - [Design a Data Protection Strategy](#design-a-Data-Protection-Strategy)
  - [Design and Document Data Flows](#design-and-Document-Data-Flows)
  - [Design a Monitoring Strategy for the Data Platform](#design-a-Monitoring-Strategy-for-the-Data-Platform)

- [Design a Business Continuity Strategy](#design-a-business-continuity-strategy)
  - [Design a Site Recovery Strategy](#design-a-Site-Recovery-Strategy)
  - [Design for High Availability](#design-for-High-Availability)
  - [Design a disaster recovery strategy for individual workloads](#design-a-disaster-recovery-strategy-for-individual-workloads)
  - [Design a Data Archiving Strategy](#design-a-Data-Archiving-Strategy)

- [Design for Deployment, Migration, and Integration](#design-for-Deployment-Migration-and-Integration)
  - [Design Deployments](#design-Deployments)
  - [Design Migrations](#design-Migrations)
  - [Design an API Integration Strategy](#design-an-API-Integration-Strategy)

- [Design an Infrastructure Strategy](#design-an-Infrastructure-Strategy)
  - [Design a Storage Strategy](#design-an-Storage-Strategy)
  - [Design a Compute Strategy](#design-an-Compute-Strategy)
  - [Design a Networking Strategy](#design-an-Networking-Strategy)
  - [Design a Monitoring Strategy for Infrastructure](#design-a-Monitoring-Strategy-for-Infrastructure)

## [Deploy and Configure Infrastructure](./AZ-300/README.md#deploy-and-configure-infrastructure-25-30)
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

## [Implement Workloads and Security](./AZ-300/README.md#implement-workloads-and-security-20-25)
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

## [Architect Cloud Technology Solutions](./AZ-300/README.md#architect-cloud-technology-solutions-5-10)
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

## [Create and Deploy Apps](./AZ-300/README.md#create-and-deploy-apps-5-10)
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

## [Implement Authentication and Secure Data](./AZ-300/README.md#implement-authentication-and-secure-data-5-10)
### Implement authentication
* implement authentication by using certificates, forms-based authentication, tokens, Windows-integrated authentication
* implement multi-factor authentication by using Azure AD options
### Implement secure data solutions
* encrypt and decrypt data at rest
* encrypt data with Always Encrypted
* implement Azure Confidential Compute and SSL/TLS communications
* manage cryptographic keys in the Azure Key Vault

## [Develop for the Cloud](./AZ-300/README.md#develop-for-the-cloud-20-25)
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

## Determine Workload Requirements
### Gather Information and Requirements
* identify compliance requirements, identity and access management infrastructure, and service-oriented architectures (e.g., integration patterns, service design, service discoverability)
* identify accessibility (e.g. Web Content Accessibility Guidelines), availability (e.g. Service Level Agreement), capacity planning and scalability, deploy-ability (e.g., repositories, failback, slot-based deployment), configurability, governance, maintainability (e.g. logging, debugging, troubleshooting, recovery, training), security (e.g. authentication, authorization, attacks), and sizing (e.g. support costs, optimization) requirements
* recommend changes during project execution (ongoing)
* evaluate products and services to align with solution
* create testing scenarios
### Optimize Consumption Strategy
* optimize app service, compute, identity, network, and storage costs
### Design an Auditing and Monitoring Strategy
* define logical groupings (tags) for resources to be monitored
* determine levels and storage locations for logs
* plan for integration with monitoring tools
* recommend appropriate monitoring tool(s) for a solution
* specify mechanism for event routing and escalation
* design auditing for compliance requirements
* design auditing policies and traceability requirements

## Design for Identity and Security
### Design Identity Management
* choose an identity management approach
* design an identity delegation strategy, identity repository (including directory, application, systems, etc.)
* design self-service identity management and user and persona provisioning
* define personas and roles
* recommend appropriate access control strategy (e.g., attribute-based, discretionary access, history-based, identity-based, mandatory, organization-based, role-based, rule-based, responsibility-based)
### Design Authentication
* choose an authentication approach
* design a single-sign on approach
* design for IPSec, logon, multi-factor, network access, and remote authentication
### Design Authorization
* choose an authorization approach
* define access permissions and privileges
* design secure delegated access (e.g., oAuth, OpenID, etc.)
* recommend when and how to use API Keys
### Design for Risk Prevention for Identity
* design a risk assessment strategy (e.g., access reviews, RBAC policies, physical access)
* evaluate agreements involving services or products from vendors and contractors
* update solution design to address and mitigate changes to existing security policies, standards, guidelines and procedures
### Design a Monitoring Strategy for Identity and Security
* design for alert notifications
* design an alert and metrics strategy
* recommend authentication monitors

## Design a Data Platform Solution
### Design a Data Management Strategy
* choose between managed and unmanaged data store
* choose between relational and non-relational databases
* design data auditing and caching strategies
* identify data attributes (e.g., relevancy, structure, frequency, size, durability, etc.)
* recommend Database Transaction Unit (DTU) sizing
* design a data retention policy
* design for data availability, consistency, and durability
* design a data warehouse strategy
### Design a Data Protection Strategy
* recommend geographic data storage
* design an encryption strategy for data at rest, for data in transmission, and for data in use
* design a scalability strategy for data
* design secure access to data
* design a data loss prevention (DLP) policy
### Design and Document Data Flows
* identify data flow requirements
* create a data flow diagram
* design a data flow to meet business requirements
* design a data import and export strategy
### Design a Monitoring Strategy for the Data Platform
* design for alert notifications
* design an alert and metrics strategy

## Design a Business Continuity Strategy
### Design a Site Recovery Strategy
* design a recovery solution
* design a site recovery replication policy
* design for site recovery capacity and for storage replication
* design site failover and failback (planned/unplanned)
* design the site recovery network
* recommend recovery objectives (e.g., Azure, on-prem, hybrid, Recovery Time Objective (RTO), Recovery Level Objective (RLO), Recovery Point Objective (RPO))
* identify resources that require site recovery
* identify supported and unsupported workloads
* recommend a geographical distribution strategy
### Design for High Availability
* design for application redundancy, autoscaling, data center and fault domain redundancy, and network redundancy
* identify resources that require high availability
* identify storage types for high availability
### Design a disaster recovery strategy for individual workloads
* design failover/failback scenarios
* document recovery requirements
* identify resources that require backup
* recommend a geographic availability strategy
### Design a Data Archiving Strategy
* recommend storage types and methodology for data archiving
* identify requirements for data archiving and business compliance requirements for data archiving
* identify SLA(s) for data archiving

## Design for Deployment, Migration, and Integration
### Design Deployments
* design a compute, container, data platform, messaging solution, storage, and web app and service deployment strategy
### Design Migrations
* recommend a migration strategy
* design data import/export strategies during migration
* determine the appropriate application migration, data transfer, and network connectivity method
* determine migration scope, including redundant, related, trivial, and outdated data
* determine application and data compatibility
### Design an API Integration Strategy
* design an API gateway strategy
* determine policies for internal and external consumption of APIs
* recommend a hosting structure for API management

## Design an Infrastructure Strategy
### Design a Storage Strategy
* design a storage provisioning strategy
* design storage access strategy
* identify storage requirements
* recommend a storage solution and storage management tools
### Design a Compute Strategy
* design compute provisioning and secure compute strategies
* determine appropriate compute technologies (e.g., virtual machines, functions, service fabric, container instances, etc.)
* design an Azure HPC environment
* identify compute requirements
* recommend management tools for compute
### Design a Networking Strategy
* design network provisioning and network security strategies
* determine appropriate network connectivity technologies
* identify networking requirements
* recommend network management tools
### Design a Monitoring Strategy for Infrastructure
* design for alert notifications
* design an alert and metrics strategy
