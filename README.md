# 🌿 Barotopa

![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38BDF8?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES2024-F7DF1E?logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?logo=vercel&logoColor=white)

A modern web application built with **Next.js 15** and **Tailwind CSS**, deployed live on Vercel.

🔗 **Live Demo:** [barotopa.vercel.app](https://barotopa.vercel.app)

---

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Running the App](#-running-the-app)
- [Deployment](#-deployment)

---

## ✨ Features

- ⚡ Built with **Next.js 15** — fast, SEO-friendly web app
- 🎨 Styled with **Tailwind CSS** — utility-first responsive design
- 🎠 Smooth sliders with **Swiper.js**
- 📱 Fully **responsive** layout via `react-responsive`
- 🖼️ Rich icon support with **React Icons** & **Heroicons**
- 🚀 Deployed on **Vercel** with zero-config CI/CD

---

## 🛠️ Tech Stack

| Category     | Technology              |
|--------------|-------------------------|
| Framework    | Next.js 15              |
| UI Library   | React 18                |
| Styling      | Tailwind CSS 3.4        |
| Slider       | Swiper.js 11            |
| Icons        | React Icons 5 + Heroicons |
| Responsive   | react-responsive 10     |
| Deployment   | Vercel                  |

---

## 📁 Project Structure

```
barotopa/
├── public/              # Static assets (images, icons, fonts)
├── src/                 # Source code
│   ├── app/             # Next.js App Router (pages & layouts)
│   ├── components/      # Reusable UI components
│   └── styles/          # Global styles
├── .gitignore
├── jsconfig.json        # JS path aliases
├── next.config.mjs      # Next.js configuration
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.mjs   # PostCSS configuration
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/zamanRaffi/barotopa.git
cd barotopa
```

2. **Install dependencies**

```bash
npm install
```

---

## ▶️ Running the App

### Development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Other commands

```bash
# Production build
npm run build

# Start production server
npm start

# Lint check
npm run lint
```

---

## 🌐 Deployment

This project is deployed on **Vercel**. Every push to the `master` branch auto-deploys to production.

🔗 [barotopa.vercel.app](https://barotopa.vercel.app)

To deploy your own copy:

1. Push the repo to GitHub
2. Import to [Vercel](https://vercel.com)
3. Deploy with one click — no configuration needed

---

## 📦 Dependencies

```json
"next": "15.0.0"
"react": "^18.3.1"
"tailwindcss": "^3.4.1"
"swiper": "^11.1.14"
"react-icons": "^5.3.0"
"@heroicons/react": "^1.0.6"
"react-responsive": "^10.0.0"
```

---

## 📜 License

This project is private. All rights reserved.
