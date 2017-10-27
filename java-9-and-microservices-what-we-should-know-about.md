# _Chapter 05_

# Java 9 and Microservices - What we should know about

_Here we highlights the most important features added for new Java version and their applicability to create excellent Microservices solutions with Java 9._

Some weeks ago the newest Java version was officially released. During the most important event promoted by Oracle, at JavaOne all new Java features and other topics were presented to the communities and enterprises, in order to foster the usage and exploration of the new capabilities added to it.

Below we selected some of those features that could help the implementation of Microservices solutions, with the advent of newer containers and other language approaches that could bring quality and accelerate the development and performance of this distributed systems.

So, let’s get started…

This article highlights the most important features added for new Java version and their applicability to create excellent Microservices solutions with Java 9.

Some weeks ago the newest Java version was officially released. During the most important event promoted by Oracle, at JavaOne all new Java features and other topics were presented to the communities and enterprises, in order to foster the usage and exploration of the new capabilities added to it.

Below we selected some of those features that could help the implementation of Microservices solutions, with the advent of newer containers and other language approaches that could bring quality and accelerate the development and performance of this distributed systems.

So, let’s get started…

## REPL – JShell \(JEP 222\)

REPL stands for Read-Eval-Print-Loop. The purpose of this is to accomplish easy test tasks in a specific codebase part, without the need to deploy the whole solution and then debug the desired source code.

In the new Java version, this approach was incorporated within the JDK, by the name of [JShell \(JEP 222\)](http://openjdk.java.net/jeps/222). The good part is that now we can test your Microservices without the need to deploy them over and over, accelerating the development, evolution and quality of the final components.

## Concurrency Updates \(JEP 266\)

This interesting feature is the reactive programming movement effort formalization for  Java language. It’s an interoperable publish-subscribe framework, enhancements to the`CompletableFuture` API, and various other improvements incorporated to the Java language, according to the [official site](http://openjdk.java.net/jeps/266).

This way, we can implement Reactive Microservices in Java using this important update in Java 9!

## Enhanced Deprecation \(JEP 277\)

This feature helps developers and systems alike to understand more the deprecation of a specific API, in a easy and seamless way. This could support the contract evolution of the exposed services.

For more information, please check [here](http://openjdk.java.net/jeps/277).

## New Version String Format \(JEP 223\)

[Semantic versioning](http://semver.org) is the message here. In the new Java version a new version scheme was defined as described below:

**Major.Minor.Security.Patch**, where:

**Major** = $MAJOR version when you make incompatible API changes,

**Minor** = $MINOR version when you add functionality in a backwards-compatible manner

**Security** = $SECURITY version when you add security critical fixes constraints including those necessary to improve security functionality or make backwards-compatible bug fixes.

**Patch** = $PATCH version when you make backwards-compatible bug fixes.

With Microservices projects [this feature](http://openjdk.java.net/jeps/223) could foster a new way to control the versioning and evolution of the projects and solutions delivered, with a clear view of what’s inside of it when this pattern is rigorously followed.

## The Best Part: Modularity \(JEP 261\)

Now Java 9 has Modularity. This means that we can create modular applications, without the need to import things we don’t need and compile things that we don’t use for that specific piece of code.

The JDK and JRE run-time images were reestructured to accommodate modules and to improve performance, security, and maintainability. A new URI scheme was defined for naming the modules, classes, and resources stored in a run-time image without revealing the internal structure or format of the image.

In the Microservices arena, this represents an excellent effort to:

* Create Specific codebase for Microservices
* Do better test our Microservices
* To deliver the Microservices

For more information, please check the [official page](http://openjdk.java.net/jeps/261).

## In Summary

All in all the Java community is working hard to accomplish and realize the best ideas and needed changes in Java in order to address the continuous business demands of our customers using the solid Microservices architectural approach.



