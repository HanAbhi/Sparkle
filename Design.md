# Saarthi AI – Design Document

## System Flow

1. User submits query via chat or voice.
2. Speech-to-text (if voice input).
3. NLP engine detects intent and extracts entities.
4. User context is matched with scheme database.
5. Recommendation engine filters eligible schemes.
6. System generates simplified explanation.
7. Optional: document checklist and reminders created.
8. Response delivered via text or voice.

---

## Tech Stack

### Frontend
- Web App / Mobile App
- WhatsApp Bot Integration
- IVR Call System (future)

### Backend
- NLP + NLU engine (Intent Detection, Entity Recognition)
- Local language language models
- Scheme database API integration
- Recommendation engine
- Document parser

### Infrastructure
- Cloud deployment (AWS / GCP)
- REST APIs
- Database (PostgreSQL / NoSQL)
- Edge caching for low-bandwidth mode

---

## Architecture Overview

Frontend Layer:
User interacts via chat or voice interface.

Processing Layer:
NLP engine processes user input.
Intent detection and entity extraction occur.
System queries scheme database.

Logic Layer:
Recommendation engine filters relevant schemes.
Eligibility rules applied.
Checklist generator created.

Response Layer:
Simplified response generated.
Voice output optional.
Notifications scheduled if enabled.

---

## Future Scope

- Integration with DigiLocker
- Aadhaar-based authentication (with consent)
- Real-time government API integration
- AI-based form auto-fill
- District-level analytics dashboard
- Expansion to skill and job matching
- Offline SMS-based interaction mode
