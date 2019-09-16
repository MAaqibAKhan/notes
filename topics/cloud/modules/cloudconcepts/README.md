# Cloud concepts

In this module you will learn about the concepts of cloud. These concepts are shared among all the cloud providers.

## What is the cloud

The terms ‘cloud computing’ and ‘the cloud’ have been used to describe all kinds of different technology. Are we
talking about Distributed computing? Networked Services? Virtualised Servers or Hosted services? The actual
definition of cloud computing as reported by NIST (National Institute of Standards and Technology) is: `Cloud computing 
is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing 
resources (e.g. networks, servers, storage, applications, and services) that can be rapidly provisioned and released 
with minimal management effort or service provider interaction`

## On demand self service

All cloud providers have a dashboard through which the customers can control the services that the provider offers. 
Hence the name `on demand self service`.

This is how it looks for Google cloud:
![Fork >](https://imgur.com/lwJQt2C.png)
This is how it looks for AWS:
![Fork >](https://imgur.com/cnqjq2M.png)
This is how it looks for Azure:
![Fork >](https://imgur.com/cK3lnGv.png)

## Broad network access

Access over network via *standard mechanisms* which would generally be taken to mean standard protocols like HTTP or 
TCP. Services should be accessible to a variety of clients running on various hardware (phones, laptops, desktops).

In other words, if it’s only accessible using a proprietary protocol or data format, from custom client, it’s probably 
not cloud computing. 

Notice that *network-accessible* is not the same thing as *internet-accessible*; there is no such thing as a private 
cloud on a public network.

## Resource pooling

Cloud services are provided to multiple tenants (users, applications) by a pool of interchangeable resources. If each 
tenant needs its own, specific, customised resources, then it’s not cloud computing. Providing on-demand resources with 
utility pricing can only make economic sense if the resources come from a shared pool.

These resources are dynamically assigned and reassigned in order to get optimal use of out of them. 
* Storage, processing, memory, etc.

**Location independent**
* Customer generally does not know/need to know exact physical location of the resources
* For regulatory and architectural reasons, the customer is generally able to specify a general location (e.g. country)
    * e.g. can this data be stored outside of the EU
    * can the application function well if the web-server is in the EU and the data it uses is in Australia
    
## Rapid elasticity

Elasticity is a fundamental property of the cloud. The ability to use exactly the resources you need, without either 
under-provisioning or excessively over-provisioning, is one of the key benefits of cloud services. Allows the customer 
to scale in and out with demand. 
* **Note**: usually scaling in and out, as opposed to scaling up and down
May even be automatic or transparent to the customer.
![Fork >](https://images.slideplayer.com/20/5990497/slides/slide_12.jpg) <-- IMAGE TO BE REPLACED WITH HUGO ONE

## Measured service

If resources are being dynamically provisioned, it’s essential that the customer should be able to monitor the 
performance and usage of those resources in real time. Most cloud resources are offered on a pay-per-use basis, and the 
customer must be able to monitor their usage in order to control their costs.
