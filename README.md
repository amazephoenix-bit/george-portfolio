# George CA – Game Portfolio 🎮

A small **game-style portfolio** built with HTML, CSS and JavaScript.  
Instead of a normal static page, you explore a tiny world with a character and three houses:

- 🏠 **Skills House** – shows my tech stack and tools  
- 🏠 **Projects House** – shows projects I’m building  
- 🏠 **About House** – shows who I am and how to contact me  

The goal of this project is to learn front-end structure while also having a fun way to present my Python / data skills.



## 🧩 Features

- **Intro screen** with “Enter World” button  
- **HUD (header)** showing name, role and version badge  
- **Night sky scene** with moon, stars, and glowing ground  
- **Three interactive houses**
  - click each house to change the content on the right panel  
- **Animated character** floating in the middle with my name  
- **Info panel** on the right with:
  - dynamic title, subtitle and badge  
  - chips for categories  
  - list of skills, projects, or about info  
- **Responsive layout** – works on desktop and mobile

---

## 🛠 Tech Stack

- **HTML5** – structure  
- **CSS3** – layout, gradients, animations  
- **JavaScript (Vanilla JS)** – handles:
  - intro hide
  - house switching
  - dynamic info panel updates

Everything is in **one file**: `index.html`.

---

## 📂 Project Structure
george-portfolio/
├── index.html # All HTML, CSS and JavaScript
└── README.md # This file



---

## ✏️ Customizing the Portfolio

All content (skills, projects, about) is controlled by a JavaScript object inside `index.html`:

---

## ✏️ Customizing the Portfolio

All content (skills, projects, about) is controlled by a JavaScript object inside `index.html`:
const houseContent = {
skills: { ... },
projects: { ... },
about: { ... },
};


### ✔ Edit Skills

Inside:
houseContent.skills.html

There is a `<ul>` list.  
Example Python skill with a project:
<li> <strong>Python</strong> <span class="project-meta">Comfortable writing scripts, functions, and working with data.</span> <span class="project-meta"><em>Project:</em> Built a Python automation script that cleans data and generates summary reports.</span> </li> ```

✔ Edit Projects

Inside:

houseContent.projects.html


Add more <li>...</li> blocks for each new project.

✔ Edit About

Inside:

houseContent.about.html


Update your story, goals, email, GitHub, and LinkedIn.


🚀 Run Locally
Option 1 — Open directly
Double-click index.html
→ opens in browser.
Option 2 — VS Code Live Server


Install Live Server extension


Right-click index.html → Open with Live Server



🌐 Deploying to GitHub Pages


Push index.html to GitHub


Go to Settings → Pages


Set:


Source: Deploy from a branch


Branch: main


Folder: / (root)




Save


Your site will appear at:
https://amazephoenix-bit.github.io/george-portfolio/


🔄 Update Steps (Git)
Whenever you change something:
git add index.html
git commit -m "Update portfolio content"
git push origin main

GitHub Pages updates automatically.

✨ Future Improvements


Add new houses (Certificates, Experience, Contact)


Add small character walking animation


Add sound effects


Add interactive transitions



👤 Author
George CA
A learner focused on Python, data analysis, and machine learning.
GitHub: https://github.com/amazephoenix-bit

---




---

## 🔗 Live Demo

GitHub Pages URL (after deployment):

```text
https://amazephoenix-bit.github.io/george-portfolio/




Open that link in your browser to view the portfolio.

---
