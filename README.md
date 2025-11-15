# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **About Section**: Showcase your skills, experience, and personality
- **Projects Section**: Display your work with titles, descriptions, and GitHub links
- **Contact Form**: Allow visitors to get in touch with you
- **Smooth Scrolling**: Enhanced user experience with smooth navigation
- **Mobile Navigation**: Hamburger menu for mobile devices

## Sections

### 1. Hero Section
- Eye-catching introduction with your name and title
- Call-to-action buttons
- Professional profile placeholder

### 2. About Section
- Personal introduction
- Skills showcase with icons
- Statistics/achievements display

### 3. Projects Section
- Project cards with:
  - Project title
  - Description
  - Technology tags
  - GitHub links
  - Live demo links (optional)

### 4. Contact Section
- Contact information
- Contact form
- Social media links

## Customization

### Personal Information
1. **Update your name**: Replace "Your Name" in the hero section
2. **Add your title**: Update "Full Stack Developer & Creative Problem Solver"
3. **Write your bio**: Customize the about section content
4. **Update contact info**: Add your real email, LinkedIn, and GitHub links

### Projects
To add your own projects, edit the projects section in `index.html`:

```html
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Your Project Title</h3>
        <p class="project-description">Your project description here...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <a href="https://github.com/yourusername/your-repo" target="_blank" class="project-github">
            <i class="fab fa-github"></i> View on GitHub
        </a>
    </div>
</div>
```

### Colors and Styling
The main colors used in the design:
- Primary Blue: `#2563eb`
- Secondary Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Gray: `#f9fafb`

You can customize these colors in the `styles.css` file.

### Adding Your Photo
Replace the profile placeholder in the hero section:
1. Add your photo to the portfolio folder
2. Replace the placeholder div with an img tag:
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. Open `index.html` in your web browser
2. Customize the content with your information
3. Add your own projects
4. Deploy to your preferred hosting platform

## Deployment Options

- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Easy deployment with continuous integration
- **Vercel**: Fast deployment with automatic HTTPS
- **Traditional Web Hosting**: Upload files via FTP

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Tips for Success

1. **Keep it updated**: Regularly add new projects and update your skills
2. **Use real projects**: Showcase actual work you've completed
3. **Write clear descriptions**: Explain what each project does and your role
4. **Include live demos**: When possible, provide links to working applications
5. **Optimize for SEO**: Add meta descriptions and proper heading structure
6. **Test on mobile**: Ensure your site works well on all devices

## License

This project is open source and available under the [MIT License](LICENSE).
