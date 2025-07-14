# Ziyu Jin - Professional Portfolio

A modern, responsive personal portfolio website showcasing my experience as an Assistant Quality Assurance Engineer and my journey in Robotics Systems.

## 🌟 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Navigation** - Smooth scrolling between sections
- **Timeline Layout** - Professional work experience presentation
- **Skills Grid** - Organized technical skills showcase
- **Contact Integration** - Easy-to-find contact information

## 🚀 Quick Start

1. **Download the HTML file**
2. **Open in browser** - Simply double-click the `portfolio.html` file
3. **Deploy online** - Upload to any web hosting service

## 📁 Project Structure

```
portfolio/
├── portfolio.html          # Main HTML file with embedded CSS and JavaScript
├── README.md              # This file
└── assets/                # (Optional) Folder for images and additional files
    └── images/
        └── profile-photo.jpg
```

## 🎨 Customization Guide

### Adding Your Photo

Replace the placeholder in the About section:

```html
<!-- Current placeholder -->
<div class="about-image">
    <span>Your Photo Here</span>
</div>

<!-- Replace with your photo -->
<div class="about-image">
    <img src="assets/images/profile-photo.jpg" alt="Ziyu Jin" 
         style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
</div>
```

### Updating Contact Information

Modify the contact section with your current details:

```html
<div class="contact-item">
    <h3>Phone</h3>
    <p>+65 9665 3059</p>
</div>
<div class="contact-item">
    <h3>Email</h3>
    <p>Jinziyu100@gmail.com</p>
</div>
```

### Adding Social Media Links

Add social media icons to the contact section:

```html
<div class="contact-item">
    <h3>LinkedIn</h3>
    <p><a href="https://linkedin.com/in/yourprofile" target="_blank">linkedin.com/in/yourprofile</a></p>
</div>
<div class="contact-item">
    <h3>GitHub</h3>
    <p><a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
</div>
```

### Color Customization

Main colors used in the design:

```css
/* Primary Colors */
--primary-blue: #3498db;
--dark-blue: #2c3e50;
--light-blue: #667eea;
--accent-red: #e74c3c;
--success-green: #27ae60;
--background-gray: #f8f9fa;
```

To change colors, find and replace these hex values in the CSS section.

## 📱 Responsive Breakpoints

The portfolio is optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Create a new repository on GitHub
2. Upload your `portfolio.html` file
3. Rename it to `index.html`
4. Go to Settings > Pages
5. Select "Deploy from a branch" and choose "main"

### Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your HTML file
3. Your site will be live instantly

### Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your project from GitHub
3. Deploy with one click

## 📋 Sections Overview

### 1. Navigation
- Fixed header with smooth scrolling
- Responsive hamburger menu (mobile)

### 2. Hero Section
- Professional introduction
- Call-to-action button

### 3. About Me
- Professional summary
- Photo placeholder
- Personal qualities

### 4. Technical Skills
- Programming languages
- Technical expertise
- Software & tools
- Languages

### 5. Work Experience
- Timeline layout
- Detailed job descriptions
- Company information

### 6. Education
- Current studies
- Completed qualifications
- Institution details

### 7. Contact
- Phone number
- Email address
- Professional invitation

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive navigation and animations
- **Responsive Design** - Mobile-first approach

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance
- Lightweight (< 50KB)
- No external dependencies
- Fast loading times
- Optimized images (when added)

## 🎯 Future Enhancements

### Planned Features
- [ ] Projects showcase section
- [ ] Blog integration
- [ ] Dark mode toggle
- [ ] Multi-language support
- [ ] Contact form functionality
- [ ] SEO optimization

### Suggested Additions
- **Projects Section**: Showcase your electronics and robotics projects
- **Certifications**: Add any relevant certifications
- **Testimonials**: Include recommendations from colleagues
- **Blog**: Share insights about quality assurance and robotics

## 📞 Support

For questions or suggestions regarding this portfolio:

- **Email**: Jinziyu100@gmail.com
- **Phone**: +65 9665 3059

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Built with focus on accessibility and user experience
- Optimized for Singapore job market standards

---

**Last Updated**: July 2024  
**Version**: 1.0.0  
**Author**: Ziyu Jin
