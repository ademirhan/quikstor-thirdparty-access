# QuikStor Third-Party API Documentation

The QuikStor API model will allow vendors to integrate QuikStor Cloud Application with any third-party self storage property management system. The API documentation gives you access to all supported functions of our service. The simple web requests over HTTP protocols (GET, POST and PUT methods) encoded in JSON formatted data allows us to provide access to the system accross multiple platform and devices.

QuikStor API is a Hybrid between REST (Representational State Transfer) and customized API based cloud service for requesting data and sending data to our QuikStor database. 

Before getting started with the API there are a few things you as the developer should be familiar with.

- JavaScript Object Notation (JSON): All returned data objects are in this form by default.
: All returned data objects (except the AuthToken) can be in this form if requested from the API.
- OAuth 2.0: API authorization is handled by OAuth validation and tokens. 

Provided below are web links to additional resources related to using the API.

- JSON Overview: http://www.json.org
- JSON.NET: http://www.newtonsoft.com/json (also available as a NuGet in Visual Studio)
- REST Wikipedia Page: http://en.wikipedia.org/wiki/Representational_state_transfer


# Standard API HTTP Return Codes

Code | Description
---------|----------
 200 | OK or Success.  
 400 | Bad Request. This indicates that the request there is an issue with the param-argument has issue.... <>. 
 401 | Unathorized. This indicates that the authorization token is invalid or expired.
 500 | Internal Server Error. This indicates that the error has occured on the server. You may need to contact QuikStor administration by sending an email to cloud_support@quikstor.com. 