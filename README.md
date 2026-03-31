# Lokesh S — AI & ML Engineer Portfolio

A modern, interactive portfolio website showcasing AI and Machine Learning expertise with a sleek cyberpunk-inspired design.

## Overview

This is a professional portfolio website built with HTML, CSS, and JavaScript, featuring:

- **Modern Design**: Dark theme with cyan and violet gradient accents
- **Smooth Animations**: Interactive cursor effects and scroll-based animations
- **Responsive Layout**: Optimized for desktop and mobile devices
- **Custom Cursor**: Animated dot and ring cursor tracking
- **Fast Performance**: Lightweight, no external frameworks required

## Features

✨ **Interactive Elements**
- Custom cursor with hover effects
- Smooth scrolling behavior
- Animated gradient text
- Floating orb background effects
- Typwriter effect for dynamic content

🎨 **Design System**
- CSS custom properties (variables) for consistent theming
- Professional color palette (Cyan #00e6be, Violet #7c3aed)
- Grid-based layout system
- Smooth transitions and transforms

📱 **Responsive Design**
- Mobile-first approach
- Flexible navigation
- Adaptive typography using `clamp()`
- Touch-friendly buttons and interactions

## Project Structure

```
├── Code.html          # Main HTML file with all code embedded
└── README.md          # This file
```

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Usage

1. **Open the Portfolio**
   - Simply open `Code.html` in your web browser
   - Or upload to a web server and access via URL

2. **Navigation**
   - Use the navigation bar to browse different sections
   - Click buttons to view projects or contact information

3. **Customization**
   - Edit the HTML file to update content, projects, and links
   - Modify CSS variables in the `:root` section for theme changes
   - Update colors, fonts, and spacing as needed

## Customization Guide

### Change Theme Colors

Located in the `<style>` section, modify the CSS variables:

```css
:root {
  --bg: #04060f;           /* Background color */
  --cyan: #00e6be;         /* Primary accent color */
  --violet: #7c3aed;       /* Secondary accent color */
  --text: #dde3f5;         /* Text color */
  --muted: #5c6a8a;        /* Muted text color */
}
```

### Update Content

Search for these sections to edit:
- **Hero Section**: Main introduction and Call-to-Action buttons
- **Navigation**: Update links and menu items
- **Projects/Experience**: Add your portfolio pieces
- **Contact Information**: Update email and social links

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **No external dependencies** - Pure HTML/CSS/JS
- **Optimized animations** - Uses `will-change` and `transform` for smooth 60fps
- **Lightweight** - Single file implementation
- **Fast load times** - Minimal assets and inline styling

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, gradients, animations, flexbox, grid
- **Vanilla JavaScript**: DOM manipulation, event handling, custom cursor
- **Google Fonts**: Syne (headers) and Space Mono (code)

## Features Breakdown

### Interactive Cursor
```javascript
// Custom cursor that follows mouse movement
- Dot cursor with glow effect
- Ring cursor that expands on hover
- Smooth tracking with requestAnimationFrame
```

### Animations
- **Grid background**: Subtle animated grid pattern
- **Floating orbs**: Blur effects with positioned elements
- **Text gradients**: Multi-color gradient text with clip
- **Button hover**: Scale and shadow effects on interaction

### Responsive Breakpoints
- Desktop: Full layout with side-by-side content
- Tablet: Adjusted spacing and typography
- Mobile: Stacked layout with optimized touch targets

## Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Enable GitHub Pages in repository settings
3. Select the branch and folder (root)
4. Your site will be live at `https://username.github.io/repo-name`

### Custom Domain
1. Add a `CNAME` file with your custom domain
2. Update your domain DNS settings to point to GitHub Pages

### Alternative Hosting
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any static file hosting service

## SEO Optimization

The website includes:
- Proper semantic HTML structure
- Meta tags for viewport and charset
- Descriptive page title
- Consider adding:
  - Meta description tags
  - Open Graph tags for social sharing
  - Structured data (Schema.org)
  - Sitemap.xml

## Accessibility

Improvements to consider:
- Add ARIA labels for interactive elements
- Ensure color contrast meets WCAG standards
- Add keyboard navigation support
- Include skip-to-content links

## Future Enhancements

- [ ] Add dark/light mode toggle
- [ ] Implement smooth scroll sections
- [ ] Add contact form with backend
- [ ] Portfolio filtering by category
- [ ] Blog section
- [ ] Analytics integration
- [ ] Newsletter signup
- [ ] Testimonials/reviews section

## License

This project is open source and available for personal and commercial use.

## Contact & Links

- **Website**: [Your Portfolio URL]
- **GitHub**: [Your GitHub Profile]
- **LinkedIn**: [Your LinkedIn]
- **Email**: [Your Email]

---

Made with ❤️ by Lokesh S
