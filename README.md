# 🎧 SpotifyClone — UI/UX Clone with Streaming, Auth & Cloudinary

A Spotify-inspired web application with media playback, album & track management, user authentication via Clerk, and media uploading to Cloudinary.

## ✨ Features

- 🔑 OAuth login & session management (Clerk)
- 🎵 Audio playback
- 📂 Upload songs & albums
- 🧩 Modular layout with Sidebar/NowPlaying
- 🔄 Real-time interaction via WebSockets
- 🎨 Responsive UI with Radix UI

## 📁 Structure

```
spotifyClone/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── features/
│   │   └── routes/
├── backend/
│   ├── src/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── controllers/
│   │   └── utils/
│   ├── seeds/
│   └── .env
```

## ⚙️ Setup

```bash
cd frontend && npm install
cd ../backend && npm install

cd backend && npm run dev
cd ../frontend && npm run dev
```

Seed data:
```bash
cd backend
npm run seed:songs
npm run seed:albums
```

`.env` backend:

```
MONGO_URI=...
CLERK_SECRET_KEY=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

---

## 📃 License

All projects are licensed under the MIT License.
