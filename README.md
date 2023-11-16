## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- Service-Oriented Architecture (SOA) is a technique, method, or approach used in an enterprise to fully utilize software components called services. This is done by combining services in such a way that they can function as one to create and perform a defined business process, function, or application. These services can communicate with each other even across different platforms and systems using standard communication protocols, which ensures their reusability.

2. List and discuss the characteristics of SOA.
- Standardized Service Contracts: It has a standardized service contract that requires proper adherence. This results in service contracts being expressed more formally since they follow a certain standard.
- Loose Coupling: Services in SOA are independent of each other, or at least are made to be less dependent on each other. It reduces the risk of services being too associated with each other that when changes are applied in a service, the associated service(s) are noticeably affected, be it in terms of performance or other affection that could result negatively between the relationships of services.
- Abstraction: It hides the details of a service and the logic behind it, making it inaccessible from the outside world. Making the use of services more secure, confidential, and safe to use within the organization only.
- Service Reusability: Each service has a different logic in it; it is divided into specific and unique logics, making them easy to reuse and combine with other services, which ensures efficiency and consistency.
- Autonomy: Services have authority over their own logic, giving them the ability to perform their logic despite influences from other services. For it to work, services must have more isolation and be more reliable and predictable.
- Statelessness: Stateless services are more ideal because they save on the consumption of resources by separating the services from their state, making them able to handle processes more reliably.
- Discoverability: Services are usually stored in a service registry, making them easier to find or discover. Service contracts contain accurate metadata for discovery, which also contains purposes and capabilities comprehensible to humans.
- Composability: Services are composable in that they can be combined and assembled in various ways to create a specific business process. It is made to be worked with in many ways to ensure flexibility.
- Interoperability: Services are operable across different platforms and systems because they communicate using standard communication protocols. Making it possible for them to work together easily.

3. Define Microservices.
- Microservices architectures are like SOAs; they contain services, but they are also called microservices that are also loosely coupled, reusable, and specialized components. Microservices are mainly made to create individual applications composed of independently deployable smaller components or services (microservices). Furthermore, microservices are cloud-native, making them more accessible to the team.

4. List and discuss the benefits of using Microservices.
- Independently Deployable: Each application created using microservices is composed of smaller pieces of components that can easily be utilized to fix something in the application, create small changes in a short amount of time, and more. This could be possible because an organization can assign teams to each service or set of services that are cross-functional and operable in an agile fashion.
- Right Tool for the Job: Applications composed of smaller parts or services are always easier and more desirable to update, upgrade, or modify than a single large application. It is also cost-efficient since it is easier to maintain.
- Precise Scaling: Its scale is controllable because services can be deployed individually. The organization has control over which services they are going to deploy for an individual application

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:
- Both contain loosely coupled, reusable, and specialized components.
- Both are architectural methods that help with the optimization and utilization of applications.
- Reusability, scalability, flexibility, and agility are common principles in these architectures.
- Both aim to reduce dependence between services.
Differences:
- The main difference is that SOA is used enterprise-wide, while microservices are application-specific. This makes SOA appear to be larger and more complex than microservices.
- Deployment in SOA may not be as independent as in microservices. SOA mostly deploys sets of components or services, while microservices are designed to deploy components independently.
- SOA tends to be more impactful because of its enterprise-wide scope than microservices.
- Communication: Microservices has its own communication protocol for its services, while SOA requires each service to share a common communication system (ESB).
- Interoperability: SOAs focus more on heterogeneous or standardized messaging protocols, while microservices often make things simpler by using lightweight messaging protocols.
- Service Granularity: SOA services can range from small to enterprise-wide services or components, while microservices mainly focus on small but highly specialized services designed to have a singular function.
- Speed: While SOAs development is more simplified, microservices architectures favor duplication rather than mainly sharing, which makes microservices architectures operate faster.

