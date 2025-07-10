# Circular Sector Drawing App

This is a simple interactive web app built with the ArcGIS API for JavaScript 4.x. It allows users to:

- Click on the map to set the center of a circular sector
- Enter direction, angle, and radius parameters
- See an instant preview of the sector drawn on the map

## How to use

1. **Clone** or **download** this repository.
2. Ensure you're connected to the internet (for ArcGIS JS API).
3. Open `index.html` in your browser to test locally.
4. To host it online, push to a GitHub repository and enable **GitHub Pages** via repo settings.
5. Share the resulting URL with others.

---

## Features 📐

- Uses `geometryEngine.destination()` to compute perimeter points based on bearing and distance
- Draws a sector polygon dynamically with client-side JS
- Includes a clear button to reset the view

---

## License

MIT License
