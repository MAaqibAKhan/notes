# Cloud enabling technologies

In this module you will learn what technologies allow cloud services to work.

## Fast wide area networks

In order to get the location-independence of the cloud, you need a fast wide-area network. Otherwise the users and the 
servers all need to be physically close, or connected by a dedicated network.

With a fast, wide-area network, we can support users in many different locations, and we can support high-availability 
and disaster recovery solutions that would previously have been unworkable.

## Powerful, inexpensive server computers

In order to get the pool of interchangeable resources required by a cloud, we need to be able to buy lots of servers 
and configurable them, and they need to be reasonably powerful.

Building a data centre is a specialist skill, and there are standards and bodies of knowledge related to it.

Data centres are becoming increasingly efficient and cheap, to the extent that it is possible to get a containerised 
`modular data centre` shipped to you.

When choosing a cloud provider, they will probably be able to document the standards
to which their data centre adheres.

TIA-942 and Uptime Institute are the two best-known examples.

## Benefits of virtualization

Benefits can include:
* Elasticity/scalability
* Resource pooling on common infrastructure
* More efficient use of physical resources
* Granularity of monitoring and pricing
* No leakage of data from one guest to another

`Noisy neighbours` – one guest using all the bandwidth/CPU/etc and the servers all need to be physically close, or 
connected by a dedicated network.

## Virtualization VS Multi-Tenanting

Virtualisation is a type of multi-tenanting, in that it allows multiple users to share a single physical resource. It 
does this by separating the users at the hypervisor level.
* Namely, every customer has their own virtual machine, from the OS up

However, when we use the term multi-tenanting, we usually use it to refer to application-level separation of users 
within a single virtual machine.
* The virtual machine is hared by many customers
* Isolation is enforced by the application

Software-as-a-service is frequently multi-tenant, for Cloud services such as Gmail
* `My webmail provider almost certainly uses virtualisation, but when I log on, I
  don’t get a virtual machine all to myself. Instead, the application prevents me
  from seeing other users email`
  
## Containers
