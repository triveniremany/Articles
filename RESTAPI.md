## Representational State Transfer Application Programming Interface
Representational state transfer is a software architectural style that defines a set of constraints to be used for creating Web services. Web services that conform to the REST architectural style, called RESTful Web services, provide interoperability between computer systems on the internet.

REST or RESTful API design (Representational State Transfer) is designed to take advantage of existing protocols. While REST can be used over nearly any protocol, it usually takes advantage of HTTP when used for Web APIs. This means that developers do not need to install libraries or additional software in order to take advantage of a REST API design. REST API Design was defined by Dr. Roy Fielding in his 2000 doctorate dissertation. It is notable for its incredible layer of flexibility. Since data is not tied to methods and resources, REST has the ability to handle multiple types of calls, return different data formats and even change structurally with the correct implementation of hypermedia.

This freedom and flexibility inherent in REST API design allow you to build an API that meets your needs while also meeting the needs of very diverse customers. Unlike SOAP, REST is not constrained to XML, but instead can return XML, JSON, YAML or any other format depending on what the client requests. And unlike RPC, users aren’t required to know procedure names or specific parameters in a specific order.

However, there are drawbacks to REST API design. You can lose the ability to maintain state in REST, such as within sessions, and it can be more difficult for newer developers to use. It’s also important to understand what makes a REST API RESTful, and why these constraints exist before building your API. After all, if you do not understand why something is designed in the manner it is, you can hinder your efforts without even realizing it.

Never email CSVs again
Never email CSVs again
Build Your First App Today.
Build Your First App Today.
Build in-demand skills like UX, UI and HCI?Northwestern online MS in Info. Design & Strategy.
Build in-demand skills like UX, UI and HCI?Northwestern online MS in Info. Design & Strategy.
If you want to be able to read API documentations and use them effectively, you’ll first need to understand everything about REST APIs. Let’s get started.
There’s a high chance you came across the term “REST API” if you’ve thought about getting data from another source on the internet, such as Twitter or Github. But what is a REST API? What can it do for you? How do you use it?

In this article, you’ll learn everything you need to know about REST APIs to be able to read API documentations and use them effectively.

What Is A REST API
Let’s say you’re trying to find videos about Batman on Youtube. You open up Youtube, type “Batman” into a search field, hit enter, and you see a list of videos about Batman. A REST API works in a similar way. You search for something, and you get a list of results back from the service you’re requesting from.

[!Web Services](/images/restapi.jpg)

An API is an application programming interface. It is a set of rules that allow programs to talk to each other. The developer creates the API on the server and allows the client to talk to it.

REST determines how the API looks like. It stands for “Representational State Transfer”. It is a set of rules that developers follow when they create their API. One of these rules states that you should be able to get a piece of data (called a resource) when you link to a specific URL.

Each URL is called a request while the data sent back to you is called a response.

## The Anatomy Of A Request
It’s important to know that a request is made up of four things:

* The endpoint
* The method
* The headers
* The data (or body)
* The endpoint (or route) is the url you request for. It follows this structure:
