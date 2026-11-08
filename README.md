# Saniya Zahra — Personal Portfolio Website

A modern, responsive, and high-performance personal portfolio built with **HTML5, Tailwind CSS, Lucide Icons, and Vanilla JavaScript**. Designed specifically to highlight expertise in **Laravel Full-Stack Web Development** and **Flutter Mobile App Engineering**.

---

## 🌟 Features Included

1. **Hero Section with Dynamic Typing**:
   - Live dynamic typewriter effect highlighting core competencies (*Laravel Full-Stack Developer*, *Flutter Mobile App Engineer*, *REST API Architect*, *AI & Gemini Integration*).
   - "Open for Roles / Internships" live glowing availability badge.
   - Profile card with GitHub avatar, verified badges, and key metrics.

2. **Real-World Project Showcase (Interactive Filter)**:
   - Filterable tabs: `All Projects`, `Laravel Web`, `Flutter Mobile`, `AI & Special`.
   - Direct links to GitHub repositories:
     - 🤖 **Book My Beauty**: AI-powered Salon Booking system with Gemini API & role-based dashboards (Final Year Project).
     - 📱 **Saniya Writes (BlogHub App)**: Flutter Android app engineered with Clean Architecture, Riverpod, Dio & REST API.
     - 📰 **BlogHub Platform**: Multi-role publishing platform with Laravel 12, Sanctum REST API, and RBAC.
     - 🥛 **Organic Dairy**: Multi-vendor e-commerce platform built with Laravel 11 & MySQL.
     - 🏆 **KIU Sports Gala**: Tournament management & real-time live scoring portal.

3. **Skills Matrix**:
   - Backend & Databases (PHP, Laravel 11 & 12, MySQL, RESTful Sanctum APIs, RBAC).
   - Mobile Development (Flutter, Dart, Riverpod, Dio, Clean Architecture, GoRouter).
   - Frontend (HTML5, CSS3, JavaScript, Tailwind CSS, Bootstrap 5, Blade, Alpine.js).
   - Developer Tools (Git, GitHub, XAMPP, VS Code, Android Studio, Postman, Vite).
   - Spoken Languages (Urdu, Shina, English).

4. **Education & Certifications Timeline**:
   - BS Information Technology (2022 - 2026) — Karakoram International University (KIU), Gilgit.
   - FSc Pre-Engineering — Fatima Jinnah Govt Degree College for Women.
   - Matriculation (Science) — Govt Girls High School Oshikhandass.
   - Certifications: British Council Advanced Web Development, Specialized MERN Stack Program, KIU Sports Management, Nikon Photography, Pre-Primary Teaching.

5. **Direct CV Download & Contact Integration**:
   - Integrated `Saniya_Zahra_CV.pdf` inside `/assets` for one-click downloading.
   - One-click copy email & copy phone with toast notifications.
   - Direct interactive contact form with instant email draft generation.
   - Direct links to GitHub and LinkedIn profiles.

---

## 📁 File Structure

```text
saniya-portfolio/
│
├── index.html        # Main single-page portfolio layout
├── styles.css        # Custom animations, glassmorphism & glow styles
├── script.js         # Interactive filtering, typing effect, mobile menu & toast
├── README.md         # Documentation & deployment guide
└── assets/
    └── Saniya_Zahra_CV.pdf   # Your uploaded resume
```

---

## 🚀 How to Run Locally

### Option 1: Direct in Browser
Simply double-click the `index.html` file on your computer to open it directly in Chrome, Edge, or Firefox.

### Option 2: Live Server in VS Code
1. Open the `saniya-portfolio` folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and click **"Open with Live Server"**.

---

## 🌐 How to Deploy to GitHub Pages (100% Free)

You can host this portfolio live on the internet under your GitHub account for free!

### Step 1: Create a GitHub Repository
1. Go to [github.com/new](https://github.com/new).
2. Set the repository name to:
   - `portfolio` (your live site will be: `https://saniya378.github.io/portfolio`)
   - OR `Saniya378.github.io` (your live site will be: `https://saniya378.github.io`)
3. Make it **Public** and click **Create repository**.

### Step 2: Push your code to GitHub
Run the following commands in PowerShell inside the `saniya-portfolio` folder:

```bash
git init
git add .
git commit -m "Initial portfolio release"
git branch -M main
git remote add origin https://github.com/Saniya378/portfolio.git
git push -u origin main
```
*(Replace `portfolio.git` with your repository name)*

### Step 3: Turn on GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** > **Pages** (in the left sidebar).
3. Under **Branch**, select `main` and root `/`, then click **Save**.
4. In 1–2 minutes, your website is LIVE worldwide! 🎉

---

## ✏️ How to Customize Later
- **To update CV**: Replace `assets/Saniya_Zahra_CV.pdf` with your updated PDF keeping the same filename.
- **To add new projects**: Duplicate any `<div class="project-card ...">` block in `index.html` and update the title, description, and GitHub URL.

