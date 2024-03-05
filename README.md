# Pre Introduction

Before we dive into Frontend development. We ensure to know about web architecture. 


## What is web architecutre 

That is backbone of the internet. 
That encompasses the structure, organization, and interaction of various components that make up a web system.
It's includes both client and server side elements, as well as the protocols and standards that facilitate communication between them.
So, Understanding of web architecture is very crucial for developers, designers and business owner alike.

These are the most crucial things in web architecutre.

### Client-Server Model

The client-server model form is the foundation of web architecture, with client (such as web browsers or mobile apps) requesting and receiving resource from servers.
The SOC (Separation of concerns) allows for scalability, as servers can handle multiple client requests simultaneously, and clients can interact with various servers across the web.

![Client Server Model Image](/assets/client-server-architecture.png)

### Three-Tire Architecture 

Three-tier architecture further divides the application into three logical layers: presentation (client), application (server), and data (database).
This modular approach enhances scalability, maintainability, and reusability, as each layer can be developed, deployed, and scaled independently.

![Three-Tire Architecture](/assets/three-tire-architecture.png)

### RESTful Architecture

Representational State Transfer (REST) is a widely adopted architectural style for designing networked applications.
RESTful systems are characterized by stateless communication, resource-based URLs, and standard HTTP methods (GET, POST, PUT, DELETE).
This simplicity and flexibility make REST an ideal choice for building scalable and interoperable web APIs.

| Method | Description |
|--------|-------------|
| GET    | The GET method is used to retrieve data from a specified resource. It should only retrieve data and should not have any other effect on the server. Requests using GET should only retrieve data and should have no other effect on the data. |
| POST   | The POST method is used to submit data to be processed to a specified resource. It is often used when submitting form data to a server. It can also be used to upload a file to a server. |
| PUT    | The PUT method is used to update or replace an existing resource or create a new resource if it doesn't exist. It replaces the current representation of the target resource with the request payload. |
| DELETE | The DELETE method is used to delete a specified resource from the server. It removes the resource identified by the URL. |
| PATCH  | The PATCH method is used to apply partial modifications to a resource. It is typically used to update specific fields of an existing resource. |
| HEAD   | The HEAD method is identical to GET, but the server doesn't return the message body in the response. It is often used to retrieve metadata about a resource, such as headers, without transferring the entire content. |
| OPTIONS | The OPTIONS method is used to describe the communication options for the target resource. It returns the HTTP methods supported by the server for the specified URL. |

### Microservices Architecture

Microservices architecture decomposes applications into small, independent services that can be developed, deployed, and scaled independently.
Each service focuses on a specific business function and communicates with other services via lightweight protocols like HTTP or messaging queues.
Microservices promote agility, allowing teams to iterate rapidly, scale horizontally, and adopt polyglot architectures.

![Microservice Architecture](/assets/microservice-architecture.png)