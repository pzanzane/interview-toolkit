1. Reactive Spring Framework, Webflux
1. @SpringApplication Annotation
2. @ComponentScan Annotation Working
3. Actuator and defualt end points of actutators
4. Active profiling
5. Spring MVC flow
6. What are some of the starter dependencies/ Basic dependenices used in spring boot.
7. defaut scope of bean in spring
8. Bean factory Vs Application context
9. AutoConfiguration in Spring Boot
10. Benefit of JPARepository Interface
11. Create a custom JPARepository
12. Can we add a Spring boot project dependency in a core java project 
13. What is Spring boot? benefits
15. Yaml Configurations
16. Use of dev tools dependency
17. Can we create a custom actutator endpoint 
18. Synchronous vs Asynchronous rest calls
19. How to make Asynchronous Rest Calls
20. Put vs Post mapping
21. Is there a difference in put and post parameters
22. DI vs IOC
23. default bean scope in spring boot
24. other bean scopes
25. prototype vs request bean scope
26. Request Param Vs Path variable
27. Can we combine Path variable and Request Param in a single rest call
28. How to accept XML as a parameter. Dependency name
29. How to send JSON as a response
30. LifeCycle method in Spring Bean
32. @EnableAutoConfiguration
33. Use of @Qualifier
34. difference between @Qualifier and @Primary
35. @Scope
36. Singleton vs prototype
37. How to configure applicationContext?
38. Benefits of Spring Boot? Which version of Spring boot
39. Configurations file in Spring -- dispatchher servlet, web.xml, servlet.xml etc
40. "#" and "$" significance @Value annotation
41. StereoType Annotations
42. Spring Boot vs Spring 
43. Benefit of Spring Data JPA
44. Version of Spring Boot Used
45. Different RequestMapping Annotations
46. RestController vs Controller
47. How to send .xls or txt file as response
48. Internal Server Error and Exception Handling in SpringBoot
50. How to Skip/disable @EnableAutoConfiguration for a class
51. Schedulers in Spring
52. Different ways to create Beans in Spring
53. Different ways to access properties in Spring


------------------------------------------
### Project Derived Interview Questions

1. What is Interface Driven Rest Controller ?
2. Why we should use Lombok library ?
3. How will you validate Request Body and Query. Path Parameters ?
4. How do you handle the exceptions in Rest API ?
5. What is Data Transfer Objects (DTO) ?
6. What is a Custom Validator, explain with example, Usually this is a business requirement eg. AccountURI.



---------------------------------------------
### From Shiv


1. What is a functional interface? Benefits of it?
-- https://www.geeksforgeeks.org/functional-interfaces-java/

2. @qulifier vs @primary
3. Factory vs Abstract Factory vs Builder pattern
4. security in your project. How to check valid client.
5. what is lazy loading in stream?
6. Hashmap vs ConcurrentHashMap
7. If Hashmap can synchronize using Collections.syncronizeMap method then why concurrentHashMap introduced?
8. Bean scopes and deprecated and newly added
9. Bean life cycle
10. Hash map internal work/ implementation. What is the difference in java 8 hashmap
11. How to make class singleton. Double locking mechanism in singleton(volatile)
12. Difference between singleton class and singleton bean
13. Implement two database connections in springboot
14. @Value?
15. @controller vs @Restcontroller
16. Exception handling @ service layer in springboot
17. How would you optimize the query
18. What is responsive page?
19. What is Kafka?
20. Spring cloud?
21. Discovery server (Eureka)? How to implement?
22. Different types of @Autowiring ? --> no(default), byName, byType and constructor
23. Why is java so popular? What is the difference between Java and othe  native language
24. Write  your own equal method to compare two strings
25. Microservices Design Patterns(whatever you know)
26. Circular dependency. How to handle
27. How is Bean works? - life cycle
28. Solid principles with examples
29. Filter Student with sub=math and marks >75
30. Why used factory Pattern?
31. What is circuit breaker
32. How to handle fault tolarence?
33. When to use a qualifier in spring?
34. How to use backend(DB)
35. When to use SAGA?
36. How do you communicate in microservices architecture?
37. How to handle global exception in microservices

##### Medline - 
1. SOLID principles
2. JVM loaders?
3. What is enhancement in the map in Java8? Why used a balanced tree?
4. How handle fault talarance in microservices 
5. Cqrs, saga, circuit breaker
6. Strategy pattern / observer
7. Write custom actuator
8. Try with resources
9. How to use custome resources in try with resources - implement Autoclosable interface
10. Circular dependency? Different ways to handle
11. Unit test vs. integration test
12. AOP- JOINPOINT
13. Transactional propogation 
14. Coding - java 8
15. Equals and hashcode contract
16. What is the cyclic barrier?
17.  JAVA8 - map vs flatmap. When to use flatmap?
    
##### Sutherland  - 
1. What are the benefits and disadvantages of microservices?
2. How to convert monolithic to microservices 
3. How do you handle the fault tolerance in microservices?
4. What is RabbitMq? How does it work?
5. What is discovery in microservices?
6. How to trace the logs
7. What is the saga, cqrs, circuit breaker 
8. What are solid principles 
9. Write a code for end to end rest service to update the account info
10. What is the default method
11. What is stream
12. What is lambda
13. Can the default method override
14. How do you handle the  security in your application?
15. What is the content of JWT?
 16. Array List vs Linked List
17. What is blue - green deployment?

##### No Name
1. What is splunk
2. Microservices Design Patterns 
3. What is observable in MS
4. What is the use of executor framework
5. What is a reentrant lock
6. What is a completable future
7. What is BFF in MS (Graph ql)
8. Sharding
7. Idempotancy in MS
8. What is CDC in the database 
9. Any experience on ELK
10. Experience on promethus?
11. What is view?
12. Java 8 - optinal, predicate, parallel stream13.  Performance testing? How do you calculate in the current application

---------------------------------------------------
### Spring Batch

#### Basic Questions:

1. What is a batch job, and how is it different from regular request/response processing in web applications?
   - Expected Answer: Batch jobs are long-running processes that typically handle large volumes of data, are executed in the background, and are scheduled to run at specific intervals. They are different from web applications which are typically request-response based.

2. What is Spring Batch, and why is it useful in batch processing?
   - Expected Answer: Spring Batch is a framework for processing large volumes of data in a systematic, repeatable, and robust way. It simplifies batch job management, transaction management, job scheduling, etc.

3. Can you explain the core components of Spring Batch?
   - Expected Answer: The core components are:
     - Job: Represents the whole batch process.
     - Step: A phase in the job, consisting of an item reader, item processor, and item writer.
     - JobRepository: Stores the status of the batch jobs.
     - JobLauncher: Used to launch the job.
     - JobInstance: A specific execution of a job.
     - JobExecution: Represents the running instance of a job.

4. How do you configure a simple Spring Batch job in Spring Boot?
   - Expected Answer: Discuss using annotations like @EnableBatchProcessing, defining jobs, steps, readers, processors, and writers using Java config or XML.

#### Intermediate Questions:

1. What is the role of ItemReader, ItemProcessor, and ItemWriter in Spring Batch?
   - Expected Answer:
     - ItemReader: Responsible for reading input data.
     - ItemProcessor: Responsible for processing the data (e.g., transforming or validating).
     - ItemWriter: Responsible for writing the processed data to a destination (e.g., database, file).

2. How would you handle job restartability in Spring Batch?
     - Expected Answer: Spring Batch has built-in mechanisms to restart jobs from where they failed, using the concept of JobInstance and JobExecution. This is done by maintaining metadata in the JobRepository that records job execution states, allowing you to resume the job from the last failed step.

3. How can you schedule a batch job in Spring Boot?
     - Expected Answer: You can use Spring’s @Scheduled annotation for simple scheduling or integrate with a more complex scheduling framework like Quartz for advanced scheduling needs.

4. What are chunk-oriented processing and tasklet in Spring Batch?
     - Expected Answer:
       - Chunk-Oriented Processing: Spring Batch reads data in chunks, processes them, and writes them in batches. E.g., reading 1000 records, processing them in chunks of 10, and writing them.
       - Tasklet: A simpler, single-step approach for batch processing, used when chunk-oriented processing isn't needed.


#### Advanced Questions:

1. How do you handle large datasets in batch jobs to avoid memory issues?
     - Expected Answer: Implement techniques like:
       - Pagination or partitioning.
       - Using JdbcPagingItemReader or JdbcCursorItemReader to fetch a subset of records.
       - Use chunking to break the process into manageable units.
       - Implement multi-threading for parallel processing using TaskExecutor or partitioned steps.

2. Explain how to implement parallel processing in Spring Batch.
     - Expected Answer: Use partitioning (splitting the job into multiple steps, each handling a subset of the data) or multi-threaded steps (executing steps in parallel by assigning different threads).

3. What are some best practices for exception handling in Spring Batch jobs?
     - Expected Answer:
       - Retry/skip logic using RetryTemplate.
       - Skipping faulty items with SkipPolicy.
       - Proper transaction management and rollback handling at the step level.
       - Using JobListener and StepListener for handling exceptions and state transitions.

4. How do you implement conditional flows in Spring Batch?
     - Expected Answer: Spring Batch supports conditional flows using decision steps (Flow and FlowBuilder). You can use JobExecutionDecider to decide the next step based on a custom condition.

5. How would you optimize the performance of a Spring Batch job that deals with millions of records?
     - Expected Answer:
       - Use chunk-oriented processing.
       - Implement multi-threading or partitioning for parallel processing.
       - Optimize database reads and writes (e.g., batching queries, using indexes).
       - Use appropriate reader/writer strategies (e.g., JdbcPagingItemReader for large datasets).

6. What is Spring Batch’s JobRepository, and how is it utilized?
     - Expected Answer: The JobRepository stores the state of jobs (including job executions, steps, and job parameters) in a persistent storage (usually a database). It ensures that job state is maintained between restarts and failures.

7. Can you describe the difference between TaskExecutor and partitioning in Spring Batch?
     - Expected Answer:
       - TaskExecutor: Executes steps asynchronously with multiple threads. It’s suitable for multi-threaded step execution.
       - Partitioning: Divides a large set of data into smaller, independent partitions and processes them in parallel steps, each running its own thread or process.

#### Behavioral/Practical Questions:

1. Describe a time when you had to troubleshoot a failing Spring Batch job. What approach did you take?
     - Look for the candidate’s experience with debugging, logs, error handling, and fixing issues in production environments.
     - How would you approach migrating a legacy batch job into a Spring Batch-based solution?

Expected Answer: The candidate should explain how they would identify the existing job's processes, configure Spring Batch components, and ensure seamless data processing with minimal downtime.
What tools or strategies have you used to monitor batch jobs in production?

Expected Answer: Mention tools like Prometheus, Spring Batch Admin, custom monitoring, or logging to capture job execution details and performance metrics.
