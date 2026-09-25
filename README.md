# FocusPulse — Pomodoro Timer & Focus Companion

> A minimalist, responsive, mobile-first Pomodoro web application featuring procedural Web Audio soundscapes, screen wake-lock, task management, and offline PWA capability.

---

## 🌟 Key Features

- **🍅 Classic Pomodoro Sets**: 25 min focus / 5 min short break / 15 min long break with dynamic round tracker dots.
- **📱 Mobile-First Design**: Optimized touch targets, haptic feedback (`navigator.vibrate`), and notch/safe-area spacing.
- **💡 Screen Wake Lock**: Keeps phone screens awake during study sessions to prevent sleep interruptions.
- **🎧 Procedural Ambient Audio**: Synthesized in real-time using the Web Audio API without internet dependencies:
  - 528Hz Solfeggio singing bowl session bell
  - Deep Brownian noise
  - Gentle rain wash
  - 432Hz calming drone
  - Optional clock tick
- **📝 Task Management**: Active task spotlight, pomodoro estimation counters, and completion tracking.
- **📊 Productivity Stats**: Focus minute counter, session totals, and daily streaks saved in `localStorage`.

---

## 📦 Included Favicons & Brand Assets

| File | Resolution | Target Platform / Purpose |
| :--- | :--- | :--- |
| `favicon.svg` | Scalable Vector | Modern desktop & mobile browsers |
| `favicon.ico` | 32×32 PNG container | Legacy browsers & fallback tabs |
| `favicon-16x16.png` | 16×16 px | Standard browser tab icon |
| `favicon-32x32.png` | 32×32 px | High-DPI browser tab icon |
| `apple-touch-icon.png` | 180×180 px | iOS Home Screen shortcut & bookmark |
| `android-chrome-192x192.png` | 192×192 px | Android home screen icon |
| `android-chrome-512x512.png` | 512×512 px | PWA splash screen & app install prompt |
| `site.webmanifest` | JSON metadata | Web app manifest for PWA installability |

---

## 🚀 Setup & Integration

FocusPulse is completely self-contained in a single HTML file with no build pipeline required.

### 1. Link Assets in HTML <head>
```html
<!-- FocusPulse Favicons -->
<link rel="icon" type="image/svg+xml" href="favicon.svg">
<link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
<link rel="manifest" href="site.webmanifest">
<meta name="theme-color" content="#ef4444">
```

### 2. Local Preview
```bash
# Python 3
python3 -m http.server 8000
```
Visit `http://localhost:8000`.

### 3. Deploy to GitHub Pages / Vercel / Netlify
Place `index.html`, `site.webmanifest`, and the favicon images into the root of your repository and publish.

---

## 📲 Install as an App on Phone (PWA)

- **iPhone (iOS Safari)**:
  1. Open the website in Safari.
  2. Tap the **Share** button (square with upward arrow).
  3. Select **Add to Home Screen**.
- **Android (Chrome)**:
  1. Open the website in Chrome.
  2. Tap the three dots menu in the top right.
  3. Tap **Install app** or **Add to Home screen**.

---

## 📄 License
MIT License. Free to use, modify, and distribute.
