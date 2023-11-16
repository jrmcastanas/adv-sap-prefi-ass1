## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
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
