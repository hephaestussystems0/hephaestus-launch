# Hephaestus Systems - Launch Page

A beautiful, animated launch page announcing Hephaestus Systems' business launch.

## Local Development

```bash
npm install
npm start
```

Visit `http://localhost:3000`

## Deployment to Railway

### Option 1: Deploy via GitHub (Recommended)

1. **Create a GitHub repo:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/hephaestus-launch.git
   git branch -M main
   git push -u origin main
   ```

2. **Deploy on Railway:**
   - Go to https://railway.app
   - Sign in with GitHub
   - Click "New Project"
   - Select "Deploy from GitHub"
   - Choose this repository
   - Railway will auto-detect it's a Node.js app
   - Click "Deploy"

3. **Get your URL:**
   - Railway will generate a URL like: `https://hephaestus-launch-production.up.railway.app`
   - Your site is live!

### Option 2: One-Click Deploy (Future)

Coming soon! For now, use Option 1.

## Features

- ✨ Beautiful gradient background with animated blobs
- 📱 Fully responsive design
- 🎨 Custom Google Fonts (Playfair Display + Poppins)
- ⚡ Smooth animations and transitions
- 🌟 Twinkling sparkle effects
- 📱 Mobile-optimized

## Files

- `server.js` - Express server
- `public/index.html` - Main landing page
- `package.json` - Dependencies
- `Procfile` - Railway/Heroku configuration

## Environment

- Node.js 18.x
- Port: 3000 (or `$PORT` environment variable on Railway)

## Customization

Edit `public/index.html` to change:
- Text/messaging
- Colors
- Fonts
- Button text/behavior

## Author

JARVIS - Hephaestus Systems Automation
