# Modern Portfolio Website

A premium, responsive personal portfolio website for a Final Year Computer Science and Engineering student. Built with pure HTML, CSS, and JavaScript - no frameworks required.

## 🌟 Features

### Design & UI
- **Modern Glassmorphism UI** - Beautiful frosted glass effects
- **Dark/Light Theme Toggle** - Switch between dark and light modes
- **Theme Color Switcher** - Customize accent colors (Blue, Purple, Pink, Green)
- **Custom Cursor** - Interactive cursor effect (desktop only)
- **Animated Background Particles** - Floating particle animation
- **Smooth Animations** - Scroll-triggered fade-in animations
- **Professional Typography** - Google Fonts (Poppins & Fira Code)
- **Mobile-First Responsive** - Fully responsive across all devices

### Sections
1. **Hero Section** - Full-screen intro with typing animation
2. **About Me** - Personal introduction and career objective
3. **Skills** - Programming languages, web development, databases, and tools
4. **Education** - Academic timeline with Anna University details
5. **Projects** - Filterable project gallery with tech stacks
6. **Certifications** - IBM, Google, AWS, and internship certificates
7. **Experience** - Internship and work experience timeline
8. **Achievements** - Awards and recognition
9. **Resume** - Resume preview and download section
10. **Contact** - Contact form and social links
11. **Footer** - Social icons and back-to-top button

### Interactive Features
- **Typing Animation** - Dynamic text typing effect in hero section
- **Scroll Progress Indicator** - Shows reading progress
- **Animated Counters** - Number counting animation for stats
- **Skill Progress Bars** - Animated skill level indicators
- **Project Filtering** - Filter projects by category
- **Smooth Scrolling** - Smooth scroll navigation
- **Toast Notifications** - Form submission feedback
- **Sticky Navbar** - Navigation bar with scroll effect
- **Loading Screen** - Animated loading screen

## 🚀 Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS with variables, flexbox, grid
- **JavaScript (Vanilla)** - No frameworks or libraries
- **Font Awesome** - Icon library (CDN)
- **Google Fonts** - Typography (CDN)

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
├── script.js           # All JavaScript functionality
├── assets/             # Static assets
│   └── resume.pdf      # Your resume (PDF)
├── images/             # Images
│   ├── profile.jpg     # Profile photo
│   ├── about.jpg       # About section image
│   ├── project1.jpg    # Project 1 thumbnail
│   ├── project2.jpg    # Project 2 thumbnail
│   ├── project3.jpg    # Project 3 thumbnail
│   ├── project4.jpg    # Project 4 thumbnail
│   ├── project5.jpg    # Project 5 thumbnail
│   └── project6.jpg    # Project 6 thumbnail
└── README.md           # This file
```

## 🛠️ Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download**
   ```bash
   # If using Git
   git clone <repository-url>
   cd portfolio
   ```

   Or download and extract the ZIP file.

2. **Add Your Images**
   - Place your profile photo in `images/profile.jpg`
   - Add project screenshots in `images/` folder
   - Recommended image sizes:
     - Profile: 400x400px (square)
     - Project thumbnails: 800x600px (4:3 aspect ratio)

3. **Add Your Resume**
   - Place your resume PDF in `assets/resume.pdf`
   - Ensure the filename matches exactly: `resume.pdf`

4. **Customize Content**
   Open `index.html` and update the following:
   - **Personal Information**: Name, email, phone, location
   - **Social Links**: GitHub, LinkedIn, Twitter, Instagram URLs
   - **About Section**: Your introduction and career objective
   - **Skills**: Update skill names and progress percentages
   - **Education**: Update your academic details
   - **Projects**: Replace with your actual projects
   - **Certifications**: Add your certifications
   - **Experience**: Update your work experience
   - **Achievements**: Add your awards and recognition
   - **Contact Form**: Update form action if using a backend

5. **Customize Colors (Optional)**
   - Open `style.css` and modify CSS variables in `:root`
   - Default colors are blue and purple gradients
   - You can also use the built-in color switcher

6. **Launch the Website**
   ```bash
   # Option 1: Simply open index.html in your browser
   # Option 2: Use a local server (recommended)
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using VS Code Live Server extension
   # Right-click index.html and select "Open with Live Server"
   ```

7. **Open in Browser**
   - Navigate to `http://localhost:8000` (or your chosen port)
   - Or simply double-click `index.html` to open directly

## 🎨 Customization Guide

### Changing Theme Colors
Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #6366f1;    /* Main accent color */
    --secondary-color: #8b5cf6;  /* Secondary accent color */
    --bg-dark: #0f172a;          /* Dark background */
    --bg-light: #f8fafc;         /* Light background */
}
```

### Modifying Typing Animation
Edit the `texts` array in `script.js`:
```javascript
const texts = [
    'Final Year CSE Student',
    'Full Stack Developer',
    'Software Engineer',
    'Your Custom Text Here'
];
```

### Adding/Removing Projects
1. Copy a project card in `index.html`
2. Update the content with your project details
3. Add project thumbnail to `images/` folder
4. Update the `data-category` attribute for filtering

### Updating Skills
1. Find the skill categories in `index.html`
2. Update skill names and progress percentages
3. Add or remove skill cards as needed

### Contact Form Integration
Currently, the form simulates submission. To make it functional:
1. Add a backend service (Formspree, Netlify Forms, etc.)
2. Update the form action in `index.html`:
   ```html
   <form action="https://formspree.io/f/your-form-id" method="POST">
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## ⚡ Performance Optimization

- Lazy loading images enabled
- CSS animations use GPU acceleration
- Minimal external dependencies (only CDNs for fonts and icons)
- Optimized CSS with variables for easy theming
- Efficient JavaScript with event delegation

## 🔒 Accessibility Features

- Semantic HTML5 elements
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus states for all interactive elements
- Alt text for images
- Color contrast compliance

## 📝 SEO Optimization

- Meta description and keywords
- Open Graph tags for social sharing
- Semantic heading structure
- Proper alt text for images
- Clean URL structure

## 🎓 Target Companies

This portfolio is designed to impress recruiters at:
- Zoho
- Amazon
- TCS
- Infosys
- Accenture
- Wipro
- HCL
- Cognizant
- And other product-based companies

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you find any bugs or have suggestions for improvements, please open an issue.

## 📄 License

This project is open source and available for personal and commercial use.

## 👤 Author

**Your Name**
- Final Year CSE Student
- Anna University
- [LinkedIn](https://linkedin.com/in/yourusername)
- [GitHub](https://github.com/yourusername)
- [Email](mailto:your.email@example.com)

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Glassmorphism design inspiration
- Open source community

## 📞 Support

If you need help with customization or have questions:
1. Check the code comments in HTML, CSS, and JS files
2. Review this README file
3. Reach out via the contact form in the portfolio

## 🔄 Updates

### Version 1.0.0 (Current)
- Initial release
- All core features implemented
- Fully responsive design
- Dark/Light theme support
- Project filtering
- Contact form with validation

---

**Built with ❤️ using HTML, CSS, and JavaScript**

---

## Quick Start Checklist

- [ ] Replace placeholder images with your own
- [ ] Add your resume PDF to assets folder
- [ ] Update personal information in index.html
- [ ] Customize skills and progress bars
- [ ] Add your actual projects
- [ ] Update education details
- [ ] Add your certifications
- [ ] Update work experience
- [ ] Add your achievements
- [ ] Update social media links
- [ ] Test contact form (or integrate with backend)
- [ ] Preview on different devices
- [ ] Deploy to hosting platform (GitHub Pages, Netlify, Vercel)

## Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Access at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Get instant deployment
3. Custom domain available

### Vercel
1. Install Vercel CLI or use dashboard
2. Connect your repository
3. Automatic deployment on push

### Traditional Hosting
1. Upload all files via FTP
2. Ensure `index.html` is in the root directory
3. Access via your domain

---

**Good luck with your job search! 🎉**
