# 🌙 The Midnight Dream Catcher

An elegant, pitch-black mobile Progressive Web Application (PWA) designed as an eye-safe bedside companion for capturing, visualizing, and decoding dreams.

🚀 **Live Production Deployment:** [dreamcatcherapp.co.uk](https://dreamcatcherapp.co.uk)

---

## ✨ Architectural Features

- **📱 Bedside Optimized UI:** A pitch-black OLED layout with streamlined amber panels to minimize eye strain during late-night or early-morning dictation.
- **🎙️ Seamless Voice Tools:** Instant native speech-to-text dictation, verbal readback, and AI voice narration overrides (Storyteller, Whisper, and Noir).
- **🎨 Accelerated Video Pipeline:** Converts user dream transcripts into instant Storyboard Frames, utilizing an optimized Image-to-Video (I2V) asynchronous queue to bypass mobile device screen-locks.
- **🕌 Multiverse Symbol Decoders:** Maps core dream metaphors across 6 custom interpretation models, including Jungian psychology, Biblical archetypes, and classical **Islamic Hadith (Tafsir al-Ahlam)** translation frameworks.
- **☁️ Cross-Device Cloud Room:** A dual-tab archive dashboard utilizing a serverless data indexer to seamlessly aggregate and stream media files across separate user devices.

---

## 🛠️ Tech Stack & Production Topology

- **Frontend:** Pure semantic HTML5, CSS3 (OLED black canvas), and asynchronous JavaScript PWA modules.
- **Domain Routing:** Hosted via GitHub Pages, managed under Cloudflare DNS proxies, with enforced SSL/HTTPS parameters at `dreamcatcherapp.co.uk`.
- **Backend Architecture:** A serverless Cloudflare Worker proxy intercepting and load-balancing API requests securely.
- **Cloud Object Storage:** Integrated with a 10 GB free-tier Cloudflare R2 bucket (`dreamcatcher-media`) utilizing native 206 Partial Content byte-range chunking for smooth iOS video streaming buffers.
- **Sub-Tier SaaS Infrastructure:** High-speed cryptographically secure Stripe Webhook signature verification routing directly into your Monzo banking engine.

---

## ⚙️ Local Development & Quick Start

1. Clone the project onto your local environment:
   ```bash
   git clone https://github.com
   ```
2. Open the directory in your favorite code editor (e.g., VS Code).
3. To spin up the frontend, open `index.html` via a local live server extension.
4. For backend deployment changes, edit the `worker.js` proxy pipeline script and deploy directly via the Cloudflare Wrangler CLI.

---

## 📜 Production Release Log

- **v1.0.0:** Legacy dream migrations, Luma I2V acceleration engine integration, and byte-range video progressive stream loaders.
- **v1.2.0:** Secure live Stripe production activation, cross-device Cloud Room tabs, and custom `co.uk` top-level business domain routing.
