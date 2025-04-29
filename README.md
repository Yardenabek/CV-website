# Personal CV Website

A clean, modern, and responsive personal CV website designed to be hosted on GitHub Pages.

## Features

- Responsive design that works on all devices
- Modern and clean UI with smooth animations
- Timeline component for education and experience
- Skills section with tags
- Project showcase
- Contact information with social links
- Mobile-friendly navigation

## Deployment

This website is designed to be deployed on GitHub Pages. To deploy:

1. Fork this repository
2. Go to your repository settings
3. Navigate to "Pages" in the sidebar
4. Under "Source", select "main" branch
5. Click "Save"

Your site will be published at `https://[your-username].github.io/CV-website`

## Customization

### Content Updates

To update the content:

1. Edit `index.html` to modify text content
2. Update `assets/css/style.css` to change styling
3. Modify `assets/js/main.js` for JavaScript functionality

### Adding a Profile Picture

1. Add your profile picture to the `assets/images` directory
2. Update the profile image placeholder in `index.html`:
   ```html
   <div class="profile-image-placeholder">
       <img src="assets/images/your-photo.jpg" alt="Your Name" class="profile-image">
   </div>
   ```

### Color Scheme

The color scheme can be modified by updating the CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
    --border-color: #e5e7eb;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE). 