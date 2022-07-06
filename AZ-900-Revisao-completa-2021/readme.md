## **Why use Cloud**

## **Beneficies of Cloud**

Principals beneficies is:
- Less operational cost
- Execute infrastructure more easy
- High availability and high escalability 

### High availability
- Basically is maintain you application available 99,999999...% of time online
- For provide High availability you can reply you application in others Zones, see the imabe below, or reply or applications machines, and apply load balance for direct the requests. 
- ![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfJ7aNbIK2G0sWwkDxlvG0sr780GCslSCRnGNH2N_tO8Z2fo8JqiXYy3GS7W9dxJJur-A&usqp=CAU)
- About this topic you can have failure in your application, because an external resource, for example, if you a site and this site consume a database, case you database is down you application need continue available but presenting a error message to consume the database 

<br>

## Services availble on Azure

#### Computer
**Azure Virtual Machines**
- Windows or Linux virtual machines (VMs) hosted in Azure.

**Azure Virtual Machine Scale Sets**
- Scaling for Windows or Linux VMs hosted in Azure.

**Azure Kubernetes Service**
- Cluster management for VMs that run containerized services.

**Azure Service Fabric**
- Distributed systems platform that runs in Azure or on-premises.

**Azure Batch**
- Managed service for parallel and high-performance computing applications.

**Azure Container Instances**
- Containerized apps run on Azure without provisioning servers or VMs.

**Azure Functions**
- An event-driven, serverless compute service.

<br>

#### Networking

**Azure Virtual Network**
- Connects VMs to incoming virtual private network (VPN) connections.

**Azure Load Balancer**
- Balances inbound and outbound connections to applications or service endpoints.

**Azure Application Gateway**
- Optimizes app server farm delivery while increasing application security.

**Azure VPN Gateway**
- Accesses Azure Virtual Networks through high-performance VPN gateways.

**Azure DNS**
- Provides ultra-fast DNS responses and ultra-high domain availability.

**Azure Content Delivery Network**
- Delivers high-bandwidth content to customers globally.

**Azure DDoS Protection**
- Protects Azure-hosted applications from distributed denial of service (DDOS) attacks.

**Azure Traffic Manager**
- Distributes network traffic across Azure regions worldwide.

**Azure ExpressRoute**
- Connects to Azure over high-bandwidth dedicated secure connections.

**Azure Network Watcher**
- Monitors and diagnoses network issues by using scenario-based analysis.

**Azure Firewall**
- Implements high-security, high-availability firewall with unlimited scalability.

**Azure Virtual WAN**
- Creates a unified wide area network (WAN) that connects local and remote sites.

<br>

#### Storage

**Azure Blob storage**
- Storage service for very large objects, such as video files or bitmaps.

**Azure File storage**
- File shares that can be accessed and managed like a file server.

**Azure Queue storage**
- A data store for queuing and reliably delivering messages between applications.

**Azure Table storage**
- Table storage is a service that stores non-relational structured data (also known as structured NoSQL data) in the cloud, providing a key/attribute store with a schemaless design.


These services all share several common characteristics:

- Durable and highly available with redundancy and replication.
- Secure through automatic encryption and role-based access control.
- Scalable with virtually unlimited storage.
- Managed, handling maintenance and any critical problems for you.
- Accessible from anywhere in the world over HTTP or HTTPS.


<br>

#### Databases

**Azure Cosmos DB**
- Globally distributed database that supports NoSQL options.

**Azure SQL Database**
- Fully managed relational database with auto-scale, integral intelligence, and robust security.

**Azure Database for MySQL**
- Fully managed and scalable MySQL relational database with high availability and security.

**Azure Database for PostgreSQL**
- Fully managed and scalable PostgreSQL relational database with high availability and security.

**SQL Server on Azure Virtual Machines**
- Service that hosts enterprise SQL Server apps in the cloud.

**Azure Synapse Analytics**
- Fully managed data warehouse with integral security at every level of scale at no extra cost.

**Azure Database Migration Service**
- Service that migrates databases to the cloud with no application code changes.

**Azure Cache for Redis**
- Fully managed service caches frequently used and static data to reduce data and application latency.

**Azure Database for MariaDB**
- Fully managed and scalable MariaDB relational database with high availability and security.

<br>

#### Web

**Azure App Service**
-Quickly create powerful cloud web-based apps.

**Azure Notification Hubs**
- Send push notifications to any platform from any back end.

**Azure API Management**
- Publish APIs to developers, partners, and employees securely and at scale.

**Azure Cognitive Search**
- Deploy this fully managed search as a service.

**Web Apps feature of Azure App Service**
- Create and deploy mission-critical web apps at scale.

**Azure SignalR Service**
- Add real-time web functionalities easily.

<br>

#### IoT

**IoT Central**
- Fully managed global IoT software as a service (SaaS) solution that makes it easy to connect, monitor, and manage IoT assets at scale.
- Provide any templates to connect net devices on plataform.
- Is a Saas service.


**Azure IoT Hub**
- Messaging hub that provides secure communications between and monitoring of millions of IoT devices.
- Can router millions of messagens in any types for another services on Azure

**IoT Edge**
- Fully managed service that allows data analysis models to be pushed directly onto IoT devices, which allows them to react quickly to state changes without needing to consult cloud-based AI models.

<br>

#### Big data

**Azure Synapse Analytics**
- Run analytics at a massive scale by using a cloud-based enterprise data warehouse that takes advantage of massively parallel processing to run complex queries quickly across petabytes of data.

**Azure HDInsight**
- Process massive amounts of data with managed clusters of Hadoop clusters in the cloud.
- You can create a cluster with types:
  - Apache Spark
  - Apache Hadoop
  - Apache Kafka
  - Apache HBase
  - Apache Storm
  - Machine Learning

**Azure Databricks**
- Integrate this collaborative Apache Spark-based analytics service with other big data services in Azure
- Helps to discovery your data
- You can integrate with Machine Learning Soluctions 
- Used with Apache Spark
- Support following languages:
  - Python, Scala, R, Java e SQL
  - Data Analyses Libraries: TensorFlow, PyTorch e scikit-learn.

**Azure Data Lake Analytics**
- Analyses Big Data about demand
- You do not need implement dedicated hardware to this soluction
- You export the data, create querys and you pay only when is running
- Is a Saas soluction

<br>

#### AI

**Azure Machine Learning Service**
- Cloud-based environment you can use to develop, train, test, deploy, manage, and track machine learning models. It can auto-generate a model and auto-tune it for you. It will let you start training on your local machine, and then scale out to the cloud.

**Azure ML Studio**
- Collaborative visual workspace where you can build, test, and deploy machine learning solutions by using prebuilt machine learning algorithms and data-handling modules.

<br>

#### AI Processors

**Vision**
- Use image-processing algorithms to smartly identify, caption, index, and moderate your pictures and videos.

**Speech**
- Convert spoken audio into text, use voice for verification, or add speaker recognition to your app.

**Knowledge mapping**
- Map complex information and data to solve tasks such as intelligent recommendations and semantic search.

**Bing Search**
- Add Bing Search APIs to your apps and harness the ability to comb billions of webpages, images, videos, and news with a single API call.

**Natural Language processing**
- Allow your apps to process natural language with prebuilt scripts, evaluate sentiment, and learn how to recognize what users want.

<br>

#### DevOps

**Azure DevOps**
- Use development collaboration tools such as high-performance pipelines, free private Git repositories, configurable Kanban boards, and extensive automated and cloud-based load testing. Formerly known as Visual Studio Team Services.

**Azure DevTest Labs**
- Quickly create on-demand Windows and Linux environments to test or demo applications directly from deployment pipelines.


___

<br>

## **Cloud Types**

### Public Cloud
- Shared resources
- Provide computacional resources for any organizations and users
- Access by security protocol (SSH, TLS, HTTPS, ...), because run in internet not in intranet 

<br>

### Private Cloud
- The resources is exclusive for customer or admin
- Run in intranet
- Resources (memory, HD,.. ) is responsable for organization
- Need self-service, if you need more resources in your cloud e can provide to customer tools to upgrade you resources
- Need separete the cost of specific machines in separated bills

<br>

### Hybrid Cloud (more common)
- Combine private cloud and public cloud

<br>


### Global Reach
- Is about the service is available around the world, 
- Azure service is avaible for all countries 
- Today Azure as datacenter in more 60 regions
- ![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRB-5t43MCoS80v-ZB5Bmyb2iS_aNq9AnWpZlCxWMP9_GLBufzflJpVLb_caJ2KVh7EOmg&usqp=CAU)

<br>

### Scalability
- In this topic is about how much you can grow up your application with resources you have 
- In case of a black friday, how many machines you have to grow up your application
- About this topic is specificaly about physical hardware, how many hardware you have to encrease your application, in cloud you do not have limit to this scalability, but on premise you need buy more machines 
- About this topic you have two types to scale, **scale up** and **scale out**, see below
- ![image](https://inverodigital.com/site-content/uploads/2021/03/scale-up-vs-scale-out.png)


### Agility
- Basicaly this topic is about ease and convenience to provide new envinments, in cloud is very easy and agile create infrastructure, provide new machines, new network communication, comparison to in house infrastructure when you need buy new machines build new local to receive and mount this structure and more.

<br> 

### Predictive Cost Considerations
- Is about the cost of your infrastructure, you can provide for your customer what is he cost about your services and structure
- We can [azure calculator](https://azure.microsoft.com/pt-br/pricing/calculator/) to estimate yours cost in cloud 

<br>

### Fault Tolerance (Tolerancia a Falha)

- About this topic you need **reply all resource** that your application need to other region, because if any resource is down you can redirect all requests to another region.
- ![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGL3WkPpIoTGff9mYVqaj23WVwZau-bKP8Pw&usqp=CAU)

<br>

### Elasticity
- You need a infrastructure can provide for you, in a simple way to increase or decrease your resources
- Must be easy and fast to provide
- ![image](https://images.ctfassets.net/xxmwcynv5jdx/5EffAh3mLOfO3dxawFBWNq/f9f076b71260de3254e85c6c464d6160/elasticity.jpg)

<br>

### Security
- Today Azure is the cloud more certified comparision to anothers cloud
- ![image](https://azsec.azurewebsites.net/wp-content/uploads/2019/11/azure_compliance.png)

<br>

### Disaster Recover
- Disaster recover have unavailablity
- You not need replace all resources, you only need the essencial of your company
- Is commom you use other cloud ou other infrastructure to make Disaster Recovery
- Is the last choice when you have a problem in your structure, because disaster recovery not is a replica of your environment
- When you apply the disaster recovery you need a plan to redirect your applications to disaster recovery, and this plan takes a time to apply, usually in hours.  
- ![image](https://jadsonalves.com.br/wp-content/uploads/2021/04/migrate-to-premium-storage-using-azure-site-recovery-1.png)

### Azure Site Recovery
- provide implementation for replicated, failover and rescue your services
- Azure Site recovery is an DRaaS (disaster recovery as a service)
- Configure an service to make available in another region on Azure
- All configurations is applied on 2 regions
- ![image](https://azurecomcdn.azureedge.net/cvt-46bef236300115b89710e1f92bdffb79d892b5ed3c447d34c0f8bf3d07a07565/images/page/services/site-recovery/prop1.png)

- * _failover_: tolerance to failure.


<br>

### Customer Latency Capabilities 
- Azure Cloud is available in more 60 regions, you can make available your application more closer of your customers and so decrease the time betwheen your application and your customer.
- The more closer you application is for your customer, smaller latency your customer have.


<br>

___

## **Models of Cloud**

### Capital Expenditure (CapEx)
- You need buy the infrastructure, and this structure is yours, you can buy with a contract or lising.
- This infrastructure is yours, and only you use this.
- When you choise for this model, you can have more discount because you reserve this machine for you to an especific duration.

<br>

### Operation Expenditure (OpEx)
- You pay only what you use. 
- Is more easy, but is more expensive for a long time, because you can stop use anytime.
- Is more easy, to grow up your structure.

<br>

> **IMPORTANT**: The Azure Cloud, provide this two types of contract.


<br>

<br>

### Manager Groups
- Manager group is resposable to manage all signatures in Azure Account
- you can have one more Manager Group
- Signatures inherit condition by Manager Group
- ![image](https://i2.wp.com/blog.rajah.ch/wp-content/uploads/2019/06/TVD_Azure_Guidelines_MG.jpg?resize=760%2C563&ssl=1)

<br>

### Azure Signature 
- One account in Azure can have one or more sign
- Is a good pratice separate each part of your company in diferrents signatures and with technique identify the billing
  - in same accout you can have signature for developers, for maketing and productions, for example...

<br>
___

## **Cloud Services**

![image](https://uploads-ssl.webflow.com/5f9497b13bcbdc738e5867c5/61af48facc039c26c05a8d08_k2TZ3iKwijvU3owlhHFMkP761IPhvGYJmrTzDnx4Y772udtHqafIAjMXKbBx4t4LSClsaaxlUqfa6VmW2873nTNCJaZY0ziK8_zL2ZBv3uvV1jzntdMbhUEWfTqGAVuq56Vt9yvQ.png)

<br>

![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSopwK8sgmzH9zjdzDvZ2C4iVIxH6zzo6N61w&usqp=CAU)

### IAAS (Infrastructure as a service)
- The responsability is for client, examples maintainable, update, stop applications
- For examples dedicated machines
  
<br>

### Paas (Plataform as a service)
- Azure cloud provide update, maintainable and resources to machine, the client is responsable about the application or data (in case of database)
- For examples SQL Service, the Cloud is responsable about the SQL application and machine, but the responsability to manage the application is to client

<br>

### Saas (Software as a service)
- The all application and machine is responsability to Cloud provide
- For example Office 365 or Cognitive Service

<br>

> **IMPORTANT**: in all cases the responsability of backup of information is to client, Cloud not is responsable for you backup information in any services 

<br>

### Shared responsabilty model 

![image](https://f.hubspotusercontent30.net/hubfs/508286/Microsoft%20Azure%20Shared%20Responsibility%20Model%20600x300.png)

![image](https://cloudberry.engineering/azure-shared-responsbility-model.png)

___

## Core components in Azure Cloud

### Azure Cloud region
- Azure cloud is available 60 more countries, not all services is available in all zones
  - When a new zone is created not all services for Azure Cloud is available in this zone in same time
- Each region have a different value to maintain your application, because regions governamental fees or taxes, energy cost, and more...
  - US region it's more cheaper 
- Each region have one or more datacenter next
  - [infrastructuremap - microsoft](https://infrastructuremap.microsoft.com/) 

![image](https://powerbiexpert.files.wordpress.com/2022/01/4eb09-image-16.png)

<br>

### Region pairs
Each region in Azure Cloud has a pair, this regions provide:
- Automaticaly replica for a some services
- Priority to rescue region in case os stop
- Distribuited updateds in sequencial to minimize downtime

For one region is par to another region one role at least 300 miles of distance each other

Follow pairs list below:

<br>

![image](https://docs.microsoft.com/en-us/learn/wwl-azure/discuss-core-azure-architectural-components/media/regional-pairs.png)

<br>

![image](https://www.pragimtech.com/blog/contribute/article_images/1220201111015353/examples-of-azure-region-pairs.jpg)


___

## High Disponibility in Azure Cloud
Each service on Azure cloud have a different availability SLA

![image](https://docs.microsoft.com/en-us/azure/architecture/high-availability/images/high-availability-004.png)


>**SLA**: Service Level Agreement

- **99,9 %** :  For Single Virtual Machine in premiun storage 
- **99,95 %**:  For hardware failure in same datacenter
- **99,99 %**:  For Available zones - protection for al datacenter
- **0 %** :     For desaster recover 
  - To enviroament DR ou Desaster Recover you need up your resources in other region, for this task the machine provide minimum of the 2h, don't have max time 

### UD and FD 
- **UD - Update Domain**: when you create a a virtual machine on Azure Cloud, you can add a Update Domain, this is second Virtual Machine created on another virutal machine used when the Microsft need down your first Virtual Machine in other virtual machine. When Microsoft need install updates or make manutanance in your primary virtual machine your application is automatically applied in other virtual machine.
- Microsoft starting updates in sequencial for update domain.

- **FD - Fault Domain**: Is the same saparation presented above, but in Fault Domain yours machines is on another Physical Rack

![image](https://k21academy.com/wp-content/uploads/2020/03/cdc20fb1fcdfaa89056821c5271332b9.png)

<br>

## Availability Zone
- Each region in Azure have three zones or datacenter, for example in Brazil South, you have three zones or datacenter. 
- When you configure a new zone availaility you basicaly separate your application for another zone, not is a replica
- Each zone are in the same region, but in another physical address

![image](https://docs.microsoft.com/en-us/azure/availability-zones/media/az-overview/az-graphic-two.png)

> Zone = Datacenter

___

## Organize Resources on Azure 

<br>

![image](https://docs.microsoft.com/pt-br/azure/cloud-adoption-framework/ready/azure-setup-guide/media/organize-resources/scope-levels.png)

<br>

### Resource Group
Basically is a container for manager and aggregate your resources in same unity   
- Is basically a logic separation
- Is the way to separate your resources in a group
- You can group a diferents resources to differents regions in the same resource group  
- ![image](https://static.packt-cdn.com/products/9781789617580/graphics/assets/0a0e0cdb-e4db-44b4-addb-087c940b469f.png)

<br>

### Resource
Bassicaly is a each component ou service on Azure

<br>

![image](https://adinermie.com/wp-content/uploads/2018/08/Azure-Subscription-Management.png)

<br>

### Subscription
Is a account on Azure, provide authentication and authorization on Azure Cloud
- You can seaparate invoices or bills byt subscriptions
- Manage access control by subscription
- ![image](https://docs.microsoft.com/pt-br/azure/role-based-access-control/media/transfer-subscription/transfer-subscription.png)

<br>

### Manage Subscription
Is responsable to manager each susbscription, is responsable to apply rules or polices for each subscription
- You can create any managemant group
- One management group tree can suport six levels to depth
- 10K manager group can use in one sigle directory
- The subscription inherit policies and rules
- ![image](https://docs.microsoft.com/en-us/azure/governance/management-groups/media/tree.png)   

<br>

___

## Core Workloads

### Azure Computer Service
Is a service on Azure to provede a computacional services for demmand, for examples, storage, processors, memory, network and operational system

<br/>

![image](https://image.slidesharecdn.com/20220210-ifsc-desenvolvimentoazurecsharp-220213220452/85/desenvolvimento-de-aplicaes-para-o-microsoft-azure-utilizando-c-14-320.jpg?cb=1649180044)

<br/>

- **Virtual Machines**
  - provide a virtual machines for user
  - is a **IaaS** product type
  - offer total control access and personalization about machine
  
- **Virtual Machine Dimension Set**
  - Provide an group of VM' s with same configurations
  - This VM' s is available in scale, when you need more machine, more instances is created.
  - The sizing  ou dimencion can be automaticale, manual or both
  - You can use this machines for Big Data or containers for example.
  - ![image](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/azure-compute-fundamentals/media/icon-scale-sets-8682cc12.png)

- **APP Service**:
  - Is a Paas service
  - compatible with .NET, .NET Core, Node, JAVA, Python or PHP
  - Is especific to provide web sites or api' s quickly
  - Run in virtual machine

- **Azure Container Services**
  - Is a virtual enviroament, ligth and not need manager operational system
  - On container is more commum machines with linus operational system running Docker engine
  - ![image](https://i.ytimg.com/vi/yv6C8gICR98/maxresdefault.jpg)
  - Is a Paas service
  - **Azure Container Service**: Is Paas service to execute one container on Azure without manager
  - **Azure Kubernetes Service**: Is a service to orchestration for container adopted for Microsoft on cloud, os recommended to distributed aplications with large volume access  
  - ![image](https://miro.medium.com/max/1400/1*iz-rfmRCryqAoaDWiUWfqA.png)

- **Azure Virtual Desktop or Windowa Virtual Desktop**
  - Pulled or Personal
  - Is a virtualization to desktop in cloud
  - You have a two types of this service: **Pooled** or **Personal**
    - Pooled: in the same session you can provide access for more one peolple in the same machine
    - Personal: each people have one session
    - ![image](https://i.ytimg.com/vi/6MrQxBsgSL0/mqdefault.jpg)

- **Azure Batch**
  - Provide large scale in parralell and high availability (HPC) VM' s
  - This resource is directed whe you have a large job to executable and you need, ten, hundred or thousands VM' s 
  - When you're ready to run a job, Batch does the following:
    - Starts a pool of compute VMs for you.
    - Installs applications and staging data.
    - Runs jobs with as many tasks as you have.
    - Identifies failures.
    - Requeues work.
    - Scales down the pool as work completes.

_____

<br>

### **Azure Networking Service**
  - ![image](https://docs.microsoft.com/pt-br/azure/expressroute/media/expressroute-howto-coexist-resource-manager/scenario1.jpg)
  
  - You create a network to comunication resources on cloud or out off cloud
  - **Azure Virtual Network (VNet) / Gateway virtual network**: 
    - allows to Azure resources communication eacth others, using internet or local network
    - Used to communite VM' s on sub-network called gateway sub-network
    - ![image](https://www.cloudmotion.com.br/blog/2021/01/14/azure-transit-vnet/transit-gateway01.png)    

   
  - **Virtual Private Network (VPN) / VPN Gateway**: 
    - allows encripted communication betwheen Azure and a local network or another cloud by internet         
    - provide a criptografy comunnication betwhen a virtual network in Azure and local network on public internet, 
    - provide VPN to communication betwhen virtual Azure network and network Microsoft
    - Vitual network can be only one VPN, but one VPN can be any connections
    - If you create any connections in same VPN, all connectiosn share the bandwidth
    - Connection VPN point-to-site
    - ![image](https://docs.microsoft.com/pt-br/azure/vpn-gateway/media/vpn-gateway-howto-point-to-site-resource-manager-portal/point-to-site-diagram.png)
    
    - Connection VPN Site-to-Site
    - ![image](https://docs.microsoft.com/pt-br/azure/vpn-gateway/media/design/vpngateway-site-to-site-connection-diagram.png)


  - **Azure Express Route / Gateway Express Route**: extends local network to azure by a private connection, by wireles or fibre
    - With ExpressRoute, your data doesn't travel over the public internet, so it's not exposed to the potential risks associated with internet communications. ExpressRoute is a private connection from your on-premises infrastructure to your Azure infrastructure. Even if you have an ExpressRoute connection, DNS queries, certificate revocation list checking, and Azure Content Delivery Network requests are still sent over the public internet 
    - Is a private conection
    - Need a new contract with your internet provide to create a communication between a Azure datacenter with your company
    - Is more expensive
    - ExpressRoute supports the following models that you can use to connect your on-premises network to the Microsoft cloud:
    - ![image](https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-networking-fundamentals/media/azure-connectivity-models-4deabab1.png)
      - CloudExchange colocation 
        - Colocated providers can normally offer both Layer 2 and Layer 3 connections between your infrastructure, which might be located in the colocation facility, and the Microsoft cloud. For example, if your datacenter is colocated at a cloud exchange such as an ISP, you can request a virtual cross-connection to the Microsoft cloud. 
      - Point-to-point Ethernet connection
        - Point-to-point connections provide Layer 2 and Layer 3 connectivity between your on-premises site and Azure. You can connect your offices or datacenters to Azure by using the point-to-point links. For example, if you have an on-premises datacenter, you can use a point-to-point Ethernet link to connect to Microsoft. 
      
      - Any-to-any connection
        - With any-to-any connectivity, you can integrate your wide area network (WAN) with Azure by providing connections to your offices and datacenters. Azure integrates with your WAN connection to provide a connection like you would have between your datacenter and any branch offices.
        - With any-to-any connections, all WAN providers offer Layer 3 connectivity. For example, if you already use Multiprotocol Label Switching to connect to your branch offices or other sites in your organization, an ExpressRoute connection to Microsoft behaves like any other location on your private WAN.

      - Directly from ExpressRoute sites
        - You can connect directly into the Microsoft's global network at a peering location strategically distributed across the world. ExpressRoute Direct provides dual 100 Gbps or 10-Gbps connectivity, which supports Active/Active connectivity at scale. 


    - ![image](https://miro.medium.com/max/1037/1*UKeZhTv7d2t0YkqpwelZkA.png)
    - ![image](https://docs.microsoft.com/pt-br/azure/vpn-gateway/media/design/vpngateway-vnet-to-vnet-connection-diagram.png)
    
<br>

- **Route Network Traffic**
  By default Azure routes traffic betwheen VNet, On premisse Network and the internet, but you can override this routes using the follow settings:
  
  - **Route Tables**
    - You can use a table to define routes betwheen VNet, resources, anyway
    - ![image](https://knowledgebase.paloaltonetworks.com/servlet/rtaImage?eid=ka14u0000008rSN&feoid=00N0g000003VPSs&refid=0EM0g000001AdEG)
  
  <br>
  
  - **Border Gateway Protocol (BGP)**
    - Works with VPN gateway, Azure Route Server or Express Route
    - Works to propagate routes for local networks on Azure
    - ![image](https://docs.microsoft.com/pt-br/azure/vpn-gateway/media/vpn-gateway-bgp-overview/full-mesh-transit.png)
  
<br>

______


- **Azure Storage Service**
- Provide phisical space to save your datas in file mode
  - **Container storage (blob)**:
    - Not need phisical separations by folder for example
    - Is recommended to a large quantities of files
    - Save files not structured
    - Save VHD (virtual image machine custumizeds)
    - Is more commum used in application
  - **Disk Storage**:
    - Disk storage is created inside a container storage, you not see this you only see the disk storage   
  - **Azure File**:
    - you can access by SMB(port 445), NFS Protocol or exmplorer in windows using //D:/public/etc... for example    
- ![image](https://i0.wp.com/eadn-wc03-4064062.nxedge.io/cdn/wp-content/uploads/2021/04/blooob.png?resize=585%2C258&ssl=1) 

<br>

- **Azure Storage account tiers**
  - When you work if Azure storage you pay the consumed based in two informations, **Quantity of record** and **Quantity of reading** 
  - **HOT**:
    -  Best choice if your file as high frequency to consume
    -  Is more expensive
    -  Is more exprensive to record, more cheaper to read    
  - **COOL**:
    - Best choice if your file is access with hfrequency during firt thirty days 
    - Is intermediate cost
    - Is intermediate cost to record and intermediate cost to read
  - **ARCHIVE**:
    - Best choice if your data no need imediate access
    - When you need a file you need request and in ten hours you have a response, because you data are migrated to another server and the file your data pass by process calling dehydration
    - Is cheaper to record but more expensive to read
  - ![image](https://miro.medium.com/max/836/1*bzXpvxmhmSSnB5iZ3i_upQ.png)

<br>

- **Azure Database Services**
- ![image](https://microsoft.github.io/AzureTipsAndTricks/files/81optionscompared.png)
  - Azure Database Cosmos DB (NoSQL)
    - Is the database more distribuited globaly on Azure Cloud
    - Has automatilly scalability independent of throughput and storage

  - Azure Database SQL Database
    - Is a Paas service, available with the last version of SQL database

  - Azure Database SQL Managed Instance
    - This type is based on service **Azure Database SQL Database** and you have the same beneficies (automaticaly updates, backups, hight availability)
    - Best choice if you do not feel security to import you data, procedures, trigger to cloud
    - You have full access to network for access you database, if you need Liked Server 
    - You can choise the database version 
    - ![image](https://blog.pythian.com/wp-content/uploads/azuresql.png)
 
  - Azure Database MySQL
  - Azure Database Postgre SQL 

<br>

> All service see above run in Daas (database as a Service) or Paas (Plataform as a Service) service, if you need anothe database service, for example Oracle Database, you need create a new machine, install and manager is resource
 
<br>

## **Azure Soluctions**
The follow services read many telemetry

<br>

### Azure IoT Central
- Is a SaaS soluction 
- Is responsable to manager all IoT devices enables 
- Make connections more easier
- Is reponsable to show the information about connected devices.. 

<br>

### Azure IoT HUB
- Is a Saas soluction
- Is responsable to manage all messages exchanged by devices and other soluction, for example IoT Central
- This soluction manager  bidirectional communication 
- Is reponsable to connect with devices..

<br>

### Azure Sphere
- What the certification, update anda manager certificates
- Manage cryptografy
- Manage the security about all devices connected in Azure IoT Central

<br>

### Big Data and Analytics

### Azure Synapse Analytics
- Is based in Data Warehouse
- Works with SQL language
- Is a SQL Cluster 
- is the best choice when you a structured datas

<br>

### Azure HDInsight
- Is the best choice when you have not structured data
- Is based in Data Warehouse
- Is a Cluster 
 
<br>

### Azure Databricks
- Is the most high level for Data Analytics
- Have a more computational power
- Works with apache clusters
- The Databricks undestand what informations you need and create news cluster during the job, when the data analytics job end he is responsable to unprovision this clusters

<br>

____


## Artificial Intelligence and Machine Learning

### Azure Machine Learning
- Based in cloud is a SaaS soluction to works with machine learning
- Is responsable to traine and implement machine learning models

<br>

### Cognitive Services
- Is a Saas soluction
- Provide easear integration for applcations to understand talk, listening and understand any needs
  
<br>

### Azure Bot Service
- Is a SaaS soluction 
- Provide tools to create bots, in personal or corporative level
- In this services you have available to use **LUIS** (Assistent for natural language) available on Azure

<br>

_____


## Serverless computation

### Azure Functions
- Is a SaaS smoluction, 
- Provide that infrastucture to run a code when configured a trigger, for example (email, event, HTTP request, ...)
- Is the best soluction when you have a code needs running in espeficic times, or from a trigger
- You pay for execution times and duration 

<br>


### Azure Logic Apps
- Is a SaaS soluction.
- Provide orchestration for taks in cloud, calling anothers services or integrations.
- Is the best choice when you need an orchestration in your tasks from a trigger.
- You pay for execution times and trigger


<br>

_____


## Azure DevOps Services
Is a integrations between developers and infrastructure

![!image](https://leonardomatsumota.files.wordpress.com/2018/09/azure-devops.png)

### Azure DevOps
- Tools to colaborate and development your applications, including pipelines, Kanban and automaticaly tests based on cloud 
- Is the best choice when you need following delive task and exports reports
- Is thes best choice when your project and source code not is open source
- Available following services:
  - **Azure Repos**
    - Manage your source-code and documentation  
  - **Azure Pipelines**
    - Tool to automate your pipeline CI/CD 
  - **Azure Artifacts**
    - Repo to deploy compiled source code and artifacts 
  - **Azure Boards**
    - Manage your tasks, PBI' s, Epics and others itens
    - You can use with Kamban, Scrum, ScrumBan, you decide the methodoly  
  - **Azure Tests Plan **
    - Tool to automate tests in your pipeline CI/CD 

### GitHub
- Version control for your source-code
- Open source
- Manager tasks, bugs, ... 
- Is the best choice when you not need following delive task and exports reports
- Is thes best choice when your project and source code is open source

<br>

#### GitHub Actions for Azure
- Automate workflow to build, test and deploy your application

<br>

### Azure DevTest Labs
- You can create an VM' s or infrastructure to deploy or test your application
- You can create this structure using **ARM**
  - ![image](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/templates/media/overview/template-processing.png)
  - ![image](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/templates/media/overview/nested-tiers-template.png)
  - ![image](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/templates/media/overview/tier-templates.png)
- When test or deploy is completed Aure stop or delet all resources created 
- In this lab you can use your *Azure credits* to provide machines or infrastructure in cloud and use to test your applications

<br>

> **Azure credits** = you win this credits all months, is a bonus tipe offer for Microsoft for your clients

> **ARM**: Azure Resource Manager, with this resource you can manage resources on Azure, you can create am script using YAML or JSON and with this script you can create all resources on Azure: 

<br>

___

## **Azure Manager Tools**
Basically is a tools available for Microsoft for oyou connect in your cloud and make operations. All Tools below are available in **Azure Resource Manager (ARM)**

- Azure Portal
- Azure PowerShell
  - Windows, Linux (you need Powersheel core) and Mac (you need Powersheel core)) 
  - Based on PowerShell command 

- Azure CLI
  - Is a pront like a PowerShell but the principal difference betwheen is a command line used, this pront is based in BASH command
  
- Azure Cloud Shell
  - is a PowerShell running in cloud

- Azure Mobile App
  - is an app to manage your cloud  

- Azure REST API

- ARM (Azure resource manager)
  - With this resource you can automate creating resources on Azure Cloud using scripts with JSON
  - You can create dozens / hundreds machines or configurations at once time and save this JSON file to next executions
   

![image](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/media/overview/consistent-management-layer.png)

<br>

___


### Azure Advisor / Azure Assistent
Is a resource that analisy in your cloud all Azure Resources and recommends best pratices based on Microsoft recomedations to optimize you Cloud, this recommendations is based on:
- Reliability
- Security
- Performance
- Cost
- Operation Excellence

![image](https://docs.microsoft.com/pt-br/azure/advisor/media/advisor-overview/advisor-dashboard.png)

> This tools only recommend, to apply this recommendations you need enter in Portal and make adjusts

<br>

### Azure Monitor
you can create alerts with SMS, e-mail, ..
Is a resource available to colect, analyse and make telemetry in your applications in Cloud, the principal tools are:

- Application Insights
  - make analisys on application

- Logs Analytics
  - Capture logs for your application
     
- Smart Alerts
  - Create alerts for your resources or applications 

- Automation Actions
  - Make actions based on your applications or cloud resources, for example, "sent an e-mail when have error log in application XYZ..."  

- Customized Dashboard
  - Is a tool to create dashboard
  - You can integrated with Grafana or Kibana   
  
![image](https://docs.microsoft.com/pt-br/learn/azure-fundamentals/monitoring-fundamentals/media/2-identify-product-options-01.png)

<br>

### Azure Service Heath / Azure Services Integrated
You can monitoring status on azure services in web-site [status.azure.com](https://status.azure.com/pt-br/status).

Evaluate problems in Azure Cloud. Make available for all customer if has identified any problem in Azure Cloud and make available reports with more technical details

Used to analyses the RCAs (root case analyses)

- Comunication about crash or stop services in Azure Cloud
- Planned manutence
- Others advices about health

![image](https://www.partech.nl/publication-image/%7B299B31CA-3E87-4103-A989-A9652136AE88%7D)


<br>

___

## **Azure Security Tools and Features**

Secuty Layer since phisicaly to remote:

![image](https://docs.microsoft.com/en-us/learn/azure-fundamentals/secure-network-connectivity-azure/media/2-defense-depth.png)

- Phisical Security
  - Physically securing access to buildings and controlling access to computing hardware within the datacenter are the first line of defense.
  - With physical security, the intent is to provide physical safeguards against access to assets. These safeguards ensure that other layers can't be bypassed, and loss or theft is handled appropriately. Microsoft uses various physical security mechanisms in its cloud datacenters.


- Identity and access
  - Control access to infrastructure and change control.
  - Use single sign-on (SSO) and multifactor authentication.
  - Audit events and changes.

- Perimeter
  - Use DDoS protection to filter large-scale attacks before they can affect the availability of a system for users.
  - Use perimeter firewalls to identify and alert on malicious attacks against your network.

- Network
  - Limit communication between resources.
  - Deny by default.
  - Restrict inbound internet access and limit outbound access where appropriate.
  - Implement secure connectivity to on-premises networks. 

- Compute
  - Secure access to virtual machines.
  - Implement endpoint protection on devices and keep systems patched and current.   

- Application
  - Ensure that applications are secure and free of vulnerabilities.
  - Store sensitive application secrets in a secure storage medium.
  - Make security a design requirement for all application development.

- Data
  - Stored in a database.
  - Stored on disk inside virtual machines.
  - Stored in software as a service (SaaS) applications, such as Office 365.
  - Managed through cloud storage.

<br>

### Azure Firewall

Provide Security for your services

  - High availability
  - Scalability
  - Rules to inboud and outbound
  - Add log in Azure Monitor
  - Protection for inboud in protocols no HTTPS (for example RDP, SSH, FTP, ...)
  - Protections for outboud in all ports
  - Protection in application layer for HTTPS outboud
  - Support to DNAT (destination network address translation)
    - ![image](https://i0.wp.com/ipwithease.com/wp-content/uploads/2017/09/SNAT-VS-DNAT-1.jpg) 

You can configure this follows tools in Azure Firewall
  - Applications rules that define FQDN(fully qualified domain names) who application can has access on sub-network
  - Network rules to be define origen address, protocol, destination port and destination address
  - NAT rules, define address and port to communication betweehn applications

<br>

### Azure DDOS Protection

Azure provide an service defend you network about attack of the DDOS

![image](https://td-mainsite-cdn.tutorialsdojo.com/wp-content/uploads/2020/08/azure-ddos-protection.png)

You have available two layer of this services:

  - Basic:
    - This Layer of Azure DDOS protection is free and anable by default in new network
    - This layer protect the Azure cloud about ddos attack
    
  - Standard:
    - Is complementar about basic protection, the only diferrence is the protection is applied in Virtual Network 

<br>

### Network Security Group (NSGs) (Mini Firewall)

- Do not has high availability
- NSGs is a minimal firewall with focus in IP list
- The principal function is filter the traffic an specific resource, with block or unblock actions
- Contain rules to **Inbound** and **Outbound**
- Works with IP list
- Can be associate to Subnet or NIC (Network interface Card)
- Is recomend associate an NSG to a Subnet and only specific cases connect to an NIC
- ![image](https://www.azureexperts.com.br/wp-content/uploads/2019/12/123.png)
- ![image](https://docs.microsoft.com/en-us/azure/bastion/media/bastion-nsg/figure-1.png)


<br>

### Azure Security Center

Is a layer based on monitoring and configurations of security. Security Central colect events of the Azure and log analitycs and correlates them to make susgestions in your **Cloud Advisor Service** 

- Make a score about your cloud, calling **Security Score**
- Secutiry Center is integrated in Azure Advisor
- You can pay if you identify that you need more monitoring in yours applications or resources

![image](https://docs.microsoft.com/pt-br/azure/defender-for-cloud/media/alerts-overview/security-center-detection-capabilities.png)

<br>

![image](https://docs.microsoft.com/pt-br/azure////security-center/media/security-center-recommendations/asc-overview.png)

<br>

### Azure Defender

Monitoring actively your resources and try identify any security failure or vunerability in your Cloud. Make available for client reports and alets if find any problem. 

This service analyse behavior 

Have aditional cost

Principal resources:
- Accordance with policies
  - execute policies in resources groups , assignatures
- Continuos avaliation
  - monitoring all services from time to time to guarantee the all services is correcty configuured
- Personal Recomendations
  - recommend new configurations based on your services
- Protection against threads
  - Analise the protection based on others reports and alerts

      

Azure Defender is available for this applications:
- Applications Services
- Storage
- SQL
- Key Vault
- Resource Manager
- DNS
- Kubernetes
- Container Registry
- Thsi service can be used in server out of cloud, through **Azure Arc**

> **Azure Arc** provides a centralized and unified way to: Manage your entire environment by projecting existing non-Azure and/or on-premises resources into Azure Resource Manager. Manage virtual machines, Kubernetes clusters and databases as if they were running on Azure

![image](https://docs.microsoft.com/pt-br/azure/security-center/media/azure-defender/sample-defender-dashboard.png)

<br>

### Azure Sentinel

This soluction, is a native in Azure Cloud and using **Security Informations Events Manager(SIEM)** and **Security Orquestration Automaticaly Response(SOAR)** to making monitoring activily an specific resource in your cloud, and using IA to identify if any problem in your cloud, this follow the specific analyse flow:
Have aditional cost.

- Collect
  - Collect all data in a cloud, or an specific resource logs, transactions, logins, ...
  - Local and anothers cloud
- Detect
  - With a data this soluctins identify whats is the normal resource usage, and with this he can identify any unusual behavior 
- Investigation
  - This soluction start investigations, analyzing this unusually behavior wit IA 
- Response
  - If has identify any problem this soluctions proactively enable new layer of security, creating a new rule in firewall, close a specific door in your machine or creating a ticket in your ticket manager.

<br>

![image](https://www.reimling.eu/wp-content/uploads/2019/09/Azure-Sentinel-logo1-672x372.png)

<br>

### Azure Key Vault

Manage and storage secrets and certifications giving more security  and  permissions to access control of this informations.

- Manage Secrets
- Manage Keys
- Manage Certifications
- Storage secrets based in security hardware (HSMs)

<br>

![image](https://docs.microsoft.com/pt-BR/azure/architecture/reference-architectures/n-tier/images/encryption.png)

<br>

### Azure Dedicated Host

Is a phisical server dedidcated for a specific company and dedicated to big workload, folow the beneficies

- Isolated hardware in server level
- Control about manutence time 
- Aligned with Azure Hybrid Cloud

![image](https://cache404.net/wp-content/uploads/2020/08/image-7-1024x487.png)

<br>



### Azure Firewall

- High availability
- Is a service type **FaaS**
- Is possible create, register and centralizer policies 
- Provide a public IP static for yours resources in virtual network, manke possible others server identify your trafic.
- Is integrated to Azure Monitor to log registry and analisy
- Is more expensive in comparison with F5 (partner firewall available in marketingplace on Azure)
- ![image](https://docs.microsoft.com/pt-br/azure/firewall/media/overview/firewall-premium.png)

<br>

____

## **Core Azure Identity Services**

Provide Authentication and Authorization

<br>

### Azure Active Directory (similar Local Active Director)
Is used to provide authentication nd authorization for logins in Azure or partiner websites

Provide follow services

- Authetication
  - Employees sign-in to access resources

- Sigle ign-on (SSO)
- Business to Business(B2B)
  - Is possible create an guest in your active directory associate your e-mail address 
  - Betwheen 2 microsoft account

- Business to Customer(B2C) Identity services
  - Provide Authorization based in Authetications services out of Microsoft, for example Google account
  - Betwheen service out of microsoft (Google, Facebook,.. ) 

- Device Manager
  - Authetication or Authorization with an pendrive   

<br>

### Azure Multi-Factor Authentication - MFA
- Authetication with cell phone token, sms message, pendrive, ... 

<br>

### Condictional Access

Is a service usage in Azure Directory for union informations about your network and make decision to apply more or less policies during Authetication and Authorization, for example if you work in home but in a specific day you are to office on the office you do not need MFA Authorization.

You can apply follow rules
- User or group membership
- Ip Location
- Devices
- Apllication
- Risk Detection
- ![image](https://docs.microsoft.com/pt-br/azure/active-directory/conditional-access/media/overview/conditional-access-overview-how-it-works.png)

<br>

### Explorer Role-Based Access Control (RBAC)

Manager access on Cloud, enable access to portal and resource controls, we have follow principal permissions:

- Owner
  - can make any changes in cloud
 
- Contributor
  - Have acces to reade, write, but do not grant access for anothers developers

- Reader
 - Can only read resources, can't make any modification.

- ![image](https://i.ytimg.com/vi/E0XDci4_kQk/maxresdefault.jpg) 

 <br>

### Resource Locks

Protect you resource againt delete accidental, manage lock by assinature, groups of resources or individual resources in Azure Portal. The Lock Resource reply inherance for your childs, for example if you apply this lock in one resource it is propagates for your childs.
You can apply _Resource Lock_ in a Resource Group and all childres inherit this policies. 
You have a follow **Lock Types**:

- CanNotDelete
  - Read = Yes
  - Update = Yes
  - Delete = No 
- ReadOnly
  - Read = Yes
  - Update = No
  - Delete = No 
 

 <br>

### TAG' s

- You can Aplly a _tag_ in an specific resource.
- TAG is by resource, not apllied with inherance
- Must used to separate cost center for especific departament
- Is created based in key : value, for example: "cost-center":"marketing"

 <br>

### Azure Policy (AAD)

- Helps the create organizational rules to evaluate the scale for resources.
- Is possible apply in a signature
- Determine an limnit to create new resources, based in categories, Storage, Network, computational, Security and Monitoring
- ![image](https://i.ytimg.com/vi/obWeyLHWQIY/maxresdefault.jpg)

 <br>

### Azure Blueprint

- Make possible that developers create scripts to provide environments, on business and organizational rules applied, using templates
- make easilly provide:
  - Role assigniment
  - Policy assignment
  - Resource manager
  - Resource group
- ![image](https://wedoazure.files.wordpress.com/2019/03/blueprints.png?w=800) 
 

 <br>

### Cloud Adoption Framework (CAF)

- Best to pratices to migrate from cloud, available by Azure
- Who migrate services, best names, best tags, best resources, who apply governance, monitoring, ... all best pratices
- [Official Link](https://docs.microsoft.com/pt-br/azure/cloud-adoption-framework/)
- ![image](https://docs.microsoft.com/pt-br/azure/cloud-adoption-framework/_images/caf-overview.png)

 <br>

## **Policy, Compliance and Data Protection**

- More information about [GDPR](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) and [LGPD](https://pt.wikipedia.org/wiki/Regulamento_Geral_sobre_a_Prote%C3%A7%C3%A3o_de_Dados).

- Azure Cloud has many certifications about data protections
- Azure is co-responsable about data tranfering in your cloud
- Azure has access on your cloud only to manage resources and collect data to analisy for recommend best pratices and best perfomance 
- Azure make available one portal to recommend best pratices, based on all clients

### Azure Trusted Center
- kwon more about privacity, conformity, policys resources and good pratices about trusted in your cloud or application.
- Azure provide a website to delivery more informações about your limits when the subject is Trusted.
- Provide list to partnes companies. 
- [Azure Trust Center](https://www.microsoft.com/en-us/trust-center/product-overview)

<br>

![image](https://files.tecnoblog.net/wp-content/uploads/2018/04/gdpr.jpg)

<br>

![image](https://blog.tactium.com.br/wp-content/uploads/2020/09/banner-LGPD.jpg)

 <br>

### Sovereign Regions (US Government Services)

- Is servers phisicaly separates of the public Azure servers
- Are services for gorvernance of country, states or counties
- Phisically available on american states  

<br>

### Sovereign Regions (Azure China)

- Azure is the first american cloud provide, certificates to operate with governament services on China
- Servers phisically separate of public Azure
- Operated by **21Vianet**
- All data is processing and operated on China country, following conform rules.

<br>

## **Plan and Cost Management** 

<br>

### Factor Affecting Costs
- 1: Resource Type
  - Each resorce have an value to use 

- 2: Service
  - Azure usege tax
  - Periods to bill (monthly, anually, ondemmand, .. ), in general contracts most biggest, for example 10 years have more discount

- 3: Location
  - Each region on cloud have one cost, for example Brazil is more expensive to United State, because the governament taxes, cost manutence and energy

- 4: Bandwidth
  - Inboud to azure not have cost, outbound have cost

- 5: Reservated Instance
  - If you reserve some instance of SQL machine for 1 year or 10 years, you can have discount about this resource, you can see this discount on [Azure Calculator](https://azure.microsoft.com/pt-br/pricing/calculator/)
  - The discount is applied on computional cost, all licenses dont have discount, for example if oyou need a SQL instance for 10 years, your discount is based on machine not on SQL Server Lincence.

- 6: Azure Hibryd Use Beneficies
  - You can apply a on-premisse licence in cloud, for example, if you had a SQL Server Lincence you can use the same Licence on Instance SQL in Cloud saving of your cost the SQL Server lincence

<br>

> You can access [Azure Latency Speed](https://www.azurespeed.com/Azure/Latency) to verify the latency of your resource in diffents regions on Azure Cloud

<br>

> You can access [Azure Region Price](https://azureprice.net/regions), to see cost of resource in each region on has Azure Clound, saving money for each resource

<br>

### Total Cost Ownership Calcular

- Is an service available on Azure Portal, to estimate how much will be saving moving to Azure Cloud, how more information you specified in this service more assertive is your estimation
- ![image](https://i0.wp.com/www.sustainablepurchasing.org/wp-content/uploads/2016/09/TCO-graphic-SH.png?resize=400%2C400&ssl=1)

<br>

### Azure Cost Management

- When yo manage all information about your cost on cloud
- you can define:
  - Reports
  - Budgets
    - If you set an Budget, and you exceds thsi budget the azure not stop your service, only send notifications about your budget 
  - Alerts
  - Reccomendations 
- ![image](https://assets.spot.io/app/uploads/2021/03/24145411/pasted-image-0-1-1.png)
 
<br>

### Service Level Agreements (SLA)

- Free resource dont have SLA
- Previous resources dont have SLA
- All SLA' s based on resources
- SLA' s based on individual resources
- ![image](https://unascimento.files.wordpress.com/2020/01/azureresilienceservices4.png)

<br>

### Azure Preview Program

While a service is on preview, this service dont have SLA

- Private Preview
  - Available only specific clients on Azure 
- Public Preview
  - All clients on Azure can evaluate this resources
- Generally available (GA)
  - After a Public Preview is complete, all customer have access for this service
  - Service region availability can vary
- ![image](https://docs.microsoft.com/en-us/azure/devops/project/navigation/media/preview-features/preview-features-user.png?view=azure-devops)
<br>


