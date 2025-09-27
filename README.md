# Abner Health Testing Solutions

A professional health testing services website built for fast deployment on Vercel with custom domain support.

## 🚀 Quick Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/abner-health)

## 📁 Project Structure

```
Abner_health/
├── index.html          # Main website file
├── vercel.json         # Vercel deployment configuration
├── images/             # Logo and service images
│   ├── 551702834_1281172327118736_3900065226629414296_n.jpg
│   ├── 551889170_772420222291016_5377369041312008962_n.jpg
│   ├── 552630647_1356816312563114_4416391529598099973_n.jpg
│   ├── 552665625_1324992739214636_8824066322279515079_n.jpg
│   ├── 553087725_1889434511985447_7303884946825117226_n.jpg
│   └── 553231848_1280417696746620_5443054716007752993_n.jpg
└── README.md           # This file
```

## 🔧 Setup Instructions

### Option 1: Deploy to Vercel (Recommended)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Abner Health website"
   git branch -M main
   git remote add origin https://github.com/yourusername/abner-health.git
   git push -u origin main
   ```

2. **Deploy on Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Sign up/in with GitHub
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will auto-detect and deploy!

3. **Add Custom Domain:**
   - In Vercel dashboard, go to your project
   - Click "Domains" tab
   - Add your custom domain
   - Follow DNS setup instructions

### Option 2: Local Development

```bash
# Serve locally (requires Python)
python -m http.server 8000

# Or with Node.js
npx serve .

# Then visit: http://localhost:8000
```

## 🎨 Customization

### Update Contact Information
Edit `index.html` lines 200-220 to update:
- Phone number
- Email address
- Physical address
- Business hours

### Replace Service Images
Currently using emoji placeholders. To add real photos:

1. Add your service images to the `images/` folder
2. Update the service cards in `index.html`:

```html
<!-- Replace this -->
<div class="service-image">🧬</div>

<!-- With this -->
<div class="service-image">
    <img src="./images/dna-testing.jpg" alt="DNA Testing" style="width: 80px; height: 80px; object-fit: cover; border-radius: 10px;">
</div>
```

### Update Logo
Replace the current logo by updating line 78 in `index.html`:
```html
<img src="./images/your-logo.png" alt="Abner Health Testing Solutions Logo" class="logo">
```

## 🌟 Features

- **Responsive Design:** Works on all devices
- **Fast Loading:** Optimized for speed
- **SEO Ready:** Proper meta tags and structure
- **Professional Layout:** Clean, medical-grade design
- **Vercel Optimized:** Ready for instant deployment

## 📱 Services Included

- DNA Testing
- Pregnancy Testing
- Legal Testing
- STD Testing
- Drug Testing

## 🔒 Custom Domain Setup on Vercel

1. **Purchase domain** from your preferred registrar
2. **In Vercel dashboard:**
   - Go to your project
   - Click "Domains"
   - Add your domain (e.g., `abnerhealthtesting.com`)
3. **Update DNS records** at your registrar:
   - Add CNAME record: `www` → `cname.vercel-dns.com`
   - Add A record: `@` → `76.76.19.61`
4. **Wait for propagation** (usually 5-30 minutes)

## 🚀 Go Live Checklist

- [ ] Update contact information
- [ ] Replace placeholder images
- [ ] Test on mobile devices
- [ ] Set up custom domain
- [ ] Test all links and contact forms
- [ ] Add Google Analytics (optional)

## 💡 Pro Tips

- **Free SSL:** Vercel provides automatic HTTPS
- **Global CDN:** Your site loads fast worldwide
- **Easy Updates:** Just push to GitHub to update
- **Analytics:** Add Vercel Analytics for visitor insights

Ready to launch your health testing business online! 🎯