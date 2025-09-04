GoBus Booking Management (split: backend & frontend)

Quick start:
1) Backend
   cd backend
   copy .env.example .env
   npm install
   npm run seed
   npm run dev

2) Frontend (new terminal)
   cd ../frontend
   npm install
   npm run dev

Open http://localhost:5173

Flow
- 54-seat map, 'W' = Window seats
- Proceed -> Passenger Details (enter data, see 10% handling fee)
- Confirmation shows summary
