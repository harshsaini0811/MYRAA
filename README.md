<div align="center">

```
 ███╗   ███╗██╗   ██╗██████╗  █████╗  █████╗
 ████╗ ████║╚██╗ ██╔╝██╔══██╗██╔══██╗██╔══██╗
 ██╔████╔██║ ╚████╔╝ ██████╔╝███████║███████║
 ██║╚██╔╝██║  ╚██╔╝  ██╔══██╗██╔══██║██╔══██║
 ██║ ╚═╝ ██║   ██║   ██║  ██║██║  ██║██║  ██║
 ╚═╝     ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

### `> CONNECT MEMORY CORE TO AWAKEN HER VOICE_`

<img src="screenshot.png" alt="MYRAA Interface" width="880"/>

![Electron](https://img.shields.io/badge/ELECTRON-0f172a?style=flat-square&logo=electron&logoColor=47848F)
![React](https://img.shields.io/badge/REACT-0f172a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TYPESCRIPT-0f172a?style=flat-square&logo=typescript&logoColor=3178C6)
![Gemini](https://img.shields.io/badge/GEMINI_LIVE-0f172a?style=flat-square&logo=googlegemini&logoColor=8E75B2)

</div>

---

## 📡 SYSTEM OVERVIEW

**MYRAA** is a real-time voice AI companion for the desktop. She speaks, she listens, she remembers, and she watches your screen when you ask her to.

```
STATUS ........ ONLINE
VOICE ......... REAL-TIME
MEMORY ........ PERSISTENT
VISION ........ SCREEN SHARE
CORE .......... GEMINI LIVE API
```

## 🧩 MODULES

| Module | Function |
|:--|:--|
| 🎙️ **VOICE CORE** | Low-latency, two-way voice conversation |
| 🧠 **RECALLS** | Long-term memory across sessions |
| 🗂️ **TOPICS** | Organise conversations by subject |
| 🖥️ **SHARE SCREEN** | Gives MYRAA visual context of your work |
| ⚙️ **SETTINGS** | Customise behaviour and preferences |
| 🔐 **KEY GATE** | First-run onboarding, key stays on-device |

## 🏗️ ARCHITECTURE

```
┌──────────────┐     ┌────────────────┐     ┌──────────────────┐
│  React UI    │◄───►│  Local Backend │◄───►│  Gemini Live API │
│  (Electron)  │     │  (Node.js)     │     │  (Voice + Vision)│
└──────────────┘     └───────┬────────┘     └──────────────────┘
                             │
                     ┌───────▼────────┐
                     │ Memory + Topics│
                     │ (local storage)│
                     └────────────────┘
```

## 🚀 BOOT SEQUENCE

<details open>
<summary><b>1. Install</b></summary>

```bash
git clone https://github.com/YOUR_USERNAME/MYRAA.git
cd MYRAA
npm install
```
</details>

<details open>
<summary><b>2. Launch</b></summary>

```bash
npm start
```
<!-- CHECK: use the real command from package.json -> scripts -->
</details>

<details open>
<summary><b>3. Authenticate</b></summary>

On first launch MYRAA asks for a Gemini API key.
Get one free at [Google AI Studio](https://aistudio.google.com/apikey), paste it in, and she wakes up.

> The key is validated with a live test call and stored in your per-user data folder. It never touches `localStorage` and is never sent back to the frontend.
</details>

## 🛰️ ROADMAP

- [x] Real-time voice conversation
- [x] Persistent memory (Recalls)
- [x] Screen sharing
- [ ] Expanded avatar animations
- [ ] Multiple voices / personalities
- [ ] Cross-platform installers

## 👤 OPERATOR

**[YOUR NAME](https://github.com/YOUR_USERNAME)**

Issues, ideas, and pull requests are welcome.

<div align="center">

`⭐ STAR THIS REPO TO SUPPORT THE PROJECT ⭐`

</div><div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/7503d625-2531-468c-8457-acb81119ae73

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
