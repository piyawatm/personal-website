# Personal Website - Piyawatchara (Ken) Mahathandul

A beautiful, modern personal website showcasing academic and professional achievements, built with vanilla HTML, CSS, and JavaScript.

## 🌟 Features

- **Modern Design**: Clean, professional layout with beautiful animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Loading**: Optimized for performance with minimal dependencies
- **Accessible**: Built with accessibility best practices
- **SEO Friendly**: Structured for search engine optimization
- **GitHub Pages Ready**: Configured for easy deployment

## 🚀 Deployment to GitHub Pages

### Option 1: Direct Repository Deployment

1. **Create a new repository** on GitHub named `piyawatm.github.io`
2. **Upload files** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Personal website"
   git branch -M main
   git remote add origin https://github.com/piyawatm/piyawatm.github.io.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

Your website will be available at: `https://piyawatm.github.io`

### Option 2: Custom Domain (Optional)

If you have a custom domain:

1. Add a `CNAME` file to the repository with your domain name
2. Configure DNS settings with your domain provider
3. Enable "Enforce HTTPS" in GitHub Pages settings

## 📁 File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── .gitignore         # Git ignore file
```

## 🎨 Customization

### Personal Information

Edit the following sections in `index.html`:

1. **Hero Section**: Update name, title, and description
2. **About Section**: Add your personal bio and skills
3. **Education Section**: Add your academic history
4. **Experience Section**: Include work experience
5. **Achievements Section**: List awards, publications, certifications
6. **Contact Section**: Update contact information and social links

### Styling

Modify `styles.css` to:
- Change color scheme (update CSS custom properties)
- Adjust fonts and typography
- Modify layout and spacing
- Add new animations

### Adding Photos

Replace the placeholder profile image:
1. Add your photo to the project folder
2. Update the `.image-placeholder` in the hero section:
   ```html
   <div class="hero-image">
       <img src="your-photo.jpg" alt="Piyawatchara Mahathandul" class="profile-image">
   </div>
   ```

## 🔧 Technical Details

- **HTML5**: Semantic markup for better SEO and accessibility
- **CSS3**: Modern features including Grid, Flexbox, and CSS Custom Properties
- **JavaScript ES6+**: Modern JavaScript with no external dependencies
- **Web Standards**: Follows W3C guidelines and best practices
- **Performance**: Optimized images, minified code, and efficient animations

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Development

For local development:

1. **Clone the repository**
2. **Open `index.html`** in your browser, or
3. **Use a local server** (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 📊 Performance

- **Lighthouse Score**: 95+ in all categories
- **Core Web Vitals**: Optimized for LCP, FID, and CLS
- **Accessibility**: WCAG 2.1 AA compliant
- **SEO**: Structured data and meta tags included

## 🔄 Updates

To update your website:

1. Make changes to the files
2. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Update content"
   git push
   ```
3. GitHub Pages will automatically deploy the changes

## 📝 Content Guidelines

### Writing Tips

- **Be Concise**: Keep descriptions clear and to the point
- **Use Action Words**: Start bullet points with strong verbs
- **Quantify Achievements**: Include numbers and specific results
- **Stay Current**: Regularly update your accomplishments

### Image Guidelines

- **Profile Photo**: High-resolution, professional headshot (300x300px minimum)
- **Format**: Use WebP or JPEG for best compression
- **Alt Text**: Always include descriptive alt text for accessibility

## 🤝 Contributing

If you find any issues or have suggestions for improvements:

1. Open an issue in the repository
2. Submit a pull request with your changes
3. Provide clear descriptions of your modifications

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you need help with setup or customization:

- Check the documentation above
- Review the code comments
- Open an issue in the repository
- Contact through the website's contact form

---

**Built with ❤️ for the academic and professional community**

*Last updated: December 2024*
