# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🚀 Fast loading and optimized
- ♿ Accessible design
- 📧 Contact form ready for integration

## Sections

1. **Hero Section** - Introduction with call-to-action buttons
2. **About Section** - Personal information and statistics
3. **Skills Section** - Technical skills and expertise
4. **Projects Section** - Portfolio showcase
5. **Contact Section** - Contact form and information

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content with your own information

## Customization

### Update Personal Information

1. **Hero Section** (`index.html`):
   - Change "Your Name" to your actual name
   - Update the job title
   - Modify the description
   - Add your social media links

2. **About Section**:
   - Replace placeholder images with your photos
   - Update the about text
   - Modify statistics (projects, experience, clients)

3. **Skills Section**:
   - Update skill cards with your technologies
   - Adjust skill percentages in the progress bars

4. **Projects Section**:
   - Replace placeholder images with project screenshots
   - Update project titles and descriptions
   - Add your project links (GitHub, live demo)

5. **Contact Section**:
   - Update contact information (email, phone, location)
   - Configure the contact form to work with your backend/email service

### Change Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Add Images

Replace placeholder images:
- Profile image: Update the `src` attribute in the hero section
- About image: Update the `src` in the about section
- Project images: Replace placeholder URLs with your project screenshots

## Contact Form Integration

The contact form is currently set up with basic validation. To make it functional:

1. **Backend Integration**: Connect to a backend service (Node.js, PHP, Python, etc.)
2. **Email Service**: Use services like:
   - EmailJS
   - Formspree
   - Netlify Forms
   - Custom backend API

Example with EmailJS:
```javascript
// Add EmailJS script to HTML
// Update form submission handler in script.js
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal and commercial use.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)

---

Made with ❤️ for showcasing your work

