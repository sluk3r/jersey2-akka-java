jersey2-akka-java
=================

An example asynchronous REST API written in Java using Jersey 2 and Akka 2.3

[![Build Status](https://travis-ci.org/pofallon/jersey2-akka-java.svg?branch=master)](https://travis-ci.org/pofallon/jersey2-akka-java)

Key concepts
------------
* Instantiating an Akka ActorSystem at server startup and injecting it into each request
* Fulfilling an asynchronous Jersey REST service invocation using Akka actors

How to run the example
----------------------
1. Clone this repository
2. Run `mvn tomcat7:run`
3. Visit `http://localhost:9090/examples/doubler/2` via curl or your favorite browser

Prerequisites
-------------
* JDK 7.x
* Maven 3.x
