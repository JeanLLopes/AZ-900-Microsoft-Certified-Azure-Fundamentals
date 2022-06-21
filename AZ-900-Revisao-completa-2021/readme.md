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

___

## **Beneficies of Cloud**

### High availability
- Basically is maintain you application available 99,999999...% of time online
- For provide High availability you can reply you application in others Zones, see the imabe below, or reply or applications machines, and apply load balance for direct the requests. 
- ![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfJ7aNbIK2G0sWwkDxlvG0sr780GCslSCRnGNH2N_tO8Z2fo8JqiXYy3GS7W9dxJJur-A&usqp=CAU)
- About this topic you can have failure in your application, because an external resource, for example, if you a site and this site consume a database, case you database is down you application need continue available but presenting a error message to consume the database 


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

- **Azure Networking Service**
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
    - Is a private conection
    - Need a new contract with your internet provide to create a communication between a Azure datacenter with your company
    - Is more expensive
  - ![image](https://miro.medium.com/max/1037/1*UKeZhTv7d2t0YkqpwelZkA.png)
  - ![image](https://docs.microsoft.com/pt-br/azure/vpn-gateway/media/design/vpngateway-vnet-to-vnet-connection-diagram.png)

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

<br>

### Azure IoT HUB
- Is a Saas soluction
- Is responsable to manage all messages exchanged by devices and other soluction, for example IoT Central
- This soluction manager  bidirectional communication 

<br>

### Azure Sphere
- What the certification, update anda manager certificates
- Manage cryptografy

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

### Artificial Intelligence and Machine Learning

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

<br>

### Serverless computation

### Azure Functions
- Is a SaaS smoluction, 
- Provide that infrastucture to run a code when configured a trigger, for example (email, event, HTTP request, ...)
- Is the best soluction when you have a code needs running in espeficic times, or from a trigger

<br>

### Azure Logic Apps
- Is a SaaS soluction.
- Provide orchestration for taks in cloud, calling anothers services or integrations.
- Is the best choice when you need an orchestration in your tasks from a trigger.

<br>

### Azure DevOps Services
Is a integrations between developers and infrastructure

### Azure DevOps
- Tools to colaborate and development your applications, including pipelines, Kanban and automaticaly tests based on cloud 

<br>

### GitHub
- Version control for your source-code
- Open source
- Manager tasks, bugs, ... 

<br>

### GitHub Actions for Azure
- Automate workflow to build, test and deploy your application

<br>

### Azure DevTest Labs
- In this lab you can use your *Azure credits* to provide machines or infrastructure in cloud and use to test your applications
  - **Azure credits** = you win this credits all months, is a bonus tipe offer for Microsoft for your clients


<br>

___

## **Azure Manager Tools**
Basically is a tools available for Microsoft for oyou connect in your cloud and make operations. All Tools below are available in **Azure Resource Manager (ARM)**

- Azure Portal
- Azure PowerShell
  - Windows, Linux (you need Powersheel core) and Mac (you need Powersheel core)) 

- Azure Cloud Shell
  - is a PowerShell running in cloud

- Azure Mobile App
  - is an app to manage your cloud  

- Azure REST API

![image](https://i.ytimg.com/vi/L_hEslzBr2o/maxresdefault.jpg)

<br>

### Azure Advisor
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
Is a resource available to colect, analyse and make telemetry in oyour applications in Cloud, the principal tools are:

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
  
![image](https://docs.microsoft.com/pt-br/azure/azure-monitor/media/data-platform/overview.png)

<br>

### Azure Service Heath

Evaluate problems in Azure Cloud. Make available for all customer if has identified any problem in Azure Cloud and make available reports with more technical details
- Comunication about crash or stop services in Azure Cloud
- Planned manutence
- Others advices about health

![image](https://www.partech.nl/publication-image/%7B299B31CA-3E87-4103-A989-A9652136AE88%7D)

___

## **Azure Security Tools and Features**

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
- Collect
  - Collect all data in a cloud, or an specific resource logs, transactions, logins, ...
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

### Network Security Group (NSGs) (Mini Firewall)

- Do not has high availability
- NSGs is a minimal firewall with focus in IP list
- The principal function is filter the traffic an specific resource, with block or unblock actions
- Contain rules to **Inbound** and **Outbound**
- Works with IP list
- Can be associate to Subnet or NIC (VM network board)
- Is recomend associate an NSG to a Subnet and only specific cases connect to an NIC
- ![image](https://www.azureexperts.com.br/wp-content/uploads/2019/12/123.png)
- ![image](https://docs.microsoft.com/en-us/azure/bastion/media/bastion-nsg/figure-1.png)


<br>

### Azure Firewall

- High availability
- Is possible create, register and centralizer policies 
- Provide a public IP static for yours resources in virtual network, manke possible others server identify your trafic.
- Is integrated to Azure Monitor to log registry and analisy
- ![image](https://docs.microsoft.com/pt-br/azure/firewall/media/overview/firewall-premium.png)

<br>

____

## **Core Azure Identity Services**

Provide Authentication and Authorization

<br>

### Azure Active Directory (similar Local Active Director)

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

### Rosurce Locks

Protect you resource againt delete accidental, manage lock by assinature, groups of resources or individual resources in Azure Portal. The Lock Resource reply inherance for your childs, for example if you apply this lock in one resource it is propagates for your childs.
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

### Azure Policies (AAD)

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


