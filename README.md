# 💙 Buddy & Belinda's 45th Anniversary Story Generator

A beautiful, interactive "Mad-Lib" style web application built to celebrate the 45th wedding anniversary of my good friends, Bud (Buddy) & B (Belinda). 

This project takes a few simple prompts about their shared life—from their first date to their little dogs—and weaves them into a personalized, heartwarming story. It also features a gorgeous, interactive 3D background because 45 years of marriage deserves a little digital magic! ✨

## ✨ Features

* **📖 Interactive Mad-Libs Engine:** A custom-built form that takes user input and dynamically generates a personalized love story.
* **💖 3D Heart Particle System:** Powered by `Three.js`, the background features floating hearts that gently react to mouse movement. 
* **💎 Sapphire & Pink Aesthetics:** The 3D hearts dynamically blend between vibrant pinks and sapphire blues (the traditional 45th-anniversary gemstone!).
* **🪞 Glassmorphism UI:** A sleek, modern user interface with frosted glass cards that make the text readable while letting the 3D background shine through.
* **🐕 Dog-Approved:** Includes special prompts dedicated to their favorite little furry friends.
* **📱 Fully Responsive:** Looks great on a phone, tablet, or desktop.

## 🚀 How to Run

This project is entirely front-end and requires **zero** build tools or server setup. 

1. Clone the repository or download the ZIP file.
2. Open the folder on your computer.
3. Double-click `index.html` to open it in your favorite web browser.
4. Fill out the form and watch the story come to life!

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for the form and story containers.
* **CSS3:** Custom styling, animations (`fade-in`), Google Fonts (*Dancing Script* & *Playfair Display*), and glassmorphism backdrop filters.
* **Vanilla JavaScript (ES6+):** Handles form submission, object mapping, and dynamic DOM manipulation for the story generation.
* **Three.js:** Used via CDN to create the custom 3D webgl particle system and generate the heart canvas textures programmatically.

## 📝 Make it Your Own (Forking)

Want to adapt this for your own friends, parents, or partner? Feel free to fork it!
To customize:
1. Open `index.html`.
2. Update the `<select id="authorName">` options to the new couple's names.
3. Edit the HTML labels in the `#loveForm` to ask questions relevant to their relationship.
4. Update the `storyHTML` template literal in the JavaScript section to map to your new variables.

## 🥂 Cheers to 45 Years!
*Here is to 45 years of yesterday, our beautiful today, and an infinite tomorrow.* Happy Anniversary, Bud & B! 

---
*Created with ❤️ for Buddy and Belinda.*
