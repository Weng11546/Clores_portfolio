# Clores_portfolio
Professional Portfolio Website

# Rowena Clores | IT Portfolio

A personal portfolio website for **Rowena Clores**, a 4th Year BSIT student at Datamex College of Saint Adeline, specializing in **Web Development** and **Data Analysis**. The site showcases her profile, skills, projects, certificates, and contact details, with a goal of becoming an **IT Project Manager**.

Built with plain HTML, CSS, and JavaScript. No frameworks or build tools required.

## Features

- Animated loading screen and typing effect in the hero section
- Light and dark mode, with the choice saved in the browser
- Floating navigation bar with scroll highlighting and a mobile menu
- Fade, slide, and unblur reveal animations on scroll
- Clickable certificates that open in a popup preview (images and PDFs)
- Individual detail pages for each project
- Fully responsive layout for desktop, tablet, and mobile
- Respects the `prefers-reduced-motion` setting

## Sections

1. **Home**: introduction, social links, and CV download
2. **Professional Profile**: who I am, my goal, and personal details
3. **Technical Skills**: programming, databases, tools, and other skills
4. **Projects**: selected works with detail pages
5. **Problem-Solving**: a step-by-step timeline of my process
6. **Employability**: communication, teamwork, time management, and mock interview
7. **Resume**: education, experience, and highlights
8. **Certificates and Achievements**: clickable certificates
9. **GitHub**: link to my repositories
10. **Contact**: email, phone, LinkedIn, and a message form
11. **Reflection**: lessons learned and career goals

## Projects

| Project | Type | Tools |
|---|---|---|
| **Poultry Feed Stock Tracking with POS Application** (`project1.html`) | Android application | Kotlin, Android SDK, Android Studio, Discord Webhooks and Bots |
| **Social Media Engagement Analysis** (`project2.html`) | Data analysis (Excel) | Excel, COUNTIF, AVERAGEIFS, SUMPRODUCT, RANK, CORREL |
| **ExpenseFlow, Expense Tracker** (`project3.html`) | Android application | Kotlin, Android Studio, Room Database, XML, Compose |

## Tech Stack

- **HTML5**: page structure
- **CSS3**: custom properties for theming, Grid, Flexbox, animations
- **JavaScript (vanilla)**: theme toggle, mobile menu, scroll effects, certificate popup
- **Poppins** font via Google Fonts
- **Font Awesome 6.5.1** icons via CDN

## Project Structure

```
.
├── index.html        Main portfolio page
├── project1.html     Poultry Feed Stock Tracking with POS
├── project2.html     Social Media Engagement Analysis
├── project3.html     ExpenseFlow (Expense Tracker)
├── style.css         Shared styles and theme variables
├── project.css       Extra styles for project pages
├── script.js         Main page behavior
├── project.js        Project page behavior
├── cert.css          Certificate popup styles
├── hero.jpg          Hero section photo
├── photo.jpg         Profile section photo
├── resume.pdf        Downloadable resume
├── cert1.pdf         Certificate: Cyber Awareness
├── cert2.pdf         Certificate: Web Dev 101
├── cert3.pdf         Certificate: Arduino 101
└── cert4.jpg         Certificate: IT Infrastructure and Cloud Computing
```

## Getting Started

1. Clone or download this repository.
2. Make sure `hero.jpg`, `photo.jpg`, `resume.pdf`, and the certificate files are in the same folder as `index.html`.
3. Open `index.html` in any modern browser.

To run a local server instead:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customization

- **Typing text**: edit the `phrases` array in `script.js`.
- **Colors and theme**: change the CSS variables at the top of `style.css`.
- **Certificates**: add a new `<li>` with a `.cert-link` in the Certificates section of `index.html`. Both images and PDFs are supported.
- **Projects**: copy `project1.html` as a template for a new project page.

## To-Do

- Replace the placeholder screenshots on the project pages with real images
- Add live demo links on the project pages
- Update the GitHub link in the GitHub section of `index.html` (currently `https://github.com/your-username`)
- Fill in the remaining placeholder content: Project 2 card on the home page, Problem-Solving, Employability, Resume, and Reflection sections
- Connect the contact form to an email service (it currently does not send messages)

## Contact

- **Email:** rowenaclores03@gmail.com
- **GitHub:** [Weng11546](https://github.com/Weng11546)
- **LinkedIn:** [Rowena Clores](https://www.linkedin.com/in/rowena-clores-4181a5334/)
- **Location:** Philippines

## License

&copy; 2026 Rowena Clores. All rights reserved.
