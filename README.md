# Secure-REST-API-Using-Spring-Basic-Authentication
Traditional authentication approaches like login pages or session identification are good for web based clients involving human interaction but this does not really fit well when communicating with [REST API] clients which may not even be a web application. Think of an API over a server which tries to communicate with another API on a totally different server or instances, without any human intervention. Basic Authentication provides a solution for this problem, although not very secure as other security features like OAuth2 etc. With Basic Authentication, clients send it’s Base64 encoded credentials with each request, using HTTP [Authorization] header . That means each request is independent of other request and server may/does not maintain any state information for the client, that is good for scalability point of view.
