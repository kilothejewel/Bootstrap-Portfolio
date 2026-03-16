# Bootstrap-Portfolio

**Professional Portfolio - Cameron Darries**

A sleek, responsive personal portfolio website built with Bootstrap 5.3. This project demonstrates clean UI/UX design, mobile-first responsiveness, semantic HTML structure, and web accessibility best practices.

---

## 🎯 Key Features

- **Modern Hero Section** - Full-screen landing page with high-contrast dark overlay for optimal readability and visual hierarchy
- **Dynamic About Card** - Custom card layout featuring professional profile image, contact information, and technical skill badges
- **Responsive Project Grid** - 6-project showcase with fluid grid layout (1 column on mobile, 2 on tablet, 3 on desktop)
- **Uniform Card Logic** - Flexbox `mt-auto` ensures action buttons align perfectly across all screen sizes
- **Validated Contact Form** - Clean, user-friendly form with HTML5 validation and smooth interactions
- **Accessible Navigation** - Sticky navbar with mobile hamburger menu and skip-to-content link
- **Professional Styling** - Custom CSS with smooth scrolling, card hover effects, and focus indicators

---

## 📱 Mobile Responsiveness

This portfolio is fully optimized for all devices:

- **Mobile (< 768px)** - Single-column layout, touch-friendly buttons, readable typography
- **Tablet (768px - 1024px)** - Two-column project grid, optimized spacing
- **Desktop (> 1024px)** - Three-column project grid, expanded hero section

The Bootstrap JS Bundle enables the mobile hamburger menu to function correctly on all devices.

---

## ♿ Accessibility Features

- **Skip Navigation Link** - Users can skip directly to main content for keyboard navigation
- **Semantic HTML** - Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` elements
- **Descriptive Alt Text** - All images include meaningful alt attributes for screen readers
- **Color Contrast** - High contrast between text and backgrounds meets WCAG AA standards
- **Focus Indicators** - Clear focus states on all interactive elements for keyboard navigation
- **Form Labels** - All form inputs have associated labels for accessibility

---

## 🛠️ Built With

- **Bootstrap 5.3** - Responsive grid system, utility classes, and pre-built components
- **Bootstrap Icons** - Professional vector iconography library
- **HTML5** - Semantic markup and form validation
- **CSS3** - Custom animations, transitions, and responsive design
- **Mobile-First Approach** - Progressive enhancement from small to large screens

---

## 📋 Technical Implementation

### Project Grid Structure
Each project card utilizes:
- `d-flex flex-column` - Flexible column layout for consistent spacing
- `mt-auto` - Auto margin to push buttons to the bottom of cards
- `gap-2` - Consistent spacing between buttons

### Custom CSS Enhancements
- Smooth scroll behavior for navigation links
- Card hover animations (translateY, box-shadow)
- Image zoom effect on hover
- Button interaction feedback
- Responsive typography scaling

### Form Validation
- HTML5 built-in validation (required, email format)
- Clean error messaging
- Accessible form structure with associated labels

---

## 🚀 How to Use

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. **Customize** the content:
   - Update personal information in the About section
   - Replace project images in the `assets` folder
   - Update project titles and descriptions
   - Add your own social media links
4. **Deploy** to your hosting service

---

## 📁 File Structure

```
Bootstrap-Portfolio/
├── index.html          # Main HTML file with semantic structure
├── styles.css          # Custom CSS with animations and hover effects
├── README.md           # Project documentation
├── package.json        # Bootstrap dependency management
└── assets/            # Project images and profile photo
    ├── Portfolio_Picture.jpeg
    ├── tesla.png
    ├── netflix.png
    ├── youtube.png
    ├── twitch.png
    ├── spotify.png
    └── shopify.png
```

---

## 🔧 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📝 Customization Guide

### Change Colors
Bootstrap utility classes use primary color. To customize:
- Modify `btn-primary` bootstrap theme or
- Update the Bootstrap CDN link to use Sass variables

### Update Social Links
Replace `#` in footer social icons with actual URLs:
```html
<a href="https://instagram.com/yourprofile" class="text-dark fs-2">
  <i class="bi bi-instagram"></i>
</a>
```

### Add New Projects
Copy any project card structure and paste at the end of the grid:
```html
<div class="col-sm-12 col-md-6 col-lg-4">
  <div class="card h-100 shadow-sm border-0">
    <img src="./assets/project.png" alt="Project description">
    <!-- ... -->
  </div>
</div>
```

---

## 👤 Author

**Cameron Darries**

- **GitHub**: https://github.com/kilothejewel
- **LinkedIn**: https://www.linkedin.com/in/cameron-darries-924253156/
- **Email**: cam0197darries@gmail.com

---

## 📄 License

This project is open source and available for personal and educational use.

---

## ✅ Production Ready Checklist

- [x] Structural Integrity - All HTML tags properly matched and nested
- [x] Bootstrap Consistency - All components follow Bootstrap standards
- [x] Accessibility - WCAG compliance with alt text and semantic HTML
- [x] Mobile Readiness - Responsive design with functioning hamburger menu
- [x] Custom Styling - Professional CSS with animations and effects
- [x] Performance - Optimized images and efficient CSS
- [x] Cross-browser - Tested on modern browsers
