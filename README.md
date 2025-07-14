
# 🎮 HackTrace – Hacker Simulation Game

[Try it now](https://nitinyadav2188.github.io/HackTrace/)

**HackTrace** is an interactive, browser-based game that simulates common hacking scenarios to teach users about cybersecurity threats in a fun and engaging way.

> 🛡️ *Learn to think like a hacker — defend like a pro!*

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Responsive](https://img.shields.io/badge/mobile-responsive-brightgreen)
![Hackathon](https://img.shields.io/badge/hackathon-ready-orange)
![Built by Nitin](https://img.shields.io/badge/built%20by-Nitin%20Yadav-blueviolet)

---

## 🚀 Features

- 🧠 Realistic cyber-attack simulations (Phishing, Social Engineering, SQL Injection, etc.)
- 🎯 Points system and level progression
- 🔁 Infinite question loop for endless learning
- 📱 Fully responsive UI (mobile + desktop)
- ✨ Clean, dark-themed interface with custom styling

---

## 📦 How to Run Locally

1. **Clone this repository**  
   ```bash
   git clone https://github.com/nitinyadav2188/HackTrace.git
   cd hacktrace
   ```

2. **Open in browser**  
   Simply open `index.html` in your preferred browser.

---

## 🌐 Use as a Chrome Extension

1. Go to `chrome://extensions/`
2. Enable **Developer Mode**
3. Click **Load Unpacked**
4. Select the project folder

> Ensure `manifest.json` is present in the root directory for extension functionality.

---

## 🧠 Learning Goals

- Recognize common attack vectors in cybersecurity
- Learn secure decision-making under realistic pressure
- Encourage ethical hacking and reporting of vulnerabilities

---

## 📈 Scoring Formula

The logic behind scoring is:

\[
\text{score}_{n+1} = \text{score}_n + \text{option.points}
\]
\[
\text{level}_{n+1} = \text{level}_n + 1
\]

---

## 🧗 Project Story

### 🔍 What Inspired Me

The idea for **HackTrace** was sparked during a cybersecurity awareness session where I noticed how many people, even in tech, were unaware of how real-world hacking tactics like phishing, SQL injection, and social engineering actually work.

> “What if there were a fun, interactive way to learn how hackers think — and how to defend against them?”

### 🧠 What I Learned

- 🛡️ Cybersecurity fundamentals
- 💻 Frontend development with HTML/CSS/JavaScript
- 🧩 Game logic design with scoring/levels
- 📱 Responsive design without frameworks

### 🔧 How I Built It

- Pure HTML + CSS + JavaScript
- Infinite questions with:
  ```js
  const question = questions[currentIndex % questions.length];
  ```
- Touch-friendly layout using CSS media queries

### 🧗 Challenges Faced

- Balancing point system and question variety
- Designing professional UI without Bootstrap/Tailwind
- Mobile layout tweaks using custom CSS

### 🌱 What’s Next?

- Add advanced topics like MITM, ransomware
- Save high scores locally
- Add multiplayer mode or leaderboard

---

## 👨‍💻 Author

Made with 💻 + ❤️ by **Nitin Yadav**  
Feel free to fork, improve, and share!

---

## 📜 License

This project is licensed under the MIT License.
