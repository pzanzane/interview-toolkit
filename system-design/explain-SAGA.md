## SAGA Pattern

### What is SAGA
Sequence of operations that collectively stands for one Transaction.
It breaks down complex transaction into series of smaller, isolated operations, each handled by different services. 

### Problem Statement.
- Tranditional distributed transaction protocol like 2-phase-commit (2PC) has limitation.
- - Blocking in Nature.
  - Single point of failure.
  - Network partition
- What is 2-phase-commit (2PC) in distributed transaction.
- - It ensures all participants in distributed transaction either commit or abort. Which ensures consistency.
  - In first phase co-ordinator asks all participants to agree to commit.
  - In second phase participants vote to commit or abort.  

### Advantage
