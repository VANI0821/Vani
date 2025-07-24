# Vani
# Image Carousel
A responsive image carousel with zoom functionality and circular navigation.
## Features
- 4 image carousel with smooth transitions
- Click images to zoom in/out
- Circular navigation dots (50% border-radius)
- Arrow navigation and keyboard support
- Auto-play (5 seconds interval)
- Modern glassmorphism design
## Usage
1. Open index.html in any browser
2. Navigate using dots, arrows, or keyboard
3. Click images to zoom
4. Press ESC to exit zoom
## Customization

*Replace images:* Change the src in HTML:
html
<img src="your-image.jpg" alt="Description" class="carousel-image">


*Change auto-play speed:* Modify the 5000 value in JavaScript:
javascript
}, 5000); // milliseconds


*Adjust zoom level:* Change scale(1.5) in CSS:
css
.carousel-image.zoomed {
    transform: scale(1.5);
}

## Browser Support
Works in all modern browsers (Chrome, Firefox, Safari, Edge).
## File Structure

├── index.html    # Main carousel file
└── README.md     # This file
