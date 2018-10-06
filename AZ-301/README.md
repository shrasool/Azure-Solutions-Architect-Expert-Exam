# Microsoft Certified Azure Solutions Architect Expert <!-- omit in toc -->
This project is my study guide to Exams *AZ-300: Microsoft Azure Architect Technologies* and *AZ-301:	Microsoft Azure Architect Design*. Below is a Table of Contents that has links to all different parts of the Exam. Everything on the [official site for the exam](https://www.microsoft.com/en-us/learning/azure-solutions-architect.aspx#skillsandknowledge) is found here verbatim. The detailed breakdown of the individual components are in the respective exam directories and are presented in an outline style with links to documentation on each Azure resource in the exams. Enjoy!

### TABLE OF CONTENTS <!-- omit in toc -->
- [Design Compute Infrastructure (20-25%)](#design-compute-infrastructure-20-25)
  - [Design solutions using virtual machines (VMs)](#design-solutions-using-virtual-machines-vms)
  - [Design solutions for serverless computing](#design-solutions-for-serverless-computing)
  - [Design microservices-based solutions](#design-microservices-based-solutions)
  - [Design web applications](#design-web-applications)
  - [Create compute-intensive applications](#create-compute-intensive-applications)
- [Design Data Implementation (15-20%)](#design-data-implementation-15-20)
  - [Design for Azure Storage solutions](#design-for-azure-storage-solutions)
  - [Design for Azure Data Services](#design-for-azure-data-services)
  - [Design for relational database storage](#design-for-relational-database-storage)
  - [Design for NoSQL storage](#design-for-nosql-storage)
  - [Design for CosmosDB storage](#design-for-cosmosdb-storage)
- [Design Networking Implementation (15-20%)](#design-networking-implementation-15-20)
  - [Design Azure virtual networks](#design-azure-virtual-networks)
  - [Design external connectivity for Azure Virtual Networks](#design-external-connectivity-for-azure-virtual-networks)
  - [Design security strategies](#design-security-strategies)
  - [Design connectivity for hybrid applications](#design-connectivity-for-hybrid-applications)
- [Design Security and Identity Solutions (20-25%)](#design-security-and-identity-solutions-20-25)
  - [Design an Identity solution](#design-an-identity-solution)
  - [Secure resources by using identity providers](#secure-resources-by-using-identity-providers)
  - [Design a data security solution](#design-a-data-security-solution)
  - [Design a mechanism of governance and policies for administering Azure resources](#design-a-mechanism-of-governance-and-policies-for-administering-azure-resources)
  - [Manage security risks by using an appropriate security solution](#manage-security-risks-by-using-an-appropriate-security-solution)
- [Design Solutions by using Platform Services (10-15%)](#design-solutions-by-using-platform-services-10-15)
  - [Design for Artificial Intelligence Services](#design-for-artificial-intelligence-services)
  - [Design for IoT](#design-for-iot)
  - [Design messaging solution architectures](#design-messaging-solution-architectures)
  - [Design for media service solutions](#design-for-media-service-solutions)
- [Design for Operations (10-15%)](#design-for-operations-10-15)
  - [Design an application monitoring and alerting strategy](#design-an-application-monitoring-and-alerting-strategy)
  - [Design a platform monitoring and alerting strategy](#design-a-platform-monitoring-and-alerting-strategy)
  - [Design an operations automation strategy](#design-an-operations-automation-strategy)

## Design Compute Infrastructure (20-25%)
### Design solutions using virtual machines (VMs)
- Design VM deployments by leveraging [availability sets](AvailabilitySet.md), fault domains, and update domains in Azure
- Use [Web App for Containers](WebAppForContainers.md)
- Design [VM Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview)
- Design for compute-intensive tasks using [Azure Batch](Batch.md) and Azure Batch AI
- Define a migration strategy from cloud services
- Determine when to use reserved instances
- Design for VMs in a DevTest Lab environment (including formulas, images, artifacts, claiming and un-claiming VMs)
- Determine when to use Accelerated Networking
- Recommend use of Azure Backup and Azure Site Recovery including support for Linux in Azure Backup and integrating Azure Backup in the VM creation process
- Recommend when to use [availability zones](https://docs.microsoft.com/en-us/azure/availability-zones/az-overview)
### Design solutions for serverless computing
- Use [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview) to implement event-driven actions
- Design data storage solutions for serverless computing
- Design for serverless computing using Azure Container Instances
- Design application solutions by using Azure Logic Apps, Azure Functions, or both
- Determine when to use API management service
- Design event routing solutions using Azure Event Grid
- Design solutions that integrate stream processing and bot messaging
### Design microservices-based solutions 
- Determine when a container-based solution is appropriate 
- Determine when container-orchestration is appropriate 
- Determine when Azure Service Fabric (ASF) is appropriate 
- Determine when Azure Functions is appropriate 
- Determine when to use API management service 
- Determine when Web API is appropriate - Doesn't really exist any more as a standalone offering. Has been folded into Azure App Services -> Web Apps.
- Determine which platform is appropriate for container orchestration 
- Consider migrating existing assets versus cloud native deployment 
- Design lifecycle management strategies
### Design web applications
- Design Azure App Service Web Apps
- Design custom web API
- Secure Web API
- Design Web Apps for scalability and performance
- Design for high availability using Azure Web Apps in multiple regions
- Determine which App service plan to use
- Design Web Apps for business continuity
- Determine when to use Azure App Service Isolated
- Design for API apps
- Determine when to use API management service
- Determine when to use Web Apps on Linux
- Determine when to use a CDN
- Determine when to use a cache, including Azure Redis cache
### Create compute-intensive applications
- Design high-performance computing (HPC) and other compute-intensive applications using Azure Services
- Determine when to use Azure Batch design stateless components to accommodate scale
- Design lifecycle strategy for Azure Batch
- Design solution that implement low priority batching and job task counting
## Design Data Implementation (15-20%)
### Design for Azure Storage solutions
Determine when to use:
- Azure Blob Storage
- Blob tiers (hot, cool, archive)
- Azure Files
- Disks
- Azure Data Box
- Azure Storage Service Encryption - Automatic. Can use KeyVault to store your own key rather than use MS keys.
- Azure StorSimple
### Design for Azure Data Services
Determine when to use:
- Azure Data Catalog
- Azure Data Factory
- Azure SQL Data Warehouse
- Azure Data Lake Analytics
- Azure Analysis Services
- Azure HDInsight
### Design for relational database storage
- Determine when to use Azure SQL Database and SQL Server Stretch Database
- Design for scalability and features
- Determine when to use Azure Database for MySQL and Azure Database for PostgreSQL
- Design for HA/DR, geo-replication
- Design a backup and recovery strategy
- Design optimization strategies for Azure SQL Data Warehouse columnar storage
### Design for NoSQL storage
Determine when to use:
- Azure Redis Cache
- Azure Table Storage
- Azure Data Lake
- Azure Search
- Time Series Insights
----------
- Design pipelines for managing recurring jobs
### Design for [CosmosDB](Cosmos.md) storage
- Determine when to use MongoDB API, Azure Cosmos DB SQL API, Graph API, Azure Tables API
- Design for cost, performance, data consistency, availability, and business continuity
## Design Networking Implementation (15-20%)
### Design Azure virtual networks
- Design solutions that use Azure networking services:
  - Design for load balancing using:
    - [Azure Load Balancer](https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview) 
    - [Azure Traffic Manager](https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview) - DNS Load Balancer
  - Define DNS, DHCP, and IP strategies 
  - Determine when to use [Azure Application Gateway](https://docs.microsoft.com/en-us/azure/application-gateway/application-gateway-introduction) - Application Layer (OSI 7) router and firewall 
  - Determine when to use [virtual network (VNet) service endpoints](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-service-endpoints-overview) 
  - Determine when to use multi-node application gateways, Traffic Manager and load balancers
### Design external connectivity for Azure Virtual Networks
- Determine when to use Azure VPN, Azure ExpressRoute and Virtual Network Peering architecture and design 
- Determine when to use User Defined Routes (UDRs) 
- Determine when to use VPN gateway site-to-site failover for ExpressRoute 
- Determine when to use the Container Networking Interface (CNI) plugin 
- Design solutions that use Global VNet Peering
### Design security strategies
- Determine when to use network virtual appliances 
- Design a perimeter network (DMZ) 
- Determine when to use a Web Application Firewall (WAF), Network Security Group (NSG), and virtual network service tunneling 
- Organize resources by designing solutions that use service tags
### Design connectivity for hybrid applications
- Design connectivity to on-premises data from Azure applications using:
  - [Azure Relay Service](https://docs.microsoft.com/en-us/azure/service-bus-relay/relay-what-is-it)
  - Azure Data Management Gateway for Data Factory
  - Azure On-Premises Data Gateway, Hybrid Connections 
  - Azure Web App’s virtual private network (VPN) capability 
- Identify constraints for connectivity with VPN 
- Identify options for joining VMs to domains
## Design Security and Identity Solutions (20-25%)
### Design an Identity solution
- Design AD Connect synchronization 
- Design federated identities using Active Directory Federation Services (AD FS) 
- Design solutions for Multi-Factor Authentication (MFA) 
- Design an architecture using Active Directory on-premises and Azure Active Directory (AAD) 
- Determine when to use Azure AD Domain Services 
- Design security for Mobile Apps using AAD
### Secure resources by using identity providers
- Design solutions that use external or consumer identity providers such as Microsoft account, Facebook, Google, and Yahoo 
- Determine when to use Azure AD B2C and Azure AD B2B 
- Design mobile apps using AAD B2C or AAD B2B
### Design a data security solution
- Design data security solutions for Azure services 
- Determine when to use Azure Storage encryption, Azure Disk Encryption, Azure SQL Database security capabilities, and Azure Key Vault
- Design for protecting secrets in ARM templates using Azure Key Vault 
- Design for protecting application secrets using Azure Key Vault 
- Design a solution for managing certificates using Azure Key Vault 
- Design solutions that use Azure AD Managed Service Identity
### Design a mechanism of governance and policies for administering Azure resources
- Determine when to use Azure RBAC standard roles and custom roles 
- Define an Azure RBAC strategy 
- Determine when to use Azure resource policies 
- Determine when to use Azure AD Privileged Identity Management 
- Design solutions that use Azure AD Managed Service Identity 
- Determine when to use HSM-backed keys
### Manage security risks by using an appropriate security solution
- Identify, assess, and mitigate security risks by using Azure Security Center, Operations Management Suite Security and Audit solutions, and other services 
- Determine when to use Azure AD Identity Protection 
- Determine when to use Advanced Threat Detection 
- Determine an appropriate endpoint protection strategy
## Design Solutions by using Platform Services (10-15%)
### Design for Artificial Intelligence Services
Determine when to use the appropriate Cognitive Services:
- Azure Bot Service
- Azure Machine Learning
- and other categories that fall under cognitive AI
### Design for IoT
Determine when to use:
- Azure Stream Analytics
- Azure IoT Hubs
- Azure Event Hubs
- Real-time analytics
- Azure Time Series Insights
- Azure IoT Edge
- Azure Notification Hubs
- Event Grid
- Other services that fall under IoT
### Design messaging solution architectures
- Design a messaging architecture 
- Determine when to use 
  - Azure Storage Queues 
  - Azure Service Bus
  - Azure Event Hubs
  - Azure Event Grid 
  - Azure Relay
  - Azure Functions
  - Azure Logic Apps
- Design a push notification strategy for Mobile Apps
- Design for performance and scale
### Design for media service solutions
- Define solutions using:
  - Azure Media Services
  - Video indexer
  - Video API
  - Computer vision API 
  - Preview, and other media related services
- Design solutions that use file-based encoding or Azure Media Analytics
## Design for Operations (10-15%)
### Design an application monitoring and alerting strategy
- Determine the appropriate Microsoft products and services for monitoring applications on Azure 
- Define solutions for analyzing logs and enabling alerts using Azure Log Analytics 
- Define solutions for analyzing performance metrics and enabling alerts using Azure Monitor 
- Define a solution for monitoring applications and enabling alerts using Application Insights
### Design a platform monitoring and alerting strategy
- Determine the appropriate Microsoft products and services for monitoring Azure platform solutions 
- Define a monitoring solution using Azure Health, Azure Advisor, and Activity Log 
- Define a monitoring solution for Azure Networks using Log Analytics and Network Watcher service 
- Monitor security with Azure Security Center 
- Design TCP connections
### Design an operations automation strategy
- Determine when to use: 
  - [Azure Automation](https://docs.microsoft.com/en-us/azure/automation/automation-intro) - A configuration management tool that allows for [Run Books](https://en.wikipedia.org/wiki/Runbook), Inventory Tracking, Update Management, and Desired State monitoring.
  - [Chef](https://en.wikipedia.org/wiki/Chef_(software)) - [In-Depth Overview](https://docs.chef.io/chef_overview.html) Uses cookbooks and recipes.
  - Puppet - [Open Source Puppet](https://puppet.com/docs/puppet/5.5/architecture.html) uses catalogs with resources and desired states within them. There is a commerical company that produces Puppet Discovery for Inventory Management and Puppet Enterprise for configuration management.
  - PowerShell - You can use just PowerShell or [PowerShell DSC](https://docs.microsoft.com/en-us/powershell/dsc/overview). Comparison of [Powershell vs. Powershell DSC](https://docs.microsoft.com/en-us/powershell/dsc/dscforengineers#i-have-powershell-why-do-i-need-desired-state-configuration).
  - [Azure Automation (DSC)](https://docs.microsoft.com/en-us/azure/automation/automation-dsc-overview) 
  - [Event Grid](https://docs.microsoft.com/en-us/azure/event-grid/overview) - Can notify Azure Automation when a VM or DB is spun up, for example.
  - [Azure Logic Apps](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview) - For more complex logic on 
- Define a strategy for auto-scaling 
- Define a strategy for enabling periodic processes and tasks 
- Define an update management strategy
