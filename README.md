# 🌐 Nayyab Gul — Personal Portfolio Website

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)](https://nayyab-gul-code.github.io)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat)]()

> A fully responsive, modern personal portfolio website built with pure HTML and CSS — hosted for free on GitHub Pages.

🔗 **Live Website:** [(https://nayyab-gul-code.github.io/)]
(https://nayyab-gul-code.github.io/)

---

## 📌 About This Project

This is my personal portfolio website built from scratch using only **HTML5** and **CSS3** — no frameworks, no libraries, no backend. It is designed to showcase my skills, projects, and contact information in a clean and professional way.

The website is completely **free to host** using GitHub Pages, which means anyone can visit it from anywhere in the world using just the URL.

---

## ✨ Features

- ✅ Fully responsive — works on mobile, tablet, and desktop
- ✅ Sticky navigation bar with smooth scroll
- ✅ Hero section with animated avatar ring
- ✅ Stats bar showing experience and achievements
- ✅ Projects section with hover card effects
- ✅ Skills section with animated progress bars
- ✅ Contact section with email button
- ✅ Clean footer with social media links
- ✅ CSS entrance animations and transitions
- ✅ Google Fonts integration (Playfair Display + DM Sans)
- ✅ No JavaScript required — pure HTML & CSS only

---

## 🗂️ Project Structure

```
nayyab-gul-code.github.io/
│
├── index.html        ← Main website file (homepage)
└── README.md         ← Project documentation (this file)
```

> **Note:** GitHub Pages automatically serves `index.html` as the homepage. The file must be named exactly `index.html`.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and content |
| CSS3 | Styling, layout, and animations |
| Google Fonts | Custom typography (Playfair Display, DM Sans) |
| CSS Grid | Responsive multi-column layouts |
| CSS Animations | FadeUp entrance, spinning avatar ring |
| GitHub Pages | Free static website hosting |

---

## 📐 Website Sections

### 1. Navigation Bar
A sticky top navbar that stays visible while the user scrolls. It contains the logo on the left and navigation links (Work, Skills, Contact) on the right. On mobile screens the links are hidden to keep the design clean.

### 2. Hero Section
The very first thing visitors see when they open the website. It contains a bold headline, a short description of who I am, two call-to-action buttons (View My Work and Get In Touch), and an animated circular avatar displaying the initials "NG" with a spinning dashed border ring.

### 3. Stats Bar
A horizontal strip displaying four key achievement numbers — Years of Experience, Projects Done, Happy Clients, and Client Satisfaction — laid out in an equal 4-column grid with dividers between each stat.

### 4. Selected Work
A project showcase section with four cards arranged in a CSS grid. The first card is a "featured" card that spans two columns and is larger than the rest. Each card shows a colorful gradient thumbnail, a category tag, a project title, and a short description. Cards lift up on hover with a shadow effect.

### 5. Skills & Tools
Eight skill cards arranged in a 4-column grid. Each card displays an emoji icon representing the skill, the skill name, and a thin red progress bar at the bottom showing the proficiency level. Cards highlight in red on hover.

### 6. Contact Section
A full-width dark banner section with a large heading, a short invitation message, and a prominent "Say Hello" button that opens the user's email client with my address pre-filled.

### 7. Footer
A simple two-column footer containing the copyright notice on the left and social media links (GitHub, LinkedIn, Twitter) on the right.

---

## 🎨 Design Decisions

**Color Palette**
The website uses a warm off-white background (`#f7f4ee`) with deep black (`#111111`) for text and bold red (`#c8392b`) as the accent color. This combination creates a premium, editorial, magazine-like feel rather than a typical tech portfolio look.

**Typography**
`Playfair Display` — a high-contrast serif font — is used for all headings to give the design a refined and sophisticated appearance. `DM Sans` is used for all body text because it is clean, modern, and highly readable at small sizes.

**Layout**
CSS Grid is used throughout the entire page for all multi-column layouts. This removes the need for any external CSS framework like Bootstrap and keeps the code lightweight and fast.

**Animations**
A subtle `fadeUp` keyframe animation plays when the page loads, making the hero section slide in smoothly from below. The avatar ring has a slow continuous `spin` animation. Hover states on cards and buttons use `transform: translateY()` for a smooth lift effect.

---

## 🚀 How to Deploy on GitHub Pages

**Step 1 — Create a GitHub Repository**
- Go to [github.com](https://github.com) and sign in
- Click the **"+"** button at the top right → select **"New repository"**
- Set the repository name to exactly: `nayyab_gul-code.github.io`
- Set visibility to **Public**
- Click **"Create repository"**

**Step 2 — Upload the Files**
- Inside the new repository, click **"Add file"** → **"Upload files"**
- Upload both `index.html` and `README.md`
- Scroll down and click **"Commit changes"**

**Step 3 — Enable GitHub Pages**
- Click the **"Settings"** tab inside your repository
- In the left sidebar, click **"Pages"**
- Under the *Branch* section, select `main` from the dropdown
- Click **"Save"**

**Step 4 — Visit Your Live Website**
- Wait 2–3 minutes for GitHub to build and deploy the site
- Open your browser and visit:
  ```
  https://nayyab-gul-code.github.io
  ```

---

## ✏️ How to Customize

To make this website your own, open `index.html` in any text editor (like VS Code or Notepad) and update the following parts:

| What to Change | Where to Find It in the Code |
|----------------|------------------------------|
| Your name in navbar | `<div class="nav-logo">` |
| Hero headline text | `<h1>` inside `.hero` section |
| Short bio description | `<p class="hero-sub">` |
| Avatar initials | `content: 'NG'` inside `.avatar-ring::after` in CSS |
| Stats numbers | `<span class="stat-num">` values |
| Project titles | `<h3 class="project-title">` in each project card |
| Project descriptions | `<p class="project-desc">` in each project card |
| Skill names | `<div class="skill-name">` in each skill card |
| Skill bar percentage | `style="width: 90%"` on each `.skill-bar` |
| Contact email address | `href="mailto:your@email.com"` in contact section |
| Footer copyright name | `<span>` inside `<footer>` |
| Social media links | `<a href="#">` tags inside `<footer>` |

---

## 📱 Browser Compatibility

| Browser | Supported |
|---------|-----------|
| Google Chrome | ✅ Yes |
| Mozilla Firefox | ✅ Yes |
| Microsoft Edge | ✅ Yes |
| Safari (macOS / iOS) | ✅ Yes |
| Opera | ✅ Yes |

---

## 📄 License

This project is open source and completely free to use. You are welcome to clone, fork, or use this code as a starting template for your own personal portfolio.

---

## 👩‍💻 Author

**Nayyab Gul**
- GitHub: [@nayyab-gul-code](https://github.com/nayyab-gul-code)
- Live Site: [nayyab-gul-code.github.io](https://nayyab-gul-code.github.io)

---

*Made with ❤️ — Hosted for free on GitHub Pages*
