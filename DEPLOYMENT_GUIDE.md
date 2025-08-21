# Portfolio Deployment Guide

## 🚀 Quick Deployment Options

### 1. GitHub Pages (Free & Easy)
**Current Setup:** Your portfolio is already on GitHub at `https://github.com/NMNayan57/Portfolio`

**To deploy:**
1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "Deploy from a branch" 
4. Choose `main` branch and `/ (root)` folder
5. Your site will be available at: `https://nmnayan57.github.io/Portfolio/`

**Pros:** Free, automatic updates when you push to main
**Cons:** Limited to static sites only

### 2. Netlify (Recommended)
**Steps:**
1. Go to [netlify.com](https://netlify.com)
2. Connect your GitHub account
3. Select your `Portfolio` repository
4. Build settings: Leave empty (static site)
5. Deploy!

**Custom domain:** You can add a custom domain in Netlify settings
**Example URL:** `https://nayan-moni-portfolio.netlify.app`

### 3. Vercel (Great for React/Next.js)
**Steps:**
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with default settings
4. Get instant URL

**Example URL:** `https://portfolio-nmnayan57.vercel.app`

### 4. Firebase Hosting
**Steps:**
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

## 📝 Important Links to Update

### Replace these placeholder links in your portfolio:

#### In `project.html`:
- **M-TRUST Framework:**
  - PyPI Package: `https://pypi.org/project/m-trust/`
  - GitHub: `https://github.com/NMNayan57/M-TRUST`
  - Documentation: `https://m-trust.readthedocs.io/`

- **MedRAG System:**
  - GitHub: `https://github.com/NMNayan57/MedRAG`
  - Live Demo: `https://medrag-demo.streamlit.app/`
  - Docs: `https://github.com/NMNayan57/MedRAG/wiki`

- **LLM Fine-tuning Pipeline:**
  - GitHub: `https://github.com/NMNayan57/medical-llm-finetuning`
  - HuggingFace: `https://huggingface.co/nmnayan57/medical-llama-2`
  - Results: `https://wandb.ai/nmnayan57/medical-llm`

- **Enterprise Chat Platform:**
  - GitHub: `https://github.com/NMNayan57/enterprise-chat-ai`
  - Live Demo: `https://chat-ai-demo.vercel.app/`
  - Architecture: `https://github.com/NMNayan57/enterprise-chat-ai/wiki/Architecture`

#### In `Research.html`:
- All paper links should point to actual publications on:
  - Google Scholar: `https://scholar.google.com/citations?user=YOUR_ID`
  - ResearchGate: `https://www.researchgate.net/profile/Nasim-Nayan`
  - ORCID: `https://orcid.org/0009-0003-4157-3518`

#### In `contact.html`:
- Research collaboration links
- Academic profiles
- CV download link: Make sure `CV_Nayan.pdf` is accessible

## 🔧 Technical Configuration

### Domain Setup (Optional)
If you want a custom domain like `nayan-moni.com`:

1. **Buy domain** from providers like:
   - Namecheap
   - GoDaddy  
   - Google Domains

2. **Configure DNS** in your hosting platform:
   - Netlify: Add custom domain in site settings
   - Vercel: Add domain in project settings
   - GitHub Pages: Add CNAME file with your domain

### SSL Certificate
All mentioned platforms provide free SSL certificates automatically.

### Performance Optimization
Your portfolio is already optimized with:
- ✅ Responsive design
- ✅ Lazy loading images
- ✅ Minified CSS (Tailwind CDN)
- ✅ Fast loading components

## 📱 Mobile Optimization
Your portfolio is mobile-friendly with:
- Responsive navigation
- Touch-friendly buttons  
- Readable typography on all devices
- Proper viewport settings

## 🔍 SEO Optimization
Already implemented:
- Meta descriptions on all pages
- Proper heading structure
- Alt text for images
- Semantic HTML

## 🚀 Recommended Deployment Flow

1. **Start with Netlify** (easiest and most reliable)
2. **Custom domain** if you want professional look
3. **Update all placeholder links** with real project links
4. **Add Google Analytics** for tracking (optional)

## 📊 Analytics Setup (Optional)

Add Google Analytics to track visitors:
1. Create Google Analytics account
2. Add tracking code to all HTML pages before `</head>`
3. Monitor portfolio performance

## 🎯 Final Checklist Before Deployment

- [ ] All placeholder links updated with real URLs
- [ ] CV file is accessible and current
- [ ] All images load properly
- [ ] Contact form works (if implemented)
- [ ] All pages tested on mobile
- [ ] Social media links verified
- [ ] Research paper links verified
- [ ] Project demo links working

## 💡 Pro Tips

1. **Regular Updates:** Keep adding new projects and publications
2. **SEO:** Use descriptive URLs and meta descriptions
3. **Performance:** Compress images for faster loading
4. **Backup:** Keep your repository as backup
5. **Monitoring:** Use uptime monitoring services

## 🌐 Example Live URLs
After deployment, your portfolio could be at:
- `https://nmnayan57.github.io/Portfolio/` (GitHub Pages)
- `https://nayan-moni-research.netlify.app/` (Netlify)
- `https://portfolio-nmnayan57.vercel.app/` (Vercel)

Choose the one that works best for your needs!