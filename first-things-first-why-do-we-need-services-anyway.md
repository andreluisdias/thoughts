# _Chapter 01_

# First things First - Why do we need Services anyway?

_For many years we have been creating and designing new solutions_ with _the services_ approach to address several known problems, such as:

## **a\) Business Layer**

The business layer should have restricted access due to security and simplification reasons. Security because it should be access contained, via a simple interface that should expose only the rules or business funcionalities needed for the system as a whole.

Simplification because once we have only one point of access we should standardize its access and content, via a well defined service interface.

## **b\) Interoperability**

Once we have a well defined Service interface, then we should run this service anywhere, abstracting to the clients all the systems and platforms internals. The service protocol and data model is known in advance.

## **c\) Client Agnostic**

The service should not care about the client which is calling it. The main role of the service is to respect its contract and deliver the message seamlessly.

## **d\) Decoupling**

With the business rules and interfaces in place, we should have natural business boundaries fostering the decoupling of funcionalities and business rules associated with it, delivering each service as a single business unit, adding value to its final customers and clients.

## **e\) Time to Market**

Once the services are well segmented, its easier to evolve them giving the company more flexibility and velocity at the client’s pace, faster and faster each time.

## f\) Business Agility

Once we could create services in an easy way, we could get some level of agility to maintain the necessary velocity to business needs.

---

All of the topics above are some of the most important ones that we have faced so far in our software career, in our software projects.

But, back in 2017…

With the adoption and growth of **Microservices** mostly by big companies, this way of thinking, this architectural approach should be here to stay and, at the same time, bring more complexity to the final solutions due to new problems and challenges that arouse from this new Architecture Style.

Today we have to understand not only the complexity of Business but we also should understand more technologies and tools available today to support the new scalable and business driven decisions made with **Microservices**.

