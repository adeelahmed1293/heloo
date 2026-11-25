# Iqra University Islamabad Campus (H-9)
## Department of Computing and Technology
### CSC 337: Web Programming Languages — Assignment No. 1
**Instructor:** Dr. Faheem Shaukat  
**Student Name:** Abid Mehsud  
**Roll No:** 45892 (Section: Morning 12:30 / Evening 03:30)  
**Program:** BS(CS) — 6th Semester  
**Due Date:** 25-Nov-2026  

---

## Project Overview
This project is an individual assignment implementing a professional, multi-page portfolio website using standard-compliant **HTML5** and **CSS3**. The architecture strictly complies with W3C web standards, utilizes zero JavaScript or external UI frameworks, and is optimized for complete responsiveness down to 375px mobile viewports without any horizontal scrolling.

### Live Links & Repository
- **GitHub Repository:** `https://github.com/abidmehsud/abid-mehsud-portfolio`
- **GitHub Pages Live Link:** `https://abidmehsud.github.io/abid-mehsud-portfolio/`

---

## Directory Structure
All file and directory names are strictly lowercase:
```
abid-mehsud-portfolio/
├── index.html              # Home page with semantic tags, hero, bio, skills, and course aside
├── hobbies.html            # Lists (ol/ul), game descriptions (CS2 & Cricket), two styled tables
├── media.html              # CSS Grid two-column layout: social cards/images & 5 YouTube videos
├── contact.html            # Contact info, styled form, embedded Google Map, friends & IDs
├── favicon.ico             # Root favicon
├── css/
│   └── style.css           # Single external stylesheet with Flexbox, CSS Grid, and media queries
├── images/
│   ├── favicon.png         # Site favicon
│   ├── profile.png         # Abid Mehsud portfolio avatar
│   ├── web-dev-local.png   # Local media diagram (HTML5/CSS3 architecture)
│   └── social-post-preview.png # Local social media announcement screenshot
└── README.md               # Complete assignment documentation
```

---

## Features & Implementation Details

### Q1: HTML Structure (4 Pages)
- **Semantic Tags:** Extensive use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<figure>`, and `<figcaption>`.
- **Meta & Head Elements:** Complete `<meta charset="UTF-8">`, responsive `<meta name="viewport">`, descriptive `<meta name="description">`, `<title>`, and favicon integration on all 4 pages.
- **Hobbies Page:** 
  - One ordered list (`<ol>`) of daily engineering routines.
  - One unordered list (`<ul>`) of creative interests.
  - In-depth descriptions of an online game (*Counter-Strike 2*) and a physical game (*Cricket*).
  - Two structured tables: Favourite Hobbies and Favourite Games (self and peer comparison).
- **Media Page:** Dual-column showcase with social posts, local image diagram, online photo from Unsplash, and 5 responsive YouTube embeds.
- **Contact Page:** Complete contact information, embedded Google Map centered at Iqra University Islamabad Campus (H-9), directory of peer names and student IDs, and an accessible contact form.

### Q2: CSS Styling and Layout
- **Single External File:** `css/style.css` linked on every page.
- **Flexbox:** Implemented for header branding, top navigation menu, and footer links.
- **CSS Grid:** Implemented for the two-column media layout (`media.html`), home layout grid, and peer cards.
- **Positioning:** Sticky navigation header (`position: sticky; top: 0; z-index: 1000;`).
- **Styled Tables:** Custom headers, border styling, alternating row striping, and interactive row hover effects (`tbody tr:hover`).
- **Styled Form:** Fluid input fields, focus rings, border-radius, and interactive submit buttons.
- **Responsive 375px:** Validated with media queries; zero horizontal overflow or scrolling on mobile viewports.
- **Zero JavaScript:** 100% pure HTML and CSS.

---

## Deployment via GitHub Pages
1. Push project files to a public GitHub repository.
2. Navigate to **Settings** → **Pages**.
3. Under **Branch**, select `main` and root directory `/`.
4. Click **Save**; the site will be published at `https://<username>.github.io/<repo-name>/`.
