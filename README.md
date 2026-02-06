# Swami Vivekananda Sangha, Kohabarawa - Website

A professional, responsive website for Swami Vivekananda Sangha NGO, built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**: Clean, professional design with warm colors inspired by service and community
📱 **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
🎨 **Beautiful Animations**: Smooth scroll animations and interactive elements
📄 **Multiple Pages**: Home, About, Programs, Gallery, Contact, and Donate pages
♿ **Accessible**: Built with semantic HTML and accessibility in mind
⚡ **Fast Loading**: Lightweight, optimized code with no external dependencies (except fonts)

## Pages Included

1. **Home (index.html)**: Welcome page with hero section, mission, programs overview, and impact stats
2. **About Us (about.html)**: Organization history, vision, mission, values, and team
3. **Programs (programs.html)**: Detailed information about all four main programs
4. **Gallery (gallery.html)**: Photo gallery organized by program categories
5. **Contact (contact.html)**: Contact form, information, volunteer and partnership sections
6. **Donate (donate.html)**: Donation information, methods, and impact details

## How to Deploy on GitHub Pages

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create your free account

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `swami-vivekananda-sangha` (or any name you prefer)
4. Make it **Public**
5. Click "Create repository"

### Step 3: Upload Your Files
1. On your repository page, click "uploading an existing file"
2. Drag and drop ALL these files:
   - index.html
   - about.html
   - programs.html
   - gallery.html
   - contact.html
   - donate.html
   - styles.css
   - script.js
   - README.md
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository Settings (top menu)
2. Scroll down to "Pages" section (left sidebar)
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes for deployment

### Step 5: Access Your Website
Your website will be available at:
```
https://YOUR-USERNAME.github.io/swami-vivekananda-sangha/
```

## Customization Guide

### 1. Update Contact Information
Replace placeholder contact details in ALL pages:
- Phone: `+91 XXXX-XXXXXX`
- Email: `info@svskbw.org`
- Bank details in donate.html
- UPI ID in donate.html

### 2. Add Your Photos to Gallery
1. Upload your photos to the repository
2. Open `gallery.html` in GitHub's editor
3. Replace emoji placeholders with:
```html
<img src="your-photo-name.jpg" alt="Description" style="width:100%; height:100%; object-fit:cover;">
```

### 3. Update Impact Numbers
In `index.html`, change the data-target values in the Impact Section:
```html
<div class="stat-number" data-target="1500">0</div>
```

### 4. Change Colors
Edit the `:root` section in `styles.css`:
```css
--primary-color: #FF6B35;  /* Main orange color */
--secondary-color: #2A9D8F; /* Green accent */
--accent-color: #F4A261;    /* Light orange */
```

### 5. Add Your Logo
1. Create a logo image (PNG with transparent background works best)
2. Upload it to your repository
3. In all HTML files, replace the SVG logo with:
```html
<img src="your-logo.png" alt="Logo" width="40" height="40">
```

## File Structure

```
swami-vivekananda-sangha/
│
├── index.html          # Home page
├── about.html          # About us page
├── programs.html       # Programs page
├── gallery.html        # Gallery page
├── contact.html        # Contact page
├── donate.html         # Donate page
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # This file
```

## Features Breakdown

### Navigation
- Sticky header that stays at the top
- Mobile-responsive hamburger menu
- Active page highlighting
- Smooth scroll to sections

### Forms
- Contact form with validation
- Success/error notifications
- Responsive layout

### Animations
- Scroll-triggered animations
- Counter animations for impact stats
- Smooth transitions and hover effects

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Touch-friendly navigation

## Browser Support

✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers

## Need Help?

If you need assistance:
1. Check GitHub Pages documentation: [pages.github.com](https://pages.github.com)
2. Common issues and solutions are in GitHub's help center
3. Make sure all files are uploaded correctly
4. Wait a few minutes after enabling Pages for the site to go live

## Updates and Maintenance

To update your website:
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes
5. Click "Commit changes"
6. Your site will update automatically in 1-2 minutes

## Credits

Website designed and developed for Swami Vivekananda Sangha, Kohabarawa.

**Design Philosophy**: Inspired by Swami Vivekananda's ideals of service, education, and empowerment, with a warm, welcoming aesthetic that reflects community and compassion.

---

**License**: This website template is created for Swami Vivekananda Sangha, Kohabarawa. Feel free to modify and use it for your organization.

**Support**: For technical questions about the website, you can create an issue in this repository.

---

May this website help spread the message of service and empower your community! 🙏
