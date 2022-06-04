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

