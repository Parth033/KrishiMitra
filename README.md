# 🌾 KrishiMitra — AI-Powered Smart Farming Assistant

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JavaScript-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-Gemini%20Vision%20%7C%20Pollinations-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/APIs-100%25%20Free-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Hindi%20%2B%20English-orange?style=for-the-badge" />
</p>

> **KrishiMitra** is a full-featured AI agricultural assistant for Indian farmers — built as a single-file Progressive Web App with 11 modules, bilingual support (Hindi + English), and zero paid APIs.

---

## 🚀 Live Demo

🔗 **[Try KrishiMitra Live →](https://parth033.github.io/KrishiMitra/)**

> ⚠️ Must be opened over **HTTPS** for weather & location APIs to work.

---

## ✨ Features

| Tab | Feature | Tech Used |
|-----|---------|-----------|
| 🏠 **Home** | Dashboard with live weather, crop stats, today's tips | Open-Meteo, Geolocation |
| 🌾 **Advisor** | 4-step AI Crop Recommendation Wizard | Pollinations AI (Free LLM) |
| 📈 **Prices** | Live crop mandi prices with trend charts | Chart.js, data.gov.in |
| 🌤 **Weather** | 7-day forecast + agricultural alerts | Open-Meteo API |
| 🤖 **AI Chat** | Bilingual farming chatbot (Hindi + English) | Pollinations AI |
| 🌱 **New Farmer** | Step-by-step crop care guide for beginners | AI-generated content |
| 🔬 **Scan Plant** | Upload leaf photo → AI disease diagnosis | Gemini Vision API |
| 🏛 **Schemes** | Government scheme eligibility checker (PM-KISAN, Fasal Bima, etc.) | Static + AI fallback |
| 📍 **Mandi Locator** | Find nearest APMC mandi with Maps link | Nominatim / ip-api.com |
| 📞 **Helpline** | Kisan helpline numbers with direct call buttons | Static data |
| 🧾 **Bill Scanner** | OCR scan of agricultural bills & mandi receipts | Gemini Vision API |

---

## 🛠 Tech Stack

```
Frontend      →  HTML5 · CSS3 · Vanilla JavaScript
Charts        →  Chart.js 4.4
AI (Text)     →  Pollinations AI (FREE, no key needed)
AI (Vision)   →  Google Gemini Vision API (free tier)
Weather       →  Open-Meteo API (FREE, no key needed)
Location      →  ip-api.com + Browser Geolocation API
Geocoding     →  Nominatim (OpenStreetMap)
Data          →  data.gov.in (Government open data)
Hosting       →  GitHub Pages
```

---

## 📡 APIs Used (All Free)

| API | Purpose | Key Required |
|-----|---------|--------------|
| [Pollinations AI](https://pollinations.ai) | AI chat + crop advisor | ❌ No |
| [Open-Meteo](https://open-meteo.com) | Live weather + 7-day forecast | ❌ No |
| [Nominatim](https://nominatim.org) | Location to mandi mapping | ❌ No |
| [ip-api.com](http://ip-api.com) | Auto-detect user location | ❌ No |
| [Gemini Vision](https://aistudio.google.com) | Plant disease scan + bill OCR | ✅ Free key |
| [data.gov.in](https://data.gov.in) | Government crop price data | ✅ Free key |

---

## ⚙️ Setup & Usage

### Option 1 — Direct (No Installation)
Just open `index.html` in any browser. Most features work offline/locally.

### Option 2 — GitHub Pages (Recommended)
1. Fork this repo
2. Go to **Settings → Pages → Source → main branch**
3. Your app is live at `https://<username>.github.io/<repo-name>/`

### Option 3 — Add Gemini API Key (For Plant Scan & Bill OCR)
1. Get free key from [aistudio.google.com](https://aistudio.google.com)
2. Open `index.html` and search for `GEMINI_KEY`
3. Paste your key — Plant Scanner and Bill OCR will activate

---

---

## 🌐 Bilingual Support

KrishiMitra supports **Hindi (हिंदी)** and **English** — toggle anytime from the top bar. All UI labels, tips, and AI responses adapt to the selected language.

---

## 🏗 Project Structure

```
KrishiMitra/
│
├── index.html          # Complete single-file app (HTML + CSS + JS)
└── README.md           # This file
```

> 💡 The entire app is intentionally single-file for easy deployment on GitHub Pages without any build tools or server setup.

---

## 🎯 Key Highlights for Recruiters

- ✅ **Zero-dependency frontend** — no npm, no framework, no build step
- ✅ **Real API integrations** — live weather, AI vision, geocoding
- ✅ **Bilingual UX** — Hindi + English with full label translation system
- ✅ **Mobile-first responsive design** — tested on Android & iOS
- ✅ **Error handling & fallbacks** — API failures gracefully handled
- ✅ **AI-powered features** — LLM chat, vision-based plant diagnosis, bill OCR

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first.

---

## 👤 Author

**Parth Agarwal**
- 🎓 BCA (AI & Data Analytics) — Teerthanker Mahaveer University, Moradabad
- 💼 [LinkedIn](https://linkedin.com/in/parth-agarwal-587b942a3)
- 🐙 [GitHub](https://github.com/Parth033)

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for Indian farmers · <strong>KrishiMitra</strong></p>
