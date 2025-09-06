# 🎬 Netflix Clone

A fully responsive **Netflix Clone** built using **HTML**, **Tailwind CSS**, and **JavaScript**.  
This project replicates the classic Netflix landing page (previous design) with clean layout, smooth interactions, and responsiveness across all devices.  

---

## ✨ Features

- 🎨 **Modern UI** styled completely with Tailwind CSS.  
- 📱 **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.  
- 🌀 **Smooth Scrolling** between sections using Tailwind’s `scroll-smooth`.  
- 🔄 **Transitions & Hover Effects** for interactive elements (buttons, links, FAQ, etc.).  
- 🎥 **Video Background Integration** for media sections.  
- ⚡ **Animations** for UI components to enhance user experience.  
- ⚙️ Built using **Tailwind CLI** (no external frameworks).  

---

## 🚀 Tech Stack

- **HTML5** – For structure  
- **Tailwind CSS** – For styling & responsiveness  
- **JavaScript (ES6)** – For interactivity  
- **Tailwind CLI** – For compiling and watching Tailwind styles  

---

## 📂 Project Setup

Follow these steps to run the project locally and use Tailwind CLI:

1. **Install Tailwind via npm**
   ```bash
   npm install -D tailwindcss

2. **Create CSS input file**
   ```bash
   @import "tailwindcss";

3. **Terminal**
   ```bash
   npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

4. **Add output.css in index.html**
   ```bash
   <link href="./src/output.css" rel="stylesheet">

For any queries refer to https://tailwindcss.com/docs/installation/tailwind-cli

# Note:
Chrome Safe Browsing may show a false positive warning because this project mimics Netflix’s UI for learning purposes.
The site works perfectly in Incognito mode or browsers like Brave/Edge/Firefox.
