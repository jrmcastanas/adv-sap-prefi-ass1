## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).

SOA is a way of making software by using existing pieces or services that can be used again for different apps. It also lets different systems or apps talk to each other through a common interface.

2. List and discuss the characteristics of SOA.

Standardized Service Contracts - This is a rule we follow when we make services so that they can work well with other services in the same group. The contracts also tell us what the service can do and what it wants from us.

Loose Coupling - This is a way of making services independent from each other, so that they can change without messing up the users who rely on them.

Abstraction - This is a way of hiding the technical details of a service and focusing on the business process it supports. This makes the service more flexible and adaptable.

Reusability - This is a way of avoiding doing the same thing twice and wasting resources by using existing services whenever possible, or making new services that can be used for multiple purposes.

Autonomy - This is a way of giving services the power and control to make their own decisions, without needing permission or interference from others.

Statelessness - This is a way of reducing the amount of information a service needs to remember or store, so that it can work better and faster.

Discoverability - This is a way of making services easy to find and understand by providing metadata that describes their purpose and capabilities to humans and systems.

Composability - This is a way of solving complex problems by breaking them down into smaller and simpler parts, and using services to combine them.

Interoperability - This is a way of making services compatible and able to share data with each other, by following common standards and protocols.

3. Define Microservices.

Microservices are like SOA, but they are used to make apps that can grow and recover more easily. They are like Lego pieces that can be put together in different ways to make bigger apps. Microservices are small, independent parts that work together through a common interface.

4. List and discuss the benefits of using Microservices.

Independently deployable - This is the main feature of microservices, which means that each service can be deployed separately without affecting the others. The services are small and communicate with each other through networks, and this gives us more options to solve the problems we encounter.

Right tool for job - This is one of the advantages of using microservices, which allows us to use the best tool for each task. Microservices can store and process more data by breaking it into smaller pieces, and each service can use its own language and framework to communicate with the application we want.

Precise Scaling - With microservices, we can deploy and scale each service individually and precisely. This means that we can handle a large number of tasks at the same time, and do it efficiently and accurately.

5. List and discuss the similarities and differences of SOA and Microservices.

Similarities Reuse - Both SOA and Microservices try to avoid making new services when there are already ones that can be used again. SOA looks for available services, while Microservices copy and paste code and don’t mind having the same data.

Synchronous calls - Both SOA and Microservices use synchronous protocols to make their services available across the enterprise. But, Microservices only use synchronous calls when they need to wait for another service’s answer before moving on.

Data duplication - Both SOA and Microservices have collections of services that do specific things. They also have to deal with complex data synchronization patterns because of data duplication.

Differences between SOA and Microservices

Communication - SOA uses an Enterprise Service Bus (ESB) to handle communication between services, but this can be a problem for the whole enterprise if one service slows down. Microservices use simpler messaging systems like APIs that enable faster communication and are developed independently with their own communication protocols.

Interoperability - SOA sets standards for services to share data and make sure that they don’t get reduced. Interoperability means the ability of different software programs to exchange data. Microservices can also exchange and use information across systems, but they have more freedom and autonomy.

Service granularity - Microservices have very specialized services that do one thing only, while SOA services can range from small and specialized to enterprise-wide and general.

Speed - SOA makes development and troubleshooting easier, but it also makes SOA work more slowly than Microservices. Microservices let developers work on small and independent parts of an app that can be quickly deployed and tested without affecting the rest of the app.

