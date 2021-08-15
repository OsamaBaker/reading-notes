# Express

1. What’s the difference between PUT and PATCH?
> Put updates a portion/component of the whole webpage, while PATCH updates the whole webpage.

2. Alternatives for json-server are Postman, Mirage, Firebase.

3. Popularity: By comparing stats,  swagger-ui is more popular then apidocjs.
Consistency: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.
Implementation complexity: apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger.json created by DotnetCore we can reuse more than 80% specification.
 Maintenance: For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.
Other benefits: Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more. 
Future: Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.

4. The difference is: SOAP is a XML-based message protocol, while REST is an architectural style. SOAP uses WSDL for communication between consumer and provider, whereas REST just uses XML or JSON to send and receive data. SOAP invokes services by calling RPC method, REST just simply calls services via URL path.


1. A web server is software and hardware that uses HTTP (Hypertext Transfer Protocol) and other protocols to respond to client requests made over the World Wide Web. The main job of a web server is to display website content through storing, processing and delivering webpages to users.

2. The primary use of Express is to provide server-side logic for web and mobile applications, and as such it's used all over the place.

3. Routing is the process of selecting a path for traffic in a network or between or across multiple networks. 