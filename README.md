# What-is-REST
# REST(REpresentational State Transfer)
REST is an architectural style. It doesn’t define so many standards like SOAP. REST is for exposing Public APIs(i.e. Facebook API, Google Maps API) over the internet to handle CRUD operations on data. REST is focused on accessing named resources through a single consistent interface.

REST stands for Representational State Transfer. (It is sometimes spelled "ReST".) It relies on a stateless, client-server, cacheable communications protocol -- and in virtually all cases, the HTTP protocol is used.

REST is an architecture style for designing networked applications. The idea is that, rather than using complex mechanisms such as CORBA, RPC or SOAP to connect between machines, simple HTTP is used to make calls between machines.

In many ways, the World Wide Web itself, based on HTTP, can be viewed as a REST-based architecture. RESTful applications use HTTP requests to post data (create and/or update), read data (e.g., make queries), and delete data. Thus, REST uses HTTP for all four CRUD (Create/Read/Update/Delete) operations.

REST is a lightweight alternative to mechanisms like RPC (Remote Procedure Calls) and Web Services (SOAP, WSDL, et al.). Later, we will see how much more simple REST is.

Despite being simple, REST is fully-featured; there's basically nothing you can do in Web Services that can't be done with a RESTful architecture. REST is not a "standard". There will never be a W3C recommendataion for REST, for example. And while there are REST programming frameworks, working with REST is so simple that you can often "roll your own" with standard library features in languages like Perl, Java, or C#.

# Why REST?
- Since REST uses standard HTTP it is much simpler in just about ever way.
- REST is easier to implement, requires less bandwidth and resources.
- REST permits many different data formats where as SOAP only permits XML.
- REST allows better support for browser clients due to its support for JSON.
- REST has better performance and scalability. REST reads can be cached, SOAP based reads cannot be cached.
- If security is not a major concern and we have limited resources. Or we want to create an API that will be easily used by other developers publicly then we should go with REST.
- If we need Stateless CRUD operations then go with REST.
- REST is commonly used in social media, web chat, mobile services and Public APIs like Google Maps.

# REST fundamentals
- Everything in REST is considered as a resource.
- Every resource is identified by a URI.
- Uses uniform interfaces. Resources are handled using POST, GET, PUT, DELETE operations which are similar to Create, Read, Update and Delete (CRUD) operations.
- Be stateless. Every request is an independent request. Each request from client to server must contain all the information necessary to understand the request.
- Communications are done via representations. E.g., XML, JSON RESTful Web Services. A RESTful web services are based on HTTP methods and the concept of REST. A RESTful web service typically defines the base URI for the services; the supported MIME-types (XML, text, JSON, user-defined, ...) and the set of operations (POST, GET, PUT, DELETE) which are supported.

# Advantages of REST
- Since REST uses standard HTTP, it is much simpler in just about every way. Creating clients, developing APIs, the documentation is much easier to understand, and there aren’t very many things that REST doesn’t do easier/better than SOAP.
- REST permits many different data formats whereas SOAP only permits XML. While this may seem like it adds complexity to REST because you need to handle multiple formats, in my experience, it has been quite beneficial. JSON usually is a better fit for data and parses much faster. REST allows better support for browser clients due to its support for JSON.
- REST has better performance and scalability. REST reads can be cached; SOAP-based reads cannot be cached.
- No expensive tools require interacting with the Web service
- Smaller learning curve
- Efficient (SOAP uses XML for all messages, REST can use smaller message formats)
- Fast (no extensive processing required)
- Closer to other Web technologies in design philosophy

# Where to use REST

areas where REST works well for are:

Limited bandwidth and resources: remember the return structure is really in any format (developer defined). Plus, any browser can be used because the REST approach uses the standard GET, PUT, POST, and DELETE verbs. Again, remember that REST can also use the XMLHttpRequest object that most modern browsers support today, which adds a bonus of AJAX.
stateless operations: if an operation needs to be continued, then REST is not the best approach and SOAP may fit it better. However, if you need stateless CRUD (Create, Read, Update, and Delete) operations, then REST is it.
Caching situations: if the information can be cached because of the stateless operation of the REST approach, this is perfect.
