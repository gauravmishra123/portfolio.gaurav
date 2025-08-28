# Gaurav Mishra - Portfolio Website

A beautiful, modern, and responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases professional skills, projects, and contact information with smooth animations and excellent user experience.

## 🌟 Features

- **Modern Design**: Clean, professional design with gradient backgrounds and glassmorphism effects
- **Responsive Layout**: Fully responsive design that works on all devices
- **Smooth Animations**: CSS animations and JavaScript interactions for engaging user experience
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Social Media Integration**: Direct links to LinkedIn, YouTube, and GitHub
- **Performance Optimized**: Fast loading with optimized assets
- **Accessibility**: Keyboard navigation and screen reader support
- **SEO Friendly**: Proper meta tags and semantic HTML

## 🚀 Quick Start

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Your Title</p>
<p class="hero-description">
    Your personal description here...
</p>
```

#### About Section
```html
<p>
    Your about me content...
</p>
```

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your Location</span>
</div>
```

### Social Media Links

Update the social media links throughout the file:

```html
<!-- LinkedIn -->
<a href="https://www.linkedin.com/in/your-profile/" target="_blank">

<!-- YouTube -->
<a href="https://www.youtube.com/@your-channel" target="_blank">

<!-- GitHub -->
<a href="https://github.com/your-username" target="_blank">
```

### Skills Section

Modify the skills in the skills section:

```html
<div class="skill-items">
    <div class="skill-item">
        <i class="fab fa-html5"></i>
        <span>HTML5</span>
    </div>
    <!-- Add more skills as needed -->
</div>
```

### Projects Section

Update the projects with your own work:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="project-url" class="project-link">Live Demo</a>
            <a href="github-url" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

## 🎯 Color Scheme

The current color scheme uses:
- **Primary Blue**: `#2563eb`
- **Gradient Purple**: `#667eea` to `#764ba2`
- **Accent Gold**: `#ffd700`
- **Text Colors**: `#333`, `#555`, `#666`

To change colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #667eea;
    --accent-color: #ffd700;
    --text-primary: #333;
    --text-secondary: #555;
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Advanced Customization

### Adding New Sections

1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Custom Animations

The website uses CSS animations and JavaScript for smooth interactions. You can modify or add new animations in the CSS file.

### Form Functionality

The contact form currently shows a success message. To make it functional:

1. Set up a backend service (Node.js, PHP, etc.)
2. Update the form action and method
3. Handle form submission on the server

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch and save

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory

## 📊 Performance Tips

- Optimize images before adding them
- Minify CSS and JavaScript for production
- Use a CDN for external libraries
- Enable gzip compression on your server

## 🔍 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Open Graph tags (can be added)
- Structured data (can be added)

## 🛠️ Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to reach out!

---

**Built with ❤️ for showcasing amazing talent and creativity**
