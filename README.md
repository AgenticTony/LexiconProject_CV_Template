# Professional CV Template - Editorial Luxe

A sophisticated, responsive CV/resume template inspired by high-end magazine design. Features an "Editorial Luxe" aesthetic with elegant typography, sophisticated color palettes, and magazine-style layouts that make your CV unforgettable.

![CV Template Preview](cv-template-desktop.png)

## ✨ Features

- **ATS-Friendly**: Semantic HTML structure optimized for applicant tracking systems
- **Fully Responsive**: Seamless experience across desktop, tablet, and mobile devices
- **Print-Ready**: Optimized print stylesheets for professional paper output
- **Editorial Design**: Magazine-inspired aesthetic with elegant serif typography and sophisticated forest green/cream/gold color palette
- **Accessibility**: High contrast support, reduced motion preferences, and semantic markup
- **Fast Loading**: No external dependencies (except fonts), under 50KB total size
- **GitHub Pages Ready**: Deploy immediately with a single file upload

## 🎯 Perfect For

- **Career Transitioners**: Professionals moving into tech from other industries
- **Technical Professionals**: Software developers, data scientists, AI engineers
- **Project Managers**: Those with technical project management experience
- **Recent Graduates**: Computer science and related technical field graduates

## 🚀 Quick Start

1. **Clone or Download** this template
2. **Open `index.html`** in your favorite editor
3. **Replace sample content** with your information
4. **Customize colors** using CSS variables (optional)
5. **Deploy** to GitHub Pages or any web hosting service

## 🎨 Customization Guide

### Changing Content

#### Personal Information
Edit the header section in `index.html`:

```html
<h1 class="name">Your Full Name</h1>
<p class="title">Your Target Job Title</p>
<div class="location">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, State/Country</span>
</div>
```

Update contact links:
```html
<a href="mailto:your.email@example.com" class="contact-link">
<a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener" class="contact-link">
<a href="https://github.com/yourusername" target="_blank" rel="noopener" class="contact-link">
```

#### Professional Summary
Replace the content in the summary section:
```html
<div class="summary-content">
    <p>Your professional summary here...</p>
</div>
```

#### Technical Skills
Update skill categories and levels:
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <div class="skill-tags">
        <span class="skill-tag level-advanced">Skill Name</span>
        <span class="skill-tag level-intermediate">Skill Name</span>
        <span class="skill-tag level-beginner">Skill Name</span>
    </div>
</div>
```

**Skill Levels:**
- `level-beginner`: 33% indicator (orange)
- `level-intermediate`: 66% indicator (teal)
- `level-advanced`: 100% indicator (navy)

#### Projects
Replace project information:
```html
<article class="project-card">
    <div class="project-header">
        <h3 class="project-title">
            <a href="https://github.com/yourproject" target="_blank" rel="noopener" class="monospace">
                Your Project Name
                <i class="fas fa-external-link-alt"></i>
            </a>
        </h3>
        <div class="project-links">
            <a href="https://yourproject.com" target="_blank" rel="noopener" class="project-link">
                <i class="fas fa-globe"></i> Live Demo
            </a>
        </div>
    </div>
    <div class="project-tech">
        <span class="tech-tag">Technology</span>
        <span class="tech-tag">Framework</span>
    </div>
    <p class="project-description">
        Your project description...
    </p>
    <div class="project-outcome">
        <strong>Impact:</strong> Your quantified impact or achievement
    </div>
</article>
```

### Changing Colors & Theme

The template uses CSS custom properties for easy theming. Edit the `:root` section in `styles.css`:

```css
:root {
    /* Editorial Luxe Color Palette */
    --forest-dark: #1a3b32;         /* Main headings, header */
    --forest-medium: #2d5a4d;       /* Accent elements */
    --forest-light: #4a7c69;        /* Secondary accents */

    --cream: #f7f4ed;               /* Main background */
    --cream-dark: #f0ebe0;          /* Section backgrounds */
    --cream-darker: #e8dfc8;        /* Alternate sections */

    --gold: #d4af37;                /* Primary accent */
    --gold-light: #e8c547;          /* Hover states */
    --gold-muted: #b8954d;          /* Subtle accents */

    --charcoal: #2c2c2c;            /* Primary text */
    --grey-medium: #6b7280;         /* Secondary text */
}
```

#### Alternative Color Schemes

**Monochrome Elegance:**
```css
--forest-dark: #2c2c2c;
--forest-light: #6b7280;
--gold: #d4af37;
--cream: #ffffff;
```

**Deep Ocean:**
```css
--forest-dark: #1e293b;
--forest-light: #475569;
--gold: #0ea5e9;
--cream: #f1f5f9;
```

**Burgundy & Gold:**
```css
--forest-dark: #7f1d1d;
--forest-light: #dc2626;
--gold: #fbbf24;
--cream: #fef7cd;
```

### Typography Customization

Change fonts by editing the font imports and variables:

```css
/* In <head> section of index.html */
<link href="https://fonts.googleapis.com/css2?family=Your+Heading+Font:wght@400;600&family=Your+Body+Font:wght@400;500;600&family=Your+Mono+Font:wght@400;500&display=swap" rel="stylesheet">

/* In styles.css */
:root {
    --font-serif: 'Your Heading Font', Georgia, serif;        /* For headings */
    --font-sans: 'Your Body Font', Arial, sans-serif;         /* For body text */
    --font-mono: 'Your Mono Font', 'Courier New', monospace;  /* For code/tech elements */
}
```

## 📱 Responsive Breakpoints

The template adapts at these breakpoints:
- **Mobile**: 0-480px (single column, stacked layout)
- **Tablet**: 481-768px (single column, larger spacing)
- **Desktop**: 769px+ (two-column header, optimized layout)

## 🖨️ Print Optimization

The template includes comprehensive print styles:
- Optimized for A4 paper size
- Black and white friendly
- Page break controls
- Essential information prioritized
- Print preview recommended before printing

To test print styles:
1. Open the CV in your browser
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Review the print preview

## 🌐 GitHub Pages Deployment

### Option 1: Direct Upload
1. Fork or download this repository
2. Customize content and colors
3. Rename repository to `yourusername.github.io` (for main site) or any name for project site
4. Enable GitHub Pages in repository settings
5. Your CV will be available at `https://yourusername.github.io`

### Option 2: Custom Domain
1. Follow Option 1 steps
2. Add a `CNAME` file with your custom domain
3. Configure DNS settings with your domain provider
4. Access your CV at your custom domain

## ♿ Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and landmark elements
- **High Contrast Support**: Adapts to user's high contrast preferences
- **Reduced Motion**: Respects user's motion preferences
- **Keyboard Navigation**: Fully navigable without mouse
- **Screen Reader Friendly**: Descriptive alt text and labels

## 🐛 Troubleshooting

### Common Issues

**Fonts not loading:**
- Check internet connection for Google Fonts
- Fallback system fonts will be used automatically

**Layout breaking on mobile:**
- Ensure viewport meta tag is present
- Test with browser dev tools at various screen sizes

**Print styles not working:**
- Use `Ctrl+P` / `Cmd+P` to access print preview
- Check browser print settings for background graphics

**Colors not changing:**
- Clear browser cache after CSS modifications
- Ensure CSS custom properties are properly formatted

## 📋 Browser Support

- **Chrome/Edge**: 88+
- **Firefox**: 85+
- **Safari**: 14+
- **Mobile browsers**: iOS Safari 14+, Chrome Mobile 88+

## 🤝 Contributing

Found a bug or have a suggestion? Please:
1. Check existing issues first
2. Create a detailed bug report or feature request
3. Include browser version and screenshot if applicable

## 📄 License

This template is open source and available under the [MIT License](LICENSE).

## 🎉 Credits

- **Fonts**: Google Fonts (Cormorant Garamond, Work Sans, JetBrains Mono)
- **Icons**: Font Awesome 6.0
- **Design Philosophy**: Inspired by high-end editorial design (Monocle, Kinfolk, Vogue)

---

**Happy job hunting!** 🚀

For questions or support, please open an issue on the GitHub repository.# LexiconProject_CV_Template
