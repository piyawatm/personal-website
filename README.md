# Personal Website - Piyawatchara (Ken) Mahathandul

A sleek, monochrome personal website showcasing the journey of a software engineer and graduate student. Features a computer science-inspired design highlighting academic excellence, professional experience, and community-impact projects.

## 🌟 Features

- **Monochrome Theme**: Clean black/white design with computer science aesthetics
- **Professional Portfolio**: Comprehensive showcase of academic and work achievements
- **Project Showcase**: Dedicated section for Debatabase-TH, research projects, and educational platforms
- **Responsive Design**: Optimized for all devices with mobile-first approach
- **Logo Integration**: Company and institution logos with fallback icons
- **Fast & Accessible**: Built with performance and accessibility best practices
- **GitHub Pages Ready**: One-click deployment to `piyawatm.github.io`

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
├── index.html          # Main HTML file with all content sections
├── styles.css          # Monochrome CSS theme with responsive design
├── script.js           # Interactive features and scroll effects
├── README.md           # Project documentation
├── CNAME              # GitHub Pages domain configuration
├── LICENSE            # MIT License
└── .gitignore         # Git ignore file
```

## 🎯 About Ken Mahattanadul

**Software Engineer & Graduate Student** pursuing M.S. in Computer Science at Brown University (2025-2027). Graduate of University of Michigan with B.S.E. in Computer Science, Summa Cum Laude. Passionate about building impactful technology solutions, from fintech infrastructure to community platforms.

### Key Highlights
- **🏆 Academic Excellence**: 8-Term Dean's List, James B. Angell Scholar, University Honors
- **💼 Professional Experience**: Software Engineer at Jobtopgun, Data Engineer at Union Pacific Railroad
- **🚀 Community Impact**: Co-founder of Debatabase-TH (Thailand's debate platform) and Vaewvakyvadi (educational platform reaching 17K+ users)
- **📚 Research**: Published author on big data systems with Union Pacific Railroad partnership

## 📋 Website Sections

### 🏠 **Hero Section**
Clean introduction with terminal-inspired design and call-to-action buttons

### 👨‍💻 **About Section** 
Personal bio highlighting software engineering background and passion for building impactful solutions

### 🎓 **Education Timeline**
- **Brown University** - M.S. Computer Science (2025-2027)  
- **University of Michigan** - B.S.E. Computer Science, Summa Cum Laude (2019-2023)

### 💼 **Professional Experience**
- **Jobtopgun** - Software Engineer (Apr 2024-Present)
- **Union Pacific Railroad** - Software Engineer, Data Analyst (Jul 2023-May 2025)  
- **Agoda** - Software Engineer Intern (May-Aug 2021)

### 🚀 **Featured Projects**
- **[Debatabase-TH](https://debatabase-th.vercel.app/)** - Thailand's comprehensive debate platform
- **Big Data Backbone** - Research project with Union Pacific Railroad  
- **[Vaewvakyvadi](https://www.vaewvakyvadi.com)** - Educational platform reaching 17K+ users

### 🏆 **Achievements & Recognition**
- Awards & Honors (Summa Cum Laude, James B. Angell Scholar, National Debate Champion)
- Technical Skills (Programming languages, Cloud & Big Data, Languages)  
- Projects & Academic Excellence (Notable projects + Academic achievements)

### 📞 **Contact Information**
Social links and professional contact details

## 🎨 Design Features

### **Monochrome Aesthetic**
- Clean black/white color palette
- Computer science-inspired typography using Fira Code and JetBrains Mono
- Minimalist animations and hover effects
- High contrast for accessibility

### **Logo Integration**  
- Company logos via Clearbit API with FontAwesome fallbacks
- Institution logos for education timeline
- Robust error handling for missing logos

## 🛠️ Customization Guide

### **Theme Customization**
The monochrome theme can be easily modified in `styles.css`:
- **Colors**: Update `background`, `color`, and `border` properties
- **Typography**: Change `font-family` from Fira Code/JetBrains Mono to your preference  
- **Layout**: Adjust Grid/Flexbox properties for different arrangements
- **Animations**: Modify `transition` and `transform` effects

### **Content Updates**
1. **Personal Info**: Update name, bio, and contact details in `index.html`
2. **Experience**: Add new roles or modify existing ones
3. **Projects**: Update project descriptions and links
4. **Achievements**: Add new awards, publications, or skills
5. **Education**: Modify timeline with your academic history

### **Adding Profile Photo**
Replace the terminal icon with your photo:
```html
<!-- In the hero section, replace: -->
<div class="image-placeholder">
    <i class="fas fa-terminal"></i>
</div>

<!-- With: -->
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-image">
</div>
```

## 🔧 Technical Stack

- **HTML5**: Semantic structure with accessibility best practices
- **CSS3**: Modern features (Grid, Flexbox, Custom Properties) + Monochrome theme
- **JavaScript ES6+**: Vanilla JS with smooth scrolling and interactive navigation
- **External APIs**: Clearbit Logo API for company/institution logos
- **Typography**: Fira Code & JetBrains Mono for computer science aesthetic
- **Performance**: Optimized for Core Web Vitals and fast loading

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Development & Testing

### **Local Development**
```bash
# Clone the repository
git clone https://github.com/piyawatm/piyawatm.github.io.git
cd piyawatm.github.io

# Option 1: Open directly in browser
open index.html

# Option 2: Use local server (recommended)
python -m http.server 8000
# or
npx serve .
```

### **Live Preview**
Visit the live website: **[piyawatm.github.io](https://piyawatm.github.io)**

## 📊 Performance & Quality

- **⚡ Fast Loading**: Optimized CSS/JS with minimal external dependencies
- **📱 Mobile-First**: Responsive design tested across all device sizes  
- **♿ Accessible**: High contrast design with semantic HTML structure
- **🔍 SEO Optimized**: Meta tags, structured data, and semantic markup
- **🌐 Cross-Browser**: Compatible with all modern browsers

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

## 🎯 Project Highlights

### **🌟 Why This Website Stands Out**

1. **Personal Branding**: Clean, professional presentation that reflects technical expertise
2. **Comprehensive Portfolio**: Education, experience, projects, and achievements in one place  
3. **Community Impact**: Showcases leadership in Thailand's debate and educational communities
4. **Technical Excellence**: Demonstrates full-stack development skills and system design experience
5. **Academic Achievement**: Highlights research publications and honors program completion

### **📈 Visitor Journey**
- **Landing**: Professional introduction with clear call-to-action
- **About**: Personal story connecting passion with technical skills  
- **Education**: Academic credentials at top-tier institutions
- **Experience**: Professional progression in software engineering
- **Projects**: Community impact through technology solutions
- **Achievements**: Recognition and technical competencies
- **Contact**: Easy connection for opportunities

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

## 🚀 **About the Developer**

**Piyawatchara (Ken) Mahattanadul** is a software engineer and graduate student passionate about building technology that creates positive community impact. From fintech infrastructure processing millions of transactions to educational platforms reaching thousands of users, Ken combines technical excellence with social responsibility.

**Connect with Ken:**
- 🌐 **Website**: [piyawatm.github.io](https://piyawatm.github.io)
- 🔗 **LinkedIn**: [Piyawatchara Mahattanadul](https://linkedin.com/in/piyawatcharamahattanadul)
- 💻 **GitHub**: [@piyawatm](https://github.com/piyawatm)
- 📧 **Email**: Available on the website

---

**Built with ❤️ for showcasing technical excellence and community impact**

*Updated: January 2025*
