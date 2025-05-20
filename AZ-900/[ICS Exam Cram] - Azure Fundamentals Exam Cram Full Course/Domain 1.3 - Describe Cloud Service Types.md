# Describe Cloud Service Types

Describe Infrastructure as a Service (IaaS)
Describe Platform as a Service (PaaS)
Describe Software as a Service (SaaS)
Identify appropriate use cases for each cloud service

*Walkthrough of 'Shared Responsibility Model'*

  

From the types of cloud, there are Iaas, Paas and SaaS. There is the model of shared responsibility. This model explains which responsibility each Cloud Service Type handles. There is an image of the model, but first I'll write which responsibility for each model, aiming to added learning possibility through repetition. 



**CSP (CloudServiceProvider) Responsibility:**

**On-Premises**: Applications, Data, Runtime, Middleware, OS, Virtualization, Servers, Storage and Networking.

**IaaS**: Virtualization, Servers, Storage and Networking.

**PaaS:**  Runtime, Middleware, OS, Virtualization, Servers, Storage and Networking

**SaaS: ** Runtime, Middleware, OS, Virtualization, Servers, Storage, networking, ***and the shared responsibility of*** Applications and Data.

**Hybrid Cloud:** The Hybrid model include the IaaS responsibility package at minimum, with capabilities to scale to more responsibilities depending on the customer's choices.



* *There is a distinction between Cloud Deployment and Cloud Services. Cloud deployment would be the Location and Ownership that each model provides. Hybrid, Private and Public, would be Deployment Models, where as Iaas, Saas and Paas are the Service Model, managing the tech stack.**



### Cloud Models and Services

#### **IaaS** - 

- ***CSP provides*** the building blocks. Building blocks are *Networking, Storage, Servers and Virtualization.*
- ***CSP manages*** staff, HW, and datacenter. These are the people hired to work within Azure servers, security, etc.
- **Service Example:** Azure Virtual Machines (AVM)

All major CSPs have an IaaS offering. In Azure, the Infrastructure as a Service is named 'Azure Virtual Machines (AVM)'.

 The Utility functionality is pushed off to the CSP.

##### IaaS Use Cases (*When to use Virtual Machines*)

- <u>During testing and development</u> - VMs offer quick and easy ways to create and configure different OS and applications.
  Deploy and deletion of VM easily, instead of how it was before, where it could take days and weeks
- <u>When running applications in the cloud</u> - Technical and Financial benefits, as when app needs to handle fluctuations in demand.
  Quickly shutting VMs down and Up whenever it's needed, like in sudden demand increase, which means paying only for the used resources
- <u>When extending your datacenter to the cloud</u> - Possibility of extending capabilities of the own on-premises network by creating a virtual network in Azure and adding VMs to that virtual network. This makes it easier and less expensive to deploy than on-premises
- <u>During disaster recovery</u> - Significant saving costs are enabled when using an IaaS-based approach to disaster recovery, due to the VMs capability (push button automated VM spin up and shutdown in a disaster). 
  - "*Based on personal research, this is very interesting. There are protocols one could set up in case of disasters, such as power outage, Ransomware attacks and many other situations. Very smart. There is auto-routing, dns rerouting, settings for specific scenarios or response, to make it seamless, many interesting features*"

#### PaaS -

- **Customer Responsibility: ** Deployment and management of apps
- **CSP Responsibility:** Provisioning, configuration, hardware and OS management
- **Service Example:** Azure SQL Database, API Management, Azure App Service



**PaaS Use Cases (*When to use PaaS Services*)**

- <u>Development Framework:</u> 

  - PaaS provides a framework, enabling possibilities to build upon or customize cloud-based applications
  - Allows application development using built-in software components
  - Reduce the amount of coding on developers side by including cloud features, such as scalability, high-availability and multi-tenant. 

  *Reduces developer effort and increases solution quality*