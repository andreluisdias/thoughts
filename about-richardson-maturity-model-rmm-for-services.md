# _Chapter 02_

# About Richardson Maturity Model \(RMM\) for Services

Richardson Maturity Model \(RMM\) it’s a model developed by **Richardson, Leonard **that helps organize your REST APIs in some levels, described below.

The importance of this topic is key, once we have to create and maintain better services APIs.

The main reason for this model to exist is to foster the evolution of the REST APIs of some system with a constant concern of Governance, sense of organization with retrocompatibility and constant improvements, using all characteristics available from the REST architecture style.

Below we have an overview of all layers within the RMM model, described in the following topics:

![](https://microservicesradar.files.wordpress.com/2017/09/rmm.png)

## Levels of RMM

### **Level 0 = **Swamp of Pox

In this level, you should have a service already exposing a resource via its URI using only one HTTP verb \(usually GET or POST\). In this phase you only use HTTP as a transport system \(think of it as a RPC using HTTP\).

### **Level 1 = Resources**

On Level 1, you talk directly with your resources - _correctly defined_ - using the appropriate division for it. Examples:

* Resource _**hotel**_
  * `/services/hotel/1/details` \(or `/services/hotel/1`\)
    Should bring details of the hotel with ID \#1
* Resource _**room **_\(from _**hotel**_ above\):

  * `services/hotel/1/rooms/all` \(or `services/hotel/1/rooms`\)
    Should bring details of all rooms of the hotel with `ID #1`

* `services/hotel/1/room/1`  
  Should bring details of the hotel room with `ID #1` of the `hotel #01`

_Observations_

* Here the details of a hotel could be location, how many stars it have, how many rooms, etc.
* Here details of the room could be the installation details, size, if it’s occupied, etc.

### **Level 2 = HTTP Verbs**

In this level, you a have a clear understanding of the semantics of HTTP verbs and can now map your service operations using HTTP verbs accordingly, using GET, POST, DELETE, PUT, standardizing your access to your services resources.

### **Level 3 = Multimedia**

In this maturity level, it's possible to extract the maximum benefit from the HTTP protocol and services resources using Multimedia \(HATEOAS\). The API should help on discoverability of all resources associated with the payload requested, via links available within the payload itself.

