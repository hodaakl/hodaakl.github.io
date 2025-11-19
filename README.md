# My GitHub Pages Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects and skills.

## Features

- 🎨 Modern and clean design with gradient effects
- 📱 Fully responsive (mobile, tablet, desktop)
- ✨ Smooth animations and transitions
- 🎯 Interactive navigation with active states
- 🚀 Fast loading and optimized performance
- 💫 Animated hero section with floating elements

## Sections

- **Home**: Hero section with call-to-action
- **About**: Personal introduction and skills showcase
- **Projects**: Portfolio of your work
- **Contact**: Social links and contact information

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `my-portfolio` or `yourusername.github.io`)
   - If you name it `yourusername.github.io` (replace with your actual username), it will be accessible at `https://yourusername.github.io`
   - Otherwise, it will be at `https://yourusername.github.io/repository-name`
4. Keep it public
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 2: Initialize Git and Push Your Code

Open your terminal in this folder and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your files
git commit -m "Initial commit: Add portfolio website"

# Add your GitHub repository as remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Scroll down and click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and folder `/ (root)`
6. Click "Save"
7. Wait a few minutes, then refresh the page
8. You'll see a message: "Your site is live at https://yourusername.github.io/repo-name/"

### Step 4: Customize Your Website

Edit the following files to personalize your website:

#### `index.html`
- Update the title, hero text, and about section
- Add your real projects (replace the placeholder projects)
- Update social media links (GitHub, LinkedIn, Email)

#### `styles.css`
- Change colors in the `:root` section at the top
- Modify fonts, spacing, or any design elements

#### `script.js`
- Add additional interactive features if desired

### Making Updates

After making changes to your website:

```bash
git add .
git commit -m "Update: describe your changes"
git push
```

Your changes will appear on your live site within a few minutes.

## Local Development

To view your website locally:

1. Simply open `index.html` in your web browser, or
2. Use a local server (recommended for better development experience):

```bash
# If you have Python installed
python -m http.server 8000

# Or if you have Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization Tips

### Change Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;     /* Main brand color */
    --primary-dark: #4f46e5;      /* Darker shade */
    --secondary-color: #ec4899;   /* Accent color */
}
```

### Add More Projects
In `index.html`, duplicate a project card and modify:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">🎯</div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tags">
            <span>Tech1</span>
            <span>Tech2</span>
        </div>
        <a href="#" class="project-link">View Project →</a>
    </div>
</div>
```

### Update Skills
Modify the skills section in `index.html`:

```html
<div class="skills">
    <span class="skill-tag">Your Skill</span>
    <span class="skill-tag">Another Skill</span>
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript (ES6+)
- No frameworks or libraries required!

## License

Feel free to use this template for your personal or commercial projects. Attribution is appreciated but not required.

## Support

If you encounter any issues:
1. Make sure all files (`index.html`, `styles.css`, `script.js`) are in the same folder
2. Check that your repository is public
3. Verify GitHub Pages is enabled in repository settings
4. Wait a few minutes after pushing changes for them to appear

---

Built with ❤️ using GitHub Pages

