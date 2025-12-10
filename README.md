# Meri McGinnis Portfolio Website

A clean, minimalistic portfolio website with bold accents and smooth animations. Built with modern HTML5, CSS3, and vanilla JavaScript.

## 🎨 Design Features

- **Clean Editorial Aesthetic** - Minimalist design with bold accent colors
- **Smooth Animations** - CSS and JavaScript animations for engaging interactions
- **Responsive Design** - Works beautifully on all devices
- **Accessibility First** - WCAG compliant with keyboard navigation and screen reader support
- **Performance Optimized** - Fast loading with lazy loading images

## 📁 File Structure

```
portfolio/
├── index.html              # Homepage
├── about.html              # About page
├── work.html               # Work landing page
├── contact.html            # Contact page with form
├── work-open-library.html  # Open Library case study (TO CREATE)
├── work-harmonic-thinking.html # Harmonic Thinking case study (TO CREATE)
├── css/
│   ├── style.css          # Main stylesheet
│   └── pages.css          # Additional styles for inner pages
├── js/
│   └── main.js            # JavaScript for interactions
├── images/                 # Add your images here
│   ├── open-library-preview.jpg
│   ├── harmonic-thinking-preview.jpg
│   └── (other project images)
└── assets/
    └── resume.pdf         # Your resume PDF
```

## 🚀 Getting Started

### 1. Add Your Content

**Images:**
- Place project preview images in the `/images` folder
- Recommended size: 1200x800px for project cards
- Use JPG for photos, PNG for graphics with transparency

**Resume:**
- Add your resume PDF to the `/assets` folder
- Name it `resume.pdf` or update the links in the HTML files

**Links:**
- Update LinkedIn URL: Search for `linkedin.com/in/your-profile` and replace with your actual LinkedIn
- Update email: Replace `your.email@example.com` with your actual email address

### 2. Customize Colors (Optional)

Open `css/style.css` and modify the CSS variables at the top:

```css
:root {
    --color-orange: #FF7843;     /* Primary color */
    --color-purple: #701C68;     /* Secondary color */
    --color-burgundy: #8B2D35;   /* Accent color */
}
```

### 3. Create Case Study Pages

You still need to create two case study pages:
- `work-open-library.html` - Use the content from your outline document
- `work-harmonic-thinking.html` - Use the Harmonic Thinking content

Copy the structure from `about.html` or `work.html` as a template.

### 4. Update Meta Information

In each HTML file, update:
- `<title>` tags with your preferred page titles
- Meta descriptions for better SEO
- Open Graph tags (if you want better social media sharing)

## 🖥️ Local Development

### Option 1: Simple Local Server (Recommended)

If you have Python installed:

```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

If you have Node.js installed:

```bash
# Install live-server globally
npm install -g live-server

# Run in your portfolio directory
live-server
```

### Option 2: VS Code Live Server

1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Direct File Opening

You can open `index.html` directly in your browser, but some features (like fonts) may not work correctly without a local server.

## 📤 Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. Create a new repository on GitHub
2. Upload all files
3. Go to Settings → Pages
4. Select your main branch
5. Your site will be live at `https://yourusername.github.io/portfolio`

### Option 2: Netlify (Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your portfolio folder
3. Get instant deployment with custom domain support

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Automatic deployments on every commit

## ✅ Checklist Before Launch

- [ ] Add all project images
- [ ] Upload resume PDF
- [ ] Update email address
- [ ] Update LinkedIn URL
- [ ] Create case study pages (work-open-library.html, work-harmonic-thinking.html)
- [ ] Test all links
- [ ] Test on mobile devices
- [ ] Test with keyboard navigation
- [ ] Test with screen reader (optional but recommended)
- [ ] Check all images have alt text
- [ ] Run through a spell-checker

## 🎯 Features Included

### Navigation
- Fixed navigation that hides on scroll down, shows on scroll up
- Mobile-responsive hamburger menu
- Smooth scroll to anchor links
- Active page indicators

### Animations
- Fade-in animations on page load
- Staggered animations for project cards
- Hover effects on cards and buttons
- Floating shapes in hero section
- Smooth transitions throughout

### Forms
- Contact form with validation
- Success/error messages
- Accessible form fields with proper labels

### Accessibility
- Skip to main content link
- Proper heading hierarchy
- Alt text for images (add your own)
- Keyboard navigation support
- Focus indicators
- ARIA labels where appropriate
- Reduced motion support

## 🔧 Customization Tips

### Adding More Projects

Copy one of the existing project card structures in `work.html`:

```html
<article class="project-card">
    <a href="your-project.html" class="project-card-link">
        <div class="project-card-image">
            <img src="images/your-image.jpg" alt="Project description">
            <div class="project-card-overlay"></div>
        </div>
        <div class="project-card-content">
            <div class="project-card-tag">Your Tags</div>
            <h3 class="project-card-title">Project Title</h3>
            <p class="project-card-description">
                Brief description
            </p>
            <span class="project-card-cta">View Project →</span>
        </div>
    </a>
</article>
```

### Changing Fonts

The site uses Google Fonts (Crimson Pro + DM Sans). To change:

1. Go to [Google Fonts](https://fonts.google.com)
2. Select your fonts
3. Update the `<link>` tag in the `<head>` of each HTML file
4. Update the CSS variables in `style.css`:

```css
:root {
    --font-display: 'Your Display Font', serif;
    --font-body: 'Your Body Font', sans-serif;
}
```

## 📱 Browser Support

- Chrome/Edge (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- iOS Safari (last 2 versions)
- Chrome Mobile (last 2 versions)

## 🆘 Common Issues

**Problem:** Fonts not loading
**Solution:** Make sure you're running a local server, not opening files directly

**Problem:** Images not showing
**Solution:** Check that image paths are correct and files exist in `/images` folder

**Problem:** Mobile menu not working
**Solution:** Check that JavaScript file is loading correctly (check browser console)

## 📞 Need Help?

If you run into issues:
1. Check the browser console for errors (F12 → Console tab)
2. Verify all file paths are correct
3. Make sure all files are in the correct folders

## 🎉 You're All Set!

Your portfolio is ready to showcase your amazing work. Good luck with your UX career!

---

Built with intention by Meri McGinnis
