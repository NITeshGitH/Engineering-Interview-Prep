# Authoritative Source Log & Verification Registry

Every piece of information, architectural pattern, and interview question documented in this repository is cross-referenced with primary documentation and engineering standards. No hallucinations, unverified rules-of-thumb, or copied materials without citation are permitted.

---

## 📚 Standard Sources & Verification Protocol

When researching any topic:
1. **Primary Documentation**: Official project/framework documentation (e.g., PostgreSQL docs, Apache Spark official guide, Python documentation, Playwright docs).
2. **Canonical Books**: Recognized authoritative textbooks (e.g., *Designing Data-Intensive Applications* by Martin Kleppmann, *Clean Code* by Robert C. Martin, *Operating System Concepts* by Silberschatz).
3. **Engineering Blogs**: Verified tech blogs from Netflix, Uber, Meta, Google, LinkedIn engineering.
4. **Original Phrasing**: Technical concepts are synthesized and written in our own original wording to maximize learning and conceptual clarity.

---

## 🗂️ Verification Registry

| Topic / Concept | Authoritative Primary Source | Verified URL / Citation | Verification Date | Scope & Key Notes |
|---|---|---|:---:|---|
| **Data Warehousing & OLAP** | Kimball Group / Modern Data Stack | [Kimball Dimensional Modeling Techniques](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/) | 2026-10-18 | Star vs Snowflake schemas, Fact & Dimension tables |
| **Delta Lake ACID Architecture** | Delta Lake Official Docs | [Delta Lake Documentation](https://docs.delta.io/latest/index.html) | 2026-10-18 | ACID guarantees over cloud object storage |
| **Relational DB & ACID Semantics** | PostgreSQL Documentation | [PostgreSQL Transaction Isolation](https://www.postgresql.org/docs/current/transaction-iso.html) | 2026-10-18 | Dirty reads, non-repeatable reads, serialization anomalies |
| **Distributed Systems Design** | *Designing Data-Intensive Applications* | Martin Kleppmann (O'Reilly Media) | 2026-10-18 | CAP theorem, partitioning, replication, consensus |
| **Web Protocols & HTTP/2, 3** | RFC 9110 (HTTP Semantics) & RFC 9113 | [IETF Datatracker RFC 9110](https://www.rfc-editor.org/rfc/rfc9110) | 2026-10-18 | Multiplexing, stream prioritization, QUIC transport |
| **Software Testing Standards** | ISTQB Foundation Syllabus | [ISTQB Standard Glossary](https://www.istqb.org/) | 2026-10-18 | Boundary Value Analysis, Equivalence Partitioning |
