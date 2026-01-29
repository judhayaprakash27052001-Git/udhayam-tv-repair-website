# jayavel TV Repair & Electronics Service Website

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://yourusername.github.io/udhayam-tv-repair-website/)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A modern, animated, and fully responsive website for **Udhayam TV Repair & Electronics Service**, a trusted business since 1990 in Chennai.

## 🌟 Features

- **Modern & Animated Design**
  - Smooth animations and transitions
  - Floating elements and hover effects
  - Gradient color scheme with gold accents

- **35+ Years Experience Showcase**
  - "Since 1990" branding throughout
  - Animated statistics counters
  - Generational expertise highlighting

- **Complete Business Information**
  - Professional services showcase
  - 30+ common TV issues listed
  - Contact form with Formspree integration
  - Working hours and location

- **Mobile Responsive**
  - Fully responsive design
  - Mobile-friendly navigation
  - Optimized for all devices

- **Formspree Email Integration**
  - Service request form sends emails
  - Loading states and success/error messages
  - Spam protection

## 🚀 Live Demo

Visit the live website: [https://yourusername.github.io/udhayam-tv-repair-website/](https://yourusername.github.io/udhayam-tv-repair-website/)

## 🛠️ Setup Instructions

### 1. Formspree Email Setup
The contact form uses Formspree for email notifications. Follow these steps:

1. Go to [formspree.io](https://formspree.io) and sign up
2. Create a new form (e.g., "Udhayam TV Repair Service Requests")
3. Copy your Formspree form ID
4. In `index.html`, find line 1306 and replace `YOUR_FORM_ID` with your actual form ID:
   ```html
   <form id="serviceForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### 2. Customization
To customize the website:

1. **Business Information**: Update contact details in the Contact section
2. **Phone Numbers**: Update phone numbers in header, hero, and contact sections
3. **Brand Colors**: Modify CSS variables in the `:root` section
4. **Content**: Edit text content as needed

### 3. Deployment
#### GitHub Pages (Free Hosting):
1. Go to your repository on GitHub
2. Click "Settings" → "Pages"
3. Under "Source", select "Deploy from a branch"
4. Select "main" branch and `/root` folder
5. Click "Save" - Your site will be live at `https://username.github.io/repository-name`

#### Custom Domain (Optional):
1. In GitHub Pages settings, add your custom domain
2. Update DNS records with your domain provider

## 📱 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid & Flexbox
- **JavaScript** - Interactive features and animations
- **Font Awesome** - Icons
- **Animate.css** - Animation library
- **Formspree** - Form handling and email
- **GitHub Pages** - Free hosting

## 📁 Project Structure

```
udhayam-tv-repair-website/
├── index.html              # Main website file
├── README.md              # This documentation
├── .gitignore            # Git ignore rules
├── LICENSE               # MIT License
└── assets/               # Future assets folder
```

## ✨ Key Sections

1. **Hero Section** - Call-to-action with trust badges
2. **Experience Banner** - 35+ years statistics
3. **Services Section** - TV repair, electronics, specialized repairs
4. **TV Issues Section** - 30+ common problems with solutions
5. **Contact Section** - Complete contact info + service request form
6. **Floating Buttons** - Quick WhatsApp and phone access

## 📞 Contact Information

- **Address**: No 784 Ponniyamman Kovil 1st Street, Vengadamangalam Rd, Melakottaiyur, Chennai, Tamil Nadu 600127
- **Phone**: +91 98765 43210, +91 87654 32109
- **Hours**: Mon-Sat: 9:00 AM - 8:00 PM, Sun: 10:00 AM - 6:00 PM
- **Since**: 1990 (35+ Years Experience)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for icons
- **Unsplash** for background images
- **Animate.css** for animations
- **Formspree** for form handling
- **GitHub** for free hosting

## 🔄 Updates & Maintenance

To update the website:
1. Edit `index.html` directly
2. Commit changes to GitHub
3. GitHub Pages will auto-deploy

---

**⭐ Star this repository if you find it useful!**
```

### **C. `.gitignore`** - Git Ignore File

```gitignore
# Dependency directories
node_modules/
jspm_packages/

# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*

# Runtime data
pids
*.pid
*.seed
*.pid.lock

# Coverage directory used by tools like istanbul
coverage/

# Dependency directories
bower_components/

# Optional npm cache directory
.npm

# Optional REPL history
.node_repl_history

# Output of 'npm pack'
*.tgz

# Yarn Integrity file
.yarn-integrity

# dotenv environment variables file
.env

# OS generated files
.DS_Store
.DS_Store?
._*
.Spotlight-V100
.Trashes
ehthumbs.db
Thumbs.db

# IDE files
.vscode/
.idea/
*.swp
*.swo

# Local development files
local-config.js
temp/
```

### **D. `LICENSE`** - MIT License File

```text
MIT License

Copyright (c) 2023 Udhayam TV Repair & Electronics Service

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### **E. `formspree-setup.md`** - Detailed Formspree Instructions

```markdown
# Formspree Setup Guide for Udhayam TV Repair Website

## Complete Step-by-Step Instructions

### Step 1: Create Formspree Account
1. Go to [https://formspree.io/register](https://formspree.io/register)
2. Sign up with your email or GitHub account
3. Verify your email address

### Step 2: Create a Form
1. After login, click "New Form"
2. Form Name: `Udhayam TV Repair Service Requests`
3. Email to send to: Enter your business email
4. Click "Create Form"

### Step 3: Get Your Form ID
1. You'll see a screen with your form endpoint
2. It will look like: `https://formspree.io/f/xqkrvqkv`
3. Copy the form ID (the last part): `xqkrvqkv`

### Step 4: Update the HTML
1. Open `index.html`
2. Find this line (around line 1306):
   ```html
   <form id="serviceForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
3. Replace `YOUR_FORM_ID` with your actual form ID

### Step 5: Configure Form Settings
In Formspree dashboard, go to:

1. **Settings Tab**
   - Form Name: Keep as is
   - Reply-To: Leave blank (auto-filled from form)
   - Subject: "New Service Request - Udhayam TV Repair"
   - Redirect: Leave blank for default success page

2. **Email Settings Tab**
   - Enable email notifications
   - Customize email template if needed
   - Add CC/BCC emails (optional)

3. **Spam Protection Tab**
   - Enable Honeypot (recommended)
   - Enable reCAPTCHA (optional)

### Step 6: Test the Form
1. Deploy your website
2. Fill out the service request form
3. Click "Request Service Call"
4. Check your email for the submission
5. Verify data is correct

### Step 7: Monitor Submissions
1. Go to Formspree dashboard
2. Click on your form
3. View "Submissions" tab to see all requests
4. You can export data as CSV if needed

## Troubleshooting

### If emails aren't received:
1. Check spam folder
2. Verify email in Formspree settings
3. Test with different email
4. Check Formspree plan limits (free: 50/month)

### If form shows error:
1. Check Formspree form ID is correct
2. Verify internet connection
3. Check browser console for errors
4. Test with different browser

## Advanced Features (Optional)

### 1. Auto-Responder
Set up automatic reply to customers:
1. In Formspree, go to form settings
2. Enable auto-response
3. Write a thank you message
4. Include next steps

### 2. Form Analytics
Track form performance:
1. Formspree provides basic analytics
2. View submission trends
3. Monitor conversion rates

### 3. Integration with Other Tools
Connect Formspree to:
- Google Sheets
- Slack notifications
- Zapier for automation

## Support
- Formspree Documentation: [https://formspree.io/help](https://formspree.io/help)
- Email: support@formspree.io
- GitHub Issues: Open in repository for website issues
```

## 3. **GitHub Pages Deployment:**

### **Enable GitHub Pages:**
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "GitHub Pages" section
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click "Save"
6. Your site will be live at: `https://YOUR_USERNAME.github.io/udhayam-tv-repair-website/`

### **Custom Domain Setup (Optional):**
1. Buy a domain (e.g., udhayamtvrepair.com)
2. In GitHub Pages settings, add custom domain
3. Update DNS records:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```

## 4. **Quick Start Script:**

Create a file `setup.sh` for quick setup:

```bash
#!/bin/bash

echo "🚀 Setting up Udhayam TV Repair Website Repository"

# Create folder structure
mkdir -p udhayam-tv-repair-website/assets/images
cd udhayam-tv-repair-website

# Create files
touch index.html README.md .gitignore LICENSE formspree-setup.md

echo "📁 Project structure created"
echo "📝 Copy your HTML code to index.html"
echo "📚 Update README.md with your details"
echo "📧 Setup Formspree: https://formspree.io"
echo "🌐 Deploy on GitHub Pages"
```

## 5. **Recommended Repository Settings:**

### **Topics (for discoverability):**
```
html-css-website, tv-repair, electronics-service, responsive-design, web-development, chennai-business
```

### **Description:**
```
Modern animated website for Udhayam TV Repair & Electronics Service (Since 1990). Features 35+ years experience showcase, service request form with Formspree email integration, and responsive design.
```

### **Website:**
Add your business website URL once deployed

### **Issues Template:**
Enable issues and pull requests for community feedback

## 6. **Next Steps After Repository Creation:**

1. **Replace placeholder content:**
   - Update all phone numbers with actual numbers
   - Update business address if different
   - Change email in formspree setup instructions

2. **Set up Formspree** and update form ID

3. **Test thoroughly:**
   - Test on mobile devices
   - Test form submission
   - Check all links work
   - Verify responsive design

4. **Share the website:**
   - Share GitHub Pages link with business
   - Add to Google My Business
   - Share on social media
   - Print QR code for physical store

5. **Regular updates:**
   - Update services as business expands
   - Add customer testimonials
   - Update working hours if changed
   - Add seasonal promotions

## **Repository URL Format:**
- **GitHub Pages URL:** `https://YOUR_USERNAME.github.io/udhayam-tv-repair-website`
- **Repository URL:** `https://github.com/YOUR_USERNAME/udhayam-tv-repair-website`

## **Pro Tips:**

1. **SEO Optimization:** Add meta tags for "TV repair near me Chennai"
2. **Analytics:** Add Google Analytics tracking code
3. **Performance:** Consider compressing images in future
4. **Backup:** Regular commits to GitHub serve as backups
5. **Updates:** Use GitHub's web editor for quick text changes

This complete setup gives you a professional GitHub repository with everything needed to deploy and maintain the Udhayam TV Repair website!
