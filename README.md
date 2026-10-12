# B. M. Muktadir Wafi — Personal Portfolio & CV Website

A modern, high-performance personal portfolio website built with clean HTML5, CSS3, and JavaScript, featuring dark mode, glowing accents, smooth micro-interactions, responsive mobile navigation, and seamless integration with LinkedIn, GitHub, and a downloadable CV.

---

## 🌟 Highlights & Features

- **Hero & Identity**: Features B. M. Muktadir Wafi's signature bio tagline, live typewriter role animation, quick access buttons to GitHub, LinkedIn, and CV download.
- **Integrated Profiles**:
  - **GitHub**: [github.com/RedRabies](https://github.com/RedRabies)
  - **LinkedIn**: [linkedin.com/in/b-m-muktadir-wafi-406b11439/](https://www.linkedin.com/in/b-m-muktadir-wafi-406b11439/)
- **Featured Projects**:
  - **SentryAid**: Scalable, decentralized public safety & emergency response network with real-time GPS volunteer dispatch and dynamic danger heatmaps.
  - **TicTacToe**: Interactive grid game with turn dynamics and game state evaluation.
  - **Cache-Conscious Systems**: Memory hierarchy analysis and RISC-V cache optimization.
- **Skills Categorizer**: Interactive category filters (Languages, Backend & Real-Time, Frontend, Systems & Tools).
- **Curriculum Vitae (CV)**:
  - Interactive on-page qualifications and education timeline.
  - One-click **Download PDF CV** button linking directly to `assets/cv.pdf`.
- **Contact Form**: Prepares a direct email draft and provides quick connection cards.
- **Aesthetic**: Modern dark mode by default with light/dark theme switch, ambient particle glow effects, and responsive mobile layout.

---

## 🚀 How to Run Locally

You don't need any complex installation or build step!

### Option 1: Direct Open
Double-click `index.html` in your file explorer to open it directly in any modern browser.

### Option 2: Local HTTP Server (Optional)
Run via Node.js or Python from this directory:

```bash
# Using Node.js (npx serve)
npx serve .

# Or using Python (if installed)
python -m http.server 3000
```
Then visit `http://localhost:3000`.

---

## 📂 File Structure

```
GitLink/
├── index.html        # Main markup and section layout
├── style.css         # Styling, dark/light themes, animations & responsive grid
├── script.js         # Typewriter effect, theme switcher, filters & interactions
├── README.md         # Project documentation
└── assets/
    ├── profile.jpg   # Local profile photo (synced from GitHub)
    └── cv.pdf        # Downloadable PDF CV (replace anytime with your updated CV)
```

---

## 🌐 Deploy to GitHub Pages (Free)

1. Initialize a git repository if not already done:
   ```bash
   git init
   git add .
   git commit -m "feat: initial portfolio release"
   ```
2. Create a new repository on your GitHub account (`RedRabies/portfolio` or `RedRabies/RedRabies.github.io`).
3. Push your code:
   ```bash
   git branch -M main
   git remote add origin https://github.com/RedRabies/YOUR-REPO-NAME.git
   git push -u origin main
   ```
4. In GitHub repository settings, go to **Pages** -> Select **Branch: main** -> **Save**. Your site will be live on the web!
