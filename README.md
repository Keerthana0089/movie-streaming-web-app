🎬 Movie Streaming Web App
A Netflix-like modern UI React application for exploring, favoriting, and AI-suggested movies.

Can be accessed by live link `https://movie-streaming-web-app-kappa.vercel.app/`
Use the demo Creditionals to login and check as it is ProtectedRoute

📌 Table of Contents
1. Project Overview  
2. Tech Stack  
3. Features  
4. Folder Structure  
5. How to Run  
6. API Reference  
7. Deployment  
8. Screenshots  
9. Future Improvements  
10. Credits


🧠 Project Overview
This is a fully responsive, theme-switchable Movie Streaming web application built with React.js. It allows users to:
- View trending and popular movies
- Search for movies by name
- Mark favorites
- Get AI-based movie suggestions
- Switch between Light and Dark modes
- Responsive UI for all screen sizes


⚙️ Tech Stack
- 💻 React.js (Frontend)
- 🎨 CSS3 (Custom styling)
- 📦 React Router (Routing)
- ☁️ TMDB API (Movie data)
- ⚙️ Vercel (Deployment)
- 🌗 ThemeContext API (Dark/Light mode)
- 📱 Responsive Design

📁 Folder Structure
src/

├── api/              # API calls (TMDB)

├── assets/           # Images, logos

├── components/       # Reusable components (Navbar, MovieCard, etc.)

├── context/          # Theme context

├── pages/            # Home, Trending, Favorites, Search

├── styles/           # Global and component styles

├── App.js            # Root component

├── index.js          # Entry point


🚀 How to Run Locally

Prerequisites
- Node.js & npm installed

#Steps
```bash
git clone https://github.com/Keerthana0089/movie-streaming-web-app.git
cd movie-streaming-web-app
npm install
npm run dev

Runs on `http://localhost:5173`



📡 API Reference

- Base URL: `https://api.themoviedb.org/3`
- Endpoints:
  - `/trending/movie/day`
  - `/search/movie`
  - `/movie/{id}`
- API Key used is stored securely in `.env`

🖼️ Screenshots
🏠 Homepage  
![Home](screenshots/home.png)

🔍 Search  
![Search](screenshots/search.png)

❤️ Favorites  
![Favorites](screenshots/favorites.png)

🤖 AI Suggestion  
![AI Modal](screenshots/ai-suggest.png)

🔧 Future Improvements

- ✅ Pagination in Trending/Search
- 🧠 Smarter AI suggestions using user behavior
- 🛡️ User authentication with backend (JWT/Firebase)
- 📱 Progressive Web App (PWA) version
- 🧩 Add Genres/Filters


Credits
- TMDB for movie data
- Font Awesome Icons
- React & Vercel ecosystem
