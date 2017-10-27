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



