# ⚡ Scan Pe

**Scan Pe** is a lightning-fast, privacy-focused Progressive Web App (PWA) built for seamless UPI payments. It features a dual-mode interface designed for both instant QR code scanning and creating clean, shareable payment links.

🌐 **Live Demo:** (https://nishantishere.github.io/ScanPe/)

---

## ✨ Features

* **📷 Fast QR Code Scanner:** Point your camera at any counter UPI QR code to instantly extract payment details, or pick/capture an image from your device gallery.
* **✨ Clean Viewfinder Interface:** Optimized scanner view with customized targeting corners and zero clutter (no native file input buttons or default white overlay boxes).
* **💸 Custom Amount & Quick Chips:** Easily add custom payment amounts or use quick-select chips (₹20, ₹50, ₹100, ₹500) to generate formatted payment links.
* **🔄 UPI Link Flipper / Pay Mode:** Switch to "Pay" mode to paste raw or messy UPI/intent links and automatically render a clean payment card layout with smooth 3D flip-and-swipe touch gestures.
* **📋 One-Tap Actions:** Instantly copy clean UPI links to your clipboard or forward payment requests directly via SMS.
* **🔌 Offline First (PWA):** Fully functional offline capability backed by a custom Service Worker and web manifest for native app installation on mobile devices.

---

## 🛠️ Tech Stack

* **Frontend:** Vanilla JavaScript, HTML5, CSS3 (Modern custom design system with dark/light theme support)
* **QR Engine:** Embedded `html5-qrcode` library
* **PWA:** Service Workers (`sw.js`) and Web Manifest (`manifest.json`)

---

## 🚀 Getting Started & Deployment

1. Clone the repository:
   ```bash
   git clone (https://github.com/Nishantishere/ScanPe.git)
