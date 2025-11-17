# AI Hackathon Portfolio - Yogita & Kriti

A modern, professional portfolio website showcasing AI projects built at hackathons by Yogita Senthil and Kriti Shukla.

## 🚀 Features

- **Hero Section with Background Image**: Team photo as hero background with beautiful gradient overlay
- **Professional Introduction**: Compelling story about our AI journey
- **Animated Elements**: Smooth fade-in animations and hover effects
- **Project Showcase**: AI-powered projects with detailed descriptions
- **Tech Stack Display**: Visual representation of tools and frameworks we use
- **Responsive Design**: Fully responsive on all devices
- **Stats Section**: Highlight hackathon attendance and projects built
- **LinkedIn Integration**: Direct links to both team members' profiles

## 🎨 Design Highlights

- Clean, modern design with gradient accents (purple/blue theme)
- Professional color scheme optimized for AI/tech portfolios
- Card-based layouts with hover effects
- Smooth animations and transitions
- Mobile-first responsive design
- Font Awesome icons throughout

## 📂 Structure

```
hackathonportfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with animations
├── script.js           # JavaScript for interactivity
├── team-photo.png      # Team photo (used as hero background)
└── README.md           # This file
```

## 🎯 Sections

### 1. Navigation
- Fixed navbar with smooth scrolling
- Mobile-responsive hamburger menu
- Active link highlighting

### 2. Hero Section
- Team photo as background with gradient overlay
- Professional tagline: "Building the Future with Artificial Intelligence"
- Mini stats badges (projects, hackathons, full-stack AI)
- Call-to-action buttons

### 3. About/Meet the Team
- Three story cards:
  - Our Journey
  - What We Do
  - Our Philosophy
- Tech Arsenal section showcasing tools:
  - OpenAI GPT-4
  - Voice AI (Vapi)
  - React & TypeScript
  - Python & Flask
  - LlamaIndex
  - Cloud Deployment

### 4. Stats Section
- 10+ AI Projects Built
- 5+ Hackathons Attended
- 100% Passion Driven
- ∞ Continuous Learning

### 5. Projects Section
Current projects featured:
1. **educAIte** - AI-powered tutoring platform
2. **Benefit Clarity AI** - SBC document parser with chat interface
3. **Safety First Now 58** - Emergency preparedness app

### 6. Contact Section
- LinkedIn profile links for both team members
- Professional contact layout

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations, gradients, and flexbox/grid
- **JavaScript** - Smooth scrolling, mobile menu, animations
- **Font Awesome 6.0** - Icons
- **Google Fonts** - Inter font family

## 🎨 Color Palette

- Primary Purple: `#667eea`
- Secondary Purple: `#764ba2`
- Accent Yellow: `#fbbf24`
- Dark Gray: `#1f2937`
- Light Background: `#f9fafb`

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. To deploy:
   - **GitHub Pages**: Enable in repository settings
   - **Netlify**: Drag and drop the folder
   - **Vercel**: Connect your repository

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Tablet: 768px
- Mobile: < 480px

## ✨ Key Features Implementation

### Hero Background
The hero section uses the team photo as a background with a gradient overlay for readability:
```css
.hero-bg-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.hero-overlay {
    background: linear-gradient(135deg, rgba(102, 126, 234, 0.92) 0%, rgba(118, 75, 162, 0.92) 100%);
}
```

### Animations
Smooth fade-in animations for hero elements:
```css
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

## 🤝 Contributing

This portfolio represents our hackathon journey. To update:
1. Add new projects to the projects section
2. Update stats as we attend more hackathons
3. Keep the tech stack current with new tools we learn

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 👥 Team

- **Yogita Senthil** - [LinkedIn](https://www.linkedin.com/in/yogita-senthil-8a9227226/) | [GitHub](https://github.com/yogitas1)
- **Kriti Shukla** - [LinkedIn](https://www.linkedin.com/in/kriti-shukla-258396182/)

---

Built with 💜 and lots of ☕ by Yogita & Kriti
