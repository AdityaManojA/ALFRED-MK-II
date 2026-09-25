# 🦇 ALFRED — MARK II (Wayne Protocol Edition)
### Autonomous Multimodal AI Desktop Assistant & Tactical Terminal
**Architect & Lead Creator:** **ADITYA MANOJ**

[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Gemini Live API](https://img.shields.io/badge/AI-Gemini%203.1%20Flash%20Live-8E75B2.svg?logo=google&logoColor=white)](https://ai.google.dev/)
[![PyQt6](https://img.shields.io/badge/GUI-PyQt6%20Software%20Renderer-41CD52.svg?logo=qt&logoColor=white)](https://riverbankcomputing.com/software/pyqt/)
[![AES-256 Remote](https://img.shields.io/badge/Mobile-Quantum%20Dashboard%20(iOS%2FAndroid)-00f0ff.svg)](https://github.com/)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

> **ALFRED MARK-II** is an autonomous, real-time voice, vision, and system-control executive assistant built for complete digital sovereignty. Powered by native bidirectional audio streaming on the Google Gemini Live API, ALFRED sees your monitors, hears your voice with sub-second response times, executes complex OS workflows, and syncs seamlessly with your mobile devices.

---

## ⚡ What's New & Upgraded by Aditya Manoj

### 🛡️ 1. The Heavenly Restriction & Drive Access Lockdown
* **Permanent Self-Preservation Barrier (Heavenly Restriction)**: ALFRED is strictly and irrevocably restricted from accessing, opening, reading, listing, modifying, or executing files inside `D:\Projects\Personal-Assistant` (and all subpaths including `Mark-LIV`).
* **C: Drive Quarantine**: Access to the C: drive is strictly and exclusively confined to the user's **Desktop** and **Documents** folders. Any attempt to touch system directories or other user folders (such as `C:\Windows`, `C:\Program Files`, `Downloads`, `AppData`, or root `C:\`) is rejected with an immediate access denial.
* **Safe Storage Zones (D: & E: Drives)**: `D:` drive and `E:` drive are designated safe zones for user files, projects, and media — with `D:\Projects\Personal-Assistant` remaining strictly isolated.
* **Multi-Layer Hard Enforcement**:
  * **Cognitive Persona Shield**: Master system prompt and runtime context enforce denial with the exact refusal phrases:
    > *"Due to the heavenly restriction placed upon my creator, I cannot."*
    > *"Access denied: Access to C: drive is restricted to Desktop and Documents only."*
  * **Global Dispatch Interceptor**: `_execute_tool()` actively validates incoming tool arguments via `core.path_guard` and aborts unauthorized requests before tool execution.
  * **Subsystem Guards**: `file_controller`, `file_processor`, `open_app`, `action_loader`, and `computer_control` enforce independent path resolution checks, rendering prompt injection or path spoofing impossible.

### 🔴 2. Emoji-Free Tactical Telemetry Stream
* Replaced all conversational emojis in system and terminal reporting with high-contrast, machine-readable ANSI Red bracketed tags (`\033[91m[...] \033[0m`).
* Standardized operational event taxonomy:
  `[phone]` (calls), `[control]` (tool execution), `[screen]` (display capture), `[camera]` (webcam), `[out]` (tool returns), `[warn]` (cautions), `[error]` (failures), `[mic]` (audio in), `[speaker]` (audio out), `[listen]` (receive loop), `[link]` (connection/resumption), `[online]` (connected), `[halt]` (interruption/shutdown), `[brief]` (morning brief), `[monitor]` (alerts), `[proactive]` (check-ins).

### 📱 3. iPhone 16 Quantum Dashboard & Remote Terminal
* **Mobile-Responsive Viewport Overhaul**: Specially engineered layout for iPhone 16 and mobile displays. Header badges are auto-compacted, and the Arc Reactor panel is collapsible on mobile devices to provide an unobstructed, full-height feed.
* **Live Telemetry Synchronization**: Real-time WebSocket broadcasting streams tool executions, vision buffers, and status transitions directly to your phone.
* **Zero Input Overflow**: Mobile input dock with flex layout ensures no clipped buttons or horizontal screen mismatch.

### 📸 4. Dual-Destination Tactical Screenshots
* Asking ALFRED to capture the screen now automatically dispatches to **both** your computer and mobile device:
  1. **Desktop**: Timestamped high-resolution capture saved to `~/Desktop/alfred_screenshot_<timestamp>.png`.
  2. **Phone**: Instantly copied to `dashboard/uploads/`, broadcasting a real-time event to the mobile interface with an **inline visual thumbnail preview** and a single-tap **View / Save Image** download link.

### 🦇 5. Wayne Tech Aesthetic & Intel HUD
* **Tactical Glassmorphism UI**: High-tech HUD featuring amber/gold accents (`#e5a93b`), reactive particle fields, and software-rendered holographic visuals.
* **Dual Interface Matrices**: Instant toggle between the 3D Holographic Head and the Quantum Reactor Matrix.
* **Dedicated Intel & Notes Terminal**: Built-in `intel_notes` module for tactical mission memos and persistent scratchpad storage.

---

## 🚀 Core Capabilities

| Capability | Architecture & Description |
|---|---|
| 🎙️ **Real-Time Voice Intelligence** | Bidirectional low-latency voice streaming via **Gemini 3.1 Flash Live**. Talk naturally in any language with sub-second time-to-first-word. |
| 🦇 **Batcave Tactical CRT Interface** | 3D rotating vector wireframe globe, real-time waveform telemetry, and tactical hex matrix stream rendered with zero GPU driver dependencies. |
| 👄 **Formant & Audio Reactivity** | Real-time audio waveform spectrum analysis and RMS power levels reactive to speech and system states. |
| 👁️ **Multimodal Vision Engine** | Single-frame on-demand screen and webcam capture (`screen_processor.py`). Captures are labelled by source and injected directly into the Gemini exchange. |
| 🖥️ **Full Computer Control** | Direct desktop automation (`computer_control.py`): keystrokes, hotkeys, mouse clicks/drags, window focus, clipboard read/write, AI element location (`screen_find`). |
| 🎚️ **Global Push-to-Talk** | Hold `Ctrl+Space` to talk. Mic remains completely closed otherwise. Truly global on Windows (30 Hz raw virtual key polling), window-scoped on macOS/Linux. |
| 🔇 **Acoustic Self-Echo Guard** | Calibrated against measured device output latency (`_out_latency + _TAIL_MARGIN`). Drops ALFRED's own voice tail so he never accidentally talks to himself. |
| 🧠 **Unlimited Memory Engine** | Tiered memory structure in `memory/long_term.json`. Core identity facts stay in context; extended history is recalled on demand via sub-millisecond local search. |
| ↩️ **Universal Action Undo** | Reverse file moves, renames, writes, creations, and OS settings changes simply by saying *"undo"* in any language. |
| ⚠️ **Human Confirmation Gate** | Irreversible commands (shutdown, restart, WiFi toggle) require an explicit physical UI click — preventing model hallucination disasters. |
| 📱 **Encrypted Web Remote** | Run `python main.py`, scan the on-screen QR code on your phone, and control ALFRED over local WiFi with AES-256 session encryption. |
| 🧩 **Self-Describing Plugin System** | Drop any single `.py` file with a `PLUGIN` dictionary into `plugins/` — ALFRED auto-discovers and registers the capability at startup. |
| 🔍 **Multi-Tier Web Search** | Deep search, news monitoring, and price comparison using Gemini Grounding with automated DuckDuckGo fallbacks. |
| ⏰ **Native OS Task Scheduler** | Schedules reminders via Windows Task Scheduler (`schtasks`), macOS `launchd`, or Linux `systemd`/`at`. |

---

## 🗺️ System Architecture

ALFRED's architecture is organized into clean, modular layers discovered dynamically at runtime:

```
ALFRED-MK-II/
├── main.py                     # Main execution loop, Gemini Live WebSocket, audio streams, tool router
├── ui.py                       # Tactical Batcave CRT HUD interface, audio visualizer, drawer settings
├── setup.py                    # OS-aware package and dependency installer
├── core/
│   ├── prompt.txt              # Master persona directives, execution rules & Heavenly Restriction
│   ├── action_loader.py        # Dynamic action discovery, parameter validation & Heavenly Restriction guard
│   ├── plugin_loader.py        # Drop-in plugin discovery, sandboxing & isolation
│   ├── echo.py                 # Device-calibrated acoustic echo cancellation guard
│   ├── hotkey.py               # Global / local Push-to-Talk chord interceptor
│   ├── undo.py                 # Stack-based reversible action journal
│   ├── confirm.py              # Cryptographic UI confirmation gate for destructive actions
│   └── audio_devices.py        # Measured host API audio device enumeration (MME / DirectSound / WASAPI)
├── actions/                    # Bundled operational tools (TOOL dictionary schema)
│   ├── computer_control.py     # OS automation, keyboard/mouse input, dual screenshots
│   ├── screen_processor.py     # Multi-monitor screen & camera capture engine
│   ├── file_controller.py      # File system operations with path restriction checks
│   ├── file_processor.py       # PDF/DOCX/TXT analysis, parsing, and summarization
│   ├── open_app.py             # OS-specific application and executable launcher
│   ├── computer_settings.py    # Volume, brightness, WiFi, power state management
│   ├── web_search.py           # Multi-mode parallel search (news, research, comparison)
│   ├── intel_notes.py          # Tactical mission note logger and scratchpad
│   ├── proactive.py            # Context-aware proactive check-in engine
│   ├── background_monitor.py   # Daily background topic watcher and headline alerts
│   ├── reminder.py             # OS-native task scheduler notifications
│   ├── system_monitor.py       # Live CPU, GPU, RAM, temperature telemetry
│   ├── dev_agent.py            # Autonomous code developer agent
│   ├── code_helper.py          # Code analysis and generation
│   ├── send_message.py         # WhatsApp and Telegram message dispatcher
│   ├── youtube_video.py        # YouTube search and playback control
│   ├── game_updater.py         # Steam and Epic Games library updater
│   └── weather_report.py       # Localized live meteorological reports
├── dashboard/                  # Quantum Mobile Remote Server
│   ├── server.py               # FastAPI + Uvicorn + WebSocket encrypted daemon
│   ├── static/
│   │   └── app.html            # iPhone 16 responsive tactical web app & telemetry console
│   └── uploads/                # Transferred files & captured screenshots
├── memory/
│   ├── memory_manager.py       # Long-term memory JSON persistence and indexing
│   ├── config_manager.py       # Settings, voice, theme, and API key management
│   └── long_term.json          # Local encrypted fact database
├── config/
│   ├── api_keys.json           # User credentials, identity settings & voice preferences
│   └── certs/                  # Local self-signed SSL/TLS certificates for HTTPS/WSS
└── graphify-out/               # GraphRAG knowledge graph, community clusters, and analysis
```

---

## ⚡ Quick Start

### 1. Prerequisites
* **Operating System**: Windows 10/11, macOS, or Linux.
* **Python**: `3.11`, `3.12`, or `3.13`.
* **Hardware**: Working microphone and speakers. *(No dedicated GPU required — Batcave CRT interface runs on lightweight software rendering).*
* **API Key**: Free Gemini API Key from [Google AI Studio](https://aistudio.google.com/).

### 2. Setup & Installation

```powershell
# Clone the repository
git clone https://github.com/AdityaManojA/ALFRED-MK-II.git
cd ALFRED-MK-II

# Run the OS-tailored setup script
python setup.py

# Launch ALFRED
python main.py
```

*On the very first launch, the setup dialog will prompt you to enter your Gemini API Key. Your settings and credentials are saved locally in `config/api_keys.json`.*

---

## 📱 Mobile Pairing (iPhone / Android)

1. Launch `python main.py`.
2. Click the **Remote / QR Code** button on the bottom toolbar.
3. Open your phone's camera and scan the QR code (or browse to `https://<YOUR_LOCAL_IP>:8765`).
4. Accept the local self-signed SSL certificate.
5. You now have full mobile access:
   * **Live Red-Tag Telemetry**: Watch ALFRED think, call tools, and respond in real time.
   * **Push-to-Talk Mic**: Hold the mobile mic button to speak into ALFRED from anywhere on your WiFi.
   * **Instant Screenshots**: Capture your desktop screen by voice; it lands directly on your phone feed with an instant preview and save link.
   * **Encrypted File Beam**: Upload files directly from your phone to your PC.

---

## 🧠 Memory & Customization

### Configuring Your Persona (`config/api_keys.json`)
```json
{
    "assistant_name": "ALFRED",
    "user_name": "Master Wayne",
    "ui_color": "#e5a93b",
    "voice_name": "Charon",
    "wake_word_enabled": false,
    "push_to_talk_enabled": true
}
```

* **Voice Selection**: Choose between `Charon`, `Puck`, `Aoede`, `Fenrir`, or `Kore` in the UI settings drawer without restarting.
* **Hue Wheel & Colors**: Customize the HUD theme live from the palette drawer; the Batcave tactical interface dynamically updates its CRT glow and accents to match.
* **Memory Management**: Open **⚙ → 🧠 MEMORY** to inspect everything ALFRED knows about you, or delete specific items in one click.

---

## 📊 Knowledge Graph (`graphify`)

This codebase is indexed with a full **GraphRAG Knowledge Graph** located in `graphify-out/`:
* **1,722 nodes** & **3,371 relationships** mapped across 103 semantic functional communities.
* Interactive navigable graph visualization: [`graphify-out/graph.html`](file:///d:/Projects/Personal-Assistant/Mark-LIV/graphify-out/graph.html).
* Exhaustive architectural breakdown: [`graphify-out/GRAPH_REPORT.md`](file:///d:/Projects/Personal-Assistant/Mark-LIV/graphify-out/GRAPH_REPORT.md).

---

## 🔒 Privacy & Security Notice

* **100% Local Processing for System Operations**: Computer control, file access, and process management run locally on your host CPU.
* **No Telemetry / No Tracking**: No proprietary servers, telemetry trackers, or cloud subscriptions are involved.
* **Data Confinement**: Audio streams leave your machine solely to Google's Gemini Live API endpoint while a turn is active.
* **Credentials Protected**: All keys, certs, and memory files are strictly excluded via `.gitignore`.

---

## 👤 Author & Credits

* **Lead Architect & Creator:** **ADITYA MANOJ**
* **Original Creator & Core Inspiration:** **[FatihMakes](https://github.com/FatihMakes)** — creator of [Mark-LIV](https://github.com/FatihMakes/Mark-LIV)
* **Project:** ALFRED-MK-II (Wayne Protocol Edition)
* **License:** [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🙏 Special Thanks & Acknowledgements

> ### 🌟 Big Shoutout & Gratitude to [FatihMakes](https://github.com/FatihMakes)!
> A massive thank you to **FatihMakes** for developing the original **[Mark-LIV](https://github.com/FatihMakes/Mark-LIV)** project! 
> 
> The initial codebase, architecture vision, and creative inspiration for this entire assistant originated from his phenomenal open-source work. Huge respect and credit to him for laying the foundation.
> 
> 👉 **Original Repository:** [https://github.com/FatihMakes/Mark-LIV](https://github.com/FatihMakes/Mark-LIV) ⭐

---
*Built with precision for autonomy, performance, and security.*

