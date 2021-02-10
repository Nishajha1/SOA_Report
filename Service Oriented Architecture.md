# Service Oriented Architecture
SOA, or service-oriented architecture, defines a way to make software components reusable via service interfaces. These interfaces utilize common communication standards in such a way that they can be rapidly incorporated into new applications without having to perform deep integration each time.


![image](https://miro.medium.com/max/700/1*Xot9nbkQAGbGaYwi84Kh-w.png)


## SOA Principles
* Standard service contract
* Interoperability
* Composablity
* Abstraction
* Discoverability
* Statelessness

## Characteristics Of SOA
There are six core values of SOA:

1.Business value is more important than technical strategy.

2.Strategic goals.

3.Intrinsic inter-operability.

4.Shared services.

5.Flexibility.

6.Evolutionary refinemen

## Elements Of SOA
![image](https://www.w3schools.in/wp-content/uploads/2016/06/SOA.jpg)

1.Application frontends:These are active elements of SOA,delivering the value ofSOA to the end user.
   * They initiate and control all the activity of enterprise system.
   * Web application,application with GUI,or a batch application.

2.Service: a software component that encapsulates a high level business concept.

3.Contract: provides a specification of the purpose, functionality, constraints, and usage of services.

4.Interface: functionality of the service exposed by the service to the clients that are connected to the service.

5.Implementation: the service implementation provides the required business logic and appropriate data. It contains one or more of the artifacts: programs, configuration, data and databases.

6.Business logic: business process represented by the service.

7.Data: data represented in the service/ used by the service.

8.Service repository: it registers the services and their attributes to facilitate the discovery of services; operation, access rights, owner, qualities, etc.

9.(Enterprise) Service Bus (ESB): (from book in slide 3: ref 1): A flexible infrastructure for integrating applications and services by : routing messages, transforming protocols between requestor and service, handling business events and delivering them, providing QoS, mediation and security, and managing the interaction among services.

10.Open standards: publicly available implementable standards 



   
   A service has four properties according to one of many definitions of SOA:

   - It logically represents a business activity with a specified outcome.
    -It is self-contained.
    -It is a black box for its consumers, meaning the consumer does not have to be aware of the service's inner workings.
    -It may consist of other underlying services.

 SOA is a approach for maintaining software systems that are based on distributed computation.SOA is not related to any technology or tool.
Service-oriented architecture integrates distributed, separately maintained and deployed software components. It is enabled by technologies and standards that facilitate components' communication and cooperation over a network, especially over an IP network.

SOA is related to the idea of an application programming interface (API), an interface or communication protocol between different parts of a computer program intended to simplify the implementation and maintenance of software. An API can be thought of as the service, and the SOA the architecture that allows the service to operate.

It is architectural pattern for building software based on loosely coupled service components.SOA separates functions into distinct units, or services, which developers make accessible over a network in order to allow users to combine and reuse them in the production of applications. These services and their corresponding consumers communicate with each other by passing data in a well-defined, shared format, or by coordinating an activity between two or more services.

Each service in an SOA embodies the code and data integrations required to execute a complete, discrete business function (e.g., checking a customer’s credit, calculating a monthly loan payment, or processing a mortgage application). The service interfaces provide loose coupling, meaning they can be called with little or no knowledge of how the integration is implemented underneath. 

# Advantages
* Reusability
*  Maintainability
*  Scalability and Availability
*  Platform Independent
*  Responsiveness and improved TTM.

# Limitations
* Complex Service Management
* Increased Overhaed
* Vendor lock-in
* Upfront Investment

# SOA and The Cloud
SOA architecture is now relatively easy to maintain using cloud solutions.SOA is better implemented and governed using cloud PLatforms.This is achieved by using amazing techologies and advanced services provided by cloud platform such as amazon web services and google cloud platform etc.We can build whole system based on service orientation from top to bottom at all level from Infrastructure to client and service consumers using cloud services.Everything that is possible through the cloud is based on services and service orientation.Cloud Computing and SOA are complementary.Cloud Computing is a broad term ,it works on entire stack from hardware to software, focuses on turning aspects of the computing stack into a Commodity while SOA focuses on turning software capablities into services.
![image](http://verticalhorizons.in/wp-content/uploads/2012/02/Cloud_Computing.png)

# Monolithic Vs SOA Vs Microservices

  Monolithic application acts as a container which is basically hosting a number of software components. It is single unit architecture.There can be a number of software components as a part of sofware application and if they all hosted together and delived together that is called monolithic application.There are various challenges that a software implementing monolithic architecture faces like,they are not flexible i.e. they cannot be build using different technologies,they are unreliable,they are not scalable,development is very slow,they are not fit for complex architecture.
  ## SOA
  SOA helps in breaking down the services or the features into smaller components,Each of these services will have multiple task in them.It is coarse grained architecture.
  
  ## Microservices
  Microservices is based on fine-grained architecture.There are multiple tasks and multiple services in microservices architecture. It is decentralised governing architecture .In microservices we have only functional and infrastructure services.Functional service is basically a combination of business service and enterprise service and an application service. Infrastructure service does all the non-business or non-technical operations like security,auditing,logging. 
  
   ![image](https://miro.medium.com/max/672/1*qAFyYAQSE3e-flZSqprHlg.jpeg)
  
# Considerations 
* Dependence on the network
* Stateless Vs Stateful Services
* Versioning
* Security



