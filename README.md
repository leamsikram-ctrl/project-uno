# GitHub Pages Hosting

This is a simple static web application ready to be hosted on GitHub Pages.

## Features

- ✨ Clean, responsive HTML/CSS/JavaScript
- 📱 Mobile-friendly design
- 🎨 Modern gradient styling
- ⚡ Smooth animations and interactions
- 📝 Contact form with validation
- 🔗 Smooth navigation

## File Structure

```
project-uno/
├── index.html       # Main HTML file
├── style.css        # Stylesheet with responsive design
├── script.js        # JavaScript for interactivity
├── README.md        # This file
├── LICENSE          # Project license
└── .gitignore       # Git ignore file
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/leamsikram-ctrl/project-uno.git
   cd project-uno
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## GitHub Pages Setup

To deploy this site on GitHub Pages:

1. **If using the `main` branch:**
   - Go to your repository settings
   - Navigate to "Pages"
   - Select "Deploy from a branch"
   - Choose `main` branch and `/root` folder
   - Click "Save"

2. **If using a `gh-pages` branch:**
   ```bash
   git checkout -b gh-pages
   git push origin gh-pages
   ```
   - Then go to repository settings → Pages
   - Select `gh-pages` branch
   - Click "Save"

3. Your site will be available at: `https://leamsikram-ctrl.github.io/project-uno/`

## Customization

### Update Site Content
- Edit `index.html` to change page content
- Modify `style.css` for colors, fonts, and layout
- Update `script.js` for interactive features

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #0066cc;
    --secondary-color: #00cc66;
    --dark-bg: #1a1a1a;
    --light-bg: #f5f5f5;
}
```

### Add New Sections
1. Add a new `<section>` element in `index.html`
2. Add corresponding styles in `style.css`
3. Add navigation link in the navbar
4. Add JavaScript functionality in `script.js` if needed

## Features Included

### Navigation
- Sticky navbar with smooth scrolling
- Active section highlighting

### Hero Section
- Eye-catching gradient background
- Call-to-action button

### About Section
- Information about the project
- Feature highlights

### Contact Section
- Contact form with validation
- Success/error messages

### Responsive Design
- Works on desktop, tablet, and mobile
- Adaptive layouts and font sizes

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- No external dependencies (pure HTML/CSS/JS)
- Optimized for fast loading
- Minimal JavaScript footprint
- Responsive images (when added)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Feel free to fork this repository and submit pull requests for improvements!

## Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [HTML5 Guide](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

Made with ❤️ for GitHub Pages
