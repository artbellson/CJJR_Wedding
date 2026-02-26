# Clark Jayson & Jovie Rose Wedding Website

Welcome to the wedding website for Clark Jayson P. Sedantes and Jovie Rose G. Pagdilao.

## 🌿 Features

- Beautiful sage green and olive green color scheme
- Compact and clean navigation menu
- Fully responsive design (mobile and desktop)
- Smooth performance without heavy animations
- Complete wedding details
- Entourage and sponsors listings
- Interactive navigation

## 📁 Files Included

- `index.html` - Main HTML structure
- `style.css` - Complete styling with responsive design
- `script.js` - Interactive JavaScript features
- `README.md` - This file

## 🚀 Deployment Instructions

### GitHub Pages Setup

1. **Upload files to your repository:**
   ```bash
   git clone https://github.com/artbellson/CJJR_Wedding.git
   cd CJJR_Wedding
   # Copy all files (index.html, style.css, script.js) to this folder
   git add .
   git commit -m "Updated wedding website with smaller menu bar"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at: `https://artbellson.github.io/CJJR_Wedding/`

3. **Custom Domain (Optional):**
   - In the "Pages" settings, enter your custom domain
   - Add a CNAME record in your domain's DNS settings pointing to `artbellson.github.io`
   - Wait for DNS propagation (usually 24-48 hours)

## 🎨 Customization

### Update Hero Photo
Replace the hero background image URL in `style.css` (around line 145):
```css
background: linear-gradient(rgba(85, 107, 47, 0.4), rgba(156, 175, 136, 0.5)),
            url('YOUR_GOOGLE_DRIVE_IMAGE_LINK') center/cover no-repeat;
```

To use your Google Drive image:
1. Make the image publicly accessible
2. Get the direct link using format: `https://drive.google.com/uc?export=view&id=FILE_ID`
3. Replace FILE_ID with your actual file ID from the sharing link

### Add QR Code
Replace the QR placeholder in `index.html` with your actual QR code image:
```html
<div class="qr-box">
    <img src="path/to/your/qr-code.png" alt="QR Code for directions" style="width: 100%; height: 100%; border-radius: 15px;">
</div>
```

## 🎯 Changes Made

- **Smaller Menu Bar**: Reduced navigation height from 1rem padding to 0.5rem
- **Compact Logo**: Reduced logo size from 2.5rem to 1.8rem
- **Smaller Nav Links**: Reduced font size from 0.95rem to 0.85rem
- **Removed Heavy Animations**: Removed AOS library and data-aos attributes
- **Smoother Performance**: Lighter JavaScript without animation libraries
- **Clean Look**: Maintained elegant design with better performance

## 🎯 Color Scheme

- Sage Green: `#9CAF88`
- Olive Green: `#6B8E23`
- Sage Light: `#D9E4C7`
- Olive Dark: `#556B2F`
- Gold Accent: `#C9A961`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- All fonts are loaded from Google Fonts
- No heavy animation libraries
- Fully responsive for all screen sizes
- No backend required - pure static HTML/CSS/JS
- Optimized for fast loading

## 💒 Wedding Details

**Date:** April 30, 2026  
**Venue:** MMSU Hostel Function Hall  
**Location:** 3H55+4JM, Manor, City of Batac, Ilocos Norte

---

**Congratulations to Clark Jayson and Jovie Rose!** 🎉

For support or questions, contact: artbellson@example.com
