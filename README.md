
# 🎵 Spotify Album Finder

A React + Vite app that lets users search for an artist and view their albums using the **Spotify Web API**.  
Built with **React Bootstrap** for UI and deployed on **Netlify**.

---

## ✨ Features
- 🔎 Search artists by name
- 💿 View albums with cover art, release date, and Spotify link
- 🎨 Clean UI with React Bootstrap
- 🚀 Fast build & deployment with Vite + Netlify

---

## ⚙️ Setup

### 1. Clone & Install
```bash
git clone https://github.com/tanisha685/Spotify-Album-finder.git
cd codex-api-template
npm install
````

### 2. Spotify App Setup

* Create an app on [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
* Copy **Client ID** & **Client Secret**.
* Add a redirect URI (e.g. `http://127.0.0.1:5173` and your Netlify URL).

### 3. Environment Variables

Create `.env` in project root:

```env
VITE_CLIENT_ID=your_spotify_client_id
VITE_CLIENT_SECRET=your_spotify_client_secret
```

### 4. Run Locally

```bash
npm run dev
```

### 5. Build for Production

```bash
npm run build
```

Deploy the `dist/` folder on **Netlify**.

---

## 🚀 Live Demo

[Netlify Deployment Link](https://album-finder-tanisha1.netlify.app/)

```

---

Do you also want me to make a **short tagline (1 line)** under the title like _“Search any artist and explore their albums instantly with Spotify API”_?
```
