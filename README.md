# FitFlow Redesign

Technology foundation for the FitFlow fitness-app redesign (SLIIT IT3060 – HCI, Lab 05).
This repo holds the code services and all supporting documentation produced across Labs 01–05.

## Recommended Stack
| Layer | Choice |
|---|---|
| Frontend | React Native (+ React Native Web) |
| Backend API | NestJS (Node.js) |
| AI / ML | Python FastAPI service + TensorFlow Lite / ML Kit on-device |
| Real-time DB | Firebase Firestore |
| Relational DB | PostgreSQL |
| Cache | Redis |
| Auth | Firebase Auth (MFA) |
| Storage | Firebase Storage / S3 |

See `docs/` for the full comparison matrix, tech-stack summary, architecture diagram and ADRs.

## Structure
- `frontend/` – React Native (+ RN Web) app
- `backend/` – NestJS core API
- `ai-service/` – Python FastAPI AI microservice
- `docs/` – documentation, comparison matrix, architecture, ADRs
- `.github/workflows/` – CI/CD

## Running (once code is added)
```bash
cd frontend && npm install && npm start
cd backend && npm install && npm run start:dev
cd ai-service && pip install -r requirements.txt && uvicorn app.main:app --reload
```
