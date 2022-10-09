# Integration testing 
## What is Integration testing?
Software components are conceptually connected and tested as a unit in a form of testing called integration testing. Multiple software modules created by various programmers make up a typical software project. This level of testing's objective is to find issues with how various software components interact when they are combined.

## Spring Boot Framework
Java Spring Framework (Spring Framework) is a well-liked, open-source, enterprise-level framework for building independent, high-quality Java Virtual Machine applications (JVM).

Through its three primary features, Java Spring Boot (Spring Boot) is a solution that accelerates and simplifies the development of web applications and microservices with the Spring Framework.
* Autoconfiguration
* Taking a position on configuration
* Being able to develop independent applications

## Implementation 
First, I downloaded need packages for supporting the Spring framework and some important plugins and dependencies to call some statements in the build.gradlew file.
Second, I gave needed permission to run gradlew 
```
chmod +x gradlew 
```
Then, I ran the following commands and they were successful for running and testing.
```
./gradlew build
./gradlew test
```
Lastly, running the all tests and they successfully passed.
![Test Result](C:\Users\acer\Desktop\2022-10-09 20_50_01-Window)

