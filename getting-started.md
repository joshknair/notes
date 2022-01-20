This document outlines the skillsets for Java Backend Engineer.

## Step 0: Environment Setup
- Download and install Java 15 or above (https://openjdk.java.net/)
- Download and install IntelliJ Community Edition

## Step 1: Core Java & Object Oriented Programming
Cover the following Java topics.  Use IntelliJ IDEA Community Edition IDE for development.  Use https://www.w3schools.com/java/default.asp as a reference.
+ Basic Concepts:
  + Basic syntax (classes, methods, running a program etc.)
  + Data types (int, char etc.) 
  + Objects and Classes
  + Constructors
  + Basic operations (number operations, string operations, char operations)
  + Loops (for, while) and decision making (if, if/else, switch)
  + String manipulation
  + Arrays
  + Packages
  + Methods
  + Interfaces
  + Abstract classes vs. Interfaces
  + File I/O
  + Exceptions (checked and runtime exceptions)
  + Regular Expression (pattern matching) - understand the basics
+ Object Oriented Programming
  + Inheritance
  + Polymorphism
  + Abstraction
  + Encapsulation
+ Data Structures & Collections
  + Collection, List, ArrayList, Set, SortedSet, Map, Hashmap, Hashtable
  + Equals & Hashcode
+ Advanced
  + Logging and log levels
  + Lamda Expression
  + Streams (functional programming)
  + Optional
  + New Date/Time APIs (Instant, LocalDate etc.)
  + Network programming (sockets)
  + Multi-threading (Thread, Runnable, Executor Framework, CallableFuture, CompletableFuture)
    + Making parallel calls
    + Aggregating results from multiple parallel calls
  + Design Patterns (see https://www.javatpoint.com/design-patterns-in-java)
    + Singleton
    + Proxy
    + Adapter
    + Builder
    + Abstract Factory
    + Factory Method
    + Facade
    + Strategy

+ Creating/Building Java Projects
  + Maven or Gradle
  + GitHub (learn to manage sourcecode in Git version control)
  + Testing
    + Unit testing (JUnit)
    + Mocking frameworks (e.g. Mockito)
    + Integration testing

## Step 2: Database
Goal of this session is to get familirized with database concepts.  Use Postgres/MySQL and Firebase for development.
+ Postgress or MySQL
  + Database overview
  + Creating a database
  + Tables, Columns
  + Primary Key/Foreign Key
  + Quering the database
+ Firebase
  + Setting up an account
  + Creating collections
  + Manipulating collections (from Java app)
  
## Step 3: Spring/SpringBoot
Learn these topics to build APIs.  
+ Spring Overview  
  + Beans
  + Scope
  + Dependency Injection
+ SpringBoot (see https://spring.io/guides)
  + JSON
  + Spring Initializer (https://start.spring.io/)
  + Build a hello world Restful api
  + Consume a service (e.g. OpenWeather API -> https://openweathermap.org/appid)
  + Deep Dive
    + Model/View/Controller
    + Controller & Controller Advice
      + HTTP Methods (GET, POST, PUT, PATCH etc.)
      + HTTP Status Codes
      + HTTP Success and Error responses   
    + Service
    + Repository
    + Spring Data
    + Actuator
    + Aspect-Oriented Programming (AOP)
    + Testing APIs
    + Docker
      + Learn the fundamentals of Docker
  + Projects
    + Sample project - see [weather-api](https://github.com/joshknair/weather-api)
      +  Key features to implement
         + Springboot webflux - reactive
         + Custom annotation for logging requests and responses (e.g.  @Log)
         + Metrics - springboot actuator
         + Caching (L1 and L2 caches
         + Unit and Integration tests
    + Convert the above prject to reactive
    + Build a RestAPI that uses Google Firebase DB
    + Build a RestAPI that uses Postgres or MySQL as the database
    + Dockerize one of the APIs for deployment
    + Convert the API to reactive (https://www.baeldung.com/spring-webflux)

## Step 4: Cloud
Learn the basics of Cloud (AWS preferred)
- TBD
- 
