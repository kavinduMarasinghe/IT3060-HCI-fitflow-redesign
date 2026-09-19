# Tech Stack Summary

| Layer | Choice | Key reason |
|---|---|---|
| Frontend | React Native (+ RN Web) | One JS/TS language across the stack; largest ecosystem; fast to market |
| AI / ML | Python FastAPI + TensorFlow Lite / ML Kit | Best ML ecosystem for cloud models; on-device inference for speed & offline |
| Backend API | NestJS (Node.js) | Real-time-friendly, typed, shares language with the frontend |
| Real-time DB | Firestore | Live feed, challenges, offline sync and push |
| Relational DB | PostgreSQL | Structured, query-heavy, compliance-grade health data |
| Cache | Redis | AI-result caching, leaderboards, sessions |
| Authentication | Firebase Auth | Drop-in, low-cost, MFA, React Native-native |
| Storage | Firebase Storage / S3 | Meal photos and media |
| Analytics | Firebase Analytics + Mixpanel | Carried over from the case study |
