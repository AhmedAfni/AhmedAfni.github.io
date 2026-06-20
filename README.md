# Afni Ahamed - Personal Portfolio Website

[![GitHub Pages Deployment](https://github.com/AhmedAfni/AhmedAfni.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/AhmedAfni/AhmedAfni.github.io/actions/workflows/pages/pages-build-deployment)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A premium, interactive, and responsive portfolio website built for **Afni Ahamed**, a Software Engineer specializing in craft-oriented backend and full-stack development.

The website is hosted live at: **[ahmedafni.github.io](https://ahmedafni.github.io/)**

---

## ✨ Features

- **Dynamic IDE Mockup**: An interactive typing effect simulator displaying custom code snippets inside a high-fidelity code editor interface.
- **Floating Pill Navbar**: Sleek, modern floating navigation bar designed with glassmorphism effects (`backdrop-blur`).
- **Interactive Mouse Spotlight**: Custom cursor-following glow element that highlights content dynamically.
- **Comprehensive Sections**:
  - **About**: Bio and background summary.
  - **Education**: BEng (Hons) Software Engineering details.
  - **Stack**: Highlighted programming languages, frameworks, and tools.
  - **Work/Projects**: Showcase of selected work.
  - **Contact**: Reach out details.
- **Modern Typography & Aesthetics**: Incorporates premium fonts (Bricolage Grotesque, Inter, JetBrains Mono) with rich HSL colors and customized TailwindCSS styling.

---

## 🛠️ Tech Stack & Styling

- **Core**: HTML5, Vanilla JavaScript (for animations and interactivity)
- **Styling**: TailwindCSS (loaded via CDN)
- **Fonts**: Google Fonts (Bricolage Grotesque, Inter, JetBrains Mono)
- **Deployment**: GitHub Pages

---

## 🚀 How to Run Locally

Since this is a static website, you can run it locally with any simple HTTP server.

### Option 1: VS Code Live Server (Easiest)
1. Open the project folder in VS Code.
2. Click **Go Live** in the bottom status bar (requires the "Live Server" extension).
3. The browser will automatically open the site at `http://127.0.0.1:5500/index.html`.

### Option 2: Using Node.js (`http-server` or `serve`)
If you have Node.js installed, run one of the following commands in the project directory:
```bash
# Using npx
npx http-server .

# Or using serve
npx serve .
```
Open your browser and navigate to the local port outputted by the terminal.

### Option 3: Python Built-in Server
If you have Python installed, run:
```bash
# Python 3
python -m http.server 8000
```
Open `http://localhost:8000` in your web browser.

---

## 🔄 CI/CD & Deployment

This project uses the built-in **GitHub Pages CI/CD pipeline**:
1. When changes are pushed or merged into the default deployment branch (`main`), GitHub automatically triggers the **GitHub Pages Build & Deployment** workflow.
2. The pipeline compiles and updates the live site within a minute.
3. You can monitor deployments under the **Actions** tab in the GitHub repository.

---

## 📄 License

This repository is licensed under the MIT License. Feel free to use it as a reference for your own portfolio!
