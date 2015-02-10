helloworld-ws: Hello World JAX-WS Web Service
==================================================
Author: Alexander Krieg

Level: Beginner

Technologies: JAX-WS, Arquillian, Docker, Soapui

Summary: Deployment of a basic JAX-WS Web service bundled in a WAR archive and running Integration tests
Target Project: WildFly
Source: <https://github.com/wildfly/quickstart/>

What is it?
-----------

1. This example demonstrates the use of *JAX-WS* in *JBoss WildFly* as a simple Hello World application.
2. This example demonstrates the use of Docker for application deployment 
3. This example demonstrates the use of SOAPUI for integration tests


System requirements
-------------------

All you need to build this project is Java 7.0 (Java SDK 1.7) or better, Maven 3.1 or better and a Docker host.

The application this project produces is designed to be run on JBoss WildFly.




Access the application 
---------------------

You can check that the Web Service is running and deployed correctly by accessing the following URL: <http://${dockerHost}:${wsport}/${wsname}?wsdl>. This URL will display the deployed WSDL endpoint for the Web Service.


