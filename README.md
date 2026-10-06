# Client Service Ordering & Management Platform

Complete full-stack project with separate frontend and backend folders.

## Structure
- `frontend/` — HTML, CSS, JavaScript, logo, client pages, admin page, tracking page.
- `backend/` — Node.js + Express API/server, MongoDB/Mongoose, email, uploads and order management.

## Run on Windows
```cmd
cd C:\projects\NEXORA_Client_Service_Platform_COMPLETE\backend
npm install
copy .env.example .env
notepad .env
npm start
```
Then open `http://localhost:5000`.

Admin: `http://localhost:5000/admin.html`
Tracking: `http://localhost:5000/track.html`

## Environment
Set `MONGODB_URI`, `GMAIL_USER`, `GMAIL_APP_PASSWORD`, `ADMIN_KEY`, `PUBLIC_BASE_URL`, and payment settings in `.env`.
Never commit or share `.env`.
