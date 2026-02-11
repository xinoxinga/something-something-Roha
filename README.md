# Valentine's Day Interactive Proposal: The Roha Edition 💖

A personalized, "prank-style" web application built to create a fun and interactive Valentine's Day proposal. This version features custom illustrations, multi-stage animations, and a "No" button designed to challenge the user before reveal.

## 🚀 Live Link
View the live project here: 
`https://xinoxinga.github.io/something-something-Roha/)New Text Document.html`

## ✨ Features
* **Trapped "No" Button Logic:** The "No" button intelligently jumps to random coordinates strictly within the boundaries of the white UI box, making it impossible to click while maintaining a clean layout.
* **Personalized Messaging:** Custom deep-pink typography for **Roha**, featuring a playful "dangerous" reveal message upon success.
* **Multi-Asset Animation:** * Starts with a custom mouse illustration (`image_31b797.png`).
  * Transitions to a celebratory cat GIF and a playful "Bubu Dudu" reaction GIF on "Yes".
* **Glassmorphism UI:** A modern, rounded "white-box" design with a soft pink background and drop shadows.

## 🛠️ Technical Implementation
* **Positioning:** Uses `position: relative` on the container and `position: absolute` on the button to keep the button "trapped" within the UI box.
* **Event Listeners:** Utilizes JavaScript `mouseover` events to trigger the movement and `click` events to handle the final state change.
* **Dynamic DOM Manipulation:** Replaces the internal HTML of the main box to show the final message and GIFs without a page reload.

## 📂 Required Files
Ensure the following files are in the root directory for the site to function correctly:
1. `New Text Document.html`
2. `image_31b797.png`
3. `cat_celebration.gif`
4. `bubu-bubu-dudu.gif`

## 📝 Usage
1. Upload all assets to a GitHub repository.
2. Enable **GitHub Pages** in the repository settings.
3. Share the generated link for the full interactive experience!
