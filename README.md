# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and professional information.

## 🌟 Features

- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Hover effects, scroll animations, and smooth transitions
- **Contact Form** - Functional contact form with validation
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Scroll Animations** - Elements animate as you scroll through the page
- **Typing Effect** - Animated text in the hero section
- **Counter Animations** - Animated statistics in the about section
- **Notification System** - Success/error messages for form submissions
- **Scroll to Top** - Convenient button to return to the top

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

1. **Clone or Download** the files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to GitHub Pages (instructions below)

## 🎨 Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Full Stack Developer & Creative Problem Solver</p>
```

#### About Section
```html
<p>
    I'm a passionate developer with a love for creating innovative digital solutions...
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
```

#### Social Links
```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <!-- Add more social links as needed -->
</div>
```

### Projects Section

Replace the sample projects with your own:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-live-demo-url" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-repo-url" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills Section

Update the skills grid with your technologies:

```html
<div class="skills-grid">
    <div class="skill-item">
        <i class="fab fa-html5"></i>
        <span>HTML5</span>
    </div>
    <div class="skill-item">
        <i class="fab fa-css3-alt"></i>
        <span>CSS3</span>
    </div>
    <!-- Add more skills -->
</div>
```

### Statistics

Update the numbers in the about section:

```html
<div class="stat-item">
    <h3>2+</h3>
    <p>Years Experience</p>
</div>
<div class="stat-item">
    <h3>20+</h3>
    <p>Projects Completed</p>
</div>
<div class="stat-item">
    <h3>15+</h3>
    <p>Happy Clients</p>
</div>
```

## 🎨 Styling Customization

### Colors

The main color scheme is defined in `styles.css`. You can customize:

- **Primary Blue**: `#2563eb`
- **Secondary Purple**: `#7c3aed`
- **Accent Yellow**: `#fbbf24`
- **Background Colors**: Various shades of gray

### Fonts

The website uses the Inter font family. You can change it by:

1. Replacing the Google Fonts link in `index.html`
2. Updating the font-family in `styles.css`

### Animations

All animations are defined in `styles.css`. You can adjust:
- Animation durations
- Transition effects
- Hover states
- Scroll animations

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Deployment to GitHub Pages

### Method 1: Using GitHub Desktop

1. **Create a new repository** on GitHub
2. **Clone** the repository to your local machine
3. **Copy** all portfolio files to the repository folder
4. **Commit and push** the changes
5. **Go to Settings** → **Pages**
6. **Select source**: Deploy from a branch
7. **Choose branch**: main (or master)
8. **Save** - Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Using Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio commit"

# Add remote repository
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages in repository settings
```

### Method 3: Direct Upload

1. **Create a new repository** on GitHub
2. **Upload** all files directly through the GitHub web interface
3. **Enable GitHub Pages** in repository settings

## 🔧 Advanced Customization

### Adding New Sections

To add a new section, follow this structure:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Custom JavaScript

Add your custom JavaScript in `script.js`:

```javascript
// Your custom code here
document.addEventListener('DOMContentLoaded', function() {
    // Initialize your custom functionality
});
```

### Custom CSS

Add your custom styles in `styles.css`:

```css
/* Your custom styles */
.custom-class {
    /* Your properties */
}
```

## 📧 Contact Form

The contact form includes:
- **Form validation** (client-side)
- **Success/error notifications**
- **Email format validation**

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
1. Set up a backend service (Node.js, PHP, etc.)
2. Use a form service like Formspree, Netlify Forms, or EmailJS
3. Configure the form action and method

## 🎯 Performance Optimization

The website is optimized for performance:
- **Minimal dependencies** (only Font Awesome and Google Fonts)
- **Optimized images** (using CSS and icons)
- **Efficient animations** (using CSS transforms)
- **Lazy loading** ready for images

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help with customization or deployment:
1. Check the GitHub Issues section
2. Create a new issue with your question
3. Include specific details about what you're trying to achieve

---

**Happy coding! 🚀**

*Built with ❤️ using HTML, CSS, and JavaScript*
