# MS Learn [5-8] - Define cloud models

Cloud models define the deployment type of cloud resources. Main cloud models: Private, Public and Hybrid.



## Private Cloud

- Natural evolution of an corporate datacenter

- Private cloud model provides high level of control for the company and its IT department.

- Private cloud has higher cost and less benefits than public cloud deployment.

- Private cloud can be hosted from on site datacenter, with possibility of hosting in a dedicated datacenter offsite, also there's potential of hosting by third party with dedicated datacenter to the company.

  (***Q- theres always gotta be a dedicated datacenter to run the private cloud no matter in what case, as long as private, requires dedicated datacenter? If not, how would it go about deploying? Can I have examples of each one of the last bullet point made?***)

## Public Cloud

- Built, controlled and maintained by a third-party cloud provider
- Key difference is accessibility to the general public, opposite of the private cloud

## Hybrid Cloud

- Computing environment using both public and private clouds in an inter-connected environment.
- Hybrid cloud can be used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources.
  *(**Q- Ex.::???**)*
- Can be used to provide extra layer of security, for example allowing users to choose which services to keep in public and which to deploy for private cloud infrastructure



#### Comparing Cloud Models 

| Public Cloud                                                 | Private Cloud                                                | Hybrid Cloud                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| No CapEx to scale up                                         | Organizations have complete control over resources and security | Provides the most flexibility                                |
| Quickly provision and deprovision of applications            | Data is not allocated with other organization's data         | Organizations determine where to run their apps              |
| Organizations pay only for what they use                     | Requires hardware purchase for startup and maintenance       | Organizations control security, compliance or legal requirements |
| Don't allow complete control over resources and security to the organization | Organizations are responsible for hardware maintenance and updates |                                                              |



## Multi-cloud

- The use of Multi public cloud providers. Management of resources and security happens in both environments
- Common when there's a need for different features present with different providers
- Common wen in the middle of the migrating to different cloud provider process

## Azure Arc

- Set of technologies for cloud environment management
- Manages cloud environments, no matter the model. Ex.: Public cloud on Azure, private cloud in datacenter, hybrid configuration, multi-cloud environment running on multiple cloud providers at once

## Azure VMware Solution

- Solution that enables VMware workload run in Azure, with seamless (no gaps, no issues) integration and scalability.
- Common use when there's an established VMware in private cloud environment and there's a need to migrate to public or hybrid cloud.
