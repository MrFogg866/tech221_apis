# tech221_apis


1. What are API’s? 
-  API stands for Application Programming Interface, they are based on a set of rules that enable different applications to communicate with each other,they are used by programmers, allowing them to interact with a application, they expose the interface and service for developers to comsume. 

2. How are they used and why are they so popular?
- API's are everywhere if you use tech then you have used a API, they allow us to share data and speed up development of new products, they make life easierfor developers by removing complexity. and save develops having to recode from scratch, saving time and money.

3. Make a diagram to showcase the data transfer process in API communication.

- ![What is this](img/what_is_api.png)

4. What is a REST API? 

- A REST API is an API that conforms to the design principles of the REST, or representational state transfer architectural style.

5. What makes an API RESTful?

- there are six REST design principles - also known as architectural constraints: Uniform interface, Client-server decoupling, Statelessness, Cacheability,
Layered systenm architecture, Code on demand

5. What is HTTP? 

- The Hypertext Transfer Protocol is an application layer protocol in the Internet protocol suite model for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.

6. Explain HTTP request structure using the diagram provided.
- to make a valid request, the client needs to include these 4 things
- URL (this is how the client tells the server which things it wants to interact)
- Method are the verbs  (request tels the server what king of action the client wants the server to take there are 5 shown below 
- List of Headers  - provide meta-information about a request 
- Body - the request body contains the data the client wants to send to the server

7. Explain HTTP response structure using the diagram provided.
- response codes are 3 digit numbers for example 200 means ok, 404 means error 
- headers - this is the content type : text 
- body -- this is the data

8. What are the 5 HTTP verbs and what do they do? GET, POST, PUT, PATCH, DELETE
- GET - asks the server to retrieve a resourse 
- POST - asks the server to create a new resource
- PUT - asks the server to edit/update an existing resource
- PATCH
- DELETE - asks the server to delete a resource

9. What is statelessness?

- As per the REST (REpresentational “State” Transfer) architecture, the server does not store any state about the client session on the server-side. This restriction is called Statelessness.

Each request from the client to the server must contain all of the necessary information to understand the request. The server cannot take advantage of any stored context on the server.

10. What is caching?

-  is the ability to store copies of frequently accessed data in several places along the request-response path.

11. Optional bonus: What is Postman? Sign up and try it out.
