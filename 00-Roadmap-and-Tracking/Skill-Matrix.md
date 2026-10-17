# Target Roles Skill Matrix & Competency Benchmarks

This matrix defines the expected competencies and interview thresholds across our three target roles:
1. **Software Developer / Software Engineer (SWE)**
2. **QA Engineer / Software Tester (SDET / Automation)**
3. **Data Engineer (DE)**

---

## 📊 Cross-Role Competency Comparison

| Competency Area | Software Engineer | QA / SDET | Data Engineer |
|---|:---:|:---:|:---:|
| **DSA & Coding** | 🟢 Expert (Medium/Hard) | 🟡 Proficient (Easy/Medium) | 🟡 Proficient (Medium) |
| **Database & SQL** | 🟡 Proficient (Schema, ACID, ORMs) | 🟡 Proficient (Validation, Queries) | 🟢 Expert (Optimization, Window functions, DWH) |
| **System Design** | 🟢 Expert (HLD & LLD) | ⚪ Foundational (System Architecture) | 🟢 Expert (Data Pipelines & Dist. Systems) |
| **Testing & Quality** | 🟡 Proficient (Unit & Integration) | 🟢 Expert (Full lifecycle, Frameworks, Load) | 🟡 Proficient (Data quality, pipeline testing) |
| **Distributed Systems** | 🟡 Proficient (Microservices, Caching) | ⚪ Foundational (Observability, Endpoints) | 🟢 Expert (Spark, Kafka, Lakehouse) |
| **Cloud & DevOps** | 🟡 Proficient (Docker, CI/CD, K8s) | 🟡 Proficient (CI/CD, Test pipelines) | 🟡 Proficient (Cloud storage, compute clusters) |

---

## 🎯 Role-Specific Competency Profiles

### 1. Software Developer / Software Engineer (SWE)
- **Primary Mission**: Build resilient, maintainable, scalable software solutions that deliver business value.
- **Key Competencies**:
  - **Data Structures & Algorithms**: Clean code under pressure, analyzing time/space trade-offs ($O(1)$, $O(N)$, $O(N \log N)$).
  - **Low-Level Design (LLD)**: Applying SOLID principles, factory/strategy/observer patterns, modular class design.
  - **High-Level Design (HLD)**: Architecting distributed systems handling $10^5+$ QPS, horizontal scaling, caching strategies, asynchronous messaging.
  - **Backend & APIs**: REST/gRPC, token-based authentication, database transactions, connection pooling.
- **Interview Threshold**:
  - Solve a LeetCode Medium problem cleanly in 25–30 mins with edge cases.
  - Drive a 45-min system design session from ambiguity to concrete architecture.

### 2. QA Engineer / Software Tester (SDET)
- **Primary Mission**: Advocate for product quality through automated test architecture, exploratory verification, and continuous integration.
- **Key Competencies**:
  - **Test Strategy & Design**: Boundary Value Analysis (BVA), Equivalence Partitioning (EP), exploratory testing techniques.
  - **Automation Frameworks**: Designing maintainable Page Object Model (POM) frameworks using Playwright, Selenium, or Cypress.
  - **API Automation**: Asserting HTTP status codes, payloads, header integrity, latency thresholds using REST Assured or Postman.
  - **Non-Functional Testing**: Simulating high-concurrency traffic with k6 or JMeter; basic security penetration verification.
  - **CI/CD Quality Gates**: Integrating automated tests into GitHub Actions or Jenkins to prevent regressions.
- **Interview Threshold**:
  - Design comprehensive edge-case test suites for ambiguous product scenarios.
  - Write clean, non-flaky automation code with proper synchronization and assertions.

### 3. Data Engineer (DE)
- **Primary Mission**: Build, optimize, and maintain scalable data pipelines and analytical infrastructure.
- **Key Competencies**:
  - **SQL & Data Modeling**: Master-level SQL (complex joins, aggregations, windowing), Star vs Snowflake schemas, SCD Types.
  - **Batch Processing**: Apache Spark internals (Catalyst optimizer, DAG execution, partition management, handling data skew).
  - **Streaming Data**: Event ingestion with Apache Kafka (producers, consumers, partition rebalancing, watermarking).
  - **Storage & Lakehouse**: Parquet/ORC columnar formats, Delta Lake / Apache Iceberg ACID semantics.
  - **Orchestration**: Building reliable, idempotent DAGs in Apache Airflow with retry policies and SLA alerting.
- **Interview Threshold**:
  - Write efficient SQL queries solving analytical windowing problems.
  - Architect high-throughput data pipelines capable of batch and near-real-time streaming.
