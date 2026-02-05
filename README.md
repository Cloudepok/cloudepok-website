# Cloudepok Website

AI-First Engineering & Consulting website.

## Quick Start

Simply open `index.html` in a browser to view locally.

## Deploy to GitHub Pages

### 1. Initialize Git
```bash
git init
git add .
git commit -m "Initial commit: Cloudepok website"
```

### 2. Create GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Name: `cloudepok-website`
3. Keep **public** (required for free GitHub Pages)
4. Don't initialize with README

### 3. Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/cloudepok-website.git
git branch -M main
git push -u origin main
```

### 4. Enable GitHub Pages
1. Repository **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Save → Site live in ~2 minutes at `https://YOUR_USERNAME.github.io/cloudepok-website`

## Custom Domain Setup

1. In Settings → Pages → Custom domain: enter `cloudepok.com`
2. At your DNS provider, add:
   - **A records** (for apex domain):
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - **Or CNAME** (for www subdomain): `YOUR_USERNAME.github.io`

3. Check "Enforce HTTPS" after DNS propagates (~24-48 hours)

## Contact Form

The contact form uses [Formspree](https://formspree.io) → submissions go to `aruna@cloudepok.com`.
