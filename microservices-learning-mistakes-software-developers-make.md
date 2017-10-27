# _Chapter 03_

# Microservices Learning Mistakes Software Developers make

When we are learning a new technology or tool we always rely on we already know or experienced in our past projects. However, we ended up assuming too many things \(mostly wrong ones\) specially when we are learning one of the most important and recent topics of our industry: **Microservices**.

Here we’ll highlight the 05 main mistakes professionals do when they are learning the Microservices subject.

So let’s get started.

## Mistake \#01 – To confuse SOA and Microservices as the same or similar things

Although both SOA and Microservices are architecture styles \(_architecture style is a formal notation to explain how an software application is assembled and its implications_\) this two variations has a lot of differences:

### SOA

* It’s approach is to connect existing applications via a single instance, the ESB, via disparated protocols
* The connection and message delivery between the endpoints must be \_orchestrated \_within the ESB
* The service that is exposed in the ESB should be written in a specific language and follow mostly SOAP protocol \(with or without WS\* stack\) or REST, via HTTP protocol
* Costly when have a huge payload to exchange between the parties due to the phases of marshalling and unmarshalling
* Vertically Scalable \(_scale-up_\)
* ESB as a single point of failure
* Harder to deploy in comparison to MSA due to dependencies of the application endpoint and ESB mediation itself
* Services are registered in advance to the execution and consumption of its contract by other Services

### Microservices

* It’s approach is to create a single application, autosufficient, that can run in an isolated environment, with its own database
* The connection between the services are _choreographed –_ this way the Microservice can respond to a specific event received
* The Microservice can be written in any programming language available for the creation of services \(Java. Python, JavaScript, .NET\)
* Follows only REST conventions. Can use binary protocols such as Google Protobuf, Twitter Finagle.
* Corresponds to a functional feature of our current Monolith system
* Fault-tolerant
* Horizontally Scalable \(_scale-out_\)
* Easy to deploy, with CD/CI in place
* Microservices register themselves in a entity called API Gateway and are automatically discovered by other Microservices

## Mistake \#02 – “If I use REST, I already have Microservices” approach

In the MSA, the REST approach is only one of the main attributes of MSA. For an application to be labeled as a _Microservice solution_ one should have all characteristics described by the 12-factor methodology.

Besides any level of maturity with REST should suffice. For more information on RMM with REST, read **Chapter 02**.

## Mistake \#03 – Microservices can run on the same container. No problem, right?

Yes. Unfortunately it’s a problem.

Microservices should:

* run totally isolated in its environment with all needed resources in hand \(_loosely coupled_\)
* be able to be scaled independently
* be able to be deployed independently, in it’s own CD/CI to accelerate the answer for changes in a specific funcional feature
* be able to be traced
* be able to be discovered by other Microservices automatically

These are necessary to maintain the right scalability, fault-tolerance and TTM \(_Time-to-Market_\) in place.

## Mistake \#04 – All Microservices should be written in the same programming language

Once the Microservices run on different containers and exposes known contracts that abstracts it’s underlying technology, there’s no need to implement all Microservices in one specific programming language.

With this in mind you could have smaller teams, each one with a specific expertise of business funcionality plus programming language to ease the evolution of the business solution as a whole, independently.

## Mistake \#05 – Microservices as it name implies, should be small

The _Micro_ in Microservices represents the business functionality that exists today in the _Monolith application_ as are called all solutions that have several functional concerns of a huge _business problem_ to solve.

This _business problem_ then is splitted in smaller pieces \(_the Microservices themselves_\) to easy compose and respond effectively to all request and business demands that may arise on the way, in all business transactions.

## Conclusion

Now that you know what not to do and are eager for more information on the Microservices topic, stay tuned for other concepts and discussions we bring to you in this blog, such as Microservices testing, Design Patterns, Architecture Design and Programming implementation for Microservices, Servleless Architecture and many more.

