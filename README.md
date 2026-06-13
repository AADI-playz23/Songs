# 🎵 Songs – YouTube Music Player

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-blue)](https://aadi-playz23.github.io/Songs/)
[![YouTube Data API](https://img.shields.io/badge/YouTube-Data%20API%20v3-red)](https://developers.google.com/youtube/v3)

> A clean, neon-themed music player that streams audio from YouTube using the official YouTube Data API v3. Built as a side project for learning and fun.

🔗 **Live demo:** [https://aadi-playz23.github.io/Songs/](https://aadi-playz23.github.io/Songs/)

---

## 📖 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Run Locally](#run-locally)
- [Project Structure](#project-structure)
- [License](#license)
- [Privacy Policy](#privacy-policy)
- [Acknowledgments](#acknowledgments)

---

## ✨ Features
- Play, pause, next, previous controls
- Search by song title or artist
- Filter by genre tags
- Responsive layout (works on desktop & mobile)
- No backend – runs entirely in your browser

## 🛠 Tech Stack
- HTML5 / CSS3 / JavaScript (vanilla)
- [YouTube Data API v3](https://developers.google.com/youtube/v3)
- Hosted on [GitHub Pages](https://pages.github.com/)

## ⚙️ How It Works
1. User searches for a song or selects from the list.
2. The app queries the YouTube Data API to get the video ID.
3. Audio is streamed directly from YouTube (using YouTube's embedded player / iframe API).
4. The original YouTube video remains accessible – standard YouTube experience is preserved.

## 🧪 Run Locally
```bash
git clone https://github.com/AADI-playz23/Songs.git
cd Songs
# Open index.html in your browser
