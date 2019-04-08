Section I : Solution Design

1:  We need to build a UI to maintain ~100 item attributes. We expect ~100 concurrent users for this app.
We also need to expose this data to consumers via a REST API, which should be able to support ~1000 requests/second.
There is also a requirement to expose updates to these attributes as event streams.  How would you build this system?

- tech stack
- database
- caching strategy
- HA
- API security

Section II : Java
1.  What's your go-to JVM based language (e.g. core java, groovy, kotlin, scala) and why?

2.  How would you process a large set of data parallelly?  e.g.  processing inventory counts for 2000+ stores.
    Would you use Fork/Join Framework vs. Parallel Streams vs. ExecutorService?
    How many threads you can run effectively on a server with 2 cores?
    How would you achieve parallelism when one server can not process the data in a timely manner?

3.  Have you ever had to tune java garbage collection?  If so, what was the situation and how did you do that?

4.  How would you share data across threads?

5.  How do you do asynchronous programming in Java?  Future vs. CompletableFuture

6.  What is reactive programming model?  How would you develop a develop a reactive REST API using SpringBoot?
    - when would you use Tomcat vs. Netty?
