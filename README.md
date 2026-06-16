# Bhakti Kajalkar — Developer Portfolio

A production-quality personal portfolio website built with pure **HTML5** and **CSS3** — no frameworks, no JavaScript, no external CSS libraries.

---

## Overview

This portfolio was created as part of an internship project to demonstrate frontend development skills including semantic markup, CSS architecture, responsive design, and accessibility best practices.

---

## Features

- **Pure HTML5 + CSS3** — zero JavaScript, zero frameworks
- **Fully responsive** — works flawlessly on mobile, tablet, and desktop
- **CSS-only mobile navigation** — hamburger menu using the checkbox trick
- **CSS Custom Properties** — centralized design token system
- **Smooth hover interactions** — cards, buttons, nav links, icons
- **Accessible** — semantic HTML5, proper heading hierarchy, ARIA labels, skip link, keyboard navigation, focus styles
- **Performance-first** — no render-blocking scripts, minimal external dependencies
- **Google Fonts** — Poppins via a single stylesheet link
- **Inline SVG icons** — no icon font dependency, crisp at all sizes
- **Respects reduced motion** — `prefers-reduced-motion` media query

---

## Sections

| Section  | Description                                            |
|----------|--------------------------------------------------------|
| Hero     | Full-screen intro with name, role, CTA buttons         |
| About    | Profile photo, personal bio, key facts                 |
| Skills   | Skill cards with SVG icons and hover elevation         |
| Projects | Project cards with tags, GitHub and demo links         |
| Contact  | Contact info, availability badge, and contact form     |

---

## Tech Stack

| Technology | Purpose                        |
|------------|--------------------------------|
| HTML5      | Semantic document structure    |
| CSS3       | Styling, layout, animations    |
| CSS Grid   | Section and card layouts       |
| Flexbox    | Component-level alignment      |
| CSS Variables | Design token system         |
| Google Fonts | Poppins typeface            |
| SVG        | Inline icons (no font needed)  |

---

## Folder Structure

```
portfolio/
│
├── index.html          # Main HTML file (single page)
├── style.css           # All styles — organized by section
├── README.md           # Project documentation
│
└── assets/
    └── images/
        └── profile.jpg # Your profile photo (replace this)
```

> **Note:** The `profile.jpg` at the project root is the profile image used in the hero and about sections. Place your own photo here and name it `profile.jpg`.

---

## Setup Instructions

**1. Clone the repository**

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

**2. Add your profile photo**

Replace `profile.jpg` in the root folder with your own photo.

**3. Update personal details**

Open `index.html` and update:
- Your name (search for `Bhakti Kajalkar`)
- Email address
- Phone number
- GitHub profile URL
- Project titles, descriptions, and links

**4. Preview locally**

Open `index.html` directly in any browser — no build step required.

Or use VS Code's Live Server extension:
```
Right-click index.html → Open with Live Server
```

---

## GitHub Pages Deployment

1. Push your project to a GitHub repository.

2. Go to **Settings → Pages**.

3. Under **Source**, select **Deploy from a branch**.

4. Choose `main` branch and `/ (root)` folder.

5. Click **Save**.

6. Your site will be live at:
   ```
   https://your-username.github.io/portfolio/
   ```

---

## Customization Guide

| What to change            | Where                                        |
|---------------------------|----------------------------------------------|
| Color accent              | `--accent` in `:root` inside `style.css`     |
| Background colors         | `--bg`, `--surface`, `--card` in `:root`     |
| Font                      | Google Fonts `<link>` in `<head>` of HTML    |
| Your name & intro         | `#hero` section in `index.html`              |
| About content             | `#about` section in `index.html`             |
| Skills                    | `#skills` section — edit `skill-card` items  |
| Projects                  | `#projects` section — edit `project-card` items |
| Contact details           | `#contact` section in `index.html`           |
| Form endpoint             | `action` attribute on `<form>` in contact section |

---

## Author

**Bhakti Kajalkar**
BSc IT Student — Mumbai University

- Email: [kajalkarbhakti@gmail.com](mailto:kajalkarbhakti@gmail.com)
- GitHub: [github.com/bhaktikajalkar](https://github.com/bhaktikajalkar)

---

## License

This project is open source and available for personal and educational use.
