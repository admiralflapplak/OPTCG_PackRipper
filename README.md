# 🏴‍☠️ One Piece TCG Pack Ripper

A highly interactive, physics-based One Piece Trading Card Game pack opening simulator. Built with vanilla HTML/CSS/JS, focusing on "juice," tactile feel, and responsive mobile design.

## 🌟 Features

### 📦 Pack Opening Experience
* **Realistic Physics:** 3D CSS packs that shake, rip, and scatter "ghost packs" based on simulated physics.
* **Dynamic Rarity Logic:** Simulates real pull rates including Double Rares, Leader Packs, and "God Packs" (Manga/Signature hits).
* **Juicy Animations:**
    * **Toss:** Cards slide off-screen and rotate as if physically thrown.
    * **Keep:** Cards shrink and fly "into" your binder.
    * **Vacuum Slide:** Remaining packs slide up smoothly to fill empty slots.
* **Particle Effects:** Legendary pulls trigger gold particle explosions and screen flash effects.

### 📱 Mobile Native Feel
* **Responsive Design:** Fully fluid grid that adapts from desktop monitors down to mobile phones (2-column layout).
* **Gyroscope Tilt:** Uses the device's accelerometer to physically tilt cards and shimmer the holographic glare when you move your phone.
* **Touch Controls:** Large, thumb-friendly stepper buttons for pack selection and a "Bottom Sheet" tooltip system for mobile readability.

### 📖 Collection Management (Binder)
* **Persistent Save:** Your collection is automatically saved to LocalStorage.
* **Import/Export:** Back up your collection to a JSON file or move it between devices.
* **Filtering:** Sort your binder by Set (OP-01 to OP-14, EB, PRB), Rarity (Manga, Alt Art, SEC), or Name search.
* **Safe Hydration:** Prevents data loss if the card database fails to load by creating temporary placeholders.

## 🎮 Controls

### Desktop
* **Hover:** Tilt cards and activate holographic glare.
* **Click Pack:** Shake and rip open.
* **Click Card:** Flip to reveal (triggers sound effects).
* **Right Click / Hover:** View card details in a smart tooltip.

### Mobile
* **Tap Pack:** Open.
* **Tilt Phone:** Activate holographic glare (Gyroscope).
* **Tap Card:** Flip to reveal or view details in the bottom sheet.

## 🚀 How to Run

No build process or installation required. This is a pure static web application.

1.  Clone the repository.
2.  Open `index.html` in any modern web browser.
3.  That's it!

## 🛠️ Tech Stack
* **Core:** HTML5, CSS3 (Advanced Animations & 3D Transforms), Vanilla JavaScript (ES6+).
* **Assets:** Canvas Confetti (for particle effects).
* **Data:** Fetches card data dynamically from the TCGCSV API.

## ⚠️ Disclaimer
This is a fan-made project and is not affiliated with Bandai Namco or the One Piece franchise. All card images and names are property of their respective owners.
