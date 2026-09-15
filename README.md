# Watchlist

A simple movie & series tracker that runs entirely in your browser. Search for titles, save them to your watchlist, and mark them as watched — all stored in localStorage.

## Features

- Search movies and series via the [OMDB API](https://www.omdbapi.com/)
- View IMDb, Rotten Tomatoes, and Metascore ratings
- Filter and sort by type, genre, rating, or date added
- Add personal notes to any title
- Separate Watchlist and Watched lists
- Export/import data as JSON
- Works as a PWA on iOS (add to home screen)

## Setup

1. Open `index.html` in a browser (or deploy to GitHub Pages / any static host)
2. Go to **Settings** and enter your [OMDB API key](https://www.omdbapi.com/apikey.aspx) (free tier available)
3. Start searching

## Tech

Single HTML file — no build tools, no dependencies, no server. All data lives in `localStorage`.
