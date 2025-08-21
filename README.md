# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional skills, certificates, and provides multiple ways for visitors to get in touch.

## Features

### 🎯 **Main Index Page (`index.html`)**
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Section**: Skills showcase organized by category (Frontend, Backend, Tools)
- **Certificates Section**: Professional certifications and achievements
- **Contact Section**: Contact form and information
- **Responsive Design**: Mobile-first approach with smooth animations

### 📖 **Individual Pages**
- **About Page** (`about.html`): Detailed information about skills, experience, and approach
- **Certificates Page** (`certificates.html`): Comprehensive list of all certifications with details
- **Contact Page** (`contact.html`): Extended contact form with project details and alternative contact methods

### ✨ **Key Features**
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Interactive Elements**: Hover effects, animations, and form validation
- **Modern UI/UX**: Clean design with gradient backgrounds and shadows
- **Font Awesome Icons**: Professional iconography throughout
- **Form Handling**: Contact form with validation and notifications
- **Responsive Grid**: CSS Grid and Flexbox for modern layouts

## File Structure

```
portfolio/
├── index.html          # Main page with all sections
├── about.html          # Dedicated About page
├── certificates.html   # Dedicated Certificates page
├── contact.html        # Dedicated Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactive functionality and form handling
- **Font Awesome**: Professional icons
- **Responsive Design**: Mobile-first approach

## Getting Started

### Prerequisites
- A modern web browser
- Basic understanding of HTML/CSS/JavaScript (for customization)

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. Navigate through the different sections using the navigation menu

### Customization

#### Personal Information
- Update contact details in all HTML files
- Replace placeholder content with your actual information
- Modify the hero section text and buttons

#### Styling
- Edit `styles.css` to change colors, fonts, and layouts
- Modify the color scheme by updating CSS variables
- Adjust animations and transitions

#### Content
- Add your actual certificates and achievements
- Update the skills section with your expertise
- Modify the about section with your personal story

#### Images
- Replace placeholder icons with actual profile photos
- Add project screenshots or portfolio images
- Update social media links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Performance Features

- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Smooth Animations**: Hardware-accelerated CSS transitions
- **Lazy Loading**: Intersection Observer for scroll animations
- **Minimal JavaScript**: Lightweight and efficient code

## Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Keyboard Navigation**: Full keyboard accessibility
- **Screen Reader Support**: ARIA labels and semantic markup
- **Color Contrast**: WCAG compliant color combinations
- **Focus Indicators**: Clear focus states for interactive elements

## Contact Form Features

- **Form Validation**: Client-side validation with helpful error messages
- **Project Details**: Comprehensive project information collection
- **Multiple Contact Methods**: Email, phone, social media, and scheduling options
- **Success Notifications**: User feedback for form submissions

## Customization Examples

### Changing the Color Scheme
```css
/* Update primary colors in styles.css */
:root {
    --primary-color: #3498db;
    --secondary-color: #667eea;
    --accent-color: #764ba2;
}
```

### Adding New Sections
```html
<!-- Add new sections in index.html -->
<section id="projects" class="projects">
    <div class="container">
        <h2 class="section-title">My Projects</h2>
        <!-- Add your project content here -->
    </div>
</section>
```

### Modifying Animations
```css
/* Adjust animation timing in styles.css */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(50px); /* Increase distance */
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

## Deployment

### Local Development
- Open files directly in a web browser
- Use a local server for testing (e.g., Live Server in VS Code)

### Web Hosting
- Upload all files to your web hosting provider
- Ensure all file paths are correct
- Test functionality after deployment

### GitHub Pages
- Push code to a GitHub repository
- Enable GitHub Pages in repository settings
- Your portfolio will be available at `username.github.io/repository-name`

## Troubleshooting

### Common Issues

1. **Font Awesome Icons Not Loading**
   - Check internet connection (CDN dependency)
   - Verify the CDN link is correct

2. **Styles Not Applying**
   - Ensure `styles.css` is in the same directory
   - Check file paths in HTML files

3. **JavaScript Not Working**
   - Verify `script.js` is in the same directory
   - Check browser console for errors

4. **Mobile Menu Not Working**
   - Ensure JavaScript is enabled
   - Check for CSS conflicts

## Contributing

Feel free to submit issues, feature requests, or pull requests to improve this portfolio template.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing or have questions about the portfolio:
- Check the browser console for JavaScript errors
- Verify all file paths are correct
- Ensure all dependencies are properly linked

---

**Happy coding! 🚀**

*This portfolio template is designed to be easily customizable while maintaining professional appearance and functionality.*
