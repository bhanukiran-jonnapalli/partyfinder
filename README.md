# PartyFinder 🎮

Find your perfect gaming teammate — powered by AI compatibility matching.

## What it does
- Match with players by game, rank, role and playstyle
- AI generates a compatibility score for every match
- Real-time chat to coordinate before jumping in
- Supports Valorant, CS2 and Genshin Impact

## Tech Stack
| Layer | Tech |
|-------|------|
| Frontend | Angular |
| Backend | Node.js + Express |
| Database | MongoDB |
| Real-time | Socket.io |
| AI | Claude API (Anthropic) |
| Auth | JWT + Google OAuth |
| Payments | Stripe |
| Deploy | Railway + Vercel |

## Status
🚧 Active development — Phase 1 (Core API)

## Structure
```
partyfinder/
├── backend/    # Node.js REST API
├── frontend/   # Angular app
└── README.md
```

## Local Setup
```bash
# Backend
cd backend && npm install && npm run dev

# Frontend
cd frontend && npm install && ng serve
```

---
Built by Kiran
