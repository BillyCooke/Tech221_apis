# API's
## What are API's?
API stands for Application Programming Interface and it is a mechanism that enables two software components to communicate with each other using a set of definitions and protocols. The best way to think about this is by using the terms client and server. For example a client could be a sports app requesting live football updates and the server would be the Sky Sports database which then sends the information over to you.

## Why are they so popular?
API's are so popular because they do not require developers to work from scratch as they allow a team to use pieces that have already been created. This is especially important for DevOps as API's allow for greater automation and can help speed up the entire process as the team does not need to work from scratch.

## API diagram
![API diagram.png](..%2F..%2F..%2F..%2FOneDrive%2FDocuments%2FSparta%20Global%2FAPI%20diagram.png)
The diagram above is a visual representation of the client/server interaction. The client sends a request to the server which in turn responds with the information requested. The server is also in communication with the database.

## REST API
REST stands for representational state transfer and it is used to conform API's to the restrains of a REST architectural style. The main benefit of REST API's is that it does not save client data but just sends plain data at the request from the client.

## What makes an API RESTful?
An API is RESTful when it is stateless. As mentioned above stateless API's do not store any information about any previous requesst where as stateful API's store some information.

## What is HTTP?
HTTP stands for Hypertext Transfer Protocol and it is a method for encoding and delivering information between a client and the server. It is the primary method of transporting information on the internet.

## HTTP in the diagram
In the above diagram we can see that requests and responses are flowing between the clients and the server and it is HTTP that is transporting the data. HTTP can be represented by the arrows used in the diagram to show the movement of data. A HTTP request will include a request line, a header and a body of text. A HTTP response will include a response line, a header and a body of text.

## What are the 5 HTTP verbs and what do they do?
* Get - This method is used to gain a representation of a resource
* POST - This is used to create a new resource and returns a dedicated URL (sending data to get data back)
* PUT - This is used to update resource information
* PATCH - This is very similar to PUT however PATCH only modifies the contents of a resource whereas PUT replaces it.
* DELETE - This is used to target a single resource and delete it entirely

## What is statelessness?
As previously touched on, statelessness means that requests can be made independent of one another and it must include all the information needed to be understood by the server. It cannot rely on previous requests to fulfill the new request.

## What is caching?
Caching is used in a stateful API where in it uses previous request information to fulfill the new request. The data is stored in a cache which is a component to store temporary files.

## What is Postman?
It is a platform that helps to accelerate the API lifecycle. It allows you to easily explore, debug and test your API's while also enabling you to define complex API requests for HTTP and REST.