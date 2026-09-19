# ADR-001 — Cross-platform framework and overall stack

- **Status:** Accepted
- **Context:** FitFlow must ship a seamless iOS/Android/web fitness experience quickly, with AI
  features and health-data compliance, on a mid-sized-team budget.
- **Decision:** Build the client in React Native (+ RN Web), with a NestJS API, a Python/FastAPI
  AI microservice, a Firestore + PostgreSQL hybrid data layer, Redis cache and Firebase Auth.
- **Consequences:** (+) one JS/TS language across the stack, fastest time-to-market, mature
  ecosystem, clean AI/real-time separation. (−) React Native's web output is less seamless than
  Flutter's and needs RN Web.
- **Alternatives:** Flutter (strong runner-up); Kotlin MP and Swift/SwiftUI (rejected on
  cross-platform reach and development speed).
