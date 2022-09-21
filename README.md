# spring-cloud-netflix-security

discovery server url
http://localhost:8761/

Every microservices must be call from secured zuul gateway to make each microservice logically secured means zuul is a only entry point.

good-morning is not secured means it can be directly accessible without token.

good-morning-secured is marked as a resource server means it will not be directly accessible without token.

please find the MicroServiceZuulAuth.postman_collection.json file and import in postman to test the demo
