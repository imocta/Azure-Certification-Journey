# Describe the benefits of high availability and scalability in the cloud

Availability(uptime) and Scalability(ability to handle demand) are two of the biggest considerations in building or deploying cloud applications.



## High Availability

High availability is important for IT resources (deploying apps, services, etc) use. It focus on maximum availability, availability at all possible times, disregarding even disruptions or types of events.

When architecting solutions, it's required to take service availability into consideration, guarantees are required. Guarantees in service availability are part of the SLAs (service-level agreements).

##### Azure SLAs *[video2m32s]*

- A SLA is a common industry term. 
- Azure SLA are represented as a percentage related to the service or application availability
- Availability is known as Up Time.
- Beyond Up Time%, there are also Down Time% and Credit, that entitles the user if the SLA is unmet
- 100% Up Time is hard to provide, due the time in services maintenance, upgrades, duplicating components, backup components with 0 interruption. That is the reason for SLAs 99%, 99.9%, 99.95%, etc., to exist and be more common. 
- There is big differences in each UpTime percentage. Ex.: 99% can be unavailable for 1.68hrs per week, 7.2hrs per month. 
- Down Time counting is cumulative, can be added up over time. **99.9%**  availability has 10m DownTime per week, 43.2m per month.
- Each Azure Service has its own SLA



## Scalability

Scalability is a major benefit of Cloud Computing. It's the scalability of cloud resources, the ability to adjust resources to meet demand.
In situations like peak traffic and overwhelmed systems, scalability means adding more resources to handle the increased demand.

The Pay as you go consumption-based model is another benefit of scalability.
It allows not overpaying for services, reducing the costs if demands drops off, reducing resources use will reduce costs.

Scaling resources generally have two varieties: *Horizontal* and *Vertical*.
Vertical scaling focus *increasing* or *decreasing* resource capability.
Horizontal scaling focus on adding or subtracting the number of resources.

*Horizontal Scaling -* *Increase/Decrease number of resources. A matter of quantity, in numbers*

*Vertical Scaling - Increase/Decrease capability of resource. A matter of service capacity*

##### Vertical scaling

An example of Virtual Scaling is developing an app and need more processing power. Vertically scaling up to add more CPUs or RAM to the virtual machine. 
In the situation where it's realized there was an over-specification of needs, it's possible to vertically scale down by lowering CPU or RAM specifications.

##### Horizontal scaling

If sudden spike in demand is experience, with horizontal scaling the deployed resource could be scaled out (both manually or automatically).
An example of this is adding an additional virtual machine or container, scaling out. The same goes for significant drops in demand, the deployed resource can be scaled in (automatically or manually), scaling in.