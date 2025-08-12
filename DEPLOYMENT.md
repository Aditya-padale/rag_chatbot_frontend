# 🚀 Quick Deployment Guide

## 📁 Files in this Repository

- **`index.html`** - Main application file with embedded CSS and JavaScript
- **`vercel.json`** - Vercel deployment configuration  
- **`package.json`** - Project metadata and scripts
- **`README.md`** - Documentation
- **`.gitignore`** - Git ignore rules

## ⚡ One-Click Deployments

### 🔥 Vercel (Recommended)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Aditya-padale/rag-chatbot-frontend)

1. Click the button above
2. Connect your GitHub account
3. Deploy automatically!

### 🌐 Netlify
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Aditya-padale/rag-chatbot-frontend)

1. Click the button above
2. Connect your GitHub account
3. Deploy automatically!

### 📄 GitHub Pages
1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **Source**: Deploy from a branch
4. Select **Branch**: `main`
5. Your site: `https://yourusername.github.io/rag-chatbot-frontend`

## 🔧 Local Development

```bash
# Clone the repository
git clone https://github.com/Aditya-padale/rag-chatbot-frontend.git
cd rag-chatbot-frontend

# Serve locally
python -m http.server 8000
# or
npx serve .
# or
live-server

# Open browser
http://localhost:8000
```

## ⚙️ Backend Configuration

**Important:** Update the backend URL in `index.html`:

```javascript
// Line ~330 in index.html
const API_BASE_URL = 'https://your-backend-api.onrender.com';
```

Replace with your actual backend URL from Render/Railway/etc.

## 🎯 Expected URLs After Deployment

- **Vercel:** `https://rag-chatbot-frontend-yourname.vercel.app`
- **Netlify:** `https://amazing-chatbot-xyz123.netlify.app` 
- **GitHub Pages:** `https://yourusername.github.io/rag-chatbot-frontend`

## ✅ Features Working

- ✅ Modern Glass Morphism UI
- ✅ Real-time chat interface  
- ✅ Connection status indicator
- ✅ Typing animations
- ✅ Sound notifications
- ✅ Mobile responsive
- ✅ Cross-browser compatible

## 🐛 Troubleshooting

1. **404 Error:** Make sure `index.html` is in the root directory
2. **API Errors:** Update the backend URL in the JavaScript code
3. **CORS Issues:** Ensure your backend allows your frontend domain

**Happy chatting! 🤖**
