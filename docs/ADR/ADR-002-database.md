# ADR-002 — Hybrid database (Firestore + PostgreSQL)

- **Status:** Accepted
- **Context:** The app needs both live, offline-capable social data and structured,
  compliance-sensitive health data.
- **Decision:** Use Firestore for real-time/offline social data and PostgreSQL as the system of
  record for health and analytical data.
- **Consequences:** (+) each workload uses the right tool. (−) two data stores to operate,
  mitigated by clear ownership boundaries.
