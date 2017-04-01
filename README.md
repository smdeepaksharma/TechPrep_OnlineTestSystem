# OnlineTestSystem - TechPrep
TechPrep is an Online Test System as a replacement for paper based tests. It is a Java based software web applications developed using the following technologies : Spring MVC, Hiberate, Apache CXF RESTful web service APIs, Java Server Faces, Boostrap, HTML 5,Maven, Jetty

![Alt text](/screenshots/ot_results.png?raw=true "Results")

# Usage
The project uses Jetty Server. 
Place the project source code in your Jetty Server's directory and run. Use the URL : localhost:XXXX/OnlineTestClient

Or use the following MAVEN commands : 
mvn package install
mvn jetty:run -Pjetty

The project has two parts. 
1. Online Test Server
2. Onine Test Web Client

Both the modules should be run seperately. 
