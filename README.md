# Wendler Zacariotto - Portfolio Website

A modern, responsive portfolio website showcasing my professional experience as a Senior Software Development Engineer at Amazon.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: Built with accessibility best practices
- **Interactive**: Smooth scrolling, mobile navigation, and scroll animations

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📁 Project Structure

```
wendler-portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository to your local machine
2. **Open** `index.html` in your web browser
3. **That's it!** The website will load and be fully functional

### Making Changes

1. **Edit content** in `index.html` to update your information
2. **Modify styles** in `styles.css` to change the appearance
3. **Add functionality** in `script.js` for interactive features

## 🌐 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `wendler-portfolio` or `your-username.github.io`)
4. Make sure it's set to **Public**
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file" on your new repository page
2. Drag and drop all files (`index.html`, `styles.css`, `script.js`, `README.md`)
3. Add a commit message like "Initial portfolio website"
4. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
# Navigate to your project folder
cd /Users/zwendler/wendler-portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio website"

# Add your GitHub repository as origin
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git

# Push to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on the **Settings** tab
3. Scroll down to the **Pages** section in the left sidebar
4. Under "Source", select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Website

Your website will be available at:
- If repository name is `your-username.github.io`: `https://your-username.github.io`
- If repository name is something else: `https://your-username.github.io/repository-name`

**Note**: It may take a few minutes for your site to be available after enabling GitHub Pages.

## 🎨 Customization Guide

### Updating Personal Information

1. **Contact Information**: Update email, LinkedIn, and GitHub links in the contact section
2. **Professional Title**: Change the hero subtitle to match your current role
3. **About Section**: Modify the about text to reflect your background
4. **Experience**: Update the timeline with your work history
5. **Skills**: Add or remove skills in the skills section
6. **Publications**: Update with your research papers and awards

### Changing Colors

The website uses a blue color scheme. To change the primary color:

1. Open `styles.css`
2. Find all instances of `#2563eb` (primary blue)
3. Replace with your preferred color (e.g., `#059669` for green)
4. Update the gradient colors in the hero and contact sections

### Adding a Profile Photo

1. Add your photo file to the project folder (e.g., `profile.jpg`)
2. In `index.html`, replace the `.profile-placeholder` div with:
```html
<div class="hero-image">
    <img src="profile.jpg" alt="Wendler Zacariotto" class="profile-photo">
</div>
```
3. Add CSS for the profile photo in `styles.css`:
```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid rgba(255, 255, 255, 0.2);
}
```

### Adding New Sections

To add a new section (e.g., "Projects"):

1. Add navigation link in the navbar
2. Create the section HTML structure
3. Add corresponding CSS styles
4. Update the JavaScript scroll detection

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile-friendly navigation with hamburger menu
- Responsive grid layouts
- Optimized typography for different screen sizes
- Touch-friendly buttons and links

## 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance Tips

- Images are optimized for web
- CSS and JavaScript are minified for production
- Uses system fonts as fallbacks
- Minimal external dependencies

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 📞 Support

If you have questions about setting up or customizing this portfolio, feel free to reach out:
- Email: wenzaca@gmail.com
- LinkedIn: [linkedin.com/in/wenzaca](https://www.linkedin.com/in/wenzaca)
- GitHub: [github.com/wenzaca](https://github.com/wenzaca)

---

**Happy coding!** 🚀
