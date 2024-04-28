---
author: Miah, Md Shahjahan
date: "2024-04-27T01:00:00Z"
published: true
status: publish
images: ['/assets/understanding-distributed-system.png']
tags:
- distributedsystem
- microservice
title: Understanding Distributed System
---

![](/assets/understanding-distributed-system.png)

## Preface
Most engineering books or blogs deep dive right into the heart of some complex topics around distributed systems which can overwhelm you, if you are not experienced enough. A common recommendation is Martin Kleppmann's Designing Data-Intensive Applications, but its concepts may be too advanced for someone new to distributed systms. Even seasoned professionals can find very complex such as consistency models and distributed transactions algorithms.

However, this article, along with its sub-articles on distributed systems, will give you a complete and solid understanding of distributed system. While I am writing this article, I am quite experienced at scalable systems.

## What information is necessary to understand?
Almost the exact order we follow when creating a new distributed application. This article will be structed with five sections to understand the complete life cycle of distributed sytems ordering with considering one of the most interesting books I have found on this topic is Understanding Distributed Systems.

- Communication
- Coordination
- Scalability
- Resiliency
- Maintainability

### Communication

Commucation is important to understanding how distributed systems work or why they are even needed at a basic level. They are essentially separated nodes that are responsible for sharing information over the network. It's essential to understand the mechanics of network communication, including the concept of a network stack and its operations at each level. With this understanding, we can begin constructing systems that effectively communicate over networks.

### Coordination
As we expand our system with additional nodes, coordinating communication becomes essential. In this segment, I'll detail methods for detecting failures within our system, managing replications, and implementing algorithms for selecting primary nodes, including various consensus algorithms.

### Scalability
When we are able to coordinate well over communication, it comes now to think how we can perform transactions over a distributed system. This is arguably the most important part of building distributed system to handle scale. I will explain how pattern works to achieving scalability like microservices, apis, messaging, partioning, replication, caching, and load balancing.

### Resiliency
A distributed system that can handle scale but is unreliable is not any good. That's why understanding resiliency in distributed system is very important. We need to understand the ins and outs of distributed systems like single points of failures, circuit breakers, retry patterns, rate limiting. Basically what I refer to as understanding downstream and upstream resiliency of distributed systems. We also need to consider database separation in distributed systems and integrating multiple databases seamlessly in distributed systems, and much more if necessary to make it resilient.

### Maintainability
Maintaining a robust distributed system poses significant challenges. It requires comprehensive testing such as load and stress testing, chaos engineering and operational procedures, covering various testing methods specific to distributed systems. Additionally, it involves understanding continuous integration and delivery practices, along with implementing crucial monitoring mechanisms essential for distributed applications.

## Conclusion
To sum up, I aim to offer sufficient insight into distributed systems, providing a solid understanding and a foundation for further exploration in the field. Additionally, I'll periodically include complete coding examples with system architecture and a GitHub link, utilizing a modern programming language and its associated datastore.
Keep an eye out for updates!

> NOTE: I'm constantly delighted to receive feedback. Whether you spot an error, have a suggestion for improvement, or just want to share your thoughts, please don't hesitate to comment/reach out. I truly value connecting with readers!