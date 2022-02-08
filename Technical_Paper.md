# REST
## Introduction to REST
**RE**presentational **S**tate **T**ransfer **(REST)** is an architectural style that defines a set of constraints to be used for creating web services. **REST API** is a way of accessing web services in a simple and flexible way without having any processing.
REST technology is generally preferred to the more robust Simple Object Access Protocol (SOAP) technology because REST uses less bandwidth, simple and flexible making it more suitable for internet usage. It’s used to fetch or give some information from a web service. 
Web services which follow the REST architectural style are known as RESTful web services. It allows requesting systems to access and manipulate web resources by using a uniform and predefined set of rules. Interaction in REST based systems happen through Internet’s Hypertext Transfer Protocol (HTTP).

## Working
A request from client to the server is sent in the form of web URL as HTTP GET or POST or PUT or DELETE request. After that a response comes back from the server in form of resource which can anything like XML, JSON, image or HTML.

![This is the process how REST works](https://media.geeksforgeeks.org/wp-content/uploads/qqqqqqq-1-1024x219.jpeg)

In **HTTP** there are five menthods commonly used i REST based architecture. They are:
1. **GET:** used to **read**(or retrieve) a representation of a resource.
2. **POST:** used to **create** new resources.
3. **PUT:** used for **updating** the capabilities.
4. **PATCH:** used for **modifying** capabilities.

## Architectural Constraints
There are six architechtural constraints which makes any web service
- **Uniform Interface:** it is a key constraint that differentiates between REST API and NON-REST API. It suggests that *there should be an uniform way of interacting with a given server irrespective of device or type of application*. There are four principle of Uniform Interface: 
    - **Resource-Based**
    - **Manipulation of resources through representation**
    - **Self-descriptive Message**
    - **Hypermedia as the Engine of application state (HATEOAS)**
- **Stateless:** It means that *the necessary state to handle the request is contained within the request itself and server would not store anything related to the session.*
- **Cacheable:** *Every response should include whether the response is cacheable or not* and for how much duration responses can be cached at the client side
- **Client-server:** *REST application should have a client-server architecture*. A Client is someone who is requesting resources and are not concerned with data storage, which remains internal to each server, and server is someone who holds the resources and are not concerned with the user interface or user state
- **Layered System:** *An application architecture needs to be composed of multiple layers.* Each layer doesn’t know any thing about any layer other than that of immediate layer and there can be lot of intermediate servers between client and the end server. 
- **Code on Demand:** It is an optional feature. According to this, *servers can also provide executable code to the client.*

## **Rules of REST API**
There are certain rules to be followed while creating REST API endpoints.
- The URI of a REST API should always end with noun.
- HTTP verbs are used to identify actions.
- Always use plural in URL to keep API URL consistent.
- Send proper HTTP code to indicate a success or error status.
- A web application should be organized into resources like users and then HTTP verbs.



## References
- https://www.researchgate.net/publication/325770704_An_Analysis_of_Public_REST_Web_Service_APIs
- https://www.geeksforgeeks.org/rest-api-introduction/?ref=lbp
- https://idratherbewriting.com/learnapidoc/docapis_introtoapis.html
- https://www.geeksforgeeks.org/rest-api-architectural-constraints/?ref=lbp
- https://idratherbewriting.com/learnapidoc/docapis_writing_process_overview.html
