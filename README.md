# Maven Archetype
This is aeloy-web-archetype which was created to ease the bootstrap process for building Maven based JSF 2.1 Web Applications.

## Features
The JSF 2 web application that will be created by this archetype will have the following features:

* JDK version 1.7
* myfaces-api 2.1.17
* myfaces-impl 2.1.17
* Servlet API 3.0
* JSP API 2.3
* JSTL 2.1
* JUnit 4.12

## usage
At first you need to clone this repository and run the following command locally to have this archetype installed.

```
cd aeloy-jsf2-archetype
mvn install
```

So you can create switch from aeloy-jsf2-archetype directory and start creating your maven based JSF 2 project
```
mvn archetype:generate -DarchetypeGroupId=br.com.aeloy -DarchetypeArtifactId=aeloy-jsf2-archetype -DarchetypeCatalog=local
```
