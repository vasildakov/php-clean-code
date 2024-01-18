# Architectural pattern

An architectural pattern is a general, reusable resolution to a commonly occurring problem in software architecture within a given context.[1] The architectural patterns address various issues in software engineering, such as computer hardware performance limitations, high availability and minimization of a business risk. Some architectural patterns have been implemented within software frameworks.

The use of the word "pattern" in the software industry was influenced by similar concepts as expressed in traditional architecture, such as Christopher Alexander's A Pattern Language (1977) which discussed the practice in terms of establishing a pattern lexicon, prompting the practitioners of computer science to contemplate their own design lexicon.

---

## Command Query Responsibility Segregation (CQRS)

In information technology, Command Query Responsibility Segregation (CQRS) is a system architecture that extends the idea behind command–query separation to the level of services.[1][2] Such a system will have separate interfaces to send queries and to send commands. As in CQS, fulfilling a query request will only retrieve data and will not modify the state of the system (with some exceptions like logging access), while fulfilling a command request will modify the state of the system.

Many systems push the segregation to the data models used by the system. The models used to process queries are usually called read models and the models used to process commands write models.

---

## Event-driven architecture
An event-driven architecture uses events to trigger and communicate between decoupled services and is common in modern applications built with microservices. An event is a change in state, or an update, like an item being placed in a shopping cart on an e-commerce website. Events can either carry the state (the item purchased, its price, and a delivery address) or events can be identifiers (a notification that an order was shipped).

Event-driven architectures have three key components: event producers, event routers, and event consumers. A producer publishes an event to the router, which filters and pushes the events to consumers. Producer services and consumer services are decoupled, which allows them to be scaled, updated, and deployed independently.

---

## Layers
In software engineering, multitier architecture (often referred to as n-tier architecture) is a client–server architecture in which presentation, application processing and data management functions are physically separated. The most widespread use of multitier architecture is the three-tier architecture.

N-tier application architecture provides a model by which developers can create flexible and reusable applications. By segregating an application into tiers, developers acquire the option of modifying or adding a specific tier, instead of reworking the entire application. A three-tier architecture is typically composed of a presentation tier, a logic tier, and a data tier.

---

## Hexagonal architecture

The hexagonal architecture, or ports and adapters architecture, is an architectural pattern used in software design. It aims at creating loosely coupled application components that can be easily connected to their software environment by means of ports and adapters. This makes components exchangeable at any level and facilitates test automation.[1]

The hexagonal architecture was invented by Alistair Cockburn in an attempt to avoid known structural pitfalls in object-oriented software design, such as undesired dependencies between layers and contamination of user interface code with business logic, and published in 2005.[2]

The term "hexagonal" comes from the graphical conventions that shows the application component like a hexagonal cell. The purpose was not to suggest that there would be six borders/ports, but to leave enough space to represent the different interfaces needed between the component and the external world.[1]

---

## Microservices

In software engineering, a microservice architecture is a variant of the service-oriented architecture structural style. It is an architectural pattern that arranges an application as a collection of loosely coupled, fine-grained services, communicating through lightweight protocols. One of its goals is that teams can develop and deploy their services independently of others. This is achieved by the reduction of several dependencies in the code base, allowing developers to evolve their services with limited restrictions from users, and for additional complexity to be hidden from users.[1] As a consequence, organizations are able to develop software with fast growth and size, as well as use off-the-shelf services more easily. Communication requirements are reduced. These benefits come at a cost to maintaining the decoupling. Interfaces need to be designed carefully and treated as a public API. One technique that is used is having multiple interfaces on the same service, or multiple versions of the same service, so as to not disrupt existing users of the code.

---

## Multitier architecture

In software engineering, multitier architecture (often referred to as n-tier architecture) is a client–server architecture in which presentation, application processing and data management functions are physically separated. The most widespread use of multitier architecture is the three-tier architecture.

N-tier application architecture provides a model by which developers can create flexible and reusable applications. By segregating an application into tiers, developers acquire the option of modifying or adding a specific tier, instead of reworking the entire application. A three-tier architecture is typically composed of a presentation tier, a logic tier, and a data tier.

---

## Service-oriented architecture

In software engineering, service-oriented architecture (SOA) is an architectural style that focuses on discrete services instead of a monolithic design.[1] By consequence, it is also applied in the field of software design where services are provided to the other components by application components, through a communication protocol over a network. A service is a discrete unit of functionality that can be accessed remotely and acted upon and updated independently, such as retrieving a credit card statement online. SOA is also intended to be independent of vendors, products and technologies.[2]

--- 

## Model–View–Controller

Model–view–controller (MVC) is a software design pattern[1] commonly used for developing user interfaces that divides the related program logic into three interconnected elements. These elements are the internal representations of information (the model), the interface (the view) that presents information to and accepts it from the user, and the controller software linking the two.[2][3]

Traditionally used for desktop graphical user interfaces (GUIs), this pattern became popular for designing web applications.[4] Popular programming languages have MVC frameworks that facilitate the implementation of the pattern.