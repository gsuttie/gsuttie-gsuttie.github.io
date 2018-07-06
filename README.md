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

      -  Create a custom image from a VM: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-create-custom-image-from-vm-using-portal Comparing custom images and formulas in DevTest Labs: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-comparing-vm-base-image-types Create a custom image from a VHD file: https://docs.microsoft.com/en-us/azure/devtest-lab/devtest-lab-create-template
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
   
      - Azure Cosmos DB Documentation: https://docs.microsoft.com/en-us/azure/cosmos-db/
      - Azure Cosmos DB: REST API Reference: https://docs.microsoft.com/en-gb/rest/api/cosmos-db/index
      - Querying Azure Cosmos DB resources using the REST API: https://docs.microsoft.com/en-gb/rest/api/cosmos-db/querying-cosmosdb-resources-using-the-rest-api
      - Getting started with Azure Cosmos DB: Graph API: https://azure.microsoft.com/en-gb/resources/samples/azure-cosmos-db-graph-dotnet-getting-started/
      - Introduction to Azure Cosmos DB: Graph API: https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction
      - Azure Cosmos DB: Develop with the Graph API in .NET: https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-develop-graph-dotnet
      - Testing the Cosmos DB graph database: https://bricaud.github.io/personal-blog/azure-and-cosmos-db-graph/
      - Introduction to Azure Cosmos DB: MongoDB API: https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-introduction
      - Build an Azure Cosmos DB: API for MongoDB app using Node.js: https://docs.microsoft.com/en-us/azure/cosmos-db/mongodb-samples
      - Connect a MongoDB application to Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/connect-mongodb-account
      - Partition and scale in Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/partition-data
      - Performance and scale testing with Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/performance-testing
      - Partitioning in Azure Cosmos DB using the SQL API: https://docs.microsoft.com/en-us/azure/cosmos-db/sql-api-partition-data
      - How to distribute data globally with Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/distribute-data-globally
      - Automatic regional failover for business continuity in Azure Cosmos DB: https://docs.microsoft.com/en-us/azure/cosmos-db/regional-failover
      - How to setup Azure Cosmos DB global distribution using the SQL API: https://docs.microsoft.com/en-us/azure/cosmos-db/tutorial-global-distribution-sql-api
      - Azure Cosmos DB server-side programming: Stored procedures, database triggers, and UDFs: https://docs.microsoft.com/en-us/azure/cosmos-db/programming
      - Stored Procedures In Azure Cosmos DB - https://www.c-sharpcorner.com/article/stored-procedures-in-azure-cosmos-db/
      - Stored Procedures: https://docs.microsoft.com/en-gb/rest/api/cosmos-db/stored-procedures
      - SQL Azure Tutorials Blog: http://sqlazuretutorials.com/wordpress/sql-stored-procedures-in-windows-azure-sql-database/
      - Azure Cosmos DB database security: https://docs.microsoft.com/en-us/azure/cosmos-db/database-security
      - Securing access to Azure Cosmos DB data: https://docs.microsoft.com/en-us/azure/cosmos-db/secure-access-to-data
      - Azure Cosmos DB firewall support: https://docs.microsoft.com/en-us/azure/cosmos-db/firewall-support
      


**Implement Redis caching**
   -  Choose a cache tier; implement data persistence; implement security and network isolation; tune cluster performance; integrate Redis caching with ASP.NET session and cache providers; implement Redis data types and operations

      - Redis Cache Documentation: https://docs.microsoft.com/en-us/azure/redis-cache/
      - How to Use Azure Redis Cache: https://docs.microsoft.com/en-us/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache
      - Redis Cache: https://azure.microsoft.com/en-gb/services/cache/
      - Introduction to the Azure Redis Cache Premium tier: https://docs.microsoft.com/en-us/azure/redis-cache/cache-premium-tier-intro
      - How to configure data persistence for a Premium Azure Redis Cache: https://docs.microsoft.com/en-us/azure/redis-cache/cache-how-to-premium-persistence
      - Import and Export data in Azure Redis Cache: https://docs.microsoft.com/en-us/azure/redis-cache/cache-how-to-import-export-data
      - Azure Redis Security Caching: https://azure.microsoft.com/en-gb/resources/videos/azure-redis-security-cacheing/
      - Increase performance through Redis Cluster in Azure Redis Cache: https://azure.microsoft.com/en-gb/resources/videos/increase-performance-through-redis-cluster-in-azure-redis-cache/
      - ASP.NET Session State Provider for Azure Redis Cache: https://docs.microsoft.com/en-us/azure/redis-cache/cache-aspnet-session-state-provider
      - Azure Redis Cache samples: https://docs.microsoft.com/en-us/azure/redis-cache/cache-redis-samples

**Implement Azure Search**
   -  Create a service index; add data; search an index; handle search results
      - Create Index (Azure Search Service REST API): https://docs.microsoft.com/en-us/rest/api/searchservice/create-index
      - Create an Azure Search service in the portal: https://docs.microsoft.com/en-us/azure/search/search-create-service-portal
      - Create an Azure Search index using the .NET SDK - https://docs.microsoft.com/en-us/azure/search/search-create-index-dotnet
      - Create, query, and filter an Azure Search index in the portal: https://docs.microsoft.com/en-us/azure/search/search-get-started-portal
      - Indexers in Azure Search: https://docs.microsoft.com/en-us/azure/search/search-indexer-overview
      - How to page search results in Azure Search: https://docs.microsoft.com/en-us/azure/search/search-pagination-page-layout
      - Queries in Azure Search: https://docs.microsoft.com/en-us/azure/search/search-query-overview
      - Service limits in Azure Search: https://docs.microsoft.com/en-us/azure/search/search-limits-quotas-capacity
      - Add scoring profiles to a search index (Azure Search Service REST API) - https://docs.microsoft.com/en-us/rest/api/searchservice/add-scoring-profiles-to-a-search-index

**Manage Identity, Application, and Network Services (10-15%)**

   -  Integrate an app with Azure Active Directory (AAD)
Develop apps that use WS-federation, OAuth, and SAML-P endpoints; query the directory by using Microsoft Graph API, MFA and MFA API
      - Integrating applications with Azure Active Directory: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-integrating-applications
      - Integrating Azure Active Directory with applications getting started guide: https://docs.microsoft.com/en-us/azure/active-directory/active-directory-integrating-applications-getting-started
      - Azure Active Directory for developers: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-developers-guide
      - Configure multi-factor authentication for SQL Server Management Studio and Azure AD: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-ssms-mfa-authentication-configure
      - Multi-Factor Authentication for Azure AD: https://azure.microsoft.com/en-gb/resources/videos/multi-factor-authentication-for-azure-ad/
      - Authentication Scenarios for Azure AD: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-scenarios
      - Azure Active Directory Authentication Protocols: https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-authentication-protocols

   -  Design and implement a messaging strategy
Develop and scale messaging solutions using service bus queues, topics, relays, event hubs, Event Grid, and notification hubs; monitor service bus queues, topics, relays, event hubs and notification hubs; determine when to use Event Hubs, Service Bus, IoT Hub, Stream Analytics, and Notification Hubs; implement Azure Event Grid
      - Service Bus queues, topics, and subscriptions: https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-queues-topics-subscriptions
      - Azure Service Bus: https://docs.microsoft.com/en-us/azure/service-bus-messaging/service-bus-fundamentals-hybrid-solutions
      - Events, Data Points, and Messages - Choosing the right Azure messaging service for your data: https://azure.microsoft.com/en-gb/blog/events-data-points-and-messages-choosing-the-right-azure-messaging-service-for-your-data/
      - An introduction to Azure Event Grid: https://docs.microsoft.com/en-us/azure/event-grid/overview
      - Azure Event Grid Documentation: https://docs.microsoft.com/en-us/azure/event-grid/
      - A Tour of Azure Messaging Services (Queues, Event Grid, IoT Hub, and More): https://buildazure.com/2017/09/07/a-tour-of-azure-messaging-services-queues-event-grid-iot-hub-and-more/
      

   -  Develop apps that use AAD B2C and AAD B2B
Design and implement .NET MVC, Web API, and Windows Desktop apps that leverage social identity provider authentication, including Microsoft account, Facebook, Google+, Amazon, and LinkedIn; leverage Azure AD B2B to design and implement applications that support partner-managed identities, enforce multi-factor authentication
      
      -  Compare B2B collaboration and B2C in Azure Active Directory: https://docs.microsoft.com/en-us/azure/active-directory/active-directory-b2b-compare-b2c
      - Azure Active Directory B2C: Sign in by using Azure AD accounts: https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-setup-aad-custom
      - Azure AD B2C: Frequently asked questions (FAQ): https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-faqs
      - Keep credentials out of code: Introducing Azure AD Managed Service Identity: https://azure.microsoft.com/en-gb/blog/keep-credentials-out-of-code-introducing-azure-ad-managed-service-identity/
      - Configure Azure Multi-Factor Authentication settings: https://docs.microsoft.com/en-us/azure/multi-factor-authentication/multi-factor-authentication-whats-next
      - How to require MFA in Azure AD Privileged Identity Management: https://docs.microsoft.com/en-us/azure/active-directory/active-directory-privileged-identity-management-how-to-require-mfa
      - What is Azure Multi-Factor Authentication?: https://docs.microsoft.com/en-us/azure/multi-factor-authentication/multi-factor-authentication
      
   -  Manage secrets using Azure Key Vault
Configure Azure Key Vault; manage access, including tenants; implement HSM protected keys; manage service limits; implement logging; implement key rotation; store and retrieve app secrets including connection strings, passwords, and cryptographic keys; implement Azure Managed Service Identity
      - Key Vault Documentation: https://docs.microsoft.com/en-us/azure/key-vault/
      - Get started with Azure Key Vault: https://docs.microsoft.com/en-us/azure/key-vault/key-vault-get-started
      - Azure Key Vault Developer's Guide: https://docs.microsoft.com/en-us/azure/key-vault/key-vault-developers-guide
      - Use Azure Key Vault from a Web Application: https://docs.microsoft.com/en-us/azure/key-vault/key-vault-use-from-web-application
      - Managed Service Identity (MSI) for Azure resources: https://docs.microsoft.com/en-us/azure/active-directory/managed-service-identity/overview
      - Use Key Vault from App Service with Managed Service Identity: https://azure.microsoft.com/en-gb/resources/samples/app-service-msi-keyvault-dotnet/
      - Use a Windows VM Managed Service Identity (MSI) to access Azure Key Vault - https://docs.microsoft.com/en-us/azure/active-directory/managed-service-identity/tutorial-windows-vm-access-nonaad

**Design and Implement Azure Compute, Web, and Mobile Services (35-40%)**
   - Design Azure App Service Web Apps
Define and manage App Service plans; configure Web Apps settings, certificates, and custom domains; manage Web Apps by using the API, Azure PowerShell, Azure Cloud Shell, and Xplat-CLI; implement diagnostics, monitoring, and analytics; design and configure Web Apps for scale and resilience; use Azure Managed Service Identity to access other Azure AD-protected resources including Azure Key Vault
      - Manage an App Service plan in Azure: https://docs.microsoft.com/en-us/azure/app-service/app-service-plan-manage
      - Azure App Service plan overview: https://docs.microsoft.com/en-us/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview
      - Designing resilient applications for Azure: https://docs.microsoft.com/en-us/azure/architecture/resiliency/
      - Scale up an app in Azure: https://docs.microsoft.com/en-us/azure/app-service/web-sites-scale
      - How to use Azure Managed Service Identity (public preview) in App Service and Azure Functions - https://docs.microsoft.com/en-us/azure/app-service/app-service-managed-service-identity

   -  Implement Azure Functions and WebJobs
Create Azure Functions; implement a webhook Function; create an event processing Function; implement an Azure-connected Function; design and implement a custom binding; debug a Function; integrate a Function with storage; implement and configure proxies; integrate with App Service plan; implement Azure Event Grid-based serverless applications

      - Azure Functions Documentation - https://docs.microsoft.com/en-us/azure/azure-functions/
      - Azure Functions Tools for Visual Studio: https://docs.microsoft.com/en-us/azure/azure-functions/functions-develop-vs
      - Create a function in Azure that is triggered by a timer - https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-scheduled-function
      - Azure Functions HTTP and webhook bindings: https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook
      - Create a function triggered by a generic webhook: https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-generic-webhook-triggered-function
      - Create a Web Hook or API Azure Function: https://azure.microsoft.com/en-gb/resources/videos/create-a-web-hook-or-api-azure-function/
      - Starting an Azure Automation runbook with a webhook: https://docs.microsoft.com/en-us/azure/automation/automation-webhooks
      - Introducing Azure Event Grid – an event service for modern applications: https://azure.microsoft.com/en-gb/blog/introducing-azure-event-grid-an-event-service-for-modern-applications/
  

   -  Implement API Management
Create managed APIs; configure API Management policies; protect APIs with rate limits; add caching to improve performance; monitor APIs; customise the Developer portal; add authentication and authorisation to applications by using API Management; configure API versions by using API Management; implement git-based configuration using API Management

      - API Management documentation: https://docs.microsoft.com/en-us/azure/api-management/
      - What is API Management?: https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts
      - Import and publish your first API: https://docs.microsoft.com/en-us/azure/api-management/import-and-publish
      - API Management policies: https://docs.microsoft.com/en-us/azure/api-management/api-management-policies
      - Policies in Azure API Management: https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-policies
      - How to set or edit Azure API Management policies: https://docs.microsoft.com/en-us/azure/api-management/set-edit-policies
      - Advanced request throttling with Azure API Management: https://docs.microsoft.com/en-us/azure/api-management/api-management-sample-flexible-throttling
      - API Management: Quota versus Rate Limits: https://blogs.msdn.microsoft.com/sanket/2017/11/02/api-management-quota-versus-rate-limits/
      - How to customize the Azure API Management developer portal using templates: https://docs.microsoft.com/en-us/azure/api-management/api-management-developer-portal-templates
      - Customize developer portal pages using Azure API Management templates: https://azure.microsoft.com/en-gb/blog/customize-your-developer-portal-pages-with-azure-api-management-templates/
      - API Versioning with Azure API Management - https://blogs.msdn.microsoft.com/apimanagement/2017/09/13/api-versioning-with-azure-api-management/
      - Versions & Revisions - https://blogs.msdn.microsoft.com/apimanagement/2017/09/14/versions-revisions/
      
      
   -  Design Azure App Service API Apps
Create and deploy API Apps; automate API discovery by using Swagger and Swashbuckle; use Swagger API metadata to generate client code for an API app; monitor API Apps
      - Host a RESTful API with CORS in Azure App Service: https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-rest-api
      - Working With Azure API Apps: https://www.c-sharpcorner.com/article/working-with-azure-api-apps/
      - Inside Web APIs with Swagger and API Managment with Brady Gaster: https://azure.microsoft.com/en-gb/resources/videos/inside-web-apis-with-swagger-and-api-managment-with-brady-gaster/
      - Announcing Azure Functions OpenAPI (Swagger) support preview: https://blogs.msdn.microsoft.com/appserviceteam/2017/03/30/announcing-functions-swagger-support/
      - Generating Swagger description metadata from your ASP.NET Core Web APIs with Swashbuckle - https://blogs.msdn.microsoft.com/cesardelatorre/2016/12/05/generating-swagger-description-metadata-from-your-asp-net-core-web-apis-with-swashbuckle/
      - How to: Monitor Apps in Azure App Service: https://docs.microsoft.com/en-us/azure/app-service/web-sites-monitor
      - Azure Monitoring REST API walkthrough: https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-rest-api-walkthrough
      - Monitoring Azure applications and resources: https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview

   -  Develop Azure Logic Apps
Create a Logic App connecting SaaS services; create a Logic App with B2B capabilities; create a Logic App with XML capabilities; trigger a Logic App from another app; create custom and long-running actions; monitor Logic Apps; integrate a logic app with a function; access on-premises data; implement Logic Apps with Event Grid
      - Azure Logic Apps Documentation: https://docs.microsoft.com/en-us/azure/logic-apps/
      - Common scenarios, examples, tutorials, and walkthroughs for Azure Logic Apps: https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-examples-and-scenarios
      - Introducing Azure Logic Apps: https://azure.microsoft.com/en-gb/resources/videos/introducing-azure-logic-apps/
      
   -  Develop Azure App Service Mobile Apps
Create a Mobile App; add offline sync to a Mobile App; add authentication to a Mobile App; add push notifications to a Mobile App
      - About Mobile Apps in Azure App Service: https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-value-prop
      - Mobile Apps Documentation: https://docs.microsoft.com/en-us/azure/app-service-mobile/
      - Easy Push Notifications with Azure App Service: https://azure.microsoft.com/en-gb/resources/videos/easy-push-notifications-with-azure-app-service/

   - Design and implement Azure Service Fabric Applications
Create a Service Fabric application; build an Actors-based service; add a web front-end to a Service Fabric application; monitor and diagnose services; migrate apps from cloud services; create, secure, upgrade, and scale Service Fabric Cluster in Azure; scale a Service Fabric app; deploy an application to a Container
      - Overview of Azure Service Fabric: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-overview
      - So you want to learn about Service Fabric?: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-content-roadmap
      - Introduction to Service Fabric Reliable Actors: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-introduction
      - Getting started with Reliable Actors: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-reliable-actors-get-started
      - Azure Service Fabric and the Actor Model with Mark Fussell: https://azure.microsoft.com/en-gb/resources/videos/azure-service-fabric-and-the-actor-model-with-mark-fussell/
      - Create a Service Fabric cluster in Azure using the Azure portal: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-cluster-creation-via-portal
      - Create a standalone cluster running on Windows Server: https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-cluster-creation-for-windows-server
      
      
 -  Design and implement Third Party Platform as a Service (PaaS)
Design and implement Third Party Platform as a Service (PaaS)": Implement Cloud Foundry; implement OpenShift; provision applications by using Azure Quickstart Templates; build applications that leverage Azure Marketplace solutions and services; implement solutions that use Azure Bot Service; create Azure Managed Applications; implement Docker Swarm applications; implement Kubernetes applications

      - Cloud Foundry on Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/cloudfoundry-get-started
      - Cloud Foundry on Azure(2): https://docs.microsoft.com/en-us/azure/cloudfoundry/
      - Deploy your first app to Cloud Foundry on Microsoft Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/cloudfoundry-deploy-your-first-app
      - OpenShift on Azure: https://docs.microsoft.com/en-us/azure/openshift/
      - Deploy OpenShift Container Platform in Azure: https://docs.microsoft.com/en-us/azure/virtual-machines/linux/openshift-container-platform
      - Azure Quickstart Templates: https://azure.microsoft.com/en-gb/resources/templates/
      - Azure Marketplace and AppSource publisher guide: https://docs.microsoft.com/en-us/azure/marketplace/marketplace-publishers-guide
      - Managed Applications are now Generally Available in the Azure Marketplace: https://azure.microsoft.com/en-us/blog/managed-applications-are-now-generally-available-in-the-azure-marketplace/
      - Announcing Terraform availability in the Azure Marketplace: https://azure.microsoft.com/en-gb/blog/announcing-terraform-availability-in-the-azure-marketplace/
      - What is Azure Marketplace?: https://azuremarketplace.microsoft.com/en-us/about
      - Azure Managed Applications: https://azure.microsoft.com/en-gb/blog/azure-managed-applications/
      - Azure Bot Service: https://azure.microsoft.com/en-gb/services/bot-service/
      - About Bot Service: https://docs.microsoft.com/en-us/azure/bot-service/bot-service-overview-introduction
      - Create a new swarm on Microsoft Azure in Docker Cloud: https://docs.docker.com/docker-cloud/cloud-swarm/create-cloud-swarm-azure/
      - Azure Container Service with DC/OS and Swarm Documentation: https://docs.microsoft.com/en-us/azure/container-service/dcos-swarm/
      - Deploy Docker Swarm cluster: https://docs.microsoft.com/en-us/azure/container-service/dcos-swarm/container-service-swarm-walkthrough
      - Container management with Docker Swarm: https://docs.microsoft.com/en-us/azure/container-service/dcos-swarm/container-service-docker-swarm
      - Introduction to Azure Container Service (AKS) preview: https://docs.microsoft.com/en-us/azure/aks/intro-kubernetes
      - Kubernetes on Azure: https://azure.microsoft.com/en-gb/services/container-service/kubernetes/
      - Deploy using Kubernetes to Azure Container Service: https://docs.microsoft.com/en-us/vsts/build-release/apps/cd/azure/deploy-container-kubernetes?view=vsts
      

   - Design and Implement DevOps
Instrument an application with telemetry; discover application performance issues by using Application Insights; deploy Visual Studio Team Services with Continuous integration (CI) and Continuous development (CD); deploy CI/CD with third party platform tools (Jenkins, GitHub, Chef, Puppet; TeamCity); implement mobile DevOps by using HockeyApp; perform root cause analysis using Azure Time Series Insights

      - What is Application Insights?: https://docs.microsoft.com/en-us/azure/application-insights/app-insights-overview
      - Telemetry – Application Instrumentation CSF Blog: https://azure.microsoft.com/en-us/blog/telemetry-application-instrumentation-csf-blog/
      - Separating telemetry from Development, Test, and Production: https://docs.microsoft.com/en-us/azure/application-insights/app-insights-separate-resources
      - Continuous Integration and Delivery: https://www.visualstudio.com/team-services/continuous-integration/
      - CI/CD for Azure Web Apps: https://azure.microsoft.com/en-gb/solutions/architecture/vsts-continuous-integration-and-continuous-deployment-for-azure-web-apps/
      - CI/CD for Containers: https://azure.microsoft.com/en-gb/solutions/architecture/cicd-for-containers/
      - CI/CD for Azure VMs: https://azure.microsoft.com/en-gb/solutions/architecture/cicd-for-azure-vms/
      - Devops for Mobile using HockeyApp: https://azure.microsoft.com/en-gb/services/hockeyapp/
      - Mobile DevOps? DevOps? What’s the Difference?: https://hockeyapp.net/best-practices/mobile-devops-devops-whats-the-difference.html
      - Root cause analysis and time exploration updates to Azure Time Series Insights: https://azure.microsoft.com/en-gb/blog/root-cause-analysis-and-time-exploration-updates-to-azure-time-series-insights/
      - Time Series Insights: https://azure.microsoft.com/en-gb/services/time-series-insights/
      
      
  This has been created so that you can make edits nd keep this information as up to date as possible.
      




