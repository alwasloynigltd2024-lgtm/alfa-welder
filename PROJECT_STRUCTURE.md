# Alfa Welder - Project Structure

## 📁 Directory Layout

```
alfa-welder/
├── index.html              # Main HTML file (entry point)
├── css/
│   └── style.css           # All styling (responsive design included)
├── js/
│   └── main.js             # JavaScript functionality (form handling, smooth scroll)
├── assets/
│   ├── images/             # Project gallery and hero images
│   │   ├── hero-bg.jpg
│   │   ├── gate-fabrication.jpg
│   │   ├── steel-framing.jpg
│   │   └── equipment-repair.jpg
│   └── icons/              # Logo and favicon
├── .gitignore              # Git ignore rules
├── README.md               # Project documentation
├── LICENSE                 # Project license (AGPL-3.0)
└── PROJECT_STRUCTURE.md    # This file
```

## 📋 File Descriptions

### **index.html**
- Main entry point for the website
- Contains semantic HTML5 structure
- Includes SEO meta tags for better search engine visibility
- Links to CSS and JavaScript files
- Responsive navigation header
- Hero section with call-to-action
- Services showcase with cards
- Gallery section for portfolio
- Contact form with validation
- Footer

### **css/style.css**
- Centralized styling for all pages
- Dark theme with orange accent color (#ff6600)
- Flexbox-based responsive layout
- Hover effects and animations
- Mobile-first responsive design
- Sticky header navigation
- Card hover animations
- Form focus states

### **js/main.js**
- Contact form validation
- Email format checking
- Form submission handling
- Smooth scroll navigation
- Console logging for debugging

## 🎨 Design Features

**Color Scheme:**
- Primary Background: `#1e1e24` (Dark Steel Grey)
- Secondary Background: `#282830` (Lighter Grey)
- Accent Color: `#ff6600` (Hazard Orange)
- Text Color: `#ffffff` (White)

**Responsive Breakpoints:**
- Desktop: Full layout
- Tablet/Mobile (≤768px): Stacked layout, adjusted font sizes

## 📸 Image Placeholders

Replace these placeholder paths with actual images:
- `assets/images/hero-bg.jpg` - Hero section background
- `assets/images/gate-fabrication.jpg` - Gallery item 1
- `assets/images/steel-framing.jpg` - Gallery item 2
- `assets/images/equipment-repair.jpg` - Gallery item 3

## 🔧 Future Improvements

1. **Backend Integration**
   - Connect contact form to email service
   - Database for project portfolio

2. **Analytics**
   - Google Analytics integration
   - Conversion tracking

3. **Performance**
   - Image optimization
   - Lazy loading
   - CSS/JS minification

4. **SEO**
   - Schema markup for local business
   - Sitemap generation
   - Meta tag optimization

5. **Features**
   - Customer testimonials section
   - Before/after photo gallery
   - Blog/news section
   - Service pricing table