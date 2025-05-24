# Mihir Gaikwad - Full Stack Developer Portfolio

A modern, responsive portfolio website showcasing skills, achievements, and contact information for Mihir Gaikwad, a Full Stack Developer.

## 🌟 Features

### Core Features
- **Responsive Design**: Fully responsive layout that works on all devices
- **Dark/Light Mode Toggle**: User-preferred theme switching with localStorage persistence
- **Smooth Animations**: Elegant hover effects and transitions throughout
- **Mobile-First Approach**: Optimized for mobile devices with hamburger menu
- **Loading Spinner**: Professional loading experience
- **Scroll-to-Top Button**: Enhanced user navigation
- **Contact Form**: Functional contact form with Formspree integration

### Sections
- **Hero Section**: Introduction with profile picture and social links
- **About Section**: Personal information with embedded video
- **Achievements Section**: Dynamic achievement cards loaded from JSON data
- **Quote of the Day**: Random inspirational quotes from API
- **Contact Section**: Contact form, information, and embedded Google Maps
- **Footer**: Professional footer with social links and copyright

### Technical Features
- **SEO Optimized**: Meta tags, Open Graph tags, and semantic HTML
- **Performance Optimized**: Fast loading times and smooth interactions
- **Accessibility**: Proper contrast ratios and semantic markup
- **Modern JavaScript**: ES6+ features and clean code structure
- **External API Integration**: Quote API for dynamic content

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with custom properties and animations
- **JavaScript (ES6+)**: Interactive functionality and API integration
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Font Awesome**: Icon library for visual elements
- **Formspree**: Contact form backend service
- **Quotable API**: Random quote generation

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── README.md              # Project documentation
├── favicon.ico            # Website favicon
└── assets/
    ├── images/
    │   └── profile.jpg    # Profile picture
    └── data/
        └── achievements.json # Achievement data (embedded in HTML)
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Internet connection for CDN resources and APIs

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mihirgaikwad/portfolio.git
   cd portfolio
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. **Access the website**
   - Direct file: `file:///path/to/index.html`
   - Local server: `http://localhost:8000`

## ⚙️ Configuration

### Contact Form Setup
The contact form uses Formspree for backend processing. To set up your own:

1. Visit [Formspree.io](https://formspree.io)
2. Create an account and get your form endpoint
3. Replace the form action URL in the HTML:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

### Customizing Content

#### Personal Information
Update the following sections in `index.html`:
- Hero section text and links
- About section content
- Contact information
- Social media links
- Profile picture URL

#### Achievements
Modify the `achievementsData` array in the JavaScript section:
```javascript
const achievementsData = [
    {
        "title": "Your Achievement",
        "year": 2024,
        "description": "Description of your achievement",
        "icon": "fas fa-trophy"
    }
    // Add more achievements...
];
```

#### Google Maps
Replace the Google Maps embed URL with your location:
```html
<iframe src="YOUR_GOOGLE_MAPS_EMBED_URL"></iframe>
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎨 Theme Customization

The website supports both dark and light themes:

### Dark Theme (Default)
- Background: Gray-900 (#111827)
- Text: White
- Accent: Blue-400 (#60A5FA)

### Light Theme
- Background: Gray-100 (#F3F4F6)
- Text: Gray-900 (#111827)
- Accent: Blue-600 (#2563EB)

### Adding Custom Themes
Modify the theme toggle functionality in the JavaScript section to add more theme options.

## 🔧 Browser Support

- **Chrome**: 88+
- **Firefox**: 85+
- **Safari**: 14+
- **Edge**: 88+

## 📊 Performance Features

- **Lazy Loading**: Images load as needed
- **Optimized Assets**: Compressed images and minified code
- **CDN Resources**: Fast loading of external libraries
- **Smooth Animations**: Hardware-accelerated CSS transitions

## 🔒 Security Features

- **Content Security**: No inline scripts execution
- **External Links**: `rel="noopener noreferrer"` for security
- **Form Validation**: Client-side and server-side validation

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: `# No build needed`
3. Set publish directory: `/` (root)
4. Deploy automatically on git push

### Vercel
1. Import your GitHub repository to Vercel
2. Configure as a static site
3. Deploy with automatic deployments enabled

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Mihir Gaikwad**
- Email: mihirgaikwad04@gmail.com
- Phone: +91 7875400163
- LinkedIn: [mihir-gaikwad-4b5b2a1b9](https://www.linkedin.com/in/mihir-gaikwad-4b5b2a1b9/)
- GitHub: [mihirgaikwad](https://github.com/mihirgaikwad)
- Twitter: [@mihir_fr13](https://twitter.com/mihir_fr13)
- Instagram: [@mihir_fr13](https://www.instagram.com/mihir_fr13)

## 🙏 Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) for the beautiful icons
- [Formspree](https://formspree.io/) for contact form backend
- [Quotable API](https://quotable.io/) for inspirational quotes
- [Google Maps](https://maps.google.com/) for location embedding

## 📈 Future Enhancements

- [ ] Blog section with markdown support
- [ ] Project portfolio with live demos
- [ ] Testimonials section
- [ ] Skills progress bars with animations
- [ ] Multi-language support
- [ ] Analytics integration
- [ ] Progressive Web App (PWA) features
- [ ] Advanced animations with GSAP

---

⭐ **Star this repository if you find it helpful!**
