# Nova Studio — Premium Product Design Partner

A premium, highly interactive digital agency portfolio landing page built for modern product, web, and brand design alignment. Rebranded from a creative design template, **Nova Studio** incorporates state-of-the-art visual aesthetics, custom mockups, and client-side interactions.

## 🚀 Key Features

* 🌓 **Reversible Dark/Light Mode Theme Toggle:** Integrated directly in the sidebar navigation with session persistence (stored in `localStorage`).
* 🎛️ **Pricing Retainer Scoper (Estimator):** Interactive toggle controls allowing clients to scope design and development retainer levels with a fluid, custom counting-up numeric animation.
* 🍱 **Asymmetrical Bento Grid:** A modern grid layout for agency values featuring a **Live Team Availability Clock** and active slots indicator.
* 🎠 **3D Featured Work Carousel:** A rotating, perspective-based 3D workspace cards carousel controlled with cursor sweeps and navigation triggers.
* 🖱️ **Morphing Trailing Custom Cursor:** A circular trailer that tracks pointer movements and expands with custom hover cues (e.g., `"DRAG"`, `"VIEW"`) over active spotlights.
* 📺 **Native HTML5 Loop Video:** A lightweight, unbranded vertical loop video (`assets/hero_video.mp4`) hosted locally to prevent iframe cookies, geoblocks, and domain embedding restrictions.
* ⚡ **Gradients & Gridlines:** Deep slate backgrounds, indigo/violet neon highlight gradients, and glowing vertical pulse vectors traveling down the grid lines.

---

## 🛠️ Technology Stack

* **Structure:** Semantic HTML5
* **Logic & Interactions:** Vanilla JavaScript (ES6)
* **Styling:** Tailwind CSS (loaded via CDN)
* **Icons:** Iconify Icons (using lightweight `<iconify-icon>` web components)
* **Visuals:** Custom PNG mockups + local MP4 background loops

---

## 📁 File Structure

```
├── assets/
│   ├── apex_invest.png        # Fintech Dashboard mockup
│   ├── pulsefit_app.png       # Mobile AI Fitness mockup
│   ├── clarity_saas.png       # SaaS analytics workspace mockup
│   ├── case_study_cover.png   # Abstract case study background cover
│   └── hero_video.mp4         # Local vertical 9:16 background loop
├── index.html                 # Main landing page entry point
├── original_site_source.html  # Reference source template code
└── .gitignore                 # Version control exclusions
```

---

## 💻 Local Setup & Preview

To run the project locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ArnavNah/nova-studio.git
   cd nova-studio
   ```

2. **Spin up a local server:**
   You can open the `index.html` directly in your browser, or run a simple local web server:
   
   *Using Node.js:*
   ```bash
   npx serve
   ```
   
   *Using Python:*
   ```bash
   python -m http.server 3000
   ```

3. Open **[http://localhost:3000](http://localhost:3000)** (or the port specified by your tool) in your web browser.
