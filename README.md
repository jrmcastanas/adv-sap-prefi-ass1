## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service Oriented Architecture is an Enterprise-Wide software development technique that utilizes reusable components called services.
Each service are self contained modules that perform specific functions, allowing for mixing and matching of components in order to build applications.
In short, SOA is an architecture that connects and matches different services to produce new applications, similar to how Lego builds structures using pre-defined bricks.
2. List and discuss the characteristics of SOA.
-Standardized Service Contracts:
Each service module follows a service description which dictates what the service is for and what it can and cannot do.
-Loose Coupling:
The services must be independent or at least have minimal dependencies with each other. Ensuring that each module is usable on its own.
-Abstraction:
The nitty and gritty details of the services are hidden or "abstracted" from public view ensuring that how the service works remains a mystery for security purposes.
-Service Reusability:
Each service must be reusable, meaning that the components can be extracted and mixed and matched with different modules without sacrificing on functionality.
-Autonomy:
Each service is self governing, having full control on its functions independently. In short, the service is isolated.
-Statelessness:
The service must be stateless, and not hold/keep a specific stated of being. Meaning, that each service should always be a blank slate.
-Discoverability:
Services are discoverable/findable. Meaning that the user can search for the services using the registry or via its metadata.
-Composability:
Each service must breakdown large problems into smaller ones. Being efficient in individual execution, exhibiting a divide and conquer strategy.
-Interoperability:
Each service must be interoperable not just focusing on one subscriber but allow a multitude of them to utilize the service.
3. Define Microservices.
- Microservices are similar to SOA but differ in scope as microservices operate on a smaller scale. 
Typically focusing on an individual application, and use a cloud native architectural approach.
Still Microservices builds individual applications using smaller services, just on a smaller scale. 
4. List and discuss the benefits of using Microservices.
-Independently Deployable:
Microservices are ready to use/deploy without the need to rely on other services as it is independently functioning on its own.
-Right Tool For The Job:
Being independent means that each module can be specialized to a specific task or problem. 
-Precise Scaling:
Since it is made up of smaller services scaling is fine tuned as services can be added based on necessity.
5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:
-Made up of Services:
Both SOA and Microservices use services as components in order to create applications.
-Loose Coupling:
Both SOA and Microservices push for independence between services.
Differences:
-Scope:
SOA is enterprise-wide while Microservices is application specific. In layman's term SOA is broader in scope while Microservices is on a smaller scale hence why it is "micro".
-Way of Reusing:
SOA Reuse the integrations themselves resulting in pure reusing, while in Microservices reusing is done via copying of code and data duplication.
-Synchronous Calls:
SOA utilize synchronous protocols since it is available throughout the entire enterprise, while Microservices use asynchronous communication.
Data Duplication:
As stated previously SOA is synchronous meaning that no data is duplicated and changes are made at the source, while Microservices specifically pushes duplication in order to maintain indipendence.
-Communication:
Each service is entirely independent in Microservices, in SOA on the otherhand, there must be a common communication protocol.
-Interoperability:
Microservices focus and strictly adheres to lightweight messaging protocols, while SOA is more loose and use heterogenous messaging protocols.
-Service granularity:
Microservices as stated before is highly specialized, while SOA is more of a mixed bag having specialized, small, and enterprise-wide services.
-Speed:
Microservices tend to operate at a much quicker rate compared to SOA.