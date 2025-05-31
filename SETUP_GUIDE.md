# Portfolio Setup Guide

## Quick Start

Your personalized portfolio is ready! Here's how to get it live on GitHub Pages:

## 📁 Files Created

- `index.html` - Main portfolio page with your information
- `styles.css` - Modern styling and responsive design
- `script.js` - Interactive features and animations
- `assets/` - Folder for images and resume
- `assets/Harsh-S-Resume.pdf` - Your resume (already added)

## 🚀 Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com)
2. Create a new repository named `harshshri07.github.io` (use your exact GitHub username)
3. Make sure it's public

### Step 2: Upload Your Portfolio

Using Git (recommended):

```powershell
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Connect to your GitHub repository
git branch -M main
git remote add origin https://github.com/harshshri07/harshshri07.github.io.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository settings
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/" (root) folder
5. Click "Save"

Your portfolio will be live at: `https://harshshri07.github.io`

## 📸 Add Your Profile Photo

1. Add your photo to the `assets/` folder
2. Name it `profile-photo.jpg` (or update the HTML to match your filename)
3. Recommended size: 400x400 pixels, square format

## 🎨 Customization

### Update Projects

Edit the projects section in `index.html`:

```html
<div class="project-card" data-aos="fade-up">
    <div class="project-image">
        <img src="assets/your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Description of your project</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/harshshri07/your-repo" target="_blank" title="View Code">
                <i class="fab fa-github"></i>
            </a>
            <a href="your-live-demo-url" target="_blank" title="Live Demo">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
</div>
```

### Update Skills

Modify the skills section in `index.html` to match your actual skills.

### Change Colors

Update colors in `styles.css` by changing the gradient values:

```css
/* Main gradient */
background: linear-gradient(135deg, #your-color1, #your-color2);
```

## 📱 Features Included

✅ **Responsive Design** - Works on all devices
✅ **Smooth Animations** - AOS library integration
✅ **Interactive Navigation** - Smooth scrolling and active states
✅ **Contact Form** - Functional with validation
✅ **Mobile Menu** - Hamburger menu for mobile devices
✅ **Project Showcase** - Linked to your GitHub repositories
✅ **Professional Styling** - Modern and clean design
✅ **SEO Friendly** - Proper meta tags and structure

## 🛠 Technical Details

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Vanilla JS for interactions
- **Font Awesome** - Icons
- **Google Fonts** - Poppins typography
- **AOS Library** - Scroll animations

## 📞 Contact Information

Your contact information has been pre-filled based on your resume:

- **Email**: shrishrimal38@gmail.com
- **Phone**: (240) 413-6360
- **LinkedIn**: harsh-shrishrimal
- **GitHub**: harshshri07

## 🎯 Next Steps

1. **Add your profile photo** to make it personal
2. **Update project details** with your actual projects
3. **Add project screenshots** to the `assets/` folder
4. **Customize colors** to match your preferences
5. **Test on different devices** to ensure responsiveness

## 🌐 Going Live

Once deployed, your portfolio will be available at:
`https://harshshri07.github.io`

Share this link on your resume, LinkedIn, and other professional profiles!

## 📝 Adding New Projects

To add a new project:

1. Add project image to `assets/` folder
2. Copy an existing project card in `index.html`
3. Update the content with your project details
4. Update GitHub and demo links

## 🔧 Troubleshooting

- **Portfolio not loading?** Check that your repository is named correctly
- **Images not showing?** Ensure images are in the `assets/` folder
- **Styling looks broken?** Clear browser cache and refresh

Need help? Feel free to reach out!

---

**Happy coding!** 🚀 