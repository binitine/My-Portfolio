# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, projects, and professional background. Built as a final project for IT Elective 4.

## 🚀 Live Demo

- **Live URL**: [https://username.github.io/portfolio](https://binitine.github.io/portfolio)
- **Repository URL**: [https://github.com/username/portfolio](https://github.com/binitine/portfolio)

> **Note**: Replace `username` with your actual GitHub username in the URLs above.

## 📋 Project Overview

This portfolio website serves as a digital resume, demonstrating proficiency in web development fundamentals. The project showcases:

- Semantic HTML5 structure
- Modern CSS with custom properties and responsive design
- Clean, aesthetic user interface
- Fully responsive layout for all devices
- Smooth animations and interactive elements

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with proper structure
- **CSS3**: Custom CSS with:
  - CSS Variables (Custom Properties)
  - Flexbox and CSS Grid for layouts
  - Media queries for responsive design
  - Smooth animations and transitions
- **JavaScript**: Vanilla JavaScript for:
  - Mobile navigation toggle
  - Smooth scrolling
  - Scroll-triggered animations
- **Git/GitHub**: Version control and deployment via GitHub Pages

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS stylesheet
└── README.md           # Project documentation
```

## ✨ Features

### Sections

1. **Hero Section**
   - Eye-catching introduction
   - Name and tagline
   - Call-to-action button
   - Smooth scroll indicator

2. **About Me**
   - Professional biography
   - Profile photo placeholder
   - Background information
   - Statistics showcase

3. **Skills**
   - Visual representation of technical skills
   - Animated progress bars
   - Skill cards with icons
   - Technologies: HTML5, CSS3, JavaScript, Python, Git/GitHub, UI/UX Design

4. **Projects Gallery**
   - At least 3 project showcases
   - Project cards with:
     - Screenshot/image
     - Title and description
     - Technology tags
     - Links to live demo and code

5. **Contact**
   - Contact information
   - Contact form (ready for Formspree integration)
   - Social media links
   - Professional presentation

### Design Features

- **Modern Aesthetic**: Gradient backgrounds, smooth animations, and clean typography
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Accessible**: Semantic HTML and proper ARIA labels
- **Interactive**: Hover effects, smooth scrolling, and animated elements
- **Performance**: Lightweight and fast-loading

## 🎨 Customization

### Update Personal Information

1. **Name and Tagline**: Edit the hero section in `index.html`
   ```html
   <span class="name">Your Name</span>
   <p class="hero-subtitle">Aspiring Web Developer</p>
   ```

2. **About Me**: Update the biography in the About section

3. **Profile Photo**: Replace the placeholder image URL with your actual photo
   ```html
   <img src="your-photo-url.jpg" alt="Profile Photo">
   ```

4. **Skills**: Modify skill names and percentages in the Skills section

5. **Projects**: Update project information, images, and links

6. **Contact**: Update email, phone, and social media links

### Color Scheme

The color scheme can be customized by modifying CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... more variables */
}
```

### Contact Form

To make the contact form functional:

1. Sign up for [Formspree](https://formspree.io/)
2. Get your form endpoint URL
3. Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Deployment

### GitHub Pages Deployment

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to repository Settings → Pages
4. Select the main branch as the source
5. Your site will be live at `https://username.github.io/repository-name`

### Local Development

1. Clone or download this repository
2. Open `index.html` in a web browser
3. For live reloading, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

## 📝 Requirements Compliance

✅ **HTML5 Structure**
- Semantic HTML5 tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<article>`)
- Proper indentation and comments
- Logical and accessible structure

✅ **CSS Styling**
- Pure CSS approach with Flexbox and CSS Grid
- CSS variables (`:root`) for theming
- Media queries for responsiveness
- Custom styling throughout

✅ **Responsiveness**
- Mobile-friendly navigation (hamburger menu)
- Responsive layouts for all screen sizes
- Touch-friendly interface elements

✅ **Content Requirements**
- Hero section with CTA
- About Me with biography and photo
- Skills visualization
- Projects gallery (3+ projects)
- Contact section with form and social links

✅ **Deployment**
- Ready for GitHub Pages
- Includes README.md documentation

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is created for educational purposes as part of the IT Elective 4 course.

## 👤 Author

Your Name
- Email: your.email@example.com
- GitHub: [@username](https://github.com/username)
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Fonts: [Google Fonts](https://fonts.google.com/) - Poppins & Playfair Display
- Icons: Custom SVG icons
- Design Inspiration: Modern portfolio trends

---

**Note**: Remember to replace all placeholder content (name, email, links, images) with your actual information before deploying!



