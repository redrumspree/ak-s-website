# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. This project serves as an excellent example for learning web development fundamentals and best practices.

## 🌟 Features

### Design & User Experience
- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **Accessibility**: Semantic HTML and keyboard navigation support

### Sections
1. **Hero Section**: Eye-catching introduction with animated title and call-to-action buttons
2. **About Section**: Personal information with feature highlights
3. **Projects Section**: Showcase of work with technology tags and links
4. **Skills Section**: Organized display of technical skills and tools
5. **Contact Section**: Contact form with validation and social media links

### Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Navigation links smoothly scroll to sections
- **Form Validation**: Contact form with client-side validation
- **Scroll Animations**: Elements animate in as you scroll
- **Active Navigation**: Current section is highlighted in navigation
- **Hover Effects**: Interactive hover states on cards and buttons

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use

### Local Development
For development, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information
1. **Name and Title**: Update the hero section in `index.html`
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <p class="hero-subtitle">Your Title Here</p>
   ```

2. **About Section**: Modify the content in the about section
3. **Contact Information**: Update email, phone, and location in the contact section
4. **Social Links**: Replace the placeholder social media links with your actual profiles

### Projects
Add your own projects by duplicating the project card structure:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">Code</a>
        </div>
    </div>
</div>
```

### Skills
Update the skills section by modifying the skill items:

```html
<div class="skill-item">
    <i class="fab fa-technology-icon"></i>
    <span>Skill Name</span>
</div>
```

### Colors and Styling
The color scheme can be customized in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --light-bg: #f8fafc;
}
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font family)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Learning Objectives

This project demonstrates:

### HTML
- Semantic HTML5 elements
- Proper document structure
- Form elements and validation
- Accessibility best practices

### CSS
- Modern CSS layout techniques (Flexbox, Grid)
- Responsive design principles
- CSS animations and transitions
- CSS custom properties (variables)
- Media queries for responsive design

### JavaScript
- DOM manipulation
- Event handling
- Form validation
- Smooth scrolling
- Intersection Observer API
- Performance optimization (debouncing)

### Web Development Best Practices
- Mobile-first responsive design
- Performance optimization
- Clean, maintainable code
- Progressive enhancement
- Cross-browser compatibility

## 🔧 Advanced Customization

### Adding a Blog Section
Create a new section in `index.html`:

```html
<section id="blog" class="blog">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <div class="blog-grid">
            <!-- Blog post cards here -->
        </div>
    </div>
</section>
```

### Adding a Dark Mode Toggle
1. Add a toggle button to the navigation
2. Create CSS variables for dark theme colors
3. Use JavaScript to toggle between themes

### Adding a Portfolio Filter
Implement filtering functionality for projects by category (e.g., Web, Mobile, Design).

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your main branch as source
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. You'll get a custom URL and can add a custom domain

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. You'll get automatic deployments on every push

## 📚 Resources for Learning

- [MDN Web Docs](https://developer.mozilla.org/) - Comprehensive web development documentation
- [CSS-Tricks](https://css-tricks.com/) - CSS tutorials and tips
- [JavaScript.info](https://javascript.info/) - Modern JavaScript tutorial
- [Web.dev](https://web.dev/) - Web development best practices

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Font Awesome for the icons
- Google Fonts for the Inter font family
- The web development community for inspiration and best practices

---

**Happy Coding! 🎉**

This portfolio website is designed to be both a functional showcase and a learning resource. Feel free to use it as a starting point for your own projects and customize it to match your personal style and needs. 