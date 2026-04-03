# Omran Yapı - Professional Website

## 📋 Project Overview

**Omran Yapı** is a professional multilingual website for a company specializing in interior and exterior finishing, renovation, and decoration services for homes and businesses. The company is based in **Gebze, Kocaeli, Turkey**.

## 🌐 Live Website

- **GitHub Pages:** https://3NZ1I.github.io/da7ambey
- **Custom Domain:** https://omranyapi.com
- **Repository:** https://github.com/3NZ1I/da7ambey

## 🌍 Languages Supported

- 🇹🇷 **Turkish** (Default)
- 🇬🇧 **English**
- 🇸🇦 **Arabic** (with RTL support)

## 🏗️ Project Structure

```
/mnt/e/Omran/
├── index.html              # Main HTML file
├── CNAME                   # Custom domain configuration (omranyapi.com)
├── css/
│   └── style.css          # All styles with responsive design
├── js/
│   ├── translations.js    # Language translations (TR/EN/AR)
│   └── main.js            # Interactive features & language switching
└── images/
    ├── background.png     # Hero section background image
    ├── logo 2.png        # Company logo (header & footer)
    └── icon.png          # Browser favicon
```

## ✨ Features

### Core Features
- **Multilingual Support** - Full Turkish, English, and Arabic translations
- **RTL Support** - Automatic right-to-left layout for Arabic
- **Language Persistence** - Saves user's language preference in localStorage
- **Responsive Design** - Mobile, tablet, and desktop optimized
- **Smooth Animations** - Scroll-triggered animations and transitions

### Sections
1. **Hero** - Full-screen banner with background image and CTAs
2. **About** - Company story with key statistics
3. **Services** - 8 service cards (painting, tiles, flooring, drywall, doors, insulation, renovation, consulting)
4. **Portfolio** - Filterable project gallery (Interior/Exterior/Commercial)
5. **Statistics** - Animated counters (500+ projects, 15+ years, 450+ clients, 25+ team)
6. **Testimonials** - Client reviews with star ratings
7. **Contact** - Contact info, working form, and Google Maps integration
8. **Footer** - Quick links, services, and company info

### Interactive Features
- Mobile hamburger menu
- Portfolio filtering
- Smooth scroll navigation
- Active nav link highlighting
- Back-to-top button
- Contact form with validation
- Animated stat counters

## 🎨 Design System

### Colors
```css
--primary: #2C3E50;        /* Navy Blue */
--primary-dark: #1A252F;
--accent: #C9A961;         /* Gold */
--accent-light: #D4BC8B;
```

### Typography
- **Headings:** Playfair Display (serif)
- **Body:** Inter (sans-serif)
- **Arabic:** Noto Sans Arabic

### Icons
- Font Awesome 6.4.0

## 📞 Company Contact Information

- **Phone:** +90 501 066 00 92 | +90 531 654 61 03
- **Email:** info@omranyapi.com
- **Address:** Gebze, Kocaeli, Turkey
- **Instagram:** https://www.instagram.com/omran_yapi

## 🚀 Development & Deployment

### Local Development
```bash
# Navigate to project
cd /mnt/e/Omran

# Start local server
python3 -m http.server 8080

# Open browser
http://localhost:8080
```

### Git Workflow
```bash
# Make changes, then commit and push
cd /mnt/e/Omran
git add .
git commit -m "Description of changes"
git pull --rebase origin main
git push origin main
```

### SSH Key Configuration
- **Key Name:** `da7ambey`
- **Location:** `~/.ssh/da7ambey`
- **SSH Config Host:** `github-da7ambey`
- **Remote URL:** `git@github-da7ambey:3NZ1I/da7ambey.git`

### Custom Domain DNS
**A Records** (point to GitHub Pages):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME Record:**
```
www -> 3NZ1I.github.io
```

## 🔧 Key Files to Edit

| File | Purpose |
|------|---------|
| `index.html` | Page structure and content |
| `css/style.css` | All styling and responsive design |
| `js/translations.js` | Language translations object |
| `js/main.js` | Interactive features and event handlers |
| `images/` | All images (logo, background, etc.) |

## 📝 Adding New Translations

In `js/translations.js`, add keys to all three language objects:

```javascript
const translations = {
    tr: {
        new_key: "Turkish text",
    },
    en: {
        new_key: "English text",
    },
    ar: {
        new_key: "Arabic text",
    }
};
```

Then use in HTML:
```html
<span data-i18n="new_key"></span>
```

## 🎯 Future Enhancements

- [ ] Add real project images to portfolio
- [ ] Implement backend for contact form
- [ ] Add WhatsApp chat widget
- [ ] Add blog/news section
- [ ] Implement image lazy loading
- [ ] Add Google Analytics tracking
- [ ] Create admin panel for content management

## 📄 Credits

- **Developed by:** [CodeB](https://bessar.work/)
- **Built with:** HTML5, CSS3, Vanilla JavaScript
- **Icons:** Font Awesome
- **Fonts:** Google Fonts (Playfair Display, Inter, Noto Sans Arabic)

## 📞 Support

For issues or questions about this project, contact the repository owner or visit https://bessar.work/
