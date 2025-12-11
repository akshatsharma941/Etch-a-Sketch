# Etch-a-Sketch
A browser-based recreation of the classic Etch-a-Sketch toy, built with HTML, CSS, and vanilla JavaScript. This project transforms a simple drawing concept into a fully interactive and customizable web application featuring dynamic grids, shading effects, color controls, and responsive layout behavior.

### Features
1. Click or Click-and-Drag Drawing

Users can draw by clicking individual cells or by holding the mouse button and dragging across the grid. The interface is designed to feel smooth and intuitive.

2. Adjustable Grid Size

The drawing grid can be resized up to a 100×100 resolution. This allows either coarse pixel-art style drawing or fine detail work, depending on preference.

3. Color Selection

A built-in color picker for precise control

A random color generator for experimentation

4. Opacity-Based Shading

Each stroke increases a cell’s opacity by a user-defined amount, enabling gradient-like effects and more nuanced drawing than simple flat fills.

5. Clear/Reset Function

A single button regenerates the grid and clears all cells instantly.

6. Responsive Layout

The drawing area automatically scales relative to the user's screen, maintaining consistent proportions across devices and resolutions.

### How It Works
1. Dynamic Grid Rendering

The script calculates the appropriate grid dimensions based on viewport size, then creates a set of div elements sized to fit perfectly into a square drawing container.

2. Per-Cell Event Handling

Each cell has:

A click listener for direct coloring

A mouseenter listener that activates only while the mouse is held down

Opacity accumulation logic for incremental shading

3. Interaction Logic

A simple isDown boolean tracks whether the mouse is currently pressed. This provides smooth, controlled drag-drawing without requiring complex pointer events.

### Technologies Used

HTML5 for structure

CSS3 for layout, responsiveness, and visual styling

JavaScript (ES6) for rendering, event handling, and application logic

No frameworks or external libraries are used, keeping the implementation lightweight and transparent.


### Project Structure
- index.html
- styles.css
(Inline JavaScript inside index.html)

### Running the Project

1. Download or clone the project repository.

2. Open index.html in any modern browser.

3. Begin drawing.

4. No build tools or installation are required.
