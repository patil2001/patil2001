# Hi, I'm Buddhaprakash Patil 👋

I am a **Backend Engineer** specializing in Java, Spring Boot, and distributed systems. I design microservices built to remain correct under retries, concurrency, and partial failure—focusing heavily on idempotency, event-driven messaging, and resilient integrations.

- 🔭 Currently a **Software Developer at Amdocs**, owning production microservices and driving batch ETL performance optimization for T-Mobile.
- ⚡ **Core Impact:** Boosted transaction reliability by **20%**, optimized Redis session token-storage by **35%**, and scaled concurrent transfers to eliminate lost updates.
- 💬 Ask me about: Defending against double-spends, transactional outbox patterns, or tuning SQL batch windows.

---

## 🛠️ Tech Stack & Systems Expertise

*   **Expert (Daily Use):** Java, Spring Boot, Spring Batch, REST API Design, Microservices, PostgreSQL, Redis
*   **Proficient (Shipped to Production):** Kafka, AWS (S3, EC2, SNS, SQS, IAM), Spring Security, Docker, Hibernate/JPA, JUnit, Mockito, Jenkins & GitHub Actions
*   **Familiar:** Kubernetes, Snowflake, MongoDB, GraphQL, Python

---

## 🚀 Key Architectural Case Studies & Projects

### 💳 [PayFlow | Microservices Wallet Backend](https://github.com/patil2001/payflow)
*Java 21 • Spring Boot 3 • JWT • JPA • Event-Driven*
A digital wallet backend built to handle critical payment system failure modes:
*   **Concurrency Control:** Implemented optimistic locking (`@Version`) with bounded retry loops executing outside the Spring transaction proxy to prevent lost updates under low contention.
*   **Double-Spend Prevention:** Enforced strict idempotency keys driven by database unique constraints to safely stop concurrent duplicate requests.
*   **Reliable Messaging:** Leveraged a Transactional Outbox pattern paired with at-least-once relay and consumer deduplication to guarantee eventually consistent processing.

### 📊 Spring Batch ETL Optimization
*Spring Batch • SQL Tuning • Table Partitioning • Amdocs (T-Mobile)*
*   **Problem:** Peak run times were blowing past the designated batch windows due to read-heavy bottlenecks.
*   **Solution:** Profiled operations and introduced SQL tuning alongside database table partitioning to enable independent slices to run in parallel steps without write contention. Cut peak runtimes significantly.

---

## 📬 Connect With Me

*   **Portfolio & Deep Dives:** [patil2001.github.io/portfolio](https://patil2001.github.io/portfolio/)
*   **LinkedIn:** [linkedin.com/in/buddhapp](https://www.linkedin.com/in/buddhapp)
*   **Email:** patilbuddhaprakash@gmail.com
