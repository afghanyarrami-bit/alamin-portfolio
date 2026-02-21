# 🚀 Alamin Portfolio

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Alamin-blue?style=for-the-badge&logo=react&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)

**A modern, responsive personal portfolio website built with React**

[🌐 Live Demo](#) • [📸 Screenshots](#screenshots) • [🛠 Installation](#installation) • [📬 Contact](#contact)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contact](#contact)
- [License](#license)

---

## 👤 About

**alamin-portfolio** is a professional personal portfolio website for **Afghanyarrami-bit / Afghanyar**, a Frontend Developer based in 🇨🇭 Switzerland. This portfolio showcases projects, skills, experience, and contact information in a clean, modern, and fully responsive design.

---

## ✨ Features

- ⚡ **Fast & Responsive** — Works perfectly on mobile, tablet, and desktop
- 🎨 **Modern UI** — Clean design with smooth animations
- 📱 **Mobile First** — Designed for all screen sizes
- 🔥 **Reusable Components** — Shared Header, Footer, Heading components
- 🏠 **Hero Section** — Eye-catching landing banner
- 👤 **About Page** — Personal introduction and background
- 🗂 **Portfolio Page** — Showcase of all major projects with live links
- 🛠 **Services Page** — Services offered as a Frontend Developer
- 📝 **Blog Page** — Articles and posts
- 🔢 **Counter Section** — Animated statistics and numbers
- ⭐ **Testimonials** — Client reviews and feedback
- 📬 **Contact Page** — Functional contact form with validation

---

## 🛠 Tech Stack

| Technology | Usage |
|---|---|
| ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) | Frontend Framework |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Programming Language |
| ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) | Styling |
| ![Lucide React](https://img.shields.io/badge/Lucide_React-FF6B6B?style=flat) | Icons |
| ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) | Build Tool |
| ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) | Version Control |

---

## 📸 Screenshots
![Alamin Portfolio](https://github.com/user-attachments/assets/296bd9ae-7f48-4374-a393-9854464d8918)

```
📁 screenshots/
├── home.png
├── projects.png
├── skills.png
└── contact.png
```

---

## ⚙️ Installation

Follow these steps to run the project locally:

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

### Steps

**1. Clone the repository**

```bash
git clone https://github.com/afghanyarrami-bit/alamin-portfolio.git
```

**2. Navigate to the project folder**

```bash
cd alamin-portfolio
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the development server**

```bash
npm run dev
```

**5. Open in browser**

```
http://localhost:5173
```

---

## 📁 Project Structure

```
alamin-portfolio/
│
├── 📁 src/
│   │
│   ├── 📁 components/
│   │   │
│   │   ├── 📁 common/                  # Shared/reusable components
│   │   │   ├── Footer.jsx              # Site footer
│   │   │   ├── Header.jsx              # Site header & navigation
│   │   │   └── Heading.jsx             # Reusable heading component
│   │   │
│   │   ├── 📁 data/                    # Data & assets
│   │   │   ├── 📁 images/
│   │   │   │   └── logo.png            # Project logo
│   │   │   └── dummydata.js            # Static data (projects, skills, etc.)
│   │   │
│   │   ├── 📁 home/                    # Home page components
│   │   │   ├── Hero.jsx                # Hero / banner section
│   │   │   └── Home.jsx                # Main home page layout
│   │   │
│   │   └── 📁 pages/                   # All page components
│   │       ├── About.jsx               # About me page
│   │       ├── Blog.jsx                # Blog page
│   │       ├── Contact.jsx             # Contact form page
│   │       ├── Counter.jsx             # Animated counters section
│   │       ├── Pages.jsx               # Pages router/wrapper
│   │       ├── Portfolio.jsx           # Portfolio / projects page
│   │       ├── Services.jsx            # Services offered page
│   │       └── Testimonials.jsx        # Client testimonials page
│   │
│   ├── App.css                         # Global styles
│   ├── App.js                          # Root app component
│   └── App.test.js                     # App tests
│
├── .gitignore
├── index.html
├── package.json
└── README.md
```

---

## 🚀 Usage

### Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

### Customize the Portfolio

To personalize this portfolio with your own data:

1. Open `src/data/HeaderData.js`
2. Update your personal info, projects, and skills
3. Replace images in `src/assets/images/`
4. Update contact information in `Contact.jsx`

---

## 🌍 Deployment

### Deploy to Vercel (Recommended)

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

### Deploy to Netlify

```bash
# Build the project
npm run build

# Drag and drop the dist/ folder to netlify.com
```

### Deploy to GitHub Pages

```bash
# Install gh-pages
npm install --save-dev gh-pages

# Add to package.json scripts:
# "deploy": "gh-pages -d dist"

npm run build
npm run deploy
```

---

## 📬 Contact

<div align="center">

**Afghanyar** — Frontend Developer 🇨🇭 Switzerland

[![GitHub](https://img.shields.io/badge/GitHub-afghanyarrami--bit-black?style=for-the-badge&logo=github)](https://github.com/afghanyarrami-bit)
[![Upwork](https://img.shields.io/badge/Upwork-Available-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use it as a template for your own portfolio!

```
MIT License © 2025 Afghanyar (afghanyarrami-bit)
```

---

<div align="center">

**Made with ❤️ in Switzerland 🇨🇭**

⭐ If you like this project, please give it a **star** on GitHub!

</div>
