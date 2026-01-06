# Mohammad Yusuf Khan - Portfolio Website

A modern, interactive portfolio website showcasing DevOps engineering expertise and experience.

## 🚀 Features

- **Modern Design**: Dark theme with vibrant cyan/blue gradients and glassmorphism effects
- **Fully Responsive**: Optimized for all devices from mobile to desktop
- **Smooth Animations**: Scroll-triggered animations, typing effects, and parallax scrolling
- **Interactive Elements**: Hover effects, dynamic navigation, and smooth scrolling
- **SEO Optimized**: Semantic HTML with proper meta tags and Open Graph support
- **Fast Loading**: Pure HTML/CSS/JS with no dependencies or build process

## 📁 Project Structure

```
Myportfolio/
├── index.html          # Main HTML file
├── style.css           # Comprehensive styling
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🌐 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `Myportfolio` (or any name you prefer)
3. Keep it public for GitHub Pages to work on free tier

### Step 2: Push Your Code

```bash
# Navigate to your project directory
cd /home/mohdyousuf/Downloads/Yusuf_personal/Myportfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/Myportfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait a few minutes for deployment
7. Your site will be available at: `https://YOUR_USERNAME.github.io/Myportfolio/`

## 💻 Local Development

To test the website locally:

```bash
# Navigate to project directory
cd /home/mohdyousuf/Downloads/Yusuf_personal/Myportfolio

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or using Python 2
python -m SimpleHTTPServer 8000

# Or using Node.js (if installed)
npx http-server -p 8000
```

Then open your browser and visit: `http://localhost:8000`

## 🎨 Customization

### Updating Content

- **Personal Information**: Edit the content in `index.html`
- **Colors**: Modify CSS variables in `style.css` (`:root` section)
- **Animations**: Adjust timing and effects in `script.js`

### Color Scheme

The current color palette uses:
- Primary Accent: `#00d4ff` (Cyan)
- Secondary Accent: `#0099ff` (Blue)
- Purple Accent: `#a855f7`
- Pink Accent: `#ec4899`

To change colors, update the CSS variables in `style.css`:

```css
:root {
  --accent-primary: #YOUR_COLOR;
  --accent-secondary: #YOUR_COLOR;
  /* ... other variables */
}
```

### Adding New Sections

1. Add HTML section in `index.html`
2. Add navigation link in the navbar
3. Style the section in `style.css`
4. The scroll animations will work automatically

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 481px - 768px
- Mobile: < 480px

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties, flexbox, and grid
- **Vanilla JavaScript**: No frameworks or libraries
- **Google Fonts**: Inter font family

## 📄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is open source and available for personal use.

## 👤 Contact

- **Email**: yusuf148khan@gmail.com
- **Phone**: +91 8003455176
- **LinkedIn**: [linkedin.com/in/yusuf-](http://linkedin.com/in/yusuf-khan-a11666209)
- **Location**: Kuchaman, Rajasthan, India

---

Built with ❤️ and passion for DevOps excellence
