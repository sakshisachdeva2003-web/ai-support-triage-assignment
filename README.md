# AI-Powered Support Ticket Triage

## Run

```bash
npm install
```

Create `backend/.env`:

```bash
DATABASE_URL="file:./dev.db"
```

Start the backend:

```bash
cd backend
npx prisma generate
npx prisma db push
npm run dev
```

Start the frontend in a second terminal:

```bash
cd frontend
npm run dev
```

Open:

- Frontend: `http://localhost:5173`
- Backend: `http://localhost:4000`

Run tests:

```bash
cd backend
npm run test
```
