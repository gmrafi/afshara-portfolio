# Afshara Tasneem Zoa - Academic Portfolio

A comprehensive professional academic portfolio website for Computer Science & Engineering student at BRAC University.

## 🌟 Features

✅ **Responsive Design** - Works on all devices (mobile, tablet, desktop)
✅ **Professional White Theme** - Clean academic aesthetic with black accents
✅ **Easy to Update** - All content in a single data object
✅ **SEO Friendly** - Proper meta tags and semantic HTML
✅ **Fast Loading** - CDN-based resources, no build process needed

## 📋 Portfolio Sections

1. **Hero Section** - Name, tagline, profile photo, CTA buttons
2. **About** - Personal bio and introduction
3. **Research Interests** - Academic focus areas (4 detailed interests)
4. **Featured Research** - Conference paper with full details
5. **Skills** - Technical skills and programming languages
6. **Projects** - Academic and personal projects (3 projects)
7. **Education** - University details and degree information
8. **Academic Coursework** - Completed and ongoing courses (6 categories)
9. **Certifications** - Online courses and training programs
10. **Extracurricular Activities** - Clubs, leadership, volunteer work
11. **Achievements** - Awards and notable accomplishments
12. **Future Goals** - Academic and career aspirations with timelines
13. **Contact** - Email, social links, ORCID ID

## 🚀 Quick Start

### 1. Add Your Profile Picture
- Your photo is already in `photos/profile.jpg`
- To change: Replace the file or update path in `portfolioData.profileImage`

### 2. Add Your CV/Resume
- See `CV_INSTRUCTIONS.md` for detailed steps
- Create a `cv` folder and add your PDF
- Update `cvLink` in the portfolioData object

### 3. Update Your Information
- Open `index.html`
- Scroll to the bottom and find the `portfolioData` object
- Edit all sections with your actual information

### 4. Deploy to GitHub Pages
```bash
# Create repository named: yourusername.github.io
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```
- Go to Settings → Pages
- Select `main` branch and save
- Your site will be live at `https://yourusername.github.io`

## 📂 File Structure

```
afshara-portfolio/
│
├── photos/
│   └── profile.jpg          # Your profile picture
├── cv/                      # Create this folder
│   └── YourCV.pdf          # Your CV/Resume (add this!)
├── index.html              # Main portfolio file
├── README.md               # This file
└── CV_INSTRUCTIONS.md      # CV setup guide
```

## ✏️ How to Update Content

All content is in the `portfolioData` object at the bottom of `index.html`. Edit these sections:

### Core Information
- `name` - Your full name
- `tagline` - Your headline/title
- `profileImage` - Path to your photo
- `bio` - About me paragraph

### Academic Content
- `research` - Your conference paper details
- `interests` - 4 research interest areas
- `coursework` - 6 course categories with status
- `certifications` - Online courses and training
- `education` - University and degree details
- `activities` - Clubs, leadership, volunteer work
- `achievements` - Awards and accomplishments
- `goals` - Future aspirations with timelines

### Technical & Projects
- `skills` - Programming languages and tools
- `projects` - 3 academic/personal projects

### Contact & Links
- `social.linkedin` - Your LinkedIn profile URL
- `social.github` - Your GitHub profile URL
- `social.email` - Your academic email
- `cvLink` - Link to your CV/Resume PDF

## 🎨 Design Features

- **Professional White Background** - Clean academic aesthetic
- **Black Accents** - Elegant highlights and borders
- **Glassmorphism Cards** - Modern card effects with shadows
- **Smooth Animations** - Hover effects and transitions
- **Status Badges** - Visual indicators for course/certification progress
- **Timeline Tags** - Future goals with time frames
- **Responsive Grid Layouts** - Adapts to all screen sizes

## 🎯 Perfect For

- Academic portfolios for university students
- Research showcase and publications
- Graduate school applications
- Internship and job applications
- Professional networking (LinkedIn, conferences)

## 📱 Browser Support

- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 Support

For questions about updating your portfolio:
1. Check `CV_INSTRUCTIONS.md` for CV setup
2. Review the `portfolioData` object comments in `index.html`
3. All content is easily customizable without coding knowledge

---

**Tech Stack:** HTML5, Tailwind CSS, JavaScript, Font Awesome Icons
**Designed for:** Academic excellence and professional growth 🎓
