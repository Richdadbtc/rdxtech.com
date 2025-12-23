# 🚀 Deployment Guide - Christian Uchenna Portfolio

## 📋 Overview
This portfolio is a static website built with pure HTML, CSS, and JavaScript. It's optimized for GitHub Pages deployment and can be hosted on any static hosting service.

---

## 🎯 GitHub Pages Deployment (Recommended)

### Quick Setup (5 minutes)

1. **Push to GitHub**
   ```bash
   cd /Users/mac/Documents/GitHub/rdxtech.com
   git add .
   git commit -m "Complete portfolio rebuild"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** > **Pages**
   - Under **Source**, select **main** branch
   - Click **Save**
   - Your site will be live at: `https://yourusername.github.io/rdxtech.com`

3. **Custom Domain (Optional)**
   - Add a `CNAME` file with your domain: `www.rdxtech.com`
   - Configure DNS settings with your domain provider
   - Add A records pointing to GitHub's IPs

---

## 📁 Project Structure
```
rdxtech.com/
├── index.html          # Main HTML file
├── style.css           # All styles (dark mode, responsive)
├── images/             # Project screenshots & assets
│   ├── logo.png
│   ├── logo 2.png
│   ├── person.png
│   ├── Project.png
│   ├── Project (1).png
│   ├── Project (2).png
│   ├── Project (3).png
│   └── Rectangle 17.png
├── DEPLOYMENT.md       # This file
└── README.md           # Project documentation
```

---

## ✏️ Content Customization Guide

### 1. **Personal Information**
**File:** `index.html`

**Update Contact Links:**
```html
<!-- Line ~38-40: Social media links -->
<a href="https://github.com/YOUR_USERNAME" target="_blank">
<a href="https://www.linkedin.com/in/YOUR_PROFILE" target="_blank">
<a href="https://api.whatsapp.com/send/?phone=YOUR_PHONE" target="_blank">
```

**Update Email:**
```html
<!-- Line ~366: Contact section -->
<a href="mailto:YOUR_EMAIL@domain.com">YOUR_EMAIL@domain.com</a>
```

### 2. **Projects**
**File:** `index.html` (Lines ~248-355)

Each project card follows this structure:
```html
<div class="project-card">
    <div class="project-image">
        <img src="./images/YOUR_IMAGE.png" alt="Project Name" />
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-type">Project Category</p>
        <p class="project-description">Your description here...</p>
        <div class="project-tech">
            <span>Flutter</span>
            <span>GetX</span>
            <!-- Add more tech tags -->
        </div>
    </div>
</div>
```

**To add a new project:**
1. Duplicate an existing `<div class="project-card">` block
2. Update the image path, title, description, and tech stack
3. Add project screenshot to `/images/` folder

### 3. **Skills**
**File:** `index.html` (Lines ~168-246)

Update skill levels:
```html
<li>
    <span class="skill-name">Your Skill</span>
    <span class="skill-level">Expert|Advanced|Intermediate</span>
</li>
```

### 4. **Resume/Experience**
**File:** `index.html` (Lines ~358-398)

Update timeline items:
```html
<div class="timeline-item">
    <div class="timeline-content">
        <h4>Your Job Title</h4>
        <p class="timeline-company">Company Name</p>
        <p class="timeline-period">2023 - Present</p>
        <ul>
            <li>Achievement or responsibility</li>
        </ul>
    </div>
</div>
```

### 5. **Downloadable CV**
**File:** `index.html` (Line ~363)

```html
<a href="./path/to/your-cv.pdf" class="btn btn-primary" download>
    <i class="fas fa-download"></i> Download CV
</a>
```

1. Add your PDF resume to the project folder
2. Update the `href` path

---

## 🎨 Design Customization

### Color Scheme
**File:** `style.css` (Lines 10-25)

```css
:root {
    --primary: #7c3aed;        /* Main purple */
    --secondary: #10b981;      /* Green accent */
    --accent: #f59e0b;         /* Amber accent */
    
    /* Update these to change the entire color scheme */
}
```

**Popular Alternatives:**
- **Blue Tech:** `--primary: #3b82f6; --secondary: #06b6d4;`
- **Green Eco:** `--primary: #10b981; --secondary: #14b8a6;`
- **Red Energy:** `--primary: #ef4444; --secondary: #f97316;`

### Typography
**File:** `style.css` (Line 38-39)

```css
--font-primary: 'Space Grotesk', sans-serif;  /* Headings */
--font-secondary: 'Inter', sans-serif;        /* Body text */
```

---

## 🖼️ Image Guidelines

### Required Images:
1. **Logo** (`logo.png`, `logo 2.png`) - 200x200px, transparent PNG
2. **Profile Photo** (`person.png`) - 400x500px recommended
3. **Project Screenshots** - 800x600px or 16:9 ratio

### Optimization:
```bash
# Use tools like TinyPNG or ImageOptim to compress images
# Keep images under 500KB each for faster loading
```

### Adding New Images:
1. Place images in `/images/` folder
2. Update `src` paths in HTML:
   ```html
   <img src="./images/your-new-image.png" alt="Description" />
   ```

---

## 🔧 Technical Notes

### Browser Compatibility
✅ Chrome, Firefox, Safari, Edge (latest versions)  
✅ Mobile browsers (iOS Safari, Chrome Mobile)  
⚠️ IE11 not supported (uses modern CSS features)

### Performance
- **Lighthouse Score Target:** 95+ on all metrics
- All images use `loading="lazy"` (automatic)
- CSS animations use GPU acceleration
- Minimal JavaScript for fast load times

### SEO Optimization
Included meta tags:
```html
<meta name="description" content="...">
<meta name="keywords" content="...">
<meta name="author" content="Christian Uchenna">
```

**To improve:**
1. Add Open Graph tags for social sharing
2. Create `sitemap.xml`
3. Add `robots.txt`

---

## 🌐 Alternative Hosting Options

### Netlify
1. Drag & drop the entire folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Custom domain automatically configured
3. **Benefit:** Instant HTTPS, form handling

### Vercel
```bash
npm i -g vercel
cd rdxtech.com
vercel
```

### Traditional Web Host
1. Upload all files via FTP
2. Ensure `index.html` is in the root directory
3. Point domain to hosting server

---

## ✅ Pre-Launch Checklist

- [ ] All personal links updated (GitHub, LinkedIn, WhatsApp)
- [ ] Email address changed
- [ ] CV/Resume PDF added and linked
- [ ] Project images uploaded
- [ ] Project descriptions customized
- [ ] Test on mobile device
- [ ] Test contact form
- [ ] Verify all links work
- [ ] Check for typos
- [ ] Run Lighthouse audit
- [ ] Test in different browsers

---

## 🐛 Troubleshooting

### Images not showing
- Check file paths are relative: `./images/photo.png`
- Verify file names match exactly (case-sensitive)
- Ensure images are in the `/images/` folder

### Styles not loading
- Clear browser cache (Cmd+Shift+R / Ctrl+Shift+R)
- Check `style.css` is in the same directory as `index.html`

### Mobile menu not working
- Verify JavaScript is enabled
- Check browser console for errors (F12)

### GitHub Pages not updating
- Wait 2-5 minutes after pushing changes
- Hard refresh browser (Cmd+Shift+R)
- Check GitHub Actions tab for build status

---

## 📞 Support

For questions or issues with this template:
- Open an issue on GitHub
- Contact: [Your Contact Method]

---

## 📄 License

This portfolio template is free to use and modify for your personal portfolio.

**Built with ❤️ for Christian Uchenna**

---

## 🔄 Version History

- **v2.0** (2024) - Complete rebuild with modern dark mode design
- **v1.0** (2024) - Initial portfolio

---

**Ready to launch? Run through the checklist above and push to GitHub! 🚀**
