# 888-fluid-tracker
A lightweight Progressive Web App (PWA) for fluid 24-hour daily time budgeting (8h Work, 8h Personal, 8h Sleep).
# 8/8/8 Fluid Time Tracker (PWA)

A responsive, single-file Progressive Web App designed for flexible 24-hour daily time budgeting based on the **8/8/8 rule** (8 hours of Work, 8 hours of Personal Time, and 8 hours of Sleep). 

Unlike traditional rigid calendar planners, this tracker lets you log time dynamically using live stopwatches, allowing you to pause, switch tasks, and accumulate time throughout the day without strict hour blocks.

---

## Key Features

* **3 Active State Timers:** Live stopwatches for Work, Personal, and Sleep categories. Starting one timer automatically pauses any other active timer.
* **Screen Lock Delta Tracking:** Uses `Date.now()` timestamp differentials rather than simple seconds counting. Timers remain 100% accurate even when your mobile screen locks or the browser goes to the background.
* **Real-time Progress Bars:** Visual progress tracking against your 8-hour target ($8\text{h} = 28,800\text{ seconds}$) for each budget category.
* **Midnight Auto-Reset & History:** Automatically archives yesterday's total times into local history at midnight and clears active counters for the new day.
* **Progressive Web App (PWA):** Features an embedded Data URI manifest allowing you to **Add to Home Screen** on Android/iOS for full-screen offline use.
* **Zero Dependencies:** Built purely with single-file HTML5, CSS3, and modern JavaScript using `localStorage`.

---

## How to Install on Mobile

1. Open the live hosted URL in **Google Chrome** on Android or **Safari** on iOS.
2. Tap the browser menu (`⋮` on Chrome / Share button on Safari).
3. Select **Add to Home Screen** (or **Install App**).
4. Launch the **888Tracker** icon directly from your home screen.

---

## Local Development

Simply download or clone the repository and open `index.html` in any web browser:

```bash
git clone [https://github.com/YOUR-USERNAME/888-fluid-tracker.git](https://github.com/YOUR-USERNAME/888-fluid-tracker.git)
cd 888-fluid-tracker
# Open index.html in your browser
