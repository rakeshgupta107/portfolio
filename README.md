# Rakesh Gupta - Portfolio Website

Senior Product Leader portfolio showcasing AI-powered SaaS platforms, enterprise products, and thought leadership.

## 🎯 Overview

This is a clean, professional portfolio built with HTML, CSS, and vanilla JavaScript. No frameworks, no build process—just modern, responsive code.

## 📁 File Structure

```
portfolio/
├── index.html          # Homepage
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # Interactions & animations
└── README.md           # This file
```

## 🚀 Setup Instructions

### 1. Create GitHub Repository

```bash
# In your terminal
mkdir portfolio
cd portfolio

# Copy all files from Claude into this folder
# (index.html, css/style.css, js/main.js)

# Initialize git
git init
git add .
git commit -m "Initial portfolio commit"

# Create repo on GitHub, then:
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

### 2. Deploy to Vercel

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Add New" → "Project"
4. Import your `portfolio` repository
5. Deploy settings:
   - **Framework Preset:** Other
   - **Build Command:** (leave empty)
   - **Output Directory:** (leave empty)
6. Click "Deploy"

**Your site will be live in ~30 seconds!**

### 3. Connect Custom Domain

1. In Vercel dashboard, go to your project
2. Settings → Domains
3. Add your domain (e.g., `rakeshgupta.co.uk`)
4. Follow Vercel's DNS instructions
5. Wait 5-10 minutes for DNS propagation

## ✏️ How to Edit

### Update Content

1. Open files in VS Code
2. Edit HTML content directly
3. Save and push to GitHub:
   ```bash
   git add .
   git commit -m "Update content"
   git push
   ```
4. Vercel auto-deploys in ~30 seconds

### Change Colors/Fonts

Edit `css/style.css` - all variables are at the top:

```css
:root {
    --bg: #0a0a0a;           /* Background */
    --text: #e8e8e8;         /* Main text */
    --accent: #00ff88;       /* Accent color */
    --font-display: 'DM Serif Display', serif;
    --font-body: 'IBM Plex Sans', sans-serif;
}
```

## 🎨 Features

- ✅ Responsive design (mobile-first)
- ✅ Smooth scroll animations
- ✅ Fast loading (no dependencies)
- ✅ SEO optimized
- ✅ Accessible
- ✅ Clean, professional aesthetic

## 📝 Next Steps

1. **Add case study pages** (in progress)
2. **Create About page**
3. **Add more LinkedIn posts to Thinking section**
4. **Update email address** in Contact section

## 🔗 Links

- Portfolio: [Your URL here]
- LinkedIn: https://linkedin.com/in/rakeshgupta
- MarginWhiz: https://marginwhiz.com

---

Built with focus on clarity, impact, and professional presentation.
