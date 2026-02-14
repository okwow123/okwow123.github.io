# AI/ML Engineer Portfolio - GitHub Pages

A modern, responsive portfolio website designed for AI/ML engineers and researchers. Built with pure HTML, CSS, and JavaScript for easy deployment on GitHub Pages.

## ✨ Features

- **Modern Dark Theme Design**: Professional dark mode UI with gradient accents
- **Responsive Layout**: Fully responsive design that works on all devices
- **GitHub Contribution Graph**: Display your coding activity directly on the main page
- **6 Blog Categories**: Organized content sections for different topics
  - 💻 Development
  - 🧠 Machine Learning
  - ☕ Java
  - 📄 Research Papers
  - 🐍 Python
  - 🤖 Artificial Intelligence
- **AI/ML Career Highlights**: Showcase your expertise and achievements
- **Smooth Animations**: Engaging scroll animations and hover effects
- **SEO Friendly**: Optimized for search engines

## 🚀 Quick Start

### 1. Set Up GitHub Repository

```bash
# Clone or fork this repository
git clone https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
cd YOUR_USERNAME.github.io

# Or create a new repository named: YOUR_USERNAME.github.io
```

### 2. Customize Your Portfolio

#### Update Personal Information

Edit `index.html`:

- **Line 22**: Change "Your Name" to your actual name
- **Line 23**: Update your job title/subtitle
- **Lines 24-28**: Write your personal introduction
- **Lines 39-47**: Update your stats (Years Experience, Projects, Papers)
- **Lines 58-69**: Add your skills/technologies
- **Line 78**: Replace `YOUR_GITHUB_USERNAME` with your GitHub username for contribution graph
- **Lines 235-248**: Update social media links (GitHub, LinkedIn, Email)

#### GitHub Contribution Graph

Replace `YOUR_GITHUB_USERNAME` in `index.html` (line 78) with your actual GitHub username:

```html
<img src="https://ghchart.rshah.org/YOUR_GITHUB_USERNAME"
     alt="GitHub Contribution Graph">
```

Example:
```html
<img src="https://ghchart.rshah.org/octocat"
     alt="GitHub Contribution Graph">
```

#### Customize Career Highlights

Edit the AI/ML Career Highlights section in `index.html` (lines 90-198) to reflect your:
- Projects and achievements
- Publications and research
- Education and certifications
- Industry experience
- Awards and recognition

### 3. Add Your Profile Image (Optional)

Replace the emoji placeholder in `index.html` (line 38) with your profile image:

```html
<!-- Before -->
<div class="profile-img-placeholder">👨‍💻</div>

<!-- After -->
<img src="assets/images/profile.jpg" alt="Your Name"
     style="width: 100%; border-radius: 15px;">
```

Then add your image to `assets/images/profile.jpg`

### 4. Deploy to GitHub Pages

```bash
# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio setup"

# Push to GitHub
git push origin main
```

Enable GitHub Pages:
1. Go to your repository settings
2. Navigate to "Pages" section
3. Select "main" branch as source
4. Click "Save"

Your site will be available at: `https://YOUR_USERNAME.github.io`

## 📝 Adding Blog Posts

To add blog posts to categories, edit the respective HTML files in the `categories/` directory:

1. Open the category file (e.g., `categories/machine-learning.html`)
2. Replace the "No Posts Yet" section with your blog post list
3. Example structure:

```html
<div class="highlights-grid">
    <div class="highlight-card">
        <h3><a href="posts/your-post.html">Your Post Title</a></h3>
        <p class="post-date">February 14, 2026</p>
        <p>Brief description of your post...</p>
        <a href="posts/your-post.html" class="btn btn-primary">Read More</a>
    </div>
</div>
```

## 🎨 Customization

### Color Scheme

Edit `css/style.css` to change colors. Main color variables are at the top:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #3b82f6;
    /* ... more colors ... */
}
```

### Fonts

Change the font family in `css/style.css`:

```css
body {
    font-family: 'Your-Font-Name', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto;
}
```

### Layout

Modify grid layouts, spacing, and component styles in `css/style.css`

## 📁 Project Structure

```
.
├── index.html              # Main homepage
├── css/
│   └── style.css          # All styles
├── js/
│   └── main.js            # JavaScript interactions
├── categories/            # Category pages
│   ├── development.html
│   ├── machine-learning.html
│   ├── java.html
│   ├── papers.html
│   ├── python.html
│   └── ai.html
├── assets/
│   └── images/            # Your images
└── README.md             # This file
```

## 🔧 Advanced Customization

### Adding a Blog Post Page Template

Create a new file `posts/sample-post.html`:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Post Title - AI/ML Portfolio</title>
    <link rel="stylesheet" href="../css/style.css">
</head>
<body>
    <!-- Navigation (copy from index.html) -->

    <article class="section">
        <h1>Your Post Title</h1>
        <p class="post-date">February 14, 2026</p>

        <!-- Your content here -->

    </article>

    <!-- Footer (copy from index.html) -->
</body>
</html>
```

### Adding Analytics

Add Google Analytics or other tracking to `index.html` before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🌟 Tips for AI/ML Portfolio

1. **Showcase Projects**: Add links to your GitHub repositories in the career highlights
2. **Include Metrics**: Quantify your achievements (accuracy, performance improvements, etc.)
3. **Research Papers**: Link to your publications on arXiv, Google Scholar, or conference sites
4. **Kaggle Profile**: Add your Kaggle profile link if you participate in competitions
5. **Code Samples**: Include Jupyter notebooks or code snippets in blog posts
6. **Visualizations**: Add charts, graphs, and model architecture diagrams

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

Feel free to use this template for your personal portfolio. No attribution required.

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request.

## 📧 Support

For questions or issues, please open an issue on GitHub.

---

**Built with ❤️ for AI/ML Engineers**
