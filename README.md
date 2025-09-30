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
│   ├── ABNER_logo.svg
│   ├── sibling-dna-test.jpg
│   ├── Non_Invasive_Pregnancy_Test.jpg
│   ├── weightloss-dna-test.jpg
│   ├── covid-19-test.jpg
│   ├── influenza-test.jpg
│   ├── Parental_DNA_Test.jpg
│   ├── hair_drug_testing.png
│   └── nail_drug_testingpng.png
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