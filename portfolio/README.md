# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio features a clean design, smooth animations, and is fully responsive across all devices.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, scroll animations, and interactive components
- **Contact Form**: Functional contact form with validation and notifications
- **Smooth Scrolling**: Seamless navigation between sections
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Performance Optimized**: Throttled scroll events and optimized animations
- **Accessibility**: Keyboard navigation support and semantic HTML

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and statistics
3. **Skills Section**: Technical skills organized by category
4. **Projects Section**: Showcase of featured projects with links
5. **Contact Section**: Contact information and working contact form

## Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Flexbox, Grid, animations, and responsive design
- **JavaScript (ES6+)**: Interactive features and modern JavaScript
- **Font Awesome**: Icons for skills and social links
- **Google Fonts**: Inter font family for typography

## Getting Started

1. **Clone or Download**: Download all files to your local machine
2. **Customize Content**: 
   - Replace placeholder images with your photos
   - Update personal information in `index.html`
   - Modify project details and links
   - Update contact information
3. **Deploy**: Upload files to your web hosting service

## Customization Guide

### Personal Information
Update the following in `index.html`:
- Replace "Your Name" with your actual name
- Update the job title in the hero section
- Modify the about section with your story
- Update contact details (email, phone, location)

### Images
Replace placeholder images:
- Hero section avatar: Update the `src` attribute in the hero-avatar img tag
- About section image: Update the about-image img src
- Project images: Replace placeholder URLs with your project screenshots

### Projects
To add or modify projects:
1. Copy a project-card div
2. Update the image, title, description, and tech tags
3. Add your project links to the overlay buttons

### Skills
To modify skills:
1. Find the skill-category sections
2. Add or remove skill-item divs
3. Update the icon classes and skill names

### Colors and Styling
Main color variables in `styles.css`:
- Primary: `#4f46e5` (Indigo)
- Secondary: `#fbbf24` (Amber)
- Background: `#f9fafb` (Gray-50)
- Text: `#1f2937` (Gray-900)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Throttled scroll events for smooth performance
- Optimized animations with CSS transforms
- Lazy loading for images
- Minimal external dependencies
- Compressed and optimized code

## SEO Optimization

- Semantic HTML structure
- Meta tags for social sharing
- Alt text for all images
- Proper heading hierarchy
- Fast loading times

## Deployment Options

### Netlify (Recommended)
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty)
3. Set publish directory: `/` (root)
4. Deploy!

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch
4. Your site will be available at `username.github.io/repository-name`

### Traditional Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Test all functionality

## Contact Form Setup

The contact form is currently set up with a simulated submission. To make it functional:

1. **Backend Integration**: Connect to a service like:
   - Formspree
   - Netlify Forms
   - EmailJS
   - Custom backend API

2. **Update JavaScript**: Modify the form submission handler in `script.js`

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Built with ❤️ for developers who want to showcase their work beautifully.**

