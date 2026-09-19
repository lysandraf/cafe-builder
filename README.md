# ☕ Cafe Builder

A free, real-time cafe finder web app built with JavaScript, Leaflet.js, and OpenStreetMap. Find nearby cafes, view them on an interactive map, and save your favorites — no API key, no billing account, no sign-up required.

## Features

- 📍 **Live location detection** — automatically centers the map on your current location (or click anywhere on the map to search that area instead)
- ☕ **Real-time cafe data** — pulls live results from OpenStreetMap's Overpass API
- 🗺️ **Interactive map** — see every nearby cafe as a pin, click for details
- ⭐ **Favorites** — star cafes to save them locally in your browser
- 🔍 **Search & filter** — search by name, or filter to just your favorites
- 📏 **Adjustable radius** — search within 1 km, 2 km, 5 km, or 10 km
- 📱 **Responsive design** — works on desktop and mobile

## How to run it

### Option 1: Try it live
Visit the GitHub Pages link (see the "About" section of this repo, once Pages is enabled).

### Option 2: Run it locally
1. Clone or download this repo
2. Open `index.html` directly in your browser, **or** for the most reliable experience (especially for location access), serve it locally:
```bash
   python3 -m http.server
```
   or
```bash
   npx serve
```
3. Open the local URL shown in your terminal

## Tech stack

- **HTML/CSS/JavaScript** — no frameworks, no build step
- **[Leaflet.js](https://leafletjs.com/)** — map rendering
- **[OpenStreetMap](https://www.openstreetmap.org/)** — map tiles
- **[Overpass API](https://overpass-api.de/)** — real-time cafe location data

## Notes

Cafe data comes from OpenStreetMap's community-maintained database, so coverage and detail (like ratings or live hours) may vary by location, especially in less-mapped areas.

## License

No license currently set — all rights reserved by default.
