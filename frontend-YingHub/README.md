# Frontend (GitHub Pages)

Drop the `dist` folder contents into your GitHub Pages repository (root or docs/).
Edit `app.js` (or the `BACKEND_URL` variable inside `index.html`) to point to your deployed backend URL (Railway).

This simple static site:
- Provides a login form that obtains a JWT from the backend.
- If the logged-in user is `admin`, shows an admin panel to create users and list users.
- Stores the JWT in localStorage (change to cookies if you prefer).

⚠️ Security note: keep your backend URL protected with HTTPS in production.
