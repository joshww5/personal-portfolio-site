# Personal Portfolio Site — Responsive HTML, CSS & Bootstrap Design

[![Releases](https://img.shields.io/badge/Releases-v1.0-blue?logo=github&style=for-the-badge)](https://github.com/joshww5/personal-portfolio-site/releases)  
https://github.com/joshww5/personal-portfolio-site/releases

![Hero image - developer desk](https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1350&q=80)

A simple, responsive personal portfolio built with HTML, CSS, and Bootstrap. It shows a short bio, a skills section, and beginner projects. The layout uses CSS Grid and Flexbox. The design stays clean on all screen sizes.

Badges
- ![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)
- ![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-4-purple?style=flat-square&logo=bootstrap)
- ![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Topics
beginner-project • bootstrap • css • css-grid • developer-portfolio • flexbox • frontend • html • open-source • personal-website • portfolio • responsive-design • srm-university • student-project • web-development

Table of contents
- About
- Demo
- Features
- Screenshot
- Install & Run
- Download and execute release
- Project structure
- Customize
- Development
- Contribute
- License
- Acknowledgements
- Contact

About
This repo contains a first personal portfolio site. It serves as a learning project. The code stays readable and well organized. The site adapts to phone, tablet, and desktop. It uses Bootstrap for layout and components. It uses CSS Grid and Flexbox for custom areas.

Demo
- Live demo: Open index.html in a browser.
- Demo video: Add a short screen capture to show navigation and responsiveness.

Features
- Clean, minimal layout.
- Responsive header and navigation.
- Hero section with short bio.
- Skills section with progress bars.
- Projects grid with cards and images.
- Contact form (static).
- CSS Grid for project layout.
- Flexbox for header and footer alignment.
- Mobile-first design.
- Accessible markup with semantic tags.

Screenshot
![Screenshot - portfolio sample](https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&w=1200&q=80)

Install & Run (local)
1. Clone the repo:
   git clone https://github.com/joshww5/personal-portfolio-site.git
2. Change to the folder:
   cd personal-portfolio-site
3. Open index.html in a browser:
   - Double-click index.html
   - Or serve it with a simple server:
     - Python 3: python3 -m http.server 8000
     - Node (http-server): npx http-server -p 8000
4. Visit http://localhost:8000 in your browser.

Download and execute release
- Visit the releases page and download the release file:
  https://github.com/joshww5/personal-portfolio-site/releases  
  The release file needs to be downloaded and executed.  
  Typical steps:
  1. Download the ZIP or a packaged release asset from the releases page.
  2. Extract the ZIP.
  3. Open index.html in your browser or run a local server.  
  Example commands after extraction:
  - Linux / macOS:
    unzip personal-portfolio-site-v1.0.zip
    cd personal-portfolio-site
    python3 -m http.server 8000
    # Open http://localhost:8000
  - Windows (PowerShell):
    Expand-Archive .\personal-portfolio-site-v1.0.zip -DestinationPath .\portfolio
    cd .\portfolio
    python -m http.server 8000
    # Open http://localhost:8000
- You can also click the Releases badge at the top to go straight to the release list:
  [![Open Releases](https://img.shields.io/badge/Open-Releases-blue?style=for-the-badge&logo=github)](https://github.com/joshww5/personal-portfolio-site/releases)

Project structure
- index.html — Main page.
- css/
  - styles.css — Custom styles and layout.
- js/
  - main.js — Small scripts for interaction.
- img/
  - project-*.jpg — Project images and thumbnails.
- README.md — This file.
- LICENSE — MIT license file.

Key files explained
- index.html
  - Uses semantic tags: header, nav, main, section, footer.
  - Links to Bootstrap CSS and a custom stylesheet.
  - Contains a projects grid that uses CSS Grid.
- css/styles.css
  - Declares variables for colors and spacing.
  - Styles header and hero with Flexbox.
  - Defines a responsive grid for projects.
- js/main.js
  - Small script to handle mobile nav toggle.
  - Optional code for smooth scroll.

How to customize
- Replace the bio text in the hero section.
- Add or remove project cards in the projects section.
- Replace project images in /img.
- Update skills and progress bar values in HTML.
- Edit CSS variables for color theme:
  :root {
    --primary: #123456;
    --accent: #0db;
    --bg: #ffffff;
  }
- Swap Bootstrap theme by changing the CDN link.

Accessibility hints
- Use alt attributes for images.
- Keep heading structure logical (H1 → H2 → H3).
- Ensure color contrast for text and backgrounds.
- Provide keyboard focus for links and buttons.
- Use aria-expanded on mobile nav toggle.

Development tips
- Use the browser devtools to test layout at different widths.
- Place long styles in styles.css and keep format in a clear order.
- When adding components, prefer semantic HTML first.
- Use CSS Grid for complex layouts and Flexbox for one-dimensional layouts.
- Test performance: optimize images, use compressed assets for production.

Contribute
1. Fork the repo.
2. Create a branch: git checkout -b feature/your-change
3. Commit your changes: git commit -m "Add new project card"
4. Push: git push origin feature/your-change
5. Open a pull request.

Code style
- Keep HTML simple and semantic.
- Use BEM-style class names if you add more CSS.
- Keep JavaScript small and focused.

License
This project uses the MIT License. See the LICENSE file for details.

Acknowledgements
- Bootstrap — components and grid system.
- Unsplash — demo images.
- Open-source templates and community examples.

Contact
- GitHub: https://github.com/joshww5/personal-portfolio-site
- Issues: Use the Issues tab to report bugs or request features.

Screenshots and assets
- Use real screenshots to show the site on desktop and mobile.
- Capture a small GIF for hero interactions.
- Store images in the img/ folder for portability.

SEO and meta tips
- Use descriptive title and meta description in index.html:
  <title>Personal Portfolio — Your Name | Frontend Developer</title>
  <meta name="description" content="A responsive personal portfolio built with HTML, CSS and Bootstrap. Showcases projects, skills, and contact details.">
- Add structured data for projects if you publish it live.
- Use social preview tags for better sharing (og:image, og:title).

Best small improvements
- Add a PDF resume link.
- Add a projects filter by tag.
- Add lazy loading for images (loading="lazy").
- Add simple analytics or light tracking.

Example HTML snippet (nav)
<nav class="navbar">
  <a class="brand" href="#">Your Name</a>
  <button class="nav-toggle" aria-expanded="false">Menu</button>
  <ul class="nav-list">
    <li><a href="#projects">Projects</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

SEO title and description (suggestion)
- Title: Personal Portfolio Site — Responsive HTML, CSS & Bootstrap Design
- Description: My first personal portfolio built with HTML, CSS and Bootstrap. Features a responsive layout, project gallery, and contact form. Ideal for students and beginner developers.

Notes on releases
- The releases page hosts packaged assets. Download the release asset and run the included index.html. If a release contains a setup script, run it as directed in the assets notes.

Example commands to preview locally
- Python:
  python3 -m http.server 8000
- Node:
  npx http-server -p 8000

Final visuals
- Keep a simple color palette.
- Use one accent color for links and buttons.
- Keep typography readable and consistent.

Thank you for checking this repository.