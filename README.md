# Bonte's Gallery

A beautiful, responsive gallery website showcasing moments captured for Bonte. Built with vanilla HTML, CSS, and JavaScript, featuring dark/light mode toggle and smooth animations.

## Features

- 🌓 **Dark/Light Mode Toggle** - Smooth theme switching with localStorage persistence
- 📱 **Fully Responsive** - Optimized for all device sizes
- 🎨 **Modern Design** - Glass morphism effects with smooth animations
- 🖼️ **Interactive Gallery** - Click images to view in lightbox modal
- ⚡ **Performance Optimized** - Optimized for fast loading
- 🔍 **SEO Friendly** - Complete meta tags for search engines

## Deployment

### Vercel Deployment

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Deploy to Vercel**:
   ```bash
   vercel --prod
   ```

3. **Follow the prompts**:
   - Set up and deploy? `Yes`
   - Which scope? Choose your Vercel account
   - Link to existing project? `No` (for first deployment)
   - What's your project's name? `bonte-gallery` (or your preferred name)
   - In which directory is your code located? `./` (current directory)

4. **Your site will be live** at the provided Vercel URL!

### Alternative Deployment Methods

The site is a static HTML site and can be deployed to any static hosting service:

- **Netlify**: Drag and drop the folder to Netlify
- **GitHub Pages**: Push to GitHub and enable Pages
- **Surge.sh**: `npm install -g surge && surge`
- **Firebase Hosting**: `firebase deploy`

## Local Development

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start local server**:
   ```bash
   npm run dev
   ```

3. **Open** `http://localhost:3000` in your browser

## Project Structure

```
final/
├── index.html          # Main HTML file
├── images/            # Gallery images
├── vercel.json        # Vercel configuration
├── package.json       # Project metadata and scripts
└── README.md         # This file
```

## Customization

### Adding New Images

1. Add your image to the `images/` folder
2. Add a new gallery card in `index.html`:

```html
<div class="gallery-card" onclick="openModal(this)">
    <img src="images/your-image.jpg" alt="Your image description">
    <div class="card-overlay">Your Image Title</div>
</div>
```

### Changing Colors

Edit the CSS variables in the `<style>` section of `index.html`:

```css
:root {
    --accent-color: #a68080;  /* Change this color */
    /* ... other variables */
}
```

## Browser Support

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

MIT License - feel free to use this project for your own purposes!

---

Made with ❤️ by MUNEZERO Alpha
