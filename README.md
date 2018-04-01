# gsuttie-gsuttie.github.io
70-532 Azure Exam links


My Exam Study Notes for the 70-532 Exam based off of the requirements on the exam web page - I'll move this to a GitHub page so that people can help keep the page links up to date.

**Create and Manage Azure Resource Manager Virtual Machines (20-25%)**
- Deploy workloads on Azure Resource Manager (ARM) virtual machines (VMs)
https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview

- Identify workloads that can and cannot be deployed; run workloads including Microsoft and Linux; create and provision VMs, including custom VM images; deploy workloads using Terraform
Windows: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/virtual-machines-windows/

  - Linux: https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/virtual-machines-linux/

   - Create a complete Linux virtual machine infrastructure in Azure with Terraform: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/terraform-create-complete-vm

   - TerraForm with Azure: https://docs.microsoft.com/en-us/azure/terraform/terraform-overview

   - Install and configure Terraform to provision VMs and other infrastructure into Azure:  https://docs.microsoft.com/en-us/azure/virtual-machines/linux/terraform-install-configure

   - Create a VM cluster with Terraform using the Module Registry: https://docs.microsoft.com/en-us/azure/terraform/terraform-create-vm-cluster-module

**Perform configuration management**

   - Automate configuration management by using PowerShell Desired State Configuration (DSC) or VM Agent (custom script extensions); enable remote debugging; implement VM template variables to configureVMs

      - Azure Automation DSC Overview: https://docs.microsoft.com/en-us/azure/automation/automation-dsc-overview

      - The what, why and how of Azure Automation Desired State Configuration (DSC): https://azure.microsoft.com/en-gb/blog/what-why-how-azure-automation-desired-state-configuration/

      - Introduction to the Azure Desired State Configuration extension handler: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/extensions-dsc-overview

      - Getting started with Azure Automation DSC: https://docs.microsoft.com/en-us/azure/automation/automation-dsc-getting-started

      - Configure a Linux virtual machine with Desired State Configuration: https://docs.microsoft.com/en-us/azure/automation/automation-quickstart-dsc-configuration

      - Using DSC on Microsoft Azure: https://docs.microsoft.com/en-us/powershell/dsc/azuredsc

**Scale ARM VMs**

   - Scale up and scale down VM sizes; deploy ARM VM Scale Sets (VMSS); configure ARM VMSS auto-scale

      - What are virtual machine scale sets: https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview

      - Vertical autoscale with virtual machine scale sets: https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-vertical-scale-reprovision

      - Tutorial: Automatically scale a virtual machine scale set with Azure PowerShell: https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/tutorial-autoscale-powershell

      - Tutorial: Automatically scale a virtual machine scale set with the Azure CLI 2.0: https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/tutorial-autoscale-cli

**Design and implement ARM VM storage**

   - Configure disk caching; plan for storage capacity; configure shared storage; configure geo-replication; implement ARM VMs with Standard and Premium Storage; implement Azure Disk Encryption for Windows and Linux ARM VMs; implement Azure Disk Storage; implement StorSimple

      - Using Managed Disks in Azure Resource Manager Templates: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/using-managed-disks-template-deployments

      - About disks storage for Azure Windows VMs: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/about-disks-and-vhds

      - Regions and availability for virtual machines in Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/regions-and-availability

      - Azure Managed Disks Overview: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/managed-disks-overview

      - Convert Azure managed disks storage from standard to premium, and vice versa: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/convert-disk-storage

      - Migrating to Azure Premium Storage (Unmanaged Disks): https://docs.microsoft.com/en-us/azure/storage/common/storage-migration-to-premium-storage

      - Azure Disk Encryption for Windows and Linux IaaS VMs: https://docs.microsoft.com/en-us/azure/security/azure-security-disk-encryption

      - How to encrypt virtual disks on a Windows VM: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/encrypt-disks

      - Encrypt an Azure Virtual Machine: https://docs.microsoft.com/en-us/azure/security-center/security-center-disk-encryption

      - Disks storage: https://azure.microsoft.com/en-gb/services/storage/unmanaged-disks/

      - StorSimple: https://azure.microsoft.com/en-gb/services/storsimple/

      - What is StorSimple: https://www.youtube.com/watch?v=zow_hRgRHmM

      -  StorSimple Pricing: https://azure.microsoft.com/en-gb/pricing/details/storsimple/

**Monitor ARM VMs**

  - Configure ARM VM monitoring; configure alerts; configure diagnostic and monitoring storage location; enable Application Insights at runtime; monitor VM workloads by using Azure Application Insights; monitor VMs using Azure Log Analytics and OMS; monitor Linux and Windows VMs by using the Azure Diagnostics Extension; monitor VMs by using Azure Monitor


      -  Use monitoring and diagnostics with a Windows VM and Azure Resource Manager templates: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/extensions-diagnostics-templateMonitor and update a Windows Virtual Machine with Azure PowerShell: https://doc.microsoft.com/en-us/azure/virtual-machines/windows/extensions-diagnostics-template

      - How to monitor virtual machines in Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/monitor

      - Monitoring Performance with Application Insights: https://azure.microsoft.com/en-us/resources/videos/monitoring-performance-with-application-insights/

      - OMS Monitoring solution for Azure Backup using Azure Log analytics: https://azure.microsoft.com/en-gb/blog/oms-monitoring-solution-for-azure-backup-using-azure-log-analytics/

      - Use Linux Diagnostic Extension to monitor metrics and logs: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/diagnostic-extension

**Manage ARM VM availability**

   -  Configure multiple ARM VMs in an availability set for redundancy; configure each application tier into separate availability sets; combine the Load Balancer with availability sets; perform automated VM maintenance

      - How to use availability sets: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-availability-setsManage the availability of Windows virtual machines in Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability

      - Example Azure infrastructure walkthrough for Windows VMs:
https://docs.microsoft.com/en-us/azure/virtual-machines/windows/infrastructure-example

      - Azure Load Balancer overview: https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overviewPlanned maintenance for virtual machines in Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/maintenance-and-updates

      - Handling planned maintenance notifications for Windows virtual machines: https://docs.microsoft.com/en-us/azure/virtual-machines/windows/maintenance-notifications

      - A new Planned Maintenance experience for your virtual machines: https://azure.microsoft.com/en-gb/blog/a-new-planned-maintenance-experience-for-your-virtual-machines/

**Design and Implement DevTest Labs**

   -  Create and manage custom images and formulas; configure a lab to include policies and procedures; configure cost management; secure access to labs; use environments in a lab;

      -  Create a custom image from a VM: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-create-custom-image-from-vm-using-portalComparing custom images and formulas in DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-comparing-vm-base-image-typesCreate a custom image from a VHD file: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-create-template
Configure Azure Marketplace image settings in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-configure-marketplace-images

      -  Manage Azure DevTest Labs formulas: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-manage-formulas

      - Azure DevTest Labs: Introducing formulas to create VMs productively: https://azure.microsoft.com/en-gb/updates/azure-devtest-labs-introducing-formulas-to-create-vms-productively/

      -  Add a VM to a lab in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-add-vm

      - Manage all policies for a lab in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-set-lab-policy

      - Manage basic policies for a lab in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-get-started-with-lab-policies

      - How to set security in DevTest Labs: https://azure.microsoft.com/en-us/resources/videos/how-to-set-security-in-your-devtest-lab/

      - Add owners and users in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-add-devtest-user

      - View the monthly estimated lab cost trend in Azure DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-configure-cost-management

**Design and Implement a Storage and Data Strategy (25-30%)**

   -  Implement Azure Storage blobs and Azure Files
Read data; change data; set metadata on a storage container; store data using block and page blobs; stream data using blobs; access blobs securely; implement async blob copy; configure Content Delivery Network (CDN); design blob hierarchies; configure custom domains; scale blob storage and implement blob tiering; create connections to files from on-premises or cloud-based Windows or Linux machines; shard large datasets; implement blob leasing; implement Storage Events; implement Azure File Sync

      -  Deciding when to use Azure Blobs, Azure Files, or Azure Disks: https://docs.microsoft.com/en-us/azure/storage/common/storage-decide-blobs-files-disksIntroduction to Blob storage: https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction

      - Quickstart: Upload, download, and list blobs using .NET: https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet?tabs=macos

      - Set Container Metadata: https://docs.microsoft.com/en-us/rest/api/storageservices/set-container-metadata

      - Set and retrieve properties and metadata: https://docs.microsoft.com/en-us/azure/storage/blobs/storage-properties-metadata

      - Setting and Retrieving Properties and Metadata for Blob Resources: https://docs.microsoft.com/en-us/rest/api/storageservices/setting-and-retrieving-properties-and-metadata-for-blob-resources

 
**Implement Azure storage tables, queues, and Azure Cosmos DB Table API**
   - Implement CRUD with and without transactions; design and manage partitions; query using OData; scale tables and partitions; add and process queue messages; retrieve a batch of messages; scale queues; choose between Azure Storage Tables and Azure Cosmos DB Table API

      - Getting Started with Azure Cosmos DB, Part 1 – CRUD: https://dontpaniclabs.com/blog/post/2017/08/17/getting-started-azure-cosmos-db-part-1-crud/

      - How to create CRUD application using Azure Cosmos DB for MongoDB applications: http://www.siddharthpandey.net/how-to-create-crud-application-using-azure-cosmos-db-for-mongodb-applications/

      - ASP.NET MVC Tutorial: Web application development with Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/sql-api-dotnet-application

      - Simple CRUD Operations In Azure Cosmos DB: https://www.c-sharpcorner.com/article/simple-crud-operations-in-cosmos-db/

      - Partition and scale in Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/partition-data

      - Partitioning in Azure Cosmos DB using the SQL API: https://docs.microsoft.com/en-us/azure/cosmos-db/sql-api-partition-data

      - Azure Cosmos DB: Partitioned collections for higher storage and throughput: https://azure.microsoft.com/en-gb/updates/documentdb-partitioned-collections-for-higher-storage-and-throughput/

      - Tutorial: Query Azure Cosmos DB by using the Table API: https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-query-table

      - SQL queries for Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/sql-api-sql-query

 
**Manage access and monitor storage**
   -  Generate shared access signatures, including client renewal and data validation; create stored access policies; regenerate storage account keys; configure and use Cross-Origin Resource Sharing (CORS); set retention policies and logging levels; analyse logs; monitor Cosmos DB storage

      -  Using shared access signatures (SAS): https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1

      - Delegating Access with a Shared Access Signature: https://docs.microsoft.com/en-us/rest/api/storageservices/delegating-access-with-a-shared-access-signature

      - Generate SAS token: https://docs.microsoft.com/en-us/rest/api/eventhub/generate-sas-token

      - Cross-Origin Resource Sharing (CORS) Support for the Azure Storage Services: https://docs.microsoft.com/en-us/rest/api/storageservices/cross-origin-resource-sharing--cors--support-for-the-azure-storage-services

      -  Host a RESTful API with CORS in Azure App Service: https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-rest-api

**Implement Azure SQL Databases**
   - Choose the appropriate database tier and performance level; configure and perform point in time recovery; enable geo-replication; import and export data and schema; scale Azure SQL databases; manage elastic pools, including DTUs and eDTUs; manage limits and resource governor; implement Azure SQL Data Sync; implement graph database functionality in Azure SQL; design multi-tenant applications; secure and encrypt data; manage data integrity; enable metrics and diagnostics logs for monitoring; use adaptive query processing to improve query performance; implement sharding and elastic tools; implement SQL Server Stretch Database
      - Azure SQL Database Documentation: https://docs.microsoft.com/en-us/azure/sql-database/
      - Choose a cloud SQL Server option: Azure SQL (PaaS) Database or SQL Server on Azure VMs (IaaS): https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas
      - Azure SQL Database Point in Time Restore: https://azure.microsoft.com/en-gb/blog/azure-sql-database-point-in-time-restore/
      - Recover an Azure SQL database using automated database backups: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-recovery-using-backups
      - Builder Day: Doing a Point-in-Time Restore in Azure SQL DB: https://www.brentozar.com/archive/2017/06/builder-day-point-time-restore-azure-sql-db/
      - Overview: Failover groups and active geo-replication: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-geo-replication-overview
      - Configure active geo-replication for Azure SQL Database in the Azure portal and initiate failover: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-geo-replication-portal
      - Designing highly available services using Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-designing-cloud-solutions-for-disaster-recovery
      - Import and export data from SQL Server and Azure SQL Database: https://docs.microsoft.com/en-us/sql/relational-databases/import-export/overview-import-export
      - Export an Azure SQL database to a BACPAC file: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-export
      - Import a BACPAC file to a new Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-import
      - SQL Server database migration to Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-cloud-migrate
      - Scaling out with Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-introduction
      - Azure SQL Database dynamically scale-up or scale-down: https://azure.microsoft.com/en-gb/resources/videos/azure-sql-database-dynamically-scale-up-or-scale-down/
      - Azure SQL Database resource limits: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-resource-limits
      - Graph processing with SQL Server and Azure SQL Database: https://docs.microsoft.com/en-us/sql/relational-databases/graphs/sql-graph-overview
      - How to configure a new multi-tenant application: https://docs.microsoft.com/en-us/azure/active-directory/application-dev-setup-multi-tenant-app
      - New multi-tenant patterns for building SaaS applications on SQL Database: https://azure.microsoft.com/en-gb/blog/new-multi-tenant-patterns-for-building-saas-applications-on-sql-database/
      -  Securing your SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-security-overview
      - Transparent data encryption for SQL Database and Data Warehouse: https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/transparent-data-encryption-azure-sql
      - Secure your Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-security-tutorial
      - Data Integrity in Azure SQL Database: https://azure.microsoft.com/en-gb/blog/data-integrity-in-azure-sql-database/
      - Azure SQL Database Data Integrity Checks: https://blobeater.blog/2017/10/04/azure-sql-database-data-integrity-checks/
      - Data Integrity in Azure SQL Database: https://odetocloud.com/2017/10/03/data-integrity-azure-sql-database/
      - Azure SQL Database metrics and diagnostics logging: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-metrics-diag-logging
      - Collect and consume log data from your Azure resources: https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview-of-diagnostic-logs
      - Monitoring database performance in Azure SQL Database: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-monitor
      - Adaptive query processing in SQL databases: https://docs.microsoft.com/en-us/sql/relational-databases/performance/adaptive-query-processing
      - Enhancing query performance with Adaptive Query Processing in SQL Server 2017: https://blogs.technet.microsoft.com/dataplatforminsider/2017/09/28/enhancing-query-performance-with-adaptive-query-processing-in-sql-server-2017/
      - Adaptive query processing in SQL databases: https://docs.microsoft.com/en-us/sql/relational-databases/performance/adaptive-query-processing
      - Get started with Elastic Database Tools: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-get-started
      - Adding a shard using Elastic Database tools: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-add-a-shard
      - SQL Server Stretch Database Documentation: https://docs.microsoft.com/en-us/azure/sql-server-stretch-database/
      - Stretch Database: https://docs.microsoft.com/en-us/sql/sql-server/stretch-database/stretch-database
      
      
**Implement Azure Cosmos DB**
   -  Choose a Cosmos DB API surface; create Cosmo DB API databases and collections; query documents; run Cosmos DB queries; create Graph API databases; execute GraphDB queries; implement MongoDB database; manage scaling of Cosmos DB, including managing partitioning, consistency, and RU/m; manage multiple regions; implement stored procedures; implement JavaScript within Cosmos DB; access Cosmos DB from REST interface; manage Cosmos DB security
      - TODO

**Implement Redis caching**
   -  Choose a cache tier; implement data persistence; implement security and network isolation; tune cluster performance; integrate Redis caching with ASP.NET session and cache providers; implement Redis data types and operations
      - TODO

**Implement Azure Search**
   -  Create a service index; add data; search an index; handle search results
      - TODO

**Manage Identity, Application, and Network Services (10-15%)**

   -  Integrate an app with Azure Active Directory (AAD)
Develop apps that use WS-federation, OAuth, and SAML-P endpoints; query the directory by using Microsoft Graph API, MFA and MFA API
      - TODO

   -  Design and implement a messaging strategy
Develop and scale messaging solutions using service bus queues, topics, relays, event hubs, Event Grid, and notification hubs; monitor service bus queues, topics, relays, event hubs and notification hubs; determine when to use Event Hubs, Service Bus, IoT Hub, Stream Analytics, and Notification Hubs; implement Azure Event Grid
      - TODO

   -  Develop apps that use AAD B2C and AAD B2B
Design and implement .NET MVC, Web API, and Windows Desktop apps that leverage social identity provider authentication, including Microsoft account, Facebook, Google+, Amazon, and LinkedIn; leverage Azure AD B2B to design and implement applications that support partner-managed identities, enforce multi-factor authentication
      - TODO
      
      
   -  Manage secrets using Azure Key Vault
Configure Azure Key Vault; manage access, including tenants; implement HSM protected keys; manage service limits; implement logging; implement key rotation; store and retrieve app secrets including connection strings, passwords, and cryptographic keys; implement Azure Managed Service Identity
      - TODO

**Design and Implement Azure Compute, Web, and Mobile Services (35-40%)**
   - Design Azure App Service Web Apps
Define and manage App Service plans; configure Web Apps settings, certificates, and custom domains; manage Web Apps by using the API, Azure PowerShell, Azure Cloud Shell, and Xplat-CLI; implement diagnostics, monitoring, and analytics; design and configure Web Apps for scale and resilience; use Azure Managed Service Identity to access other Azure AD-protected resources including Azure Key Vault
      - TODO

   -  Implement Azure Functions and WebJobs
Create Azure Functions; implement a webhook Function; create an event processing Function; implement an Azure-connected Function; design and implement a custom binding; debug a Function; integrate a Function with storage; implement and configure proxies; integrate with App Service plan; implement Azure Event Grid-based serverless applications
      - TODO


   -  Implement API Management
Create managed APIs; configure API Management policies; protect APIs with rate limits; add caching to improve performance; monitor APIs; customise the Developer portal; add authentication and authorisation to applications by using API Management; configure API versions by using API Management; implement git-based configuration using API Management
      - TODO
      
   -  Design Azure App Service API Apps
Create and deploy API Apps; automate API discovery by using Swagger and Swashbuckle; use Swagger API metadata to generate client code for an API app; monitor API Apps
      - TODO


   -  Develop Azure Logic Apps
Create a Logic App connecting SaaS services; create a Logic App with B2B capabilities; create a Logic App with XML capabilities; trigger a Logic App from another app; create custom and long-running actions; monitor Logic Apps; integrate a logic app with a function; access on-premises data; implement Logic Apps with Event Grid
      - TODO
      
   -  Develop Azure App Service Mobile Apps
Create a Mobile App; add offline sync to a Mobile App; add authentication to a Mobile App; add push notifications to a Mobile App
      - TODO

   - Design and implement Azure Service Fabric Applications
Create a Service Fabric application; build an Actors-based service; add a web front-end to a Service Fabric application; monitor and diagnose services; migrate apps from cloud services; create, secure, upgrade, and scale Service Fabric Cluster in Azure; scale a Service Fabric app; deploy an application to a Container
      - TODO
      
 -  Design and implement Third Party Platform as a Service (PaaS)
Design and implement Third Party Platform as a Service (PaaS)": Implement Cloud Foundry; implement OpenShift; provision applications by using Azure Quickstart Templates; build applications that leverage Azure Marketplace solutions and services; implement solutions that use Azure Bot Service; create Azure Managed Applications; implement Docker Swarm applications; implement Kubernetes applications
      - TODO

   - Design and Implement DevOps
Instrument an application with telemetry; discover application performance issues by using Application Insights; deploy Visual Studio Team Services with Continuous integration (CI) and Continuous development (CD); deploy CI/CD with third party platform tools (Jenkins, GitHub, Chef, Puppet; TeamCity); implement mobile DevOps by using HockeyApp; perform root cause analysis using Azure Time Series Insights
      - TODO




