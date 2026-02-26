# Clark Jayson & Jovie Rose Wedding Website

Welcome to the wedding website for Clark Jayson P. Sedantes and Jovie Rose G. Pagdilao.

## 🌿 Features

- Beautiful sage green and olive green color scheme
- **Uses local files from public folder**
- Direct page access (no welcome overlay)
- Manual music control with play/pause button
- Smooth scroll animations (AOS library)
- Fully responsive design (mobile and desktop)
- Complete wedding details
- Entourage and sponsors listings

## 📁 File Structure

```
CJJR_Wedding/
├── index.html          # Main website file
├── style.css           # All styling
├── script.js           # Interactive features
├── README.md           # This file
└── public/             # Media folder
    ├── image.png       # Hero background image (place your photo here)
    └── audio.mp3       # Background music (place your audio here)
```

## 🚀 Setup Instructions

### 1. Add Your Files

**Before deploying, you MUST add these files:**

1. **Hero Photo**: Save your couple photo as `public/image.png`
   - Recommended size: 1920x1080 or larger
   - Format: PNG, JPG, or JPEG (rename to image.png)

2. **Background Music**: Save your audio file as `public/audio.mp3`
   - Format: MP3
   - Download from Google Drive first, then place here

### 2. Deploy to GitHub Pages

```bash
# 1. Clone your repository
git clone https://github.com/artbellson/CJJR_Wedding.git
cd CJJR_Wedding

# 2. Extract the ZIP and copy ALL files to the repo folder
# Make sure to include the public folder with your files

# 3. Add your image and audio
# Place your couple photo as: public/image.png
# Place your audio file as: public/audio.mp3

# 4. Push to GitHub
git add .
git commit -m "Wedding website with local media files"
git push origin main

# 5. Enable GitHub Pages in Settings > Pages > Source: main branch
```

Your website will be live at: `https://artbellson.github.io/CJJR_Wedding/`

## 🎯 What Changed from Previous Version

| Feature | Previous Version | This Version |
|---------|-----------------|--------------|
| **Welcome Overlay** | ✅ Had welcome screen | ❌ Removed - direct access |
| **Music Autoplay** | ✅ Auto-played after click | ❌ Manual play only |
| **Hero Image** | Google Drive link | ✅ Local file: `public/image.png` |
| **Audio** | Google Drive link | ✅ Local file: `public/audio.mp3` |
| **User Experience** | Click to enter | ✅ Immediate access |

## 🎵 Music Player

- **Manual control**: Click the floating button to play/pause
- **Location**: Bottom-right corner
- **File**: Loads from `public/audio.mp3`
- **Note**: Music will NOT autoplay (user must click play button)

## 🖼️ Hero Image

- **File**: `public/image.png`
- **Location**: Hero section background
- **Note**: Replace this file with your actual couple photo before deploying

## ⚠️ IMPORTANT: Before Deploying

**You MUST add these files to the public folder:**

1. ✅ `public/image.png` - Your hero photo
2. ✅ `public/audio.mp3` - Your background music

**Without these files, the website will show:**
- ❌ Broken image in hero section
- ❌ Music player won't work

## 💒 Wedding Details

**Date:** April 23, 2026  
**Time:** 3:00 PM  
**Venue:** MMSU Hostel Function Hall  
**Location:** 3H55+4JM, Manor, City of Batac, Ilocos Norte

## 🎨 Color Scheme

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

---

**Congratulations to Clark Jayson and Jovie Rose!** 🎉

For support or questions, contact: artbellson@example.com
