# EscapeBored 🌌

**Escape scrolling, find focus.**

EscapeBored is a premium, mobile-first mindful dashboard designed to rescue you from doomscrolling and guide you into focused, high-value mindfulness activities. By replacing screen distractions with curated, mood-matched activities and rich audio-visual environments, EscapeBored converts aimless screen time into mindful focus.

---

## 🚀 Key Features

### 1. Minimalist, Guided Onboarding
* **Decision Fatigue Prevention:** Hides all widgets by default. Instead of showing multiple competing tools, users are welcomed with a single primary action: **"I'm Bored — Give Me Something To Do"**.
* **Activity Matching Engine:** Matches users to a custom-tailored activity based on their current psychological mood (Bored, Curious, Restless, Stressed, Unmotivated) and available time (ranging from 30 seconds to 15 minutes).
* **Surprise & Curiosity:** Generates 100+ highly engaging, novel prompts (e.g., strange historical paradoxes, lateral mysteries, somatic exercises, and micromoves).

### 2. High-Fidelity Workspace Backgrounds
* **Vibrant Pixel Art Wallpaper:** Separated background image layers with color boosts (`contrast` and `saturation` filters) rendering at native resolution.
* **Optimal Legibility:** Keeps overlays subtle (15% dark opacity) while using dense glassmorphic containers (`rgba(15, 15, 15, 0.65)` with heavy blur) so text is always highly readable.

### 3. Deep Lofi & Ambient Sound Mixer
* **Audio Presets:** Instantly toggle curated environments like *Deep Focus*, *Rainy Cafe*, *Cozy Study*, or *Night Coding*.
* **Independent Mix Controls:** Adjust sliders for music volume, rain volume, and ambient drone volume.
* **Transitions:** Smooth fade-ins and fade-outs to prevent abrupt audio starts.

### 4. Upgraded Interactive Mindfulness Tools
* ⌨️ **Typing Sprint:** Features Personal Best tracking, a deterministic Daily Challenge Quote generator, an unlockable trophy achievements drawer, and a live SVG sparkline chart of WPM performance.
* 🎨 **Creative Doodle Canvas:** Provides a shuffle deck of 30+ surreal prompts to bypass blank-page anxiety, plus a Daily Creativity Challenge with bonus CP points.
* 📓 **Clarity Journal:** Generates deep philosophical writing prompts client-side and tracks daily reflection habits using streak flame indicators (`🔥`).
* ⏱️ **Focus Sprint Timer:** A dual-pane widget including a pomodoro timer and a **Focus Stats** view showcasing daily target dials, an SVG weekly trend bar chart, and a soundscapes distribution graph.

---

## 🛠️ Technology Stack
* **Framework:** [Astro](https://astro.build/) (Static Site Generation)
* **Styling:** CSS & [Tailwind CSS](https://tailwindcss.com/)
* **State & Data Persistence:** LocalStorage (fully client-side, zero server latency)

---

## 🧞 Commands

All commands are run from the root of the project:

| Command | Action |
| :--- | :--- |
| `npm install` | Installs dependencies |
| `npm run dev` | Starts local development server at `localhost:4321` |
| `npm run build` | Builds the production bundle to `./dist/` |
| `npm run preview` | Previews the build locally before deployment |
