# Movie App

A simple movie browsing web app built with HTML, CSS, and JavaScript. It displays a list of popular movies from The Movie Database (TMDB) and lets users search for movies by title. Check the app here:

https://julianhoxha.github.io/MovieApp/

## Features

- Displays popular movies on page load
- Search movies by title using the TMDB API
- Shows movie poster, title, rating, and overview
- Color-coded rating badges for quick review
- Hover effect to reveal movie overview
- Clean dark-themed layout

## Tech Stack

- HTML5
- CSS3
- JavaScript
- TMDB API

## Project Structure

- `index.html` – App structure and layout
- `style.css` – Styling for the page and movie cards
- `script.js` – Fetches movie data and renders it to the page
- `image/` – Stored image assets

## How to Run

1. Open the project folder in your browser.
2. Open `index.html` directly in a web browser.
3. Make sure you have an internet connection, because the app fetches data from TMDB.

## Notes

- The app uses a TMDB API key stored directly in `script.js`.
- If the API request stops working, you may need to generate a new API key from the TMDB website.
- This is a front-end demo project and does not require a backend or build step.

## Example Behavior

- On load, the app fetches trending/popular movies.
- When a user enters a movie name and submits the search form, it requests matching results from TMDB and updates the page.

## License

This project is for educational/demo purposes.
