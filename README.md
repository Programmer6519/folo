

# folo

Backend for Folo — a minimal Instagram-like web app. This repository contains starter backend files (Express + Sequelize + MySQL) and a frontend placeholder.

Backend quickstart

1. Open a terminal and navigate to the backend folder:

```powershell
cd C:\Users\Ghazi\Documents\folo\backend
```

2. Install dependencies:

```powershell
npm install
```

3. Copy the sample `.env` and fill in your values (MySQL credentials, `JWT_SECRET`, and Cloudinary keys):

```powershell
copy .env .env.local
# then edit .env.local in your editor
```

4. Start the dev server (requires `nodemon`):

```powershell
npm run dev
```

Notes
- Sequelize is used as the ORM; configure `backend/config/db.js` to match your environment or use the provided `.env` values.
- Image uploads are intended to use Cloudinary — set Cloudinary env vars before using upload endpoints.
- This README is minimal — controllers, models and routes will be implemented in the `backend/` folder.

If you want, I can scaffold the frontend or re-populate server controllers and models now.

