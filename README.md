🚀 Overview
A modern, responsive portfolio website for Louisana Mallari, showcasing skills as a Frontend Developer and UI/UX Designer. This portfolio features a dark/light theme toggle, interactive elements, and a clean, professional design.

✨ Features
🎨 Design & UI
Dual Theme Support: Dark (default) and Light modes with persistent preference saving

Responsive Design: Fully responsive across all device sizes (mobile, tablet, desktop)

Modern Aesthetics: Gradient accents, smooth animations, and clean typography

Interactive Elements: Hover effects, transitions, and particle animations

📱 Sections Included
Hero Section - Introduction with profile image and call-to-action buttons

About Me - Personal bio with interactive photo upload functionality

Expertise - Key skills and capabilities presented with icons

Skills - Technical and soft skills with visual percentage indicators

Projects - Portfolio showcase with live project links (5 projects included)

Experience & Education - Timeline format with institution images and links

Contact - Contact information and message form

⚡ Interactive Features
Theme Toggle: Switch between dark and light modes

Mobile Navigation: Collapsible menu for mobile devices

Image Upload: Click profile images to upload new photos

Smooth Scrolling: Navigation between sections

Form Submission: Contact form with validation

PDF Download: Resume download functionality

Project Links: Direct links to live projects on Vercel

🛠️ Technologies Used
Frontend
HTML5: Semantic markup structure

CSS3: Custom properties, Flexbox, Grid, animations

JavaScript: ES6+ for interactive functionality

Font Awesome: Icons for UI elements

Google Fonts: Inter font family

Key CSS Features
CSS Custom Properties (variables) for theming

CSS Grid and Flexbox for layouts

CSS Transitions and Animations

Responsive media queries

Gradient backgrounds

📁 File Structure
text
portfolio/
├── index.html                 # Main HTML file
├── image/                     # Image assets folder
│   ├── lou_image.jpg         # Profile photo
│   ├── 2.png                 # Project 2 image
│   ├── 3.png                 # Project 3 image
│   ├── 4.png                 # Project 4 image
│   ├── 5.png                 # Project 5 image
│   └── 7.png                 # Project 1 image
├── Louisana_Mallari_Resume.pdf # Resume PDF
└── README.md                 # This documentation
🔧 Setup & Customization
Prerequisites
Modern web browser

Text editor (VS Code recommended)

GitHub account for hosting

Steps to Deploy
Clone or Download the project files

Update Personal Information:

Replace lou_image.jpg with your own profile photo

Update contact information in the Contact section

Modify project details and links

Replace resume PDF with your own

Update Social Links:

LinkedIn: Replace href in social-links sections

GitHub: Update href in social-links sections

Figma/Dribbble: Add your profile links

Update Project Links:

Each project has a "View Project" button

Replace placeholder Vercel URLs with your actual project links

Local Development
Simply open index.html in any modern web browser. No build process or dependencies required.

📱 Responsive Breakpoints
Desktop: 1200px+ (Full layout)

Tablet: 768px - 992px (Adjusted layouts)

Mobile: < 768px (Stacked columns, mobile menu)

🎯 JavaScript Functionality
Core Functions
Theme Management: Toggle and persist theme preferences

Navigation: Mobile menu toggle and smooth scrolling

Form Handling: Contact form submission with validation

Image Upload: Profile photo upload with localStorage persistence

Interactive Elements: Hover effects, animations, and transitions

Browser Compatibility
Chrome (recommended)

Firefox

Safari

Edge

🚀 Deployment Options
GitHub Pages (Recommended)
Create a new repository on GitHub

Upload all project files

Go to Settings > Pages

Select "main" branch and root folder

Your site will be live at https://username.github.io/repository-name

Vercel
Create Vercel account

Import GitHub repository

Deploy with default settings

Custom domain can be added

Netlify
Drag and drop project folder to Netlify

Automatic deployment

Custom domain configuration available

🔗 Live Project Links (To be Updated)
Replace the following placeholder links with your actual project URLs:

Mabini Landing Page: https://mabini-landing-page-omega.vercel.app

E-commerce: https://e-commerce-f75d.vercel.app

Migration: https://migration-system-lk33.vercel.app

Auth: http://lyn-lou-auth.vercel.app

Ordering System: https://ordering-louisana.vercel.app

📝 Customization Guide
Changing Colors
Modify the CSS variables in the :root and .light-mode selectors at the top of the <style> section:

css
:root {
    --primary: #3B82F6;      /* Change blue color */
    --accent: #10B981;       /* Change green color */
    /* ... other variables */
}
Adding New Projects
Duplicate a project card structure and update:

Image source

Project title

Description

Tags

Project link

Updating Skills
Modify the skills lists in the Skills section:

Technical skills with percentages

Tools & workflow items

Soft skills

📊 SEO & Performance
SEO Features
Semantic HTML5 elements

Meta viewport for responsiveness

Descriptive alt tags for images

Proper heading hierarchy

Performance Optimizations
Minimal external dependencies

Inline CSS to reduce HTTP requests

Optimized images (recommended to compress)

Lazy loading for images (can be added)

🐛 Troubleshooting
Common Issues
Images not displaying: Check file paths in src attributes

Links not working: Verify href values are correct

Mobile menu not opening: Check JavaScript console for errors

Theme not saving: Clear localStorage and reload

Browser Support Notes
CSS Grid and Flexbox fully supported in modern browsers

CSS Custom Properties require modern browsers

Some animations may be less smooth in older browsers

📄 License
This portfolio template is free to use for personal and commercial projects. Attribution is appreciated but not required.

🤝 Contributing
While this is a personal portfolio, feel free to fork and adapt for your own use. For improvements or bug fixes, submit a pull request.

📧 Contact
For questions or support:

Email: mallarilouisana2@gmail.com

Location: San Francisco, Mabini, Philippines

Phone: +(63)936 911 6834

Last Updated: March 2025
Version: 1.0
Author: Louisana Mallari

