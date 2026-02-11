# Valentine's Day Interactive Proposal: The Roha Edition 💖

A personalized, full-experience web application built for a serious Valentine's Day proposal. This project combines interactive JavaScript logic, custom visual assets, and a synchronized audio reveal.

## 🚀 Live Link
View the live project here: 
`https://xinoxinga.github.io/something-something-Roha/New Text Document.html`

## ✨ New Features
* **Synchronized Audio Reveal:** A hidden audio player triggers automatically upon clicking "Yes."
* **Calibrated Audio Levels:** The music volume is hard-coded to 80% (0.8) to ensure a pleasant listening experience across different devices.
* **Trapped "No" Button Logic:** The "No" button remains trapped within the white glass container, preserving the UI layout while maintaining the playful interaction.
* **Multi-Stage Visuals:** * **State 1:** Custom mouse illustration (`image_31b797.png`).
    * **State 2:** Success celebration with `cat_celebration.gif` and a secondary `bubu-bubu-dudu.gif` reaction.

## 🛠️ Technical Details
* **Audio Handling:** Uses the HTML5 `<audio>` element with JavaScript-controlled `.play()` and `.volume` properties to bypass browser autoplay restrictions.
* **CSS Layout:** Employs `position: relative` on the parent container to act as a boundary for the `absolute` positioned runaway button.
* **Color Palette:** Specifically uses Deep Pink (`#d63384`) for the primary proposal text to enhance visibility and romantic tone.

## 📂 Required Files & Structure
For the site to function as intended, the following files must be in the root directory:
1. `valentine.html` - Main application.
2. `image_31b797.png` - Primary illustration.
3. `cat_celebration.gif` - Success animation 1.
4. `bubu-bubu-dudu.gif` - Success animation 2.
5. `our-song.mp3` - Background music file.

## 📝 Deployment Instructions
1. Upload all 5 assets to your GitHub repository.
2. Ensure filenames are exactly as written in the code (lowercase recommended).
3. Enable **GitHub Pages** in settings and point to the `main` branch.
