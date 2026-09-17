MAA SHYAMAKALI PUJA - COMPLETE WEBSITE

FRONTEND:
Open index.html locally, or upload the frontend files to GitHub Pages.

BACKEND:
1. Install Node.js.
2. Open the backend folder in a terminal.
3. Run: npm install
4. Set an environment variable ADMIN_KEY to a secret value.
5. Run: npm start
6. Backend runs on http://localhost:3000
7. After online deployment, edit config.js and set API_BASE_URL to the deployed backend URL.

DATABASE:
SQLite database file messages.db is created automatically by server.js.
For production hosting, use a host with persistent disk or replace SQLite with a managed PostgreSQL database.

ADMIN API:
GET /api/admin/messages with header x-admin-key: YOUR_SECRET
DELETE /api/admin/messages/ID with the same header.

PRIVACY:
The public API returns only visitor name, message and date/time.
Mobile number and address remain private in the database/admin API.
Never commit your ADMIN_KEY to GitHub.

VIDEO:
Put your MP4 at videos/puja-video.mp4.

EDITING:
Committee sample details are in index.html. Basic public text can also be edited there.
