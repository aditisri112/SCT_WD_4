# 🌸 To-Do Web App

A clean, distraction-free, and aesthetically pleasing To-Do Web Application designed with soft pastel tones, fluid micro-interactions, and a minimalist human-centric design. Built as a single-file architecture (`HTML5`, `CSS3`, and `Vanilla JS`), it runs instantly in any browser without needing setup or dependencies.

---

## ✨ Key Features

- **🎨 Pastel Aesthetics:** Handpicked organic pastel color palette designed to reduce visual fatigue and maximize daily focus. No robotic, overly technical, or rigid "AI-style" frameworks.
- **📁 List Organization:** Sort tasks seamlessly into native lists (**Personal, Work, Shopping, Ideas**) using an elegant, swipeable horizontal tab manager.
- **⏰ Smart Scheduling:** Assign custom dates and times to any task to track upcoming deadlines cleanly.
- **✏️ Inline Editing:** Edit your tasks natively inside the element—no jarring modal pop-ups or clunky dialogue screens.
- **🔄 Local Storage Persistence:** Your workspace auto-saves in the browser instantly. Refresh or close your window without ever losing your progress.
- **📱 True Fluid Responsiveness:** Completely optimized for layout changes, scaling beautifully from desktop down to mobile viewports.

---

## 🛠️ Architecture & Tech Stack

This project is highly modularized into **one single file** for lightweight execution and instant portability.
- **Markup:** Semantic HTML5
- **Styling:** Custom CSS3 with CSS Variables, Custom Checkbox Overrides, Custom Micro-animations, and Glassmorphic Blur Panels
- **Behavior:** Pure Vanilla JavaScript (ES6+), Event Delegation, Native Object Mapping
- **Typography:** `Plus Jakarta Sans` via Google Fonts

---

## 🚀 Quick Start / How to Run

Because the web app requires no bundlers, compilation, or web servers, running it is incredibly simple:

1. **Clone or Download** the codebase.
2. Save the code as `index.html`.
3. **Double-click** the `index.html` file to open it instantly in your web browser of choice (Chrome, Safari, Edge, Firefox).

---

## 📂 Code Structure Overview

```html
index.html
 ├── <head>          ├── <style>         ├── <body>          └── <script>        ```

---

## 💡 How to Interact with the App

- **Creating Tasks:** Enter your task name, choose an optional completion target date/time, select your desired Category Tab, and click **Add**.
- **Switching Views:** Click on any category tab (`All Tasks`, `Personal`, `Work`, `Shopping`, `Ideas`) to filter out your active list dynamically. 
- **Completing Items:** Tap or click the custom checkmark box. The task will smoothly fade out and apply a soft cross-out decoration.
- **Updating Items:** Click the 📝 pencil icon to edit your text directly on the line. Click the checkmark icon or press `Enter` to lock it in.
- **Removing Items:** Press the 🗑️ trash icon to instantly erase a task from your system.

---

## 📝 Future Feature Roadmap

If you plan to scale this project further, here are great human-centric additions to build next:
- [ ] **Dark Mode Integration:** Soft midnight pastels for low-light environments.
- [ ] **Custom Lists:** Allow users to type and generate brand new custom-colored categories dynamically.
- [ ] **Drag and Drop Sorting:** Implementing native HTML5 Drag and Drop APIs to manually order priorities.
- [ ] **Progress Indicators:** A subtle donut chart or linear progress bar showing today's percentage of completion.
