# java-grpc-demo

Rebuild the application:


$ mvn -DskipTests package
Restart both the server and the client each in its own Cloud Shell session.

To start the server:


$ mvn exec:java -Dexec.mainClass=com.example.grpc.App
...
Server Started
To start the client:


$ mvn exec:java -Dexec.mainClass=com.example.grpc.Client
...
greeting: "Hello there, Ray"
greeting: "Hello there, Ray"
greeting: "Hello there, Ray"
