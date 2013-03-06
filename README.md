embedded-jetty-example
======================

An example that embeds the Jetty web server into a standalone JAR, making it really easy to deploy and run your Java web apps.

How to compile and run
----------------------
	mvn clean package
	java -jar target/embedded-jetty-example.jar 8080

Then point your browser to http://localhost:8080.
