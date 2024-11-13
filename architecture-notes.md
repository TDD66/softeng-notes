# Micro-service

Positives:
- Teams working in seperate code bases so they can deploy whenever they're ready.
- Easy to scale up.
- Services communicate each other using defined interfaces which gives a good layer of abstraction (one service will not need to care about the internals of another service).
- Services are generally reusable as they are written with decoupled interfaces.

Negatives:
- Increased organisational complexity and overhead (more people needed to manage the projects different teams are doing).
- Increased testing complexity.
- Increased security complexity.
- Teams can end up duplicating necessary resources, like databases.

![diagram of microservices architecture](https://juniper-prod.scene7.com/is/image/junipernetworks/dgm-1200x625-microsvcs-cloud-architecture-2X-11AUG23?fmt=png8-alpha&wid=2400&dpr=off)

Microservice architecture is useful when you have a product/service that is rapidly growing.

## Comparision with Monolithic Architecture
In monolithic architectures, all processes and services are tightly coupled and run as a single service. If one process of the app spikes in demand, the entire architecture must scale. 

In this aspect microservices are superior because since services are decoupled when one service increases in demand only that service needs to scale.

However, monolithic structures are easier to deploy and debug because everything is in a single code base.