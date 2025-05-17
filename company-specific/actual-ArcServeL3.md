## 16 May 2025
### Panel
- Bharadwaj.Ghadiam
- Pravallika.Modugula
-------------------
- Design Requirements
  - - Design database for the same
  - - Design API for the same
  - Arcseve will have multiple batches.
  - For each batch, we need to store the name, start month and current instructor.
  - Each batch of Arcserve will have multiple students.
  - Each batch has multiple topic.
  - For each Class, store the name, date and time, instructor of the class.
  - Every student has a buddy, who is also a student.
  - A student may move from one batch to another.
  - For each batch a student moves to, the date of starting is stored.
  - Every student has a mentor.
  - For every batch, store if it is an DataStructures or a AI/ML batch
  - For every mentor, we store their name and current company name.
  - Store information about all mentor sessions (time, duration, student, mentor, Student rating, mentor rating)


System Design & Database

    In between, one question: for a batch, consider 1 lakh students — how often do you filter the students based on some email? How will you make your query run faster?

    Why does index help you?

    Will you create an index on the entire column, or will you do something specific?

    There is nothing you can do on tables to improve performance. How can you improve your UI user performance?

    By doing pagination, you need to know how many pages are there. Hibernate needs to know the count of rows — how will you automate that too?

    If we want to disable pagination and query based on page size, how are we going to do that?

    Do you know any caching strategies we can use?

    What is the latest Spring Boot version you used in your project?

    Have you done Spring Security?

    Have you implemented authentication using Spring Security on your own in any project?

🔐 Authentication & Authorization

    In OAuth, can we get refresh tokens?

    In JWT, can we do role-based authorization?

    You know transactions in Spring Boot — how do you use them?

    Imagine BookMyShow: several users try to select the same seat. How do you ensure a seat is booked by only one person using Spring-level transactions?

    You know there’s isolation levels in transactions — can you use serializable here?

⚙️ Performance Monitoring

    In a production application, how would you identify or resolve any performance bottlenecks?

    Can we check the statistics of any database query? How much time it's taking?

    If there are any memory leaks, how can we detect them?

    What about heap dumps — have you used them?

    Have you worked on any localization in your project?

📨 Messaging & Kafka

    If you have any messaging service, how can we handle message deduplication in an at-least-once delivery system?

    First I send the message but don’t receive the acknowledgment — if I try to send the same message again, how do we handle this?

    Can we maintain any data structure to track if a message was already sent to the user?
