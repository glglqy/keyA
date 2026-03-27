# KeyA the AI Webpage

A simple, responsive webpage showcasing "KeyA the AI" with a modern design and light blue background.

## Files

- `index.html` - Main HTML file
- `style.css` - Stylesheet with responsive design
- `README.md` - This file

## Image Source

The image is loaded from `../acca7b3a844bbdf4.jpg` (relative path to the Desktop).

## How to View

1. Open `index.html` in any modern web browser
2. Alternatively, you can serve it locally with a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000

   # Then visit http://localhost:8000
   ```

## Features

- Responsive design (mobile-friendly)
- Modern card-based layout
- Interactive hover effects
- Light blue gradient background
- Font Awesome icons
- Google Fonts (Inter)
- Simple JavaScript for interactivity

## Customization

To change the background color, edit the `background` property in `style.css` (line 12):
```css
background: linear-gradient(135deg, #e6f7ff 0%, #f0f9ff 100%);
```

To change the image, replace `../acca7b3a844bbdf4.jpg` with your image path in `index.html` (line 24).

## Browser Support

Compatible with all modern browsers (Chrome, Firefox, Safari, Edge).