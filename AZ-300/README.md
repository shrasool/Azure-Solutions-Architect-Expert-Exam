# Microsoft Azure Architect Technologies <!-- omit in toc -->
The study guide to Exams *AZ-300: Microsoft Azure Architect Technologies*. Below is a Table of Contents that has links to all different parts of this Exam. Everything on the [official site for the AZ-300 exam](https://www.microsoft.com/en-us/learning/exam-AZ-300.aspx) is found here verbatim. The detailed breakdown of the individual components are presented in an outline style with links to documentation on each Azure resource in the exams. Enjoy!

### TABLE OF CONTENTS <!-- omit in toc -->
- [Deploy and Configure Infrastructure (25-30%)](#deploy-and-configure-infrastructure-25-30)
  - [Analyze resource utilization and consumption](#analyze-resource-utilization-and-consumption)
  - [Create and configure storage accounts](#create-and-configure-storage-accounts)
  - [Create and configure a Virtual Machine (VM) for Windows and Linux](#create-and-configure-a-virtual-machine-vm-for-windows-and-linux)
  - [Automate deployment of Virtual Machines (VMs)](#automate-deployment-of-virtual-machines-vms)
  - [Create connectivity between virtual networks](#create-connectivity-between-virtual-networks)
  - [Implement and manage virtual networking](#implement-and-manage-virtual-networking)
  - [Manage Azure Active Directory (AD)](#manage-azure-active-directory-ad)
  - [Implement and manage hybrid identities](#implement-and-manage-hybrid-identities)
- [Implement Workloads and Security (20-25%)](#implement-workloads-and-security-20-25)
  - [Migrate servers to Azure](#migrate-servers-to-azure)
  - [Configure serverless computing](#configure-serverless-computing)
  - [Implement application load balancing](#implement-application-load-balancing)
  - [Integrate on-premises network with Azure virtual network](#integrate-on-premises-network-with-azure-virtual-network)
  - [Manage role-based access control (RBAC)](#manage-role-based-access-control-rbac)
  - [Implement Multi-Factor Authentication (MFA)](#implement-multi-factor-authentication-mfa)
- [Architect Cloud Technology Solutions (5-10%)](#architect-cloud-technology-solutions-5-10)
  - [Select an appropriate compute solution](#select-an-appropriate-compute-solution)
  - [Select an appropriate integration solution](#select-an-appropriate-integration-solution)
  - [Select an appropriate storage solution](#select-an-appropriate-storage-solution)
- [Create and Deploy Apps (5-10%)](#create-and-deploy-apps-5-10)
  - [Create web applications by using PaaS](#create-web-applications-by-using-paas)
  - [Create app or service that runs on Service Fabric](#create-app-or-service-that-runs-on-service-fabric)
  - [Design and develop applications that run in containers](#design-and-develop-applications-that-run-in-containers)
- [Implement Authentication and Secure Data (5-10%)](#implement-authentication-and-secure-data-5-10)
  - [Implement authentication](#implement-authentication)
  - [Implement secure data solutions](#implement-secure-data-solutions)
- [Develop for the Cloud (20-25%)](#develop-for-the-cloud-20-25)
  - [Develop long-running tasks](#develop-long-running-tasks)
  - [Configure a message-based integration architecture](#configure-a-message-based-integration-architecture)
  - [Develop for asynchronous processing](#develop-for-asynchronous-processing)
  - [Develop for autoscaling](#develop-for-autoscaling)
  - [Implement distributed transactions](#implement-distributed-transactions)
  - [Develop advanced cloud workloads](#develop-advanced-cloud-workloads)

## Deploy and Configure Infrastructure (25-30%)
### Analyze resource utilization and consumption
* [configure diagnostic settings on resources](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/azure-diagnostics?toc=/azure/azure-monitor/toc.json);
[Alternate link](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview-of-diagnostic-logs#resource-diagnostic-settings)
* [create baseline for resources](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-alerts-dynamic-thresholds?toc=/azure/azure-monitor/toc.json);
[Alternate](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-enable-diagnostic-logs-using-template?toc=/azure/azure-monitor/toc.json)
* [create and rest alerts](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/alert-metric)
* [analyze alerts across subscription](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-activity-logs-subscriptions)
* [analyze metrics across subscription](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-metric-charts);
[Alternate link](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview-unified-alerts?toc=/azure/azure-monitor/toc.json)
* [create action groups](https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-action-groups)
* [monitor for unused resources](https://docs.microsoft.com/en-us/azure/cost-management/dashboards)
* [monitor spend](https://docs.microsoft.com/en-us/azure/billing/billing-getting-started)
* [report on spend](https://docs.microsoft.com/en-us/azure/billing/billing-download-azure-invoice-daily-usage-date)
* [utilize Log Search query functions](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-tutorial-viewdata)
* [view alerts in Log Analytics](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-solution-alert-management)
### Create and configure storage accounts
* [configure network access to the storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security)
* [create](https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?tabs=portal) and [configure storage account](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction)
* [generate shared access signature](https://docs.microsoft.com/en-gb/azure/storage/blobs/storage-dotnet-shared-access-signature-part-2)
* [install](https://azure.microsoft.com/en-us/features/storage-explorer/) and use [Azure Storage Explorer](https://docs.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=macos)
* [manage access keys](https://docs.microsoft.com/en-us/azure/key-vault/key-vault-ovw-storage-keys)
* [monitor activity log by using Log Analytics](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-azure-storage-iis-table?toc=/azure/azure-monitor/toc.json)
* [implement Azure storage replication](https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy)
### Create and configure a Virtual Machine (VM) for Windows and Linux 
* [configure high availability](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability);
ADDITIONAL: [Linux HA](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-availability-sets)
* [configure monitoring, networking, storage, and virtual machine size](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-monitoring);
ADDITIONAL: [Linux monitoring](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-monitoring)
* [deploy and configure scale sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app)
### Automate deployment of Virtual Machines (VMs)
* [modify Azure Resource Manager (ARM) template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal)
* [configure location of new VMs](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-templates-resources#location)
* [configure VHD template](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/prepare-for-upload-vhd-image)
* [deploy from template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy)
* [save a deployment as an ARM template](https://docs.microsoft.com/en-us/azure/azure-resource-manager/manage-resource-groups-portal#export-resource-groups-to-templates) 
* [deploy Windows and Linux VMs](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-automate-vm-deployment);
ADDITIONAL: [Windows](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/powershell-samples);
[Linux](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/cli-samples);
[Azure deployment sample repo](https://github.com/Azure/azure-quickstart-templates/tree/master/101-vm-simple-linux)
### Create connectivity between virtual networks
* [create and configure VNET peering](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-manage-peering)
* [create and configure VNET to VNET](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-peering-overview);
ADDITIONAL: [Sample template](https://github.com/Azure/azure-quickstart-templates/tree/master/201-vnet-to-vnet-peering)
* [verify virtual network connectivity](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-howto-site-to-site-resource-manager-portal#VerifyConnection)
* [create virtual network gateway](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-vnet-vnet-rm-ps)
[Overview](https://docs.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways)
### Implement and manage virtual networking
* [configure private and public IP addresses, network routes, network interface, subnets, and virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/manage-virtual-network);
ADDITIONAL: [Planning](https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-vnet-plan-design-arm?toc=%2fazure%2fnetworking%2ftoc.json)
### Manage Azure Active Directory (AD)
* [add custom domains](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-custom-domain)
* configure Azure AD [Identity Protection](https://docs.microsoft.com/en-us/azure/active-directory/identity-protection/enable), Azure [AD Join](https://docs.microsoft.com/en-us/azure/active-directory/devices/azureadjoin-plan), and [Enterprise State Roaming](https://docs.microsoft.com/en-us/azure/active-directory/active-directory-windows-enterprise-state-roaming-overview)
* [configure self-service password reset](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-sspr-howitworks)
* [implement conditional access policies](https://docs.microsoft.com/en-us/azure/active-directory/conditional-access/app-based-mfa)
* [manage multiple directories](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-administer#how-can-i-add-and-manage-multiple-directories)
* [perform an access review](https://docs.microsoft.com/en-us/azure/active-directory/governance/perform-access-review)
### Implement and manage hybrid identities
* [install](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-install-roadmap) and configure [Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-hybrid-identity#install-azure-ad-connect)
* [configure federation](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-fed-management) and [single sign-on](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso)
* [manage Azure AD Connect](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-post-installation)
* [manage password sync and writeback](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-writeback)

## Implement Workloads and Security (20-25%)
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

## Architect Cloud Technology Solutions (5-10%)
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

## Create and Deploy Apps (5-10%)
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

## Implement Authentication and Secure Data (5-10%)
### Implement authentication
* implement authentication by using certificates, forms-based authentication, tokens, Windows-integrated authentication
* implement multi-factor authentication by using Azure AD options
### Implement secure data solutions
* encrypt and decrypt data at rest
* encrypt data with Always Encrypted
* implement Azure Confidential Compute and SSL/TLS communications
* manage cryptographic keys in the Azure Key Vault

## Develop for the Cloud (20-25%)
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
