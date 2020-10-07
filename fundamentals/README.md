REST - Representational State Transfer
URL - Uniform Resource Locator
URI - Uniform Resource Identifier
URN - Universal Resource Name

* URN can be a URL, both are always URIs.

* REST Constraints -
a. Client Server Architecture
b. Statelessness
c. Cachability
d. Layered System
e. Code on demand
f. Uniform interface
    1. Resource Identification
    2. Resource manipulations through representations
    3. Self descriptive messages
    4. Hypermedia as engine

* REST clients - 
a. https://getpostman.com
b. https://insomnia.rest
c. Visual Studio Code (REST Client)

* Resource - Data contained at the end of resource URI
* Representation - Representation of the data obtained on access
* Methods - HTTP Methods(Verbs)

* HTTP Methods - 
1. GET - Get resource
2. POST - Create resource and add to collection(201 - Created)
3. PUT - Update existing singleton resource(200 - OK)
4. PATCH - Modify existing singleton resource
5. DELETE - Delete Singleton resource
6. OPTIONS - Description of the communication option for the target resource
7. HEAD - Head section of the response

* HTTP Response codes - 
1. 1XX - Information

2. 2XX - Success
    200 - OKK
    201 - Created(Should be returned on success of POST Request)
    204 - No Content

3. 3XX - Redirection
    301 - Moved permanently
    302/303 - Found at this other URL
    307 - Temporary redirect
    308 - Resume incomplete

4. 4XX - Client error
    400 - Bad request
    401 - Unauthorized
    403 - Forbidden
    404 - Not found
    405 - Method not allowed(Ex : Let's say GET request is used instead of POST)

5. 5XX - Server error
    500 - Internal Server Error
    502 - Bad Gateway
    503 - Service Unavailable