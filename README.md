# Nirmal Singh - Portfolio Website

A modern, responsive single-page portfolio website for Nirmal Singh, a Data Entry Operator & Network Specialist with 2+ years of experience.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

### Currently Implemented

✅ **Modern Single-Page Design**
- Clean, professional layout with smooth scrolling navigation
- Responsive design that works on all devices (desktop, tablet, mobile)
- Dark theme with cyan/turquoise accent colors

✅ **Interactive Sections**
- **Home/Hero**: Animated floating shapes background with professional introduction
- **About Me**: Detailed profile with highlights and placeholder for personal image
- **Work Experience**: Timeline-based experience display with tags
- **Skills**: Categorized skill sets with animated progress bars
  - MS Office Suite (Excel, Word, PowerPoint, Access)
  - Network Administration (Configuration, Troubleshooting, Security)
  - Creative Design (Flyers, Pamphlets, Instagram Stories)
  - Additional Skills with tags
- **Portfolio**: Filterable project gallery with categories (Flyers, Social Media, Pamphlets)
- **Contact**: Contact form and information section

✅ **Enhanced User Experience**
- Light/Dark theme toggle with persistent storage
- Sticky navigation bar with active section highlighting
- Smooth scroll animations and transitions
- Mobile-responsive hamburger menu
- Scroll-to-top button
- Intersection Observer for scroll-triggered animations
- Typing effect on hero subtitle
- Mouse parallax effect on background shapes

✅ **Professional Elements**
- Social media integration (LinkedIn, GitHub, Instagram, Email)
- Professional color scheme and typography
- Hover effects and micro-interactions
- Accessible design with ARIA labels
- SEO-friendly semantic HTML

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file with all sections
├── css/
│   └── style.css      # Complete stylesheet with themes and animations
├── js/
│   └── main.js        # All JavaScript functionality
└── README.md          # Project documentation (this file)
```

## 🎨 Design Features

### Color Palette
- **Primary Background**: `#0a0e27` (Dark Navy)
- **Secondary Background**: `#151932` (Deep Blue)
- **Accent Color**: `#00d9ff` (Cyan)
- **Secondary Accent**: `#00a8cc` (Turquoise)
- **Text Primary**: `#ffffff` (White)
- **Text Secondary**: `#b8b9c1` (Light Gray)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### Icons
- **Font Awesome 6.4.0** for all icons

## 🚀 Getting Started

### Installation

1. **Download/Clone the project**
   ```bash
   # If using git
   git clone <repository-url>
   ```

2. **Open the website**
   - Simply open `index.html` in a web browser
   - No build process or dependencies required!

### Customization Guide

#### 1. Replace Personal Information

**In `index.html`, update:**

- **Contact Information** (Search for these sections):
  ```html
  <!-- Update email -->
  <a href="mailto:nirmal.singh@example.com">
  
  <!-- Update phone -->
  <p>+91 XXXXX XXXXX</p>
  
  <!-- Update location -->
  <p>Your City, Your State</p>
  ```

- **Social Media Links**:
  ```html
  <a href="https://www.linkedin.com" target="_blank">
  <a href="https://github.com" target="_blank">
  <a href="https://www.instagram.com" target="_blank">
  ```

#### 2. Add Your Personal Image

Replace the image placeholder in the About section:

```html
<!-- Find this code in the About section -->
<div class="about-image">
    <div class="image-placeholder">
        <i class="fas fa-user"></i>
    </div>
</div>

<!-- Replace with: -->
<div class="about-image">
    <img src="images/your-photo.jpg" alt="Nirmal Singh" style="border-radius: 50%; width: 250px; height: 250px; object-fit: cover; box-shadow: var(--shadow-accent);">
</div>
```

#### 3. Add Portfolio Images

Create an `images/` folder and add your design work:

```html
<!-- Find portfolio items and replace placeholder with: -->
<div class="portfolio-image">
    <img src="images/flyer-design-1.jpg" alt="Business Flyer">
    <div class="portfolio-overlay">
        <!-- overlay content -->
    </div>
</div>
```

#### 4. Update Work Experience

Modify the timeline section with your actual work history:

```html
<!-- Update dates, titles, companies, and descriptions -->
<div class="timeline-date">2022 - Present</div>
<h3 class="timeline-title">Your Job Title</h3>
<p class="timeline-company">Your Company Name</p>
```

#### 5. Adjust Skills

Update skill levels and add/remove skills as needed:

```html
<!-- Change the width percentage to match your skill level -->
<div class="skill-progress" style="width: 95%"></div>
```

## 🎯 Functional Entry Points

### Navigation Links (Anchor IDs)
- `#home` - Hero/Landing section
- `#about` - About Me section
- `#experience` - Work Experience timeline
- `#skills` - Skills & Expertise section
- `#portfolio` - Portfolio gallery with filters
- `#contact` - Contact form and information

### Interactive Elements

1. **Theme Toggle**: Click the sun/moon button (top-right) to switch themes
2. **Portfolio Filters**: Click filter buttons to show specific categories
3. **Contact Form**: Submit form (currently logs to console, needs backend integration)
4. **Scroll to Top**: Click arrow button (bottom-right) when scrolling down
5. **Mobile Menu**: Click hamburger icon on mobile to open navigation

## 📋 Features Not Yet Implemented

### High Priority
⏳ **Portfolio Gallery**
- Real images need to be uploaded to replace placeholders
- Consider adding a lightbox/modal for full-size image viewing

⏳ **Contact Form Backend**
- Currently logs to console only
- Needs integration with email service (EmailJS, Formspree, or backend API)

⏳ **Personal Images**
- Profile photo in About section
- Background images if desired

### Medium Priority
⏳ **Enhanced Portfolio**
- Add project descriptions and details
- Link to live projects or downloadable files
- Add project categories/tags

⏳ **Testimonials Section**
- Add client testimonials/recommendations
- Could include ratings or endorsements

⏳ **Resume/CV Download**
- Add downloadable PDF resume
- Consider adding a "Download CV" button

### Low Priority
⏳ **Blog/Articles Section** (Optional)
- Share insights about data entry, networking, or design
- Could boost SEO and demonstrate expertise

⏳ **Analytics Integration**
- Add Google Analytics or similar tracking
- Monitor visitor behavior and popular sections

⏳ **Performance Optimization**
- Image optimization and lazy loading
- Minify CSS/JS for production
- Add service worker for offline capability

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Custom properties (variables), Grid, Flexbox, animations
- **JavaScript (ES6+)**: Modern vanilla JavaScript, no frameworks
- **Font Awesome**: Icon library (v6.4.0)
- **Google Fonts**: Inter font family
- **Intersection Observer API**: For scroll animations
- **LocalStorage API**: Theme preference persistence

## 📱 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Recommended Next Steps

1. **Content Updates**
   - Replace all placeholder text with your actual information
   - Add your professional photo in the About section
   - Upload your design portfolio images
   - Update social media links with your profiles

2. **Contact Form Integration**
   - Set up EmailJS, Formspree, or Web3Forms for contact form
   - Or create a simple backend API endpoint
   - Add form validation and success/error messages

3. **SEO Optimization**
   - Update meta descriptions and title
   - Add Open Graph tags for social sharing
   - Create a sitemap.xml
   - Add structured data (Schema.org)

4. **Performance**
   - Compress and optimize images
   - Add lazy loading for portfolio images
   - Minify CSS and JavaScript for production
   - Set up CDN for faster delivery

5. **Deployment**
   - Use the **Publish tab** to deploy your website
   - Consider custom domain for professional appearance
   - Set up SSL certificate (usually automatic)

## 📞 Support & Customization

Need help customizing or have questions? 

- Update content directly in `index.html`
- Modify colors in `css/style.css` (check CSS variables at top)
- Adjust functionality in `js/main.js`

## 📄 License

This is a personal portfolio website. Feel free to use the code structure as inspiration for your own portfolio.

---

**Built with ❤️ for Nirmal Singh**

*Last Updated: 2024*