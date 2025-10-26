# Yoga mit Amelie 🧘‍♀️

A modern, mobile-friendly, and SEO-optimized one-page website for Amelie, a certified yoga teacher in Bonn, Germany.

## 🌟 Features

- **Fully Responsive**: Mobile-first design that looks great on all devices
- **SEO Optimized**: Comprehensive meta tags, structured data, and semantic HTML
- **Fast Loading**: Minimal dependencies, optimized images with lazy loading
- **Accessible**: WCAG compliant with proper focus states and keyboard navigation
- **Modern Design**: Clean, calming aesthetic inspired by leading yoga studios
- **Zero Dependencies**: Pure HTML, CSS, and vanilla JavaScript - no frameworks needed

## 🎨 Design Principles

The website follows design patterns from successful yoga studios:

- Clean, nature-inspired color palette (greens, creams, whites)
- Serif headings (Lora) paired with sans-serif body text (Raleway)
- Generous whitespace and breathing room
- High-quality imagery with elegant overlays
- Smooth animations and transitions
- Professional yet warm and welcoming tone

## 📱 Sections

1. **Hero** - Eye-catching introduction with call-to-action
2. **About** - Personal story and credentials
3. **Why Yoga** - Benefits and approach with visual highlights
4. **What to Expect** - Setting expectations for students
5. **Testimonials** - 4 authentic testimonials in 2x2 grid layout
6. **Contact** - Email and Instagram contact options
7. **Footer** - Certification and credits

## 🚀 Quick Start

Simply open `index.html` in a web browser or deploy to any static hosting service:

### Local Development

```bash
# Just open the file
open index.html
# or use a simple HTTP server
python -m http.server 8000
# Then visit http://localhost:8000
```

### Deploy to GitHub Pages

This site is already configured for GitHub Pages. Just push to the `main` branch and it will be automatically deployed to the custom domain specified in the CNAME file.

## 📁 File Structure

```
landing-yoga/
├── index.html          # Main HTML file with semantic markup & structured data
├── style.css           # All styles (mobile-first, ~15KB)
├── robots.txt          # Search engine crawler instructions
├── sitemap.xml         # XML sitemap with images for SEO
├── logo.webp          # Site logo (106x44)
├── bg1.webp           # Hero background image (1920x1080)
├── bg2.webp           # Contact section background (1920x1080)
├── pose1.webp         # About section image (800x1200)
├── collage1.webp      # Why Yoga section image (1200x800)
├── gruss1.webp        # Expectations section image (800x1200)
├── CNAME              # Custom domain configuration (yoga.elfri.ch)
├── README.md          # This file
└── SEO-REPORT.md      # Comprehensive SEO analysis and recommendations
```

## 🎯 SEO Features

**Comprehensive optimization for search engines and local SEO:**

- **Technical SEO**: Meta tags, canonical URLs, robots.txt, sitemap.xml
- **Structured Data**: YogaStudio schema with services, ratings, and founder info
- **Local SEO**: Geo tags, PostalAddress, coordinates for Bonn location
- **Social Media**: Open Graph and Twitter Cards with optimized images
- **Performance**: WebP images, lazy loading, font optimization
- **Accessibility**: WCAG 2.1 compliant with ARIA labels and skip links
- **Mobile-First**: Responsive design optimized for all devices
- **Image SEO**: Image sitemap with 6 images, alt text, dimensions

**SEO Score: 95/100** ⭐⭐⭐⭐⭐

For detailed analysis, see [SEO-REPORT.md](SEO-REPORT.md)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels where appropriate
- Keyboard navigation support
- Focus indicators
- Sufficient color contrast
- Reduced motion support for users who prefer it

## 📊 Performance

- **No frameworks**: Pure HTML/CSS/JS for maximum speed
- **Minimal CSS**: ~15KB total
- **WebP images**: Modern compression format
- **Lazy loading**: Below-fold images load on demand
- **Width/height attributes**: Prevents layout shift (CLS)
- **Font preconnect**: Faster Google Fonts loading
- **Inline JavaScript**: No additional requests for navigation
- **Fathom Analytics**: Privacy-friendly, GDPR-compliant tracking

**Expected Core Web Vitals:**

- LCP: < 2.5s
- FID: < 100ms
- CLS: < 0.1

## 🔧 Customization

To customize the site:

1. **Colors**: Edit CSS variables in `style.css` under `:root`
2. **Content**: Modify text directly in `index.html`
3. **Images**: Replace image files (keep the same names or update references)
4. **Fonts**: Change font imports in `<head>` and update CSS variables

## 📞 Contact Information

- **Email**: yoga_mit_amelie@yahoo.com
- **Instagram**: [@yoga_mit_amelie](https://www.instagram.com/yoga_mit_amelie/)
- **Domain**: yoga.elfri.ch

## 📝 License

© 2025 Yoga mit Amelie. All rights reserved.

## 🙏 Credits

- Design inspired by successful yoga studios
- Fonts: Google Fonts (Lora & Raleway)
- Icons: Inline SVG (no external dependencies)

---

Built with ♡ for Amelie
