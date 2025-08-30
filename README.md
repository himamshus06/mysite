# Professional Portfolio Website

A modern, responsive portfolio website showcasing expertise in **Speaking**, **Development**, and **Filmmaking**. Built with HTML5, CSS3, and vanilla JavaScript.

## 🚀 Features

### Design & Layout
- **Modern & Professional**: Clean, contemporary design with gradient accents
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS transitions and JavaScript-powered animations
- **Accessibility**: Keyboard navigation and focus management

### Sections
1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal description with skill categorization
3. **Speaking**: Showcase of public speaking engagements and workshops
4. **Development**: Portfolio of software development projects
5. **Filmmaking**: Video production and film projects
6. **Contact**: Contact form and information
7. **Footer**: Social links and quick navigation

### Interactive Elements
- Mobile-friendly navigation with hamburger menu
- Smooth scrolling between sections
- Hover effects and animations
- Contact form with validation
- Notification system
- Scroll progress indicator

## 🛠️ Setup Instructions

### Prerequisites
- A modern web browser
- Basic knowledge of HTML/CSS/JavaScript (for customization)

### Installation
1. **Download/Clone** the project files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your personal information
4. **Deploy** to your preferred hosting service

### File Structure
```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    <span class="highlight">Your Name</span> • 
    <span class="highlight">Your Title</span> • 
    <span class="highlight">Your Expertise</span>
</h1>
<p class="hero-subtitle">
    Your personal tagline or description
</p>
```

#### About Section
```html
<p>
    Replace with your personal bio and professional summary
</p>
```

#### Skills
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <div class="skill-tags">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
        <!-- Add more skills -->
    </div>
</div>
```

### Projects & Work
Update the development and filmmaking sections with your actual projects:

#### Development Projects
```html
<div class="project-card">
    <div class="project-image">
        <!-- Replace icon with your project image -->
        <i class="fas fa-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology Used</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">View Demo</a>
            <a href="your-source-code" class="project-link">Source Code</a>
        </div>
    </div>
</div>
```

#### Video Projects
```html
<div class="video-card">
    <div class="video-thumbnail">
        <!-- Replace with actual video thumbnail -->
        <i class="fas fa-play-circle"></i>
    </div>
    <div class="video-info">
        <h3>Your Video Title</h3>
        <p>Video description</p>
        <div class="video-details">
            <span class="detail">Duration: X min</span>
            <span class="detail">Genre: Your Genre</span>
        </div>
    </div>
</div>
```

### Contact Information
Update the contact section with your actual details:

```html
<div class="contact-methods">
    <div class="contact-method">
        <i class="fas fa-envelope"></i>
        <span>your-email@example.com</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-phone"></i>
        <span>Your Phone Number</span>
    </div>
    <div class="contact-method">
        <i class="fas fa-map-marker-alt"></i>
        <span>Your Location</span>
    </div>
</div>
```

### Social Media Links
Update the footer social links:

```html
<div class="social-links">
    <a href="your-linkedin"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter"><i class="fab fa-twitter"></i></a>
    <a href="your-github"><i class="fab fa-github"></i></a>
    <a href="your-youtube"><i class="fab fa-youtube"></i></a>
</div>
```

## 🎯 Adding Real Content

### Images
1. **Profile Photo**: Replace the hero section icon with your photo
2. **Project Screenshots**: Add actual project images to the development section
3. **Video Thumbnails**: Replace video placeholders with real thumbnails

### Videos
1. **Embed Videos**: Replace video cards with embedded YouTube/Vimeo players
2. **Video Links**: Add direct links to your video content

### Projects
1. **Real Links**: Update project demo and source code links
2. **Live Projects**: Link to deployed applications
3. **GitHub**: Connect to your actual repositories

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and deploy

### Netlify
1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository for automatic deployment

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory

### Traditional Hosting
1. Upload files via FTP/SFTP
2. Ensure all files are in the correct directory structure

## 🔧 Advanced Customization

### Colors & Theme
Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #2d3748;
    --background-color: #f7fafc;
}
```

### Fonts
Change the Google Fonts import in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

### Animations
Customize animation timing and effects in `styles.css`:

```css
.transition {
    transition: all 0.3s ease;
}
```

## 📱 Mobile Optimization

The website is already optimized for mobile devices with:
- Responsive grid layouts
- Mobile-first navigation
- Touch-friendly buttons and interactions
- Optimized typography scaling

## ♿ Accessibility Features

- Semantic HTML structure
- Keyboard navigation support
- Focus management
- Screen reader friendly
- High contrast ratios
- Responsive design

## 🚀 Performance Tips

1. **Optimize Images**: Compress and resize images before adding
2. **Minify CSS/JS**: Use build tools to minify files for production
3. **Lazy Loading**: Implement lazy loading for images and videos
4. **CDN**: Use CDN for external resources (Font Awesome, Google Fonts)

## 🔍 SEO Optimization

- Semantic HTML structure
- Meta descriptions and titles
- Proper heading hierarchy
- Alt text for images
- Clean URL structure

## 📞 Support & Customization

For additional customization or support:
1. Review the code comments for guidance
2. Modify CSS classes to match your design preferences
3. Add or remove sections as needed
4. Integrate with your preferred backend for the contact form

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for showcasing your professional portfolio**

*Feel free to modify, enhance, and make this portfolio truly yours!* 