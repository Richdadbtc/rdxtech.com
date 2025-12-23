# Christian Uchenna - Full-Stack Mobile Developer Portfolio

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**A modern, dark-mode portfolio showcasing real mobile engineering work**

[View Live Demo](#) • [Report Bug](#) • [Request Feature](#)

</div>

---

## 🎯 About This Portfolio

This is a professional portfolio website for **Christian Uchenna**, a full-stack mobile developer specializing in Flutter, fintech applications, telecom platforms, and enterprise-scale systems.

### ✨ Key Features

- **🌙 Dark Mode Design** - Modern fintech/startup aesthetic with purple & green accents
- **📱 Fully Responsive** - Perfect on desktop, tablet, and mobile
- **⚡ Fast Performance** - Optimized for speed with lazy loading and efficient animations
- **🎨 Clean Architecture** - Well-structured, maintainable code
- **🚀 GitHub Pages Ready** - Static site, easy deployment
- **♿ Accessible** - Semantic HTML and ARIA labels
- **🎭 Smooth Animations** - Intersection Observer for scroll-triggered effects
- **💼 Professional** - Recruiter and client-friendly layout

---

## 🛠️ Tech Stack

### Core Technologies
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - No frameworks, pure ES6+

### Design System
- **Typography**: Space Grotesk + Inter fonts
- **Colors**: Purple (#7c3aed), Green (#10b981), Amber (#f59e0b)
- **Icons**: Font Awesome 6.6.0

### Features
- CSS Grid & Flexbox for layouts
- CSS custom properties (variables) for theming
- Intersection Observer API for animations
- Smooth scroll behavior
- Mobile-first responsive design

---

## 📁 Project Structure

```
rdxtech.com/
│
├── index.html              # Main HTML file with all content
├── style.css               # Complete stylesheet (1000+ lines)
├── DEPLOYMENT.md           # Detailed deployment guide
├── README.md               # This file
│
└── images/                 # All visual assets
    ├── logo.png
    ├── logo 2.png
    ├── person.png
    ├── Project.png
    ├── Project (1).png
    ├── Project (2).png
    ├── Project (3).png
    └── Rectangle 17.png
```

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/Richdadbtc/rdxtech.com.git
cd rdxtech.com
```

### 2. Open locally
```bash
# Simply open index.html in your browser
open index.html

# Or use a local server (recommended)
python -m http.server 8000
# Then visit: http://localhost:8000
```

### 3. Deploy to GitHub Pages
```bash
git add .
git commit -m "Initial commit"
git push origin main

# Enable GitHub Pages in repository settings
# Settings > Pages > Source: main branch
```

**See [DEPLOYMENT.md](DEPLOYMENT.md) for detailed deployment instructions.**

---

## 📝 Customization

### Update Personal Information

**Contact Links** (`index.html` lines ~38-40):
```html
<a href="https://github.com/YOUR_USERNAME">
<a href="https://www.linkedin.com/in/YOUR_PROFILE">
<a href="https://api.whatsapp.com/send/?phone=YOUR_PHONE">
```

**Email** (`index.html` line ~366):
```html
<a href="mailto:your.email@domain.com">your.email@domain.com</a>
```

### Change Color Scheme

**Edit CSS Variables** (`style.css` lines 10-25):
```css
:root {
    --primary: #7c3aed;        /* Change main color */
    --secondary: #10b981;      /* Change accent color */
    --accent: #f59e0b;         /* Change highlight color */
}
```

### Add/Edit Projects

Duplicate a project card block in `index.html` (lines ~248-355):
```html
<div class="project-card">
    <div class="project-image">
        <img src="./images/your-project.png" alt="Project Name" />
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project</h3>
        <p class="project-description">Description here...</p>
        <!-- Add your tech stack -->
    </div>
</div>
```

**Full customization guide:** See [DEPLOYMENT.md](DEPLOYMENT.md)

---

## 🎨 Design Highlights

### Dark Mode Aesthetic
- Background: Pure black (#0a0a0a) with card layers
- Text: White with varying opacity for hierarchy
- Accents: Purple gradient for CTAs and highlights

### Responsive Breakpoints
- **Desktop**: 1200px container
- **Tablet**: 1024px (2-column grid)
- **Mobile**: 768px (single column, hamburger menu)

### Animations
- Scroll-triggered fade-ins (Intersection Observer)
- Hover effects on cards and buttons
- Smooth gradient transitions
- 3D tilt effect on project cards

---

## 📊 Portfolio Sections

1. **Hero** - Introduction with gradient headline and code preview
2. **About** - Professional background and expertise highlights
3. **Skills** - Categorized technical stack (Mobile, Backend, Fintech, etc.)
4. **Projects** - 6 real projects with detailed descriptions:
   - Swiftcom (eSIM platform)
   - RD Exchange (Crypto app)
   - Banking/Fintech App
   - Hotspot (Discipleship platform)
   - Pocket Tasks
   - Government Tracking System
5. **Resume** - Timeline of professional experience
6. **Contact** - Contact info + functional form

---

## ⚡ Performance

- **Lighthouse Score**: 95+ (target)
- **Load Time**: < 2 seconds
- **Image Optimization**: Lazy loading enabled
- **Animation**: GPU-accelerated transforms
- **Bundle Size**: < 100KB (excluding images)

### Optimization Features
- Minimal JavaScript (no libraries)
- Efficient CSS (no bloat)
- Compressed images recommended
- Modern font loading strategy

---

## 🌐 Browser Support

✅ Chrome (latest)  
✅ Firefox (latest)  
✅ Safari (latest)  
✅ Edge (latest)  
✅ Mobile browsers (iOS Safari, Chrome Mobile)  
❌ Internet Explorer (not supported)

---

## 📄 License

This project is open source and available for personal use. Feel free to fork and customize for your own portfolio.

---

## 🤝 Connect

- **GitHub**: [@Richdadbtc](https://github.com/Richdadbtc)
- **LinkedIn**: [Christian Uchenna](https://www.linkedin.com/in/christian-uchenna-581041189)
- **WhatsApp**: [Send Message](https://api.whatsapp.com/send/?phone=2348147088231)

---

## 🙏 Acknowledgments

- **Fonts**: Google Fonts (Space Grotesk, Inter)
- **Icons**: Font Awesome
- **Design Inspiration**: Modern fintech and startup aesthetics

---

<div align="center">

**Built with ❤️ by Christian Uchenna**

⭐ Star this repo if you found it helpful!

</div>
