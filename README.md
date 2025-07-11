# Alfonso De La Garza - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Full-Stack Software Developer.

## ✨ Features

### 🎨 Design & UX
- **Modern Design**: Clean, professional design with smooth animations
- **Dark Mode**: Toggle between light and dark themes with persistent preference
- **Responsive**: Fully responsive design that works on all devices
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation

### 🚀 Functionality
- **Loading Animation**: Smooth loading experience with spinner
- **Mobile Menu**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Elegant navigation between sections
- **Scroll Animations**: Elements animate as they come into view
- **Typing Effect**: Animated text in the hero section
- **Particle Effects**: Subtle background animations
- **Contact Form**: Functional contact form with validation

### 🛠 Technical Features
- **CSS Variables**: Easy theme customization
- **Modular Code**: Separated CSS and JavaScript files
- **Performance Optimized**: Debounced scroll events and efficient animations
- **SEO Optimized**: Meta tags, Open Graph, and Twitter Cards
- **Cross-browser Compatible**: Works on all modern browsers

## 📁 File Structure

```
alfonsounadm.github.io/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Sections

1. **Hero Section**: Introduction with animated typing effect
2. **About**: Personal story and background
3. **Skills**: Technical skills organized by category
4. **Projects**: Featured projects with links
5. **Contact**: Contact form and social media links

## 🎨 Color Scheme

### Light Theme
- Primary: `#667eea` (Purple Blue)
- Secondary: `#764ba2` (Purple)
- Text: `#333` (Dark Gray)
- Background: `#fff` (White)

### Dark Theme
- Primary: `#8b9eff` (Light Purple Blue)
- Secondary: `#a78bfa` (Light Purple)
- Text: `#e2e8f0` (Light Gray)
- Background: `#1a202c` (Dark Blue Gray)

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. The website will load with all features enabled

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Customization

### Adding New Projects
Edit the projects section in `index.html`:

```html
<div class="project-card fade-in">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h4>Project Name</h4>
        <p>Project description...</p>
        <div class="project-links">
            <a href="#"><i class="fab fa-github"></i> Code</a>
            <a href="#"><i class="fas fa-external-link-alt"></i> Live Demo</a>
        </div>
    </div>
</div>
```

### Modifying Colors
Update CSS variables in `styles.css`:

```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... other variables */
}
```

### Adding New Skills
Edit the skills section in `index.html`:

```html
<div class="skill-card fade-in">
    <h4><i class="fas fa-icon"></i> Category Name</h4>
    <ul class="skill-list">
        <li>Skill 1</li>
        <li>Skill 2</li>
        <!-- ... more skills -->
    </ul>
</div>
```

## 🌟 Key Features Explained

### Dark Mode Toggle
- Persistent theme preference using localStorage
- Smooth transitions between themes
- Automatic icon updates (moon/sun)

### Mobile Menu
- Hamburger button with smooth animations
- Full-screen overlay on mobile
- Auto-close when clicking links or outside

### Scroll Animations
- Uses Intersection Observer API for performance
- Staggered animations for skill cards
- Different animation types: fade-in, slide-in-left, slide-in-right

### Contact Form
- Client-side validation
- Success/error notifications
- Form reset after successful submission

## 📈 Performance Optimizations

- **Debounced Scroll Events**: Prevents excessive function calls
- **CSS Transforms**: Hardware-accelerated animations
- **Efficient Selectors**: Optimized CSS selectors
- **Minimal DOM Manipulation**: Reduced reflows and repaints

## 🔒 Security Features

- **Form Validation**: Client-side input validation
- **XSS Prevention**: Proper HTML escaping
- **External Links**: `rel="noopener noreferrer"` for security

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

**Built with ❤️ by Alfonso De La Garza** 