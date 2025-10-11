# 🎬 My Movie Finder (React + TMDB API)

A modern and responsive movie search app built with **React** and **Vite**, using **The Movie Database (TMDB) API**.  
Easily search for movies, explore trending titles, and enjoy a smooth, fast user experience.

---

## 🚀 Features

- 🔍 **Search movies** by title in real time (with debounce to reduce API calls)
- 📈 **View trending movies** fetched from Appwrite database
- 🧠 **Debounced search input** for optimized performance
- 🔄 **Loading spinner** for smoother UX
- ⚙️ **Environment variables** for secure API key handling
- 🧩 **Modular React components** (MovieCard, Search, Spinner)
- 🌐 **Fully responsive UI**

---

## 🧰 Tech Stack

- **React 18 + Vite**
- **TMDB API (v4 Auth Token)**
- **Appwrite** for trending movies & analytics
- **JavaScript (ES6+)**
- **Tailwind CSS** *(optional, if used for styling)*

---

## 🗂️ Project Structure

my-first-react-app/
├── public/
├── src/
│ ├── assets/
│ ├── components/
│ │ ├── MovieCard.jsx
│ │ ├── Search.jsx
│ │ └── Spinner.jsx
│ ├── App.jsx
│ ├── appwrite.js
│ ├── index.css
│ └── main.jsx
├── .env.local
├── package.json
├── vite.config.js
└── README.md

## ⚙️ Environment Variables

Create a `.env.local` file in the root directory and add your TMDB API key:
VITE_TMDB_API_KEY=your_tmdb_v4_access_token


> ⚠️ Use your **v4 Read Access Token** from [TMDB API settings](https://www.themoviedb.org/settings/api).  
> Do **not** commit `.env.local` to GitHub.

---

## 🧑‍💻 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/my-movie-finder.git
   cd my-movie-finder

2. Install dependencies
npm install


3. Run the development server
npm run dev


4. Build for production
npm run build

## 🖼️ Preview

Here’s what the app looks like:
🔹 Search Bar to find movies
🔹 Trending Movies section
🔹 Movie Cards with posters, titles, and release info
🔹 Spinner while fetching

## 🧾 License
This project is licensed under the MIT License – you’re free to use, modify, and distribute it.

## 💡 Credits

The Movie Database (TMDB):
    for movie data
Appwrite:
    for backend integration

Built by Khelif Abdellah with ❤️ using React and Vite