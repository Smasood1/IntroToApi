# IntroToApi

Chapter 1: Intro

```
A Server is a powerful computer that runs an API

API is the "hidden" portion of a website that is meant for computer consumption.
  -When 2 systems link we say they are integrated. 
  -In an integration there are 2 sides, client and server.
  -A client can manipulate the data that is available through the API
  
Client is a program that exchanges data with a server through an API.
```


Chapter 2: Protocols

```
Request Response Cycle
  - Request consists of a url(Unique address), a method(GET(Retrieve), POST(Create), PUT(edit/update existing resource), 
    DELETE(delete a resource)), a list of headers(provide meta-information about a request), and a body(condatins the data the client
    wants to add to the server).
    
  - Response consists of a status code(3 digit codes that have unique meanings. Can communicate errors as well as successfull requests), a       list of headers, and a body.
  
```

Chapter 3: Data Formats

```
In order for 2 computers to communicate they need to understand the data that is passed through, for example in API 2 common formats are 
JSON and XML. 

  - JSON: JavaScript Object Notation
  - Object: an object
  - Key: an attribute about an object
  - Value: the value of an attribute
  - XML: Extensible Markup Language
```

Chapter 4: Authentication, Part 1
```
Client can prove its identity to the server, a process known as authentication.

  - Authentication: process of the client proving its identiy to the server
  - Credentials: secret pieces of info used to prove the clients identity 
  - Basic Auth: scheme that uses an encoded username and password for credentials
  - API Key Auth: scheme that uses a unique key for credentials
  - Authorization Header: the HTTP header used to hold credentials
```

Chapter 5: Authentication, Part 2

```
2 versions of OAuth(1 and 2) and differences between them
  - OAuth1 access tokens do not expire, requires the client to ask the server for a request       token, requires requests to be digitally signed.
```

Chapter 6: API Design

```
SOAP: API architecture known for standardized message formats
  - REST: API architecture that centers around manipulating resources
  
  - Resource: API term for a business noun like customer or order
  
  - Endpoint: A URL that makes up part of an API. In REST, each
    resource gets its own endpoints
    
  - Query String: A portion of the URL that is used to pass data to the server
  
  - Query Parameters: A key-value pair found in the query string (topping=cheese)
  
  - Pagination: Process of splitting up results into manageable chunks
```
