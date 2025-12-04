# 🎬 The Movie House

A modern movie discovery web application that lets users search, explore, and view trending movies based on real user activity. Built using **React**, **Tailwind CSS**, **TMDB API**, and **Appwrite** for backend + database storage.

---

## 🚀 Features

### 🔍 Movie Search
- Search any movie using the **TMDB API**  
- Debounced search (`useDebounce`) to minimize API calls  
- Real-time results with posters, titles, and descriptions  

### 📈 User-Driven Trending Movies
- Trending section updates based on **what users search for**  
- Each search increases a count stored in **Appwrite Database**  
- Movies with the highest search frequency appear in the Trending list  

### 🎥 Movie Display
- Clean, responsive UI using **TailwindCSS**  
- High-quality posters from TMDB  
- Smooth UI experience using React hooks  

### 🗄️ Backend & Storage (Appwrite)
- Appwrite handles:
  - Storing user search activity  
  - Counting searches  
  - Fetching trending data  
- All API keys stored safely in `.env.local`

---

## 🛠️ Tech Stack

### Frontend
- **React.js**
- **Vite**
- **Tailwind CSS**
- React Hooks: `useState`, `useEffect`, `useCallback`, `useDebounce`

### Backend / Database
- **Appwrite Cloud**
  - Database
  - Collections
  - Secure API interactions

### External API
- **TMDB API** for movies, posters, and search results

---
