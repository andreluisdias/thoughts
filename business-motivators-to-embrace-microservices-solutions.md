# _Chapter 04_

# Business Motivators to Embrace Microservices Solutions

_Microservices Architecture style is no longer a hype by now._

Big players and several industry movements recently are fostering the focus and then the adoption of this important concept through out a big range of software application solutions, such as:

* Financial Services
* Insurance Services
* IoT Solutions
* Video streaming solutions, such as Netflix
* Social media solutions, such as Twitter
* Logistic solutions, such as Uber

In this article we will highlight the main drivers that are common sense in the industry today in order to you adopt and start working with Microservices from now on:

## Fast Spin to Release New Solutions \(AKA Faster Time to Market\)

Microservices embrace automation.

Once you have a plausible pipeline to package and deliver your Microservices \(CD/CI\) with any automation suite you want or have today, you should be able to obtain the best advantages of this approach since the beginning, since the first Microservices you deliver in Production.

Automation is key if you are planning to expand the number of Microservices in your solution in the future, a normal way to do once you start to break down your currently monolith. It will support the evolution that is inherited with the adoption of this architectural style.

It’s key because you need to assure the delivery quality level in the final product. With proper automation and control, you can achieve the desirable result in a faster way.

## Small Teams, to Code and Deploy \(Team Empowement\)

With the concept of dedicated and powered teams that are responsible for all aspects and codebase of a business context \(and thus a Microservice\), after sometime you should see a natural positive performance in delivering new features and business value for a particular Microservice.

![](https://microservicesradar.files.wordpress.com/2017/10/dedicated-teams.png?w=1140 "dedicated-teams")

##### Microservices can have dedicated Teams for two different Microservices that need to communicate each other

The team’s mindset around that specific business context \(Boundary Context / Domain Driven Design concept\) should evolve naturally due to daily business challenges and demands that occur. It’s normal that their expertise grows more and more each time.

Giving the needed freedom of choice to the team so it can define the best way to deliver the business service required.

The team will embrace the changes and deliver it accordingly.

## Ease of Maintainance

Once you have specific and smaller teams to evolve and admin the Microservices and the segmented codebase per Microservice, the minimum changes you place in the code will not put the whole solution down because of cross reference in compile time or runtime.

You will not have to rebuild the whole solution because you edited a single dependency that is really used in another module. This is past.

Testing should be easier as well \(up to some point\) once you have the specific business scope to test and vaildate.

## Independent Scalability of Components

Microservices run in separated execution units, called containers. Containers deliver all resources needed by services.

For each Microservice, you should have a dedicated container that supports it. That’s why the automation in this case is so important \(not only to package and testing\) but as well to deliver the final product, with all resources that are needed by the service, delivered in the format of a container with the Microservice embedded in it.

Once you deliver the container, you can scale it in a independent way, each container with its only level of scalability, according to the needs of the solution as a whole.

One question that arises in this point is: how can we guarantee for sure when to scale a Microservice. How can we monitor any Microservices so we can scale it appropriately?

The answer to this question remains in the scope of some Design Patterns for Microservices that will be covered in future posts in this channel. Right now you should realize that is natural within the Microservices architecture to address this kind of problem, in a seamlessly way.

## Programming Language Free of Choice

Microservices implementation is flexible.

Each Microservice can be written in a different programming language, just because they run separately and communicate effectively via well defined interfaces over well know protocols.

![](https://microservicesradar.files.wordpress.com/2017/10/programing-language-agnostic.png?w=647&h=369 "programing-language-agnostic")

##### Microservices can be implemented in different programming languages

The most common programming languages/frameworks used today are: [Java](https://docs.oracle.com/javase/8/docs/technotes/guides/language/index.html), [.NET](https://www.microsoft.com/net/), [Go \(Golang\)](https://golang.org), [Java Script/Node.JS](https://nodejs.org/en/) or [Python](https://www.python.org).

This gives flexibility to the solution once you can explore the best approaches and features of each programming language.

## Microservices Should Be Simple

They are made with only one object in mind. Simplicity.

As Einstein said: [_Everything should be made as simple as possible, but no simpler_](https://quoteinvestigator.com/2011/05/13/einstein-simple/)

Of course the simplicity comes with a price. But you should vouch for the Microservices Architecture and design your solutions in it with all the benefits it brings to you. Do the trade-off by yourself and you see the advantages in it.

## Conclusion

Microservices should address a specific business domain and deliver great business value through its well defined and public and API documentation.

In essence, these are today the main drivers that we believe you should considered when you start thinking about a new solution design using the Microservices Architecture \(MSA\) style.

