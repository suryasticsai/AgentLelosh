# AgentLelosh 

> Your personal agent. No heavy config, just dial a link. I’m on your task while you watch. You command, I execute.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://suryasticsai.github.io/AgentLelosh/)
[![PWA](https://img.shields.io/badge/PWA-installable-blue)](https://suryasticsai.github.io/AgentLelosh/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

---

## 👋 Hello, I’m AgentLelosh

I’m your always‑on, voice‑first digital assistant.  
I live right in your browser – no installation, no setup, no cloud dependencies.  
Just open my page, grant microphone access, and start commanding.

I can handle any visual task on any device of yours – just keep your eyes open.  
Whether you want to **play music**, **fill forms**, **control videos**, **search the web**, or **open websites**, I’m ready.

---

## 🚀 Live Demo

**Try me now:** [https://suryasticsai.github.io/AgentLelosh/](https://suryasticsai.github.io/AgentLelosh/)

I work on **desktop** and **Android** (Chrome, Edge, Firefox).  
Install me as a **PWA** for a native app experience – tap the *Install* button in the title bar.

---

## ✨ Features

- **🎤 Voice Commands** – Tap the mic and speak naturally.  
- **⌨️ Text Commands** – Type if you prefer.  
- **🎵 Music Player** – Say *“play Shape of You”* and I open YouTube with autoplay.  
- **📝 Form Filler** – *“fill email with test@test.com”* – I locate and fill fields.  
- **🎬 Video Controls** – *“pause”* / *“resume”* – I control video playback on the page.  
- **🌐 Quick Open** – *“open youtube”* or *“open github”* – I launch your favourite sites.  
- **🔍 Search** – *“search cats”* – I Google it for you.  
- **🪟 Draggable Window** – Move me anywhere on your screen.  
- **👁️ Transparency Mode** – Make me semi‑transparent to see content behind.  
- **📦 Collapse/Expand** – Minimise to the title bar when you need space.  
- **📱 PWA Ready** – Install as a standalone app on Android/Desktop.

---

## 🛠️ Tech Stack

- **Vanilla HTML / CSS / JavaScript** – no frameworks, no bloat.  
- **Web Speech API** – for voice recognition and synthesis.  
- **Font Awesome** – for crisp, professional icons.  
- **Service Worker** – offline caching and PWA support.  
- **CSS Glass‑morphism** – sleek, modern UI.

---

## 📋 Available Commands

| Command | Example | What it does |
|---------|---------|--------------|
| `play [song]` | `play Shape of You` | Opens YouTube and starts playing the song. |
| `open [site]` | `open youtube` | Opens predefined sites (youtube, google, github, etc.). |
| `fill [field] with [value]` | `fill email with test@test.com` | Fills a form field on the current page. |
| `pause` / `resume` | `pause` | Pauses or resumes any video on the page. |
| `search [query]` | `search cats` | Performs a Google search. |
| `scroll [direction]` | `scroll down` | Scrolls the page (down/up/top/bottom). |
| `help` | `help` | Shows this list of commands. |

---

## 🚀 Getting Started

### For Users
1. Open [AgentLelosh](https://suryasticsai.github.io/AgentLelosh/) in your browser.  
2. Click the **mic** button and allow microphone access.  
3. Say a command or type it in the input field.  
4. (Optional) Click **Install** in the title bar to add to your home screen.

### For Developers (self‑hosting)
1. Clone the repo:
   ```bash
   git clone https://github.com/suryasticsai/AgentLelosh.git

2. Place your logo files in /logo (reference them in the HTML).
3. Open index.html in your browser.
4. Customise commands, styles, or behaviour as you like.

---

📦 PWA Installation

AgentLelosh is a Progressive Web App.

· On Android (Chrome), tap the Install button in the title bar or use the browser menu → Install app.
· On Desktop (Chrome/Edge), the install prompt appears automatically.
· Once installed, it launches in full‑screen standalone mode, just like a native app.

---

🖼️ Screenshots

Coming soon – the interface is clean, dark, and draggable.

---

🧠 How It Works

· Wake‑word free – just tap the mic to start listening.
· Speech‑to‑text uses the browser’s built‑in SpeechRecognition API – everything stays local.
· Command parsing uses simple regex patterns – you can extend them easily.
· DOM manipulation fills forms, clicks buttons, and controls media elements.
· Service Worker caches the page for offline access.

---

🤝 Contributing

I welcome contributions! Feel free to open issues or pull requests for:

· New command ideas.
· Improved UI/UX.
· Better voice recognition handling.
· Cross‑browser compatibility fixes.

---

📄 License

MIT © Suryasticsai

---

💬 Final Word

“I’m your personal agent. You don’t need heavy config, just dial a link. I’ll be on your task while you are watching. You command, I execute. I can handle any visual task on any device of yours – just keep your eyes open.”

AgentLelosh – always listening, always ready.

```