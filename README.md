# 🎛️ Sound Engine
### AI Music Prompt Generator — Curated by Sound Fader Inc.

> **Sound Engine** is a browser-based AI music prompt generator built for producers, beatmakers, and artists who want to craft stellar, unique tracks using Suno AI. Select from dozens of musical parameters and let Claude generate optimized Suno-ready prompts, structured field outputs, and 10 unique song concepts in seconds.

---

## ✨ Features

- **11 Dropdown Categories** covering every dimension of a track's DNA
- **Subgenre / Fusion selector** — blend genres for unique hybrid sounds
- **Producer Influence library** — 70+ producers across Trap, Boom Bap, R&B, Pop, West Coast, ATL, and more
- **Genre browser** — 100+ genres and subgenres from all Suno-supported styles
- **BPM slider**, Key & Scale picker, Chord Progressions, Bass Movement, Drum Patterns
- **Atmosphere, Sound Design, Vocal Chop, Sample Loops, Mixing Aesthetic** controls
- **⚄ Randomize All** — instant random combination for inspiration
- **3 AI-powered generation modes:**
  - 🎛️ **Suno Fields** — 8 copy-ready fields formatted for Suno's interface
  - ✦ **Full Prompt** — one optimized Suno prompt with style tags
  - 💡 **10 Song Ideas** — titled concepts with descriptions and genre tags
- **⚡ Generate Everything** — runs all three simultaneously
- **Copy buttons** on every output panel
- Powered by **Claude (claude-sonnet-4-20250514)** via the Anthropic API

---

## 🚀 Getting Started

### Prerequisites

- An [Anthropic API key](https://console.anthropic.com/) (free tier available)
- A modern web browser (Chrome, Firefox, Safari, Edge)

### Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sound-engine.git
   cd sound-engine
   ```

2. Open `index.html` in your browser — no build step, no dependencies, no server required.

3. When prompted (or on first generation), enter your Anthropic API key.

> **Note:** This app calls the Anthropic API directly from the browser. Your API key is used client-side and is never stored on any server. Share the app only with trusted collaborators.

---

## 🌐 Deployment (Cloudflare Pages)

This app is deployed as a static site via **Cloudflare Pages**.

1. Fork or clone this repo to your GitHub account
2. Go to [Cloudflare Pages](https://dash.cloudflare.com) → Workers & Pages → Create a Project
3. Connect your GitHub repo
4. Set build settings:
   - **Framework preset:** None
   - **Build command:** *(leave blank)*
   - **Build output directory:** *(leave blank)*
5. Click **Save and Deploy**

Your app will be live at `https://sound-engine.pages.dev` (or your custom domain).

---

## 🎚️ How to Use

1. **Select your parameters** — work through each section (Core Sound, Melodic Layer, Texture, Production)
2. **Optional:** Choose a subgenre fusion and/or producer influence to add specificity
3. **Hit a Generate button:**
   - *Generate Suno Fields* → copy individual fields directly into Suno's interface
   - *Build Full Prompt* → one complete prompt to paste into Suno's style box
   - *Generate 10 Song Ideas* → explore concept directions before committing
   - *Generate Everything* → get all outputs at once
4. **Copy & paste** into [Suno](https://suno.com) and create

---

## 🗂️ Project Structure

```
sound-engine/
│
├── index.html        # The entire app — single file, no dependencies
└── README.md         # This file
```

---

## 🔑 API Key Security

This app uses **Option B** (client-side API key) — meaning the Anthropic API key is entered and used directly in the browser. This is appropriate for:

- Personal use
- Internal team tools shared with trusted people
- Private/unlisted deployments

**Do not share your live URL publicly** if you don't want others to use your API credits. For a fully public release, a server-side proxy (Cloudflare Worker) is recommended to protect your key.

---

## 🛠️ Built With

| Tool | Purpose |
|------|---------|
| HTML / CSS / Vanilla JS | Single-file app, zero dependencies |
| [Anthropic Claude API](https://docs.anthropic.com) | AI prompt & idea generation |
| [Cloudflare Pages](https://pages.cloudflare.com) | Static site hosting |
| [Google Fonts](https://fonts.google.com) | Orbitron + Space Mono typography |

---

## 📄 License

© 2026 Sound Fader Inc a Division of RJV Media Lab, Inc. All rights reserved.

This project is proprietary software. Unauthorized copying, distribution, or modification is not permitted without explicit written consent from Sound Fader Inc.

---

## 🤝 Contact

**Sound Fader Inc.**  
For inquiries, collaborations, or licensing:  
📧 [business@rjvmedialab.com](mailto:business@rjvmedialab.com)  
🌐 [RJV Media Lab](https://rjvmedialab.com)

---

*Sound Engine — Where your sound starts.*
