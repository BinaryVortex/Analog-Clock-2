# Analog Clock

Analog Clock Built Using HTML, CSS and JavaScript.


## Preview

![Analog Clock preview](./Screenshot%202024-07-03%20111419.png)


## About

A simple, lightweight analog clock implemented with HTML for structure, CSS for styling, and a small JavaScript snippet to rotate the hour, minute and second hands in real time.

This project is great for beginners who want to practice DOM manipulation, CSS positioning and transforms.


## Features

- Smooth, real-time analog clock using CSS transforms
- Simple, self-contained code (index.html, style.css, script.js)
- Easy to customize size, colors and hand lengths


## How it works (brief)

- The clock face is built with HTML elements positioned around a circular container.
- The three hands (hour, minute, second) are absolutely positioned with their transform-origin set to the bottom so they rotate around the center.
- A short setInterval in `script.js` reads the current time and applies rotation angles to each hand:
  - Seconds: seconds * 6 degrees
  - Minutes: minutes * 6 degrees
  - Hours: hours * 30 degrees + partial offset from minutes


## Run locally

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Analog-Clock-2.git

2. Open `index.html` in your browser (no build tools or server required):

   - Double-click `index.html`, or
   - Run a local static server (optional): `python -m http.server` and open `http://localhost:8000`


## Customize

- style.css — change colors, size (frame width/height), fonts, and shadows
- script.js — adjust hand lengths or rotation math if you want alternate behavior


## Files

- index.html — markup for the clock face
- style.css — styles and layout
- script.js — clock update logic
- Screenshot 2024-07-03 111419.png — preview image used in this README


## Contributing

Contributions, suggestions and improvements are welcome. Feel free to open an issue or submit a pull request.


## License

No license specified. If you want to allow others to use or modify this project, consider adding a LICENSE file (for example MIT).