# Computer Science Portfolio Website

A modern, responsive portfolio website designed for computer science graduates to showcase their skills, projects, and experience.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill bars
  - Mobile hamburger menu
  - Contact form with validation
  - Parallax effects
- **Sections Included**:
  - Hero section with call-to-action buttons
  - About section with personal stats
  - Featured projects showcase
  - Technical skills with progress bars
  - Contact form and social links
- **Performance Optimized**: Fast loading with minimal dependencies

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🛠️ Setup Instructions

### Option 1: Local Development (Recommended)

1. **Open** the `index.html` file in your web browser
2. **Customize** the content with your personal information (see Customization section below)

### Option 2: Live Server (For Development)

If you have VS Code with Live Server extension:

1. Open the project folder in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. The website will open in your browser with auto-reload

### Option 3: Deploy to Web Hosting

1. **Choose a hosting service** (GitHub Pages, Netlify, Vercel, etc.)
2. **Upload** all files to your hosting service
3. **Update** the contact form action URL if needed
4. **Test** the live website

## 🎨 Customization Guide

### 1. Personal Information

**Update the following in `index.html`:**

- **Name**: Replace "Your Name" throughout the file
- **Title**: Change "Computer Science Graduate" to your actual title
- **Description**: Update the hero description and about section
- **Contact Info**: 
  - Email: `your.email@example.com`
  - Phone: `+1 (555) 123-4567`
  - Location: `Your City, State`
- **Social Links**: Update the href attributes for your social media profiles

### 2. Projects Section

**Replace the example projects with your own:**

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-globe"></i> <!-- Change icon as needed -->
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### 3. Skills Section

**Update programming languages and technologies:**

- **Programming Languages**: Modify the skill bars in the skills section
- **Technologies & Frameworks**: Update the skill tags grid

### 4. About Section

**Customize the about content:**

- Update the personal description
- Modify the statistics (projects completed, languages, etc.)
- Add your own image by replacing the placeholder

### 5. Styling Customization

**Color Scheme**: Update the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;    /* Main blue color */
    --secondary-color: #fbbf24;  /* Accent yellow color */
    --text-color: #333;          /* Main text color */
    --bg-color: #ffffff;         /* Background color */
}
```

**Fonts**: Change the Google Fonts import in the HTML head section

## 📱 Responsive Breakpoints

The website is optimized for:

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Technical Details

### Dependencies

- **Font Awesome**: For icons (loaded via CDN)
- **Google Fonts**: Inter font family (loaded via CDN)
- **No JavaScript frameworks**: Pure vanilla JavaScript for better performance

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

### Performance Features

- Optimized CSS with minimal redundancy
- Efficient JavaScript with event delegation
- Lazy loading for animations
- Compressed and minified assets (when deployed)

## 📧 Contact Form

The contact form includes:

- Client-side validation
- Email format validation
- Required field checking
- Success message display
- Form reset after submission

**Note**: The form currently shows a success message. To make it functional, you'll need to:

1. Set up a backend service (Node.js, PHP, Python, etc.)
2. Update the form action URL
3. Handle the form submission on the server

## 🚀 Deployment Options

### GitHub Pages
1. Create a new repository
2. Upload all files
3. Go to Settings > Pages
4. Select source branch
5. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be live instantly
3. Custom domain can be added in settings

### Vercel
1. Connect your GitHub repository
2. Deploy with one click
3. Automatic deployments on code changes

## 🎯 SEO Optimization

To improve search engine visibility:

1. **Update meta tags** in the HTML head
2. **Add alt text** to images
3. **Include relevant keywords** in content
4. **Add structured data** markup
5. **Create a sitemap.xml**

## 📈 Analytics

To track website visitors:

1. **Google Analytics**: Add tracking code to HTML head
2. **Google Search Console**: Verify ownership
3. **Social media tracking**: Add pixel codes if needed

## 🛡️ Security Considerations

- Validate all form inputs
- Use HTTPS for live deployment
- Keep dependencies updated
- Implement CSP headers if needed

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you have improvements or bug fixes, pull requests are welcome!

## 📞 Support

If you need help customizing or deploying your portfolio:

1. Check this README for common issues
2. Review the code comments
3. Test in different browsers
4. Validate HTML and CSS

---

**Happy coding! 🚀**

*Remember to replace all placeholder content with your actual information before deploying.*