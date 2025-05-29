# GTA VI Website Clone

A modern, responsive clone of the Grand Theft Auto VI promotional website, inspired by Rockstar Games' official website design.

## Features

- Responsive design that works on all devices
- Hero section with video background and animated logo
- News section with dynamic content cards
- Media gallery with lightbox functionality
- Newsletter subscription form
- Smooth scrolling and parallax effects
- Modern animations and transitions
- Dark theme with neon accents

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- JavaScript (ES6+)
- Responsive Design
- Intersection Observer API for lazy loading
- Modern CSS animations and transitions

## Setup Instructions

1. Clone the repository:

```bash
git clone [repository-url]
```

2. Navigate to the project directory:

```bash
cd gta-vi-website
```

3. Open `index.html` in your web browser or use a local development server.

## Project Structure

```
gta-vi-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── assets/            # Media assets directory
│   ├── images/        # Image files
│   └── videos/        # Video files
└── README.md          # Project documentation
```

## Customization

### Colors

The website uses CSS variables for easy color customization. You can modify the colors in the `:root` section of `styles.css`:

```css
:root {
  --primary-color: #000000;
  --secondary-color: #ff0000;
  --accent-color: #ff69b4;
  --text-color: #ffffff;
  --highlight-color: #00ff00;
}
```

### Content

To update the content:

1. Replace the images in the `assets` directory
2. Update the text content in `index.html`
3. Modify the news and media items as needed

## Browser Support

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Rockstar Games' official website design
- Uses Helvetica Neue font family
- Implements modern web design practices and animations
