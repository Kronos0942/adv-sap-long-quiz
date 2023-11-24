## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- Service Oriented Architecture is structural approach where softwares are developed as reusable components that represents as a service where each services execute a certain business function.
2. List and discuss the characteristics of SOA.
- Standardized Service Contracts = agreements guaranteeing a service is using the standardized policy in order to be reusable and avoid incompatibility with other services.
- Loose Coupling = services are designed to be independent so that other services will not be affected whenever changes happen to one service.
- Abstraction = the logic and other complex details of services are hidden from consumers.
- Service Reusability = services use different logics from one another so that they can be reusable and avoid being duplicates of other services.
- Autonomy = services should be handling/controlling their own functions by themselves without any outside influences from other services.
- Statelessness = services don't store past information making them ideal for reuse and scalability.
- Discoverability = services should be discoverable so that they can be implemented.
- Composability = services are able to break down problems to smaller ones in order for them to efficiently deal with each problem.
- Interoperability = different kinds of technologies are able to use services since they use common standards that make them useable without encountering incompatibility issues.
3. Define Microservices.
- Microservices are just like services, they are individual reusable components but they are typically used in creating individual applications for scalability.
4. List and discuss the benefits of using Microservices.
- Independently deployable = microservices can be easily and takes a short time to be deployed individually since they are smaller and are mostly used for small changes.
- Right tool for the job = microservices are able to fit the needs of many certain tasks especially with how technology is changing all the time, making it easier and less expensive to implement.
- Precise Scaling = microservices can be scaled one by one depending on the size it only requires, making it consume less infrastructure in the process.
5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:
- Services and microservices are both made to be independently provide different functions.
- Services and microservices are both reusable and can be integrated to different technologies.

Differences: 
- Services standardizes how different services are integrated with each other enteprise-wide, while microservices only focuses application-specific.
- Services is integrated in an enteprise scope, while microservices are integrated in an application scope.
- Services share a enterprise service bus for commom communication, while microservices each has its own communication protocol.
- Services uses heterogeneous messaging protocols, while microservices lightweight messaging protocols.
- Services range from small specialized services to enterprise-wide services, while microservices is made up of only highly specialized services.
- Services operates slowly since it takes advantages of sharing, while microservices operates faster since it takes advantage of duplication rather than sharing.
6. Define Web Services.
- Web services are softwares that make use of the internet so that devices are able to communicate with one another using standardized messaging systems.
7. List and discuss the benefits of using Web Services.
- Exposing Existing Functions on the Network = Web services exposes the functions of existing codes in a network once it is called using HTTP requests. When the codes are exposed, your program's functionalities can now be used by other applications/softwares.
- Interoperability = Web services allow different types of services, and softwares/applications to interact and communicate with each other without any incompatibility issues.
- Standardized Protocol = Web services is able to provide consistent and quality usage on different systems since it uses standardized industry-standard protocols.
- Low Cost Communication = Web services can be implemented on low-cost internets and many transport mechanisms since it uses SOAP(Simple Object Access Protocol) over HTTP protocol.
8. List and discuss the characteristics of Web Services.
- XML-Based = Web services use XML(Extensible Markup Language) for data exchange and data representation. Since XML is versatile, it allows web services to be operatble on different systems/devices.
- Loosely Coupled = In web services, any change to a component does not affect other components since consumers and web services aren't tied to one another directly.
- Coarse-Grained = Web services are able to provide a good amount of functionality on large components since it is coarse-grained.
- Ability To Be Synchronous Or Asynchronous = Web services are able to be both synchronouse and asynchronous because of its flexibility. Allowing many different kinds of operations.
- Supports Remote Procedure Calls = Using web services, clients are able to call different functions and procedure on remote objects since it is XML-based.
- Support Document Exchange = Web services allow the transfering and exchanging of data between system/devices for business integration due to XML representing data in a generic way.
9. List and discuss the distinct roles in Web Services Architecture.
- Provider = This role is the one responsible for creating and deploying web services, and allowing clients the usage of it.
- Requestor = This role is also known as the consumer since they are the ones looking for desired functions by requesting services.
- Broker =  This role acts as a middleman for the provider and requestor. If a requestor finds a specific function, a broker is the one responsible to find it and bind it to the provider.
10. List and discuss the Web Services Components.
- SOAP(Simple Object Access Protocol) = This component of web services allow the transferring and exchanging of data between devices and applications.
- WSDL(Web Services Description Language) = This component of web services is the one responsible for describing web services. It is also the one that navigates for the consumer so that they can access the service.
- UDDI(Universal Description, Discovery and Integration) = This component of web services is the one responsible for the describing, publishing, and searching of a web service.