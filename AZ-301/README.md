# Microsoft Azure Architect Design <!-- omit in toc -->
The study guide to Exams *AZ-301: Microsoft Azure Architect Design*. Below is a Table of Contents that has links to all different parts of this Exam. Everything on the [official site for the AZ-301 exam](https://www.microsoft.com/en-us/learning/exam-AZ-301.aspx) is found here verbatim. The detailed breakdown of the individual components are presented in an outline style with links to documentation on each Azure resource in the exams. Enjoy!

### TABLE OF CONTENTS <!-- omit in toc -->
- [Determine Workload Requirements (10-15%)](#determine-workload-requirements-10-15)
  - [Gather Information and Requirements](#gather-information-and-requirements)
  - [Optimize Consumption Strategy](#optimize-consumption-strategy)
  - [Design an Auditing and Monitoring Strategy](#design-an-auditing-and-monitoring-strategy)
- [Design for Identity and Security (20-25%)](#design-for-identity-and-security-20-25)
  - [Design Identity Management](#design-identity-management)
  - [Design Authentication](#design-authentication)
  - [Design Authorization](#design-authorization)
  - [Design for Risk Prevention for Identity](#design-for-risk-prevention-for-identity)
  - [Design a Monitoring Strategy for Identity and Security](#design-a-monitoring-strategy-for-identity-and-security)
- [Design a Data Platform Solution (15-20%)](#design-a-data-platform-solution-15-20)
  - [Design a Data Management Strategy](#design-a-data-management-strategy)
  - [Design a Data Protection Strategy](#design-a-data-protection-strategy)
  - [Design and Document Data Flows](#design-and-document-data-flows)
  - [Design a Monitoring Strategy for the Data Platform](#design-a-monitoring-strategy-for-the-data-platform)
- [Design a Business Continuity Strategy (15-20%)](#design-a-business-continuity-strategy-15-20)
  - [Design a Site Recovery Strategy](#design-a-site-recovery-strategy)
  - [Design for High Availability](#design-for-high-availability)
  - [Design a disaster recovery strategy for individual workloads](#design-a-disaster-recovery-strategy-for-individual-workloads)
  - [Design a Data Archiving Strategy](#design-a-data-archiving-strategy)
- [Design for Deployment, Migration, and Integration (10-15%)](#design-for-deployment-migration-and-integration-10-15)
  - [Design Deployments](#design-deployments)
  - [Design Migrations](#design-migrations)
  - [Design an API Integration Strategy](#design-an-api-integration-strategy)
- [Design an Infrastructure Strategy (15-20%)](#design-an-infrastructure-strategy-15-20)
  - [Design a Storage Strategy](#design-a-storage-strategy)
  - [Design a Compute Strategy](#design-a-compute-strategy)
  - [Design a Networking Strategy](#design-a-networking-strategy)
  - [Design a Monitoring Strategy for Infrastructure](#design-a-monitoring-strategy-for-infrastructure)


## Determine Workload Requirements (10-15%)
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

## Design for Identity and Security (20-25%)
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

## Design a Data Platform Solution (15-20%)
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

## Design a Business Continuity Strategy (15-20%)
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

## Design for Deployment, Migration, and Integration (10-15%)
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

## Design an Infrastructure Strategy (15-20%)
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
