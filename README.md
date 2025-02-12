# Microservices Architecture

- Name = Aldika Fama Reynanda 
- Class = B4CC 

# What are Microservices ?
Microservice are small business services that can work together and can be deployed autonomously / independently. These services communicate with each other by talking over the network and bring many advantages with them. One of the biggest advantages is that they can be deployed independently. However, it offers the opportunity to work with many different technologies.

These services are built around business capabilities and independently deployable by fully automated deployment process. There is a minimum of centralized management of these services, which may be written in different programming languages and use different data storage technologies.

So we can say that, Microservices architecture is a cloud native architectural approach in which applications composed of many loosely coupled and independently deployable smaller components.

# Microservices;

- have their own technology stack, included the database and data management model;
- communicate to each other over a combination of REST APIs, event streaming, and message brokers;
- are organized by business capability, with the line separating services often referred to as a bounded context.

# Microservices Characteristics
Microservices are small, independent, and loosely coupled. A single small team of developers can write and maintain a service. Each service is a separate codebase, which can be managed by a small development team.

**Services** can be deployed independently. A team can update an existing service without rebuilding and redeploying the entire application. Services are responsible for persisting their own data or external state. This differs from the traditional model, where a separate data layer handles data persistence.

Services communicate with each other by using well-defined APIs. Internal implementation details of each service are hidden from other services. Services don’t need to share the same technology stack, libraries, or frameworks.

During the article, we are going to refer to these microservices characteristics when we develop our reference application.

Again if we referring the Martin Fowler article, There are some common characteristics for microservices architectures that fit the label.
Martin Fowler explain these characteristics at below captions;

**Componentization via Services****
Component is a unit of software that is independently replaceable and upgradeable.

**Organized around Business Capabilities**
The microservice approach to division is splitting up into services organized by business capability.

**Products not Projects**
This is Amazon’s notion of “you build, you run it” where a development team takes full responsibility for the software in production.

**Smart endpoints and dumb pipes**
Microservices aim to be as decoupled and as cohesive as possible, so they own their own domain logic and receiving a request, applying logic and producing a response with using restful apis.

**Decentralized Governance**
Netflix is a good example of an organization that follows this philosophy. Sharing useful and all tested code as libraries encourages other developers to solve similar problems in similar ways.

**Decentralized Data Management**
Microservices also decentralize data storage decisions. We can say this approach as a Polyglot Persistence or Polyglot Databases. That means Microservices prefer letting each service manage its own database, either different instances of the same database technology, or entirely different database systems.

**Infrastructure Automation**
That means automate deployment to each new environment and for every microservices with separately.

**Design for failure**
Microservices design by dealing failures and try to manage failures with managing errors with proper actions.