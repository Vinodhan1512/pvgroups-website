# PV Groups Consultancy Service - Official Website

Professional static website for PV Groups Consultancy Service, showcasing software development and IT consulting services.

## 🚀 Live Website

Once deployed, your website will be available at:
- `https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME/`
- Or with custom domain: `https://www.pvgroups.com`

## 📁 Project Structure

```
pvgroups-website/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # All styles and responsive design
├── js/
│   └── script.js          # Navigation, forms, and interactions
├── assets/                # Images and media files
│   └── .gitkeep
└── README.md              # This file
```

## ✨ Features

- **Fully Responsive**: Mobile-first design that works on all devices
- **Professional Design**: Clean, modern UI with enterprise-grade aesthetics
- **Smooth Animations**: CSS-only animations for performance
- **Contact Form**: mailto integration for lead capture
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized CSS and JavaScript
- **No Dependencies**: Pure HTML, CSS, and JavaScript (no build process required)

## 🛠️ Technologies Used

- HTML5
- CSS3 (CSS Variables, Flexbox, Grid)
- Vanilla JavaScript
- Google Fonts (DM Serif Display, Work Sans)

## 📋 Deployment Instructions

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. Enter repository name (e.g., `pvgroups-website`)
5. Choose **Public** visibility
6. Click **"Create repository"**

### Step 2: Upload Files

**Option A: Using Git Command Line**

```bash
# Navigate to your project folder
cd /path/to/pvgroups-website

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: PV Groups website"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. On your repository page, click **"uploading an existing file"**
2. Drag and drop all project files maintaining folder structure
3. Commit changes

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **"Save"**
6. Wait 2-3 minutes for deployment
7. Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/`

### Step 4: Verify Deployment

1. Visit your GitHub Pages URL
2. Test all sections and navigation
3. Test on mobile devices
4. Verify contact form opens email client

## 🌐 Custom Domain Setup (Optional)

### Step 1: Purchase Domain

Purchase a domain from providers like:
- GoDaddy
- Namecheap
- Google Domains
- Hostinger

### Step 2: Configure DNS Settings

Add the following DNS records in your domain provider's settings:

**A Records:**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

**CNAME Record (for www subdomain):**
```
Type: CNAME
Name: www
Value: YOUR_USERNAME.github.io
```

### Step 3: Configure GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under **"Custom domain"**, enter your domain (e.g., `pvgroups.com`)
3. Click **"Save"**
4. Wait for DNS check to complete (may take 24-48 hours)
5. Enable **"Enforce HTTPS"** once DNS is verified

## 📝 Customization Guide

### Update Contact Email

1. Open `index.html`
2. Find the email address in the Contact section
3. Replace `info@pvgroups.com` with your actual email
4. Open `js/script.js`
5. Update the mailto link on line 63

### Add Your Logo

1. Save your logo as `logo.png` or `logo.svg` in the `assets/` folder
2. Open `index.html`
3. Find the `.logo` section in the navbar
4. Replace text with: `<img src="assets/logo.png" alt="PV Groups Logo" height="40">`

### Change Colors

1. Open `css/style.css`
2. Modify CSS variables in the `:root` section (lines 9-25)
3. Save and push changes

### Add Favicon

1. Create a 32x32 or 64x64 favicon.ico file
2. Save it in the root directory
3. Add to `<head>` in `index.html`:
```html
<link rel="icon" type="image/x-icon" href="favicon.ico">
```

## 🔄 Updating Your Website

After making changes:

```bash
# Save your changes in code editor
# Stage changes
git add .

# Commit changes
git commit -m "Description of changes"

# Push to GitHub
git push origin main
```

GitHub Pages will automatically rebuild and deploy your site within 1-2 minutes.

## 📱 Testing Checklist

Before going live, test:

- [ ] All navigation links work
- [ ] Mobile responsive design works on phones and tablets
- [ ] Contact form opens email client correctly
- [ ] All sections display properly
- [ ] Images load (if you added any)
- [ ] Page loads quickly
- [ ] No console errors in browser

## 🐛 Troubleshooting

**Site not loading after deployment:**
- Wait 5 minutes for initial deployment
- Check GitHub Pages settings are correct
- Verify branch is set to `main` and folder to `/ (root)`

**Contact form not working:**
- Verify email client is configured on user's device
- Check mailto link syntax in `script.js`

**Custom domain not working:**
- Wait 24-48 hours for DNS propagation
- Verify DNS records are correct
- Check GitHub Pages custom domain settings

**Styles not loading:**
- Check file paths are relative (starting with `css/` or `js/`)
- Verify all files are committed and pushed to GitHub

## 📧 Support

For questions or assistance:
- Email: info@pvgroups.com
- Create an issue in this repository

## 📄 License

© 2024 PV Groups Consultancy Service. All rights reserved.

## 🎉 Deployment Commands Summary

```bash
# Quick deployment (after initial setup)
git add .
git commit -m "Update website content"
git push origin main
```

Your website will be live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/` within 1-2 minutes!

---

**Built with ❤️ for PV Groups Consultancy Service**
