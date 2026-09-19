# 🩺 MediGen

> **A web app for building and engineering highly customizable slides for medical presentations.**
> ساخت و مهندسی اسلایدهای ارائه پزشکی با قابلیت شخصیسازی بالا — کاملاً در مرورگر، آفلاین.

[![Made with HTML](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-e34f26?style=flat-square)](#)
[![PWA](https://img.shields.io/badge/PWA-Offline--Ready-5a0fc8?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

---

## ✨ Features

- 🏥 **Full case template** — cover, demographics, chief complaint, HPI, PMH, medications, ROS, physical exam, labs, imaging, DDx, diagnosis, treatment, follow-up
- 🎨 **8 color themes** + fully custom colors
- 🎯 **10 header styles** (Band, Minimal, Side, Gradient, Underline, Pill, Boxed, Accent Bar, Neon, Split)
- 🔤 **Global fonts & sizes** — Vazirmatn, Tahoma, B Nazanin, IRANSans, Calibri…
- 🖼 **Image slides** with built-in cropper (16:9, 4:3, 1:1, rotate, flip)
- 📄 **Custom blank slides** — free title + text
- 📝 **Inline markup** — `**bold**`, `==highlight==`, `!!accent!!`, `~~strike~~`, `[r]red[/r]`, `[b]blue[/b]`, …
- 🎤 **Voice dictation** (Persian & English) on every text field
- 🔍 **Review of Systems** — 13 systems, click-to-cycle positive / negative
- 📈 **Lab trends** — comma-separated values rendered as an arrow chart table
- 🤖 **AI assistant** — copy prompt → paste JSON → auto-fill the whole case
- 📤 **Export** — PowerPoint (.pptx), PDF, self-contained HTML, PNG per slide
- 🌐 **Bilingual** — Persian (RTL) & English (LTR), full UI translation
- 💾 **File handling** — save / open / recent files (Chrome / Edge)
- 📴 **Offline-ready PWA** — installable, works without internet
- 🔒 **Privacy-first** — everything stays in your browser, no server, no tracking

---

## 🚀 Usage

### آنلاین (سریعترین راه)
باز کن: **https://YOUR-USERNAME.github.io/MediGen/**

### نصب بهعنوان اپ (PWA)
- **Android / Desktop (Chrome/Edge):** دکمه «Install» در نوار آدرس ظاهر میشه → بزن.
- **iOS (Safari):** دکمه Share → **Add to Home Screen**.

### آفلاین
بعد از اولین بار باز کردن، سرویسورکر همهچیز رو کش میکنه. بدون اینترنت هم کار میکنه.

---


---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save |
| `Ctrl + Shift + S` | Save As |
| `Ctrl + O` | Open |
| `Ctrl + N` | New File |
| `Ctrl + P` | Preview Slides |
| `Ctrl + Z` / `Ctrl + Y` | Undo / Redo |
| `Ctrl + Shift + D` | Voice Dictation |
| `?` | Help |
| `Esc` | Close modal |

---

## 🤖 AI Workflow

1. `AI → Copy AI Prompt`
2. Paste in ChatGPT / Claude / Gemini + paste the patient history
3. Copy the returned JSON
4. `AI → Paste AI Response` → `✓ Apply`

---

## 🛠 Tech Stack

- Pure **HTML + CSS + JavaScript** — no framework, no build step
- [PptxGenJS](https://gitbrent.github.io/PptxGenJS/) · [html2canvas](https://html2canvas.hertzen.com/) · [jsPDF](https://github.com/parallax/jsPDF) · [Cropper.js](https://fengyuanchen.github.io/cropperjs/)
- Fonts: [Vazirmatn](https://github.com/rastikerdar/vazirmatn)

---

## 📄 License

Released under the **MIT License** — see [LICENSE](LICENSE) for details.

---

## 👤 Author

**Mir Sajjad Aleyasin**
Telegram: [@DMSA2002](https://t.me/DMSA2002)

---

<p align="center"><sub>Made with ❤️ for the medical community</sub></p>


