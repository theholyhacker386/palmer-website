# Freedom Properties 23 - Website

Professional real estate investor website for Freedom Properties 23

## 📁 Files Included

- `index.html` - Main homepage with all sections
- `privacy-policy.html` - Separate privacy policy page
- `styles.css` - All styling with light blue color scheme
- `script.js` - JavaScript functionality (carousel, smooth scrolling, form validation)

## 🖼️ Image Placeholders to Replace

You need to add your actual images to replace the placeholders. Here's where to add each image:

### 1. Hero Background Image
**Location:** `styles.css` - Line ~230
```css
.hero {
    background-image: linear-gradient(rgba(74, 144, 226, 0.7), rgba(74, 144, 226, 0.7)), url('YOUR-HERO-IMAGE.jpg');
}
```
- Replace `YOUR-HERO-IMAGE.jpg` with your house photo
- Recommended size: 1920x1080px
- Upload image to your website's `/images/` folder

### 2. Palmer Vilagi Photo (Owner Photo)
**Location:** `index.html` - Line ~67
```html
<img src="images/palmer-vilagi.jpg" alt="Palmer Vilagi - Owner" class="placeholder-img">
```
- Replace the placeholder SVG with your owner photo path
- Recommended size: 400x400px (square)
- Upload to `/images/palmer-vilagi.jpg`

### 3. About Section House Photo
**Location:** `index.html` - Line ~73
```html
<img src="images/house-about.jpg" alt="House" class="placeholder-img">
```
- Replace with a professional house photo
- Recommended size: 800x600px
- Upload to `/images/house-about.jpg`

### 4. Facebook Review Screenshots (Testimonials)
**Location:** `index.html` - Lines ~129, ~136, ~143

Replace all three testimonial placeholder images:
```html
<img src="images/testimonial-1.jpg" alt="Customer Review 1">
<img src="images/testimonial-2.jpg" alt="Customer Review 2">
<img src="images/testimonial-3.jpg" alt="Customer Review 3">
```
- Take screenshots of your Facebook reviews
- Crop them nicely
- Recommended size: 600x400px
- Upload to `/images/testimonial-1.jpg`, etc.

## 📧 Contact Form Setup

The contact form is already configured to send emails to **Palmervilagi@freedomproperties23.com** using FormSubmit.co (free service).

### First-Time Setup:
1. When someone first submits the form, FormSubmit will send a confirmation email to Palmervilagi@freedomproperties23.com
2. Click the confirmation link in that email
3. After confirmation, all future form submissions will be sent directly to your email

### Form Features:
- All submissions go to your email
- No spam (honeypot protection included)
- Clean email template
- Mobile-friendly

## 🚀 Deploying to IONOS

### Step 1: Prepare Your Files
1. Create an `/images/` folder in your palmer-website directory
2. Add all your actual images to the `/images/` folder
3. Update the HTML and CSS files with the correct image paths (see above)

### Step 2: Upload to IONOS
1. Log in to your IONOS account at https://www.ionos.com
2. Go to your hosting control panel
3. Open the File Manager or connect via FTP:
   - **FTP Host:** Usually `ftp.yourdomain.com` or provided by IONOS
   - **Username:** Your IONOS FTP username
   - **Password:** Your IONOS FTP password

### Step 3: Upload Files
1. Navigate to your website's root directory (usually `/htdocs/` or `/public_html/`)
2. Upload these files:
   - `index.html`
   - `privacy-policy.html`
   - `styles.css`
   - `script.js`
   - `/images/` folder with all your images

### Step 4: Test Your Website
1. Visit http://freedomproperties23.com in your browser
2. Test all navigation links
3. Test the contact form (submit a test inquiry)
4. Check on mobile devices
5. Test the testimonials carousel

## ✅ Pre-Launch Checklist

- [ ] Replace all 4 image placeholders with actual photos
- [ ] Test contact form and confirm email to Palmervilagi@freedomproperties23.com
- [ ] Check all links work correctly
- [ ] Test on mobile phone
- [ ] Test on tablet
- [ ] Verify phone number (541-760-7408) is clickable
- [ ] Check Privacy Policy page loads correctly
- [ ] Test testimonials carousel swiping on mobile

## 🎨 Customization

### Changing Colors
All colors are defined in `styles.css` at the top:
```css
:root {
    --primary-color: #4A90E2;  /* Main blue color */
    --primary-dark: #357ABD;   /* Darker blue for hovers */
    --primary-light: #87CEEB;  /* Light blue accents */
}
```

### Changing Text
All text content is in `index.html` and can be edited directly.

### Changing Phone Number or Email
Update in these locations:
- Header: Line ~24 in `index.html`
- Contact section: Lines ~154-167 in `index.html`
- Footer: Lines ~177-178 in `index.html`
- Contact form action: Line ~174 in `index.html`
- Privacy Policy page: Lines ~24 and ~177 in `privacy-policy.html`

## 📱 Features

✅ Fully responsive (mobile, tablet, desktop)
✅ Light blue professional color scheme
✅ Sticky navigation header
✅ Smooth scrolling
✅ Working contact form (sends to email)
✅ Swipeable testimonials carousel
✅ Mobile menu
✅ Fast loading
✅ SEO optimized
✅ Professional animations

## 🆘 Support

If you need help:
1. Email: Palmervilagi@freedomproperties23.com
2. Phone: 541-760-7408

## 📝 Notes

- The website is built with vanilla HTML, CSS, and JavaScript (no frameworks needed)
- All images should be optimized for web (compressed to under 500KB each)
- FormSubmit.co is free for unlimited submissions
- IONOS hosting supports all modern web features

---

**Built for Freedom Properties 23**
*Professional Real Estate Investing in Florida & Oregon*
