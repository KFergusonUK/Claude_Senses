# 👁️🎤 Claude Senses

**Real-time vision & voice streaming with Claude AI — runs entirely in your browser.**

No installs. No backend. No account needed beyond your own Anthropic API key.

![Claude Senses](https://img.shields.io/badge/Claude-Sonnet_4-7c6bff?style=flat-square) ![Zero Backend](https://img.shields.io/badge/backend-none-4dffb4?style=flat-square) ![Browser Only](https://img.shields.io/badge/runs_in-browser-ff6b9d?style=flat-square)

---

## ✨ What it does

Claude Senses gives Claude real-time eyes and ears through your webcam and microphone:

- **📸 Snap & Ask** — capture a frame from your camera and ask Claude about it
- **🎤 Voice input** — speak naturally; Claude hears you *and* sees the camera simultaneously
- **⚡ Auto-capture** — Claude observes and comments on your scene every 5–60 seconds automatically
- **💬 Multi-turn conversation** — Claude remembers the context of your whole session
- **✏️ Custom system prompt** — change how Claude behaves to suit your use case

---

## 🚀 Getting started

### 1. Get an Anthropic API key

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up or log in
3. Navigate to **API Keys** → **Create Key**
4. Copy your key (it starts with `sk-ant-...`)

> 💡 You'll need a little API credit — Anthropic offers $5 free to start. Each vision + voice request costs fractions of a cent.

### 2. Open the app

👉 **[Open Claude Senses](https://yourusername.github.io/claude-senses)** *(replace with your GitHub Pages URL)*

Or download `index.html` and open it directly in Chrome.

### 3. Paste your key

On first load, paste your API key into the prompt. It's saved in your browser's local storage — it never leaves your device or touches any server other than Anthropic's directly.

### 4. Allow camera & microphone

Click **Start Camera** and grant browser permissions when asked.

---

## 🖥️ Browser compatibility

| Browser | Camera | Voice | Recommended |
|---|---|---|---|
| Chrome (desktop) | ✅ | ✅ | ⭐ Best |
| Firefox (desktop) | ✅ | ✅ | ✅ Good |
| Edge (desktop) | ✅ | ✅ | ✅ Good |
| Safari (desktop) | ✅ | ⚠️ | Works |
| Mobile browsers | ⚠️ | ⚠️ | Not recommended |

**Desktop Chrome is the recommended browser.**

---

## 🔒 Privacy & security

- Your API key is stored only in **your browser's localStorage** — it never touches any server we control
- Camera frames are sent **directly from your browser to Anthropic's API** — no middleman
- No analytics, no tracking, no accounts
- You can clear your key any time via the ⚙ API Key button

---

## 💡 Ideas for what to try

- *"What do you see?"* — great starting point
- *"Is there anything unusual in this room?"*
- *"Read any text you can see"*
- *"Describe the lighting and mood of this scene"*
- Enable **Auto** every 10s and walk around — Claude narrates what it observes
- Use **Voice** and have a hands-free conversation while Claude watches

---

## 🛠️ Self-hosting / deploying

This is a single HTML file with no dependencies. To deploy your own copy:

**GitHub Pages (free, recommended):**
1. Fork this repo
2. Go to Settings → Pages
3. Set source to `main` branch, root folder
4. Your app is live at `https://yourusername.github.io/claude-senses`

**Or just open locally:**
```
# No server needed — just open the file
open index.html   # macOS
start index.html  # Windows
```

---

## 📄 License

MIT — do whatever you like with it.

---

*Built with Claude Sonnet 4 · Anthropic Vision API · Web Speech API*
