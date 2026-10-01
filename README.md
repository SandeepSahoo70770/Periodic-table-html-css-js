# Interactive 3D Periodic Table

An interactive periodic table web application with animated 3D layouts, built using HTML, CSS, and JavaScript.

![Tech](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tech](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tech](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Features

- **5 Layout Modes**: Table, Sphere, Helix, Grid, and Random
- **3D Parallax Effect**: Scene tilts dynamically based on cursor position
- **Animated Transitions**: Smooth spring-based animations between layouts
- **Element Details**: Click any element to expand and view properties (atomic mass, density, melting/boiling points)
- **Keyboard Support**: Press `Escape` to collapse expanded elements
- **Responsive Design**: Adapts to different screen sizes
- **Color-Coded Categories**: Elements colored by type (noble gases, alkali metals, etc.)

## Technologies Used

- **HTML5** — Semantic markup with template-based rendering
- **CSS3** — Custom properties, 3D transforms, CSS Grid, Flexbox, animations
- **JavaScript (ES Modules)** — Dynamic DOM generation, event handling
- **Anime.js v4.3.0** — Animation engine (loaded via CDN)

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/SandeepSahoo70770/Periodic-table-html-css-js.git
   ```

2. Open `index.html` in your browser.

That's it! No build step or server required.

## Usage

| Action | How |
|--------|-----|
| Switch layout | Click the layout buttons at the top (table, sphere, helix, grid, random) |
| View element details | Click on any element card |
| Collapse element | Click the element again or press `Escape` |
| Tilt scene | Move your cursor around the viewport |

## Project Structure

```
Periodic-table-html-css-js/
├── index.html      # Main HTML structure
├── style.css       # All styles, CSS variables, and responsive rules
├── script.js       # Element data, DOM generation, layouts, and interactions
└── README.md       # This file
```

## Credits

- 3D transform calculations ported from the [three.js CSS3D periodic table demo](https://threejs.org/examples/css3d_periodictable.html)
- Made with ❤️ by [mr____sandeep____0007](https://www.instagram.com/mr____sandeep____0007/)
