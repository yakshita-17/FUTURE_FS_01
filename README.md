Yakshita — Personal Professional Portfolio Website

Future Interns | Full Stack Web Development — Task 1 (2026)

A clean, responsive, and professional portfolio website built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just fast, accessible, production-ready code.

🔗 Live Demo

Deploy to Vercel or Netlify and paste your link here
https://yakshita.vercel.app


📌 Table of Contents

About the Project
Features
Tech Stack
Project Structure
Getting Started
Deployment
Customization Guide
Screenshots
Author
License


About the Project
This portfolio website was built as Task 1 of the Future Interns Full Stack Web Development internship program. The goal was to create a real, production-ready personal portfolio that can be shown to recruiters, clients, and hiring managers.
The site showcases:

Who Yakshita is as a developer
Skills and tech stack
Projects built (including Future Interns tasks)
Professional experience and journey
A working contact form


Features

Hero Section — Bold animated name reveal with CTA buttons and scroll indicator
Marquee Ticker — Scrolling tech stack banner
About Section — Bio, stats grid, and profile image placeholder
Skills Section — 4 categories: Frontend, Backend, Database, Tools & DevOps
Projects Section — Featured project card + 3 additional project cards with live/GitHub links
Experience Timeline — Internship and learning journey
Contact Form — Name, email, subject, message with success feedback
Custom Cursor — Animated dot + ring cursor with blend mode
Scroll Progress Bar — Accent-colored progress line at the top of the page
Sticky Navigation — Frosted glass effect on scroll
Mobile Hamburger Menu — Full-screen overlay navigation for small screens
Scroll Reveal Animations — Elements fade up as they enter the viewport
Fully Responsive — Works on all screen sizes (mobile, tablet, desktop)
SEO Friendly — Semantic HTML structure with meta description


Tech Stack
LayerTechnologyMarkupHTML5 (Semantic)StylingCSS3 (Custom Properties, Grid, Flexbox, Animations)LogicVanilla JavaScript (ES6+)FontsGoogle Fonts — Bebas Neue, DM Sans, JetBrains MonoDeploymentVercel / Netlify (recommended)
No npm, no build tools, no dependencies. Open index.html and it just works.

Project Structure
yakshita-portfolio/
│
├── index.html          # Complete single-file portfolio (HTML + CSS + JS)
└── README.md           # Project documentation

This is a single-file project. All CSS is embedded in <style> tags and all JavaScript is embedded in <script> tags within index.html. This keeps deployment simple and eliminates any asset loading issues.


Getting Started
Prerequisites
No installations required. You only need a modern web browser.
Run Locally
Option 1 — Open directly:
bash# Simply double-click index.html
# or open it in your browser
open index.html
Option 2 — Using VS Code Live Server:

Install the Live Server extension in VS Code
Right-click index.html → Open with Live Server
Visit http://127.0.0.1:5500

Option 3 — Using Python:
bash# Python 3
python -m http.server 8000

# Then visit http://localhost:8000

Deployment
Deploy to Vercel (Recommended)

Push your code to a GitHub repository
Go to vercel.com and sign in with GitHub
Click New Project → Import your repository
Leave all settings as default → Click Deploy
Your site is live at https://your-project.vercel.app

Deploy to Netlify

Go to netlify.com and sign in
Click Add new site → Deploy manually
Drag and drop your project folder onto the Netlify dashboard
Your site is live instantly

Deploy to GitHub Pages

Push your code to a GitHub repository
Go to Settings → Pages
Under Source, select main branch → / (root)
Click Save — your site will be live at https://username.github.io/repo-name


Customization Guide
Open index.html and update the following sections with your real information:
Personal Info
What to changeWhere to find itYour name displaySearch for YAKSHITA in the hero sectionHero subtitle text.hero-sub paragraphAbout Me bio paragraphsInside #about sectionStats numbers (5+, 3+, etc.).stat-num divs in the about section
Projects
Search for project-card divs and replace:

.project-title — Your project name
.project-desc — Your project description
.project-tag spans — Your tech stack tags
href="#" on project links — Your live URL and GitHub URL

Experience
Update the .timeline-item divs with your real dates, roles, and companies.
Contact & Social Links
What to changeWhere to find itEmail addressmailto:yakshita@email.comGitHub profile linkhref="https://github.com/"LinkedIn profile linkhref="https://linkedin.com/"
Profile Photo
Replace the avatar placeholder inside .about-image-frame with:
html<img src="your-photo.jpg" alt="Yakshita" style="width:100%;height:100%;object-fit:cover;" />
Color Theme
All colors are CSS variables at the top of the <style> block:
css:root {
  --accent: #e8ff47;   /* Change to your preferred accent color */
  --accent2: #ff6b35;  /* Secondary accent */
  --bg: #0a0a0a;       /* Main background */
  --text: #f0ede6;     /* Primary text color */
}

Screenshots

Add screenshots of your live website here after deployment

Hero Section        →  Bold name reveal with animated entrance
About Section       →  Bio + stats grid
Skills Section      →  Tech stack categories
Projects Section    →  Featured + project cards
Contact Section     →  Form + social links

Author
Yakshita
Full Stack Developer Intern @ Future Interns

GitHub: @yakshita
LinkedIn:https://www.linkedin.com/in/yakshita-pasala-283440348?utm_source=share_via&utm_content=profile&utm_medium=member_android
Email: yakshitapasala1@gmail.com
