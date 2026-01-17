# Udhayam TV Repair & Electronics Service Website

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


   2. Customization
To customize the website:

Business Information: Update contact details in the Contact section

Phone Numbers: Update phone numbers in header, hero, and contact sections

Brand Colors: Modify CSS variables in the :root section

Content: Edit text content as needed

3. Deployment
GitHub Pages (Free Hosting):
Go to your repository on GitHub

Click "Settings" → "Pages"

Under "Source", select "Deploy from a branch"

Select "main" branch and /root folder

Click "Save" - Your site will be live at https://username.github.io/repository-name

Custom Domain (Optional):
In GitHub Pages settings, add your custom domain

Update DNS records with your domain provider

📱 Technologies Used
HTML5 - Semantic markup

CSS3 - Modern styling with CSS Grid & Flexbox

JavaScript - Interactive features and animations

Font Awesome - Icons

Animate.css - Animation library

Formspree - Form handling and email

GitHub Pages - Free hosting

📁 Project Structure
text
udhayam-tv-repair-website/
├── index.html              # Main website file
├── README.md              # This documentation
├── .gitignore            # Git ignore rules
├── LICENSE               # MIT License
└── assets/               # Future assets folder
✨ Key Sections
Hero Section - Call-to-action with trust badges

Experience Banner - 35+ years statistics

Services Section - TV repair, electronics, specialized repairs

TV Issues Section - 30+ common problems with solutions

Contact Section - Complete contact info + service request form

Floating Buttons - Quick WhatsApp and phone access

📞 Contact Information
Address: No 784 Ponniyamman Kovil 1st Street, Vengadamangalam Rd, Melakottaiyur, Chennai, Tamil Nadu 600127

Phone: +91 98765 43210, +91 87654 32109

Hours: Mon-Sat: 9:00 AM - 8:00 PM, Sun: 10:00 AM - 6:00 PM

Since: 1990 (35+ Years Experience)

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Font Awesome for icons

Unsplash for background images

Animate.css for animations

Formspree for form handling

GitHub for free hosting

🔄 Updates & Maintenance
To update the website:

Edit index.html directly

Commit changes to GitHub

GitHub Pages will auto-deploy

⭐ Star this repository if you find it useful!


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
