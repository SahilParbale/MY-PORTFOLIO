# Modern Portfolio Website

A responsive, modern portfolio website built with HTML, CSS, and JavaScript featuring a dark theme with beautiful animations and transition effects.

## 🌟 Features

### Design & Theme
- **Dark Theme**: Elegant dark color scheme with cyan accents
- **Responsive Design**: Fully responsive across all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Glass Morphism**: Backdrop blur effects and transparent elements

### Sections
- **Hero Section**: Animated introduction with typing effect
- **About**: Personal information with animated statistics
- **Education**: Timeline-based education history
- **Experience**: Professional experience with hover effects
- **Skills**: Animated skill bars with progress indicators
- **Projects**: Portfolio projects with technology tags
- **Contact**: Contact form with social media links

### Animations & Effects
- **Scroll Animations**: Elements animate as they come into view
- **Hover Effects**: Interactive hover animations on cards and buttons
- **Typing Effect**: Animated text typing in hero section
- **Parallax Effects**: Subtle parallax scrolling
- **Skill Bar Animations**: Animated progress bars
- **Counter Animations**: Animated statistics counters
- **Smooth Scrolling**: Smooth navigation between sections

### Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Active Navigation**: Highlights current section in navigation
- **Scroll to Top**: Floating button to return to top
- **Form Validation**: Contact form with validation
- **Notifications**: Success/error notifications
- **Social Links**: Animated social media icons

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. The website should load with all animations and features

### File Structure
```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

#### Hero Section
```html
<span class="name">Your Name</span>
<span class="title">Your Title</span>
<p class="hero-description">Your description here</p>
```

#### About Section
```html
<p>Your personal description...</p>
<div class="stat">
    <h3>2+</h3>
    <p>Years Experience</p>
</div>
```

#### Education
```html
<div class="timeline-content">
    <div class="timeline-date">2020 - 2024</div>
    <h3>Your Degree</h3>
    <h4>Your University</h4>
    <p>Your description</p>
    <div class="grade">Your Grade</div>
</div>
```

#### Experience
```html
<div class="experience-card">
    <div class="experience-header">
        <h3>Your Position</h3>
        <span class="company">Company Name</span>
        <span class="duration">Duration</span>
    </div>
    <ul class="experience-list">
        <li>Your achievement</li>
    </ul>
</div>
```

#### Skills
```html
<div class="skill-item">
    <div class="skill-name">Skill Name</div>
    <div class="skill-bar">
        <div class="skill-progress" data-percent="85"></div>
    </div>
</div>
```

#### Projects
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

#### Contact Information
```html
<div class="contact-item">
    <div class="contact-icon">
        <i class="fas fa-envelope"></i>
    </div>
    <div class="contact-details">
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### Color Scheme
To change the color scheme, modify these CSS variables in `styles.css`:

```css
/* Primary Colors */
--primary-color: #00d4ff;
--secondary-color: #0099cc;
--background-dark: #0f0f23;
--background-medium: #1a1a2e;
--background-light: #16213e;
```

### Fonts
The website uses Google Fonts (Poppins). To change fonts:

1. Update the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

2. Update the font-family in `styles.css`:
```css
body {
    font-family: 'YourFont', sans-serif;
}
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

### Mobile Features
- Hamburger navigation menu
- Optimized layouts for small screens
- Touch-friendly buttons and links
- Reduced animations for better performance

## 🎯 Performance Optimizations

- **Lazy Loading**: Images and animations load as needed
- **CSS Animations**: Hardware-accelerated animations
- **Minimal JavaScript**: Efficient event handling
- **Optimized Assets**: Compressed images and fonts

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

If you have any questions or need help customizing the portfolio:

1. Check the customization guide above
2. Review the code comments
3. Open an issue for bugs or feature requests

## 🎨 Additional Customization Tips

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Adding Animations
1. Define keyframes in CSS
2. Apply animations to elements
3. Use Intersection Observer for scroll-triggered animations

### Adding Interactive Features
1. Add event listeners in JavaScript
2. Create smooth transitions
3. Ensure accessibility compliance

## 🚀 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository settings
3. Enable GitHub Pages
4. Select source branch

### Netlify
1. Connect your GitHub repository
2. Deploy automatically
3. Custom domain (optional)

### Vercel
1. Import your repository
2. Deploy with one click
3. Automatic deployments on push

---

**Enjoy your new portfolio website!** 🎉 