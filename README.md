# 💼 CareerHunt — Job Portal Website (Static Version)

CareerHunt is a modern, fully responsive **job portal website** built using **HTML**, **Tailwind CSS**, and **JavaScript**.  
It includes essential pages like job listings, resume uploads, employer job posting, and user sign-in — perfect for demonstrating a full professional front-end job platform.

[🌐 Live Demo](https://subhajitindia99das.github.io/CareerHunt/) • [📁 GitHub Repo](https://github.com/Subhajitindia99das/CareerHunt)

![GitHub stars](https://img.shields.io/github/stars/Subhajitindia99das/CareerHunt?style=social)
![GitHub forks](https://img.shields.io/github/forks/Subhajitindia99das/CareerHunt?style=social)
![GitHub language count](https://img.shields.io/github/languages/count/Subhajitindia99das/CareerHunt)

---

## 📌 Tech Stack Used

- 🧱 HTML5  
- 💨 Tailwind CSS (manually configured with Vite)  
- ⚙️ JavaScript (Vanilla)  
- 🎨 AOS (Animate on Scroll) Library  

---

## 🚀 Features

- Home page with clean hero section and CTA  
- Browse Jobs & Job Details pages  
- Upload Resume and Post a Job sections  
- Sign In / Sign Up UI pages  
- AOS-based scroll animations  
- Dark/Light mode toggle  
- Mobile-friendly navigation with hamburger menu  
- Responsive layout on all devices  
- Clean and modern UI with custom visuals

---

## 📁 Project File Structure

```plaintext
CareerHunt/
├── index.html
├── about.html
├── contact.html
├── jobs.html                <-- Browse Jobs Page
├── job-details.html
├── post-job.html
├── upload.html             <-- Upload Resume
├── sign-in.html
├── sign-up.html
├── dist/
│   └── output.css          <-- Final Tailwind compiled CSS
├── images/
│   ├── logo.png
│   ├── favicon.ico
│   ├── hero-banner.jpg
│   ├── postjob.jpg
│   └── ...                 <-- Other UI images (testimonials, icons, etc.)
├── js/
│   └── script.js           <-- Handles nav toggle, scroll animation, theme
├── css/
│   └── style.css           <-- Optional global styles if any
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── README.md               <-- With setup + project info
```

---

## 📦 Installation (Simple Steps)

> ⚠️ Tailwind CSS is manually configured. Use these steps to edit and preview the project locally.

1. **Clone the repository**
   ```bash
   git clone https://github.com/Subhajitindia99das/CareerHunt.git
   cd CareerHunt

2. **Install required packages**
   ```bash
    npm install

4. **Start Tailwind watcher to build CSS**
   ```bash
   npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

6. **Open the project**
  - Just open `index.html` in your browser.
  - You can use Live Server in VS Code for smooth reloads.
   
✅ Now you're ready to edit and preview your site locally!

## 🧑‍💻 Author
Made with ❤️ by Subhajit Das
📍 B.Tech CSE Student, MSIT Kolkata

## 📄 License
This project currently does not use any open-source license.
All rights reserved by the author.
