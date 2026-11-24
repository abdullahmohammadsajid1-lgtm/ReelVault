# ReelVault — Cinema & Series Explorer

**ReelVault** is a responsive, API-driven web application for exploring movies and TV series. Built with vanilla HTML, CSS, and JavaScript, it features live search, category browsing, type filtering, detailed title modals, and persistent favorites stored in the browser.

## Features

- **Live Catalog Search:** Search films and TV series in real time via the OMDb API.
- **Curated Categories & Type Filters:** Browse quick picks (Popular, DC & Batman, Marvel, Sci-Fi, Mystery, Action) and filter results by **All**, **Movies**, or **Series**.
- **Title Details Modal:** View IMDb ratings, release year, runtime, maturity rating, full plot summary, genre, director, and cast.
- **Persistent Favorites:** Save or remove titles in your Favorites tab using `localStorage`, retaining your list across page reloads.
- **Complete UI States:** Smooth loading spinner, clear error alerts, and empty state guidance.
- **Responsive Dark Interface:** Midnight Slate and Emerald Mint theme optimized for desktop and mobile devices.

## Tech Stack

- **HTML5**
- **CSS3** (Flexbox, CSS Grid, Custom Properties, Responsive Design)
- **JavaScript (ES6+)** (Fetch API, Async/Await, DOM Manipulation, Array Methods, Local Storage)
- **OMDb API**

## Project Structure

```text
reelvault-app/
├── index.html      # Main layout and title details modal
├── style.css       # Midnight Slate & Emerald Mint responsive styling
├── script.js       # API integration, filtering, and favorites logic
└── README.md       # Project documentation
```

## How to Run

1. Extract or clone the project folder.
2. Open `index.html` in any modern web browser (or run using VS Code Live Server).
