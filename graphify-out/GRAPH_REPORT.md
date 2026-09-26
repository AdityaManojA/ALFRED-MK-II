# Graph Report - Alfred-Mark-II  (2026-09-26)

## Corpus Check
- 58 files · ~150,928 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 6 file(s) not represented in the graph (top: (none) 3, .ico 2, .bak 1)

## Summary
- 1736 nodes · 3451 edges · 96 communities (81 shown, 15 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 149 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `025a91b6`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- game_updater.py
- MainWindow
- _BrowserSession
- gemini.py
- file_controller.py
- computer_control.py
- mono_font
- qcol
- JarvisLive
- CustomizeOverlay
- desktop.py
- code_helper.py
- memory_manager.py
- plugin_loader.py
- dev_agent.py
- tech_font
- json
- file_processor.py
- confirm.py
- EchoGuard
- llm_client.py
- check_path_access
- sys
- audio_devices.py
- tts.py
- config_manager.py
- FileDropZone
- daily_brief.py
- crypto-js.min.js
- TronScoreBackgroundPlayer
- send_message.py
- screen_processor.py
- load_api_keys
- .__init__
- VisemeStream
- action_loader.py
- _tlog
- ._build_app
- server.py
- PushToTalk
- background_monitor.py
- computer_settings
- platform
- get_input_device
- ._apply_name_update
- JarvisUI
- setter
- .run
- get_plugin_enabled
- ._build_jarvis_icon
- NotesTerminalWidget
- TacticalAudioPlayerWidget
- web_search.py
- DashboardServer
- _SysMetrics
- WakeWordDetector
- ._play_audio
- ._apply_ptt_shortcut
- PluginSettingsOverlay
- intel_notes.py
- main.py
- LogWidget
- MemoryOverlay
- ui.py
- _SessionRegistry
- .__init__
- _VolumeSliderPopup
- WhisperSTT
- _ensure_network_access
- .__init__
- browser_control.py
- _detect_action
- open_app.py
- ._decrypt
- .__init__
- ._launch
- .clear_chat
- pathlib
- threading
- get_plugin_config
- _template.py
- _get_base_dir
- Graphify + Antigravity Project Workflow & Setup Guide
- _get_macos_wifi_interface
- _ddg_news
- get_push_to_talk_enabled
- weather_report.py
- _QuotaCooldown
- _get_base_dir
- get_hud_style

## God Nodes (most connected - your core abstractions)
1. `MainWindow` - 88 edges
2. `JarvisLive` - 53 edges
3. `JarvisUI` - 44 edges
4. `mono_font()` - 35 edges
5. `tech_font()` - 34 edges
6. `_BrowserSession` - 32 edges
7. `TronScoreBackgroundPlayer` - 26 edges
8. `_resolve_path()` - 24 edges
9. `qcol()` - 24 edges
10. `computer_control()` - 21 edges

## Surprising Connections (you probably didn't know these)
- `🛡️ 1. The Heavenly Restriction & Drive Access Lockdown` --references--> `computer_control()`  [INFERRED]
  readme.md → actions/computer_control.py
- `🛡️ 1. The Heavenly Restriction & Drive Access Lockdown` --references--> `file_controller()`  [INFERRED]
  readme.md → actions/file_controller.py
- `🛡️ 1. The Heavenly Restriction & Drive Access Lockdown` --references--> `file_processor()`  [INFERRED]
  readme.md → actions/file_processor.py
- `🦇 5. Wayne Tech Aesthetic & Intel HUD` --references--> `intel_notes()`  [INFERRED]
  readme.md → actions/intel_notes.py
- `🛡️ 1. The Heavenly Restriction & Drive Access Lockdown` --references--> `open_app()`  [INFERRED]
  readme.md → actions/open_app.py

## Import Cycles
- None detected.

## Communities (96 total, 15 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (78): _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini(), Path (+70 more)

### Community 1 - "MainWindow"
Cohesion: 0.06
Nodes (8): QHBoxLayout, QMainWindow, MainWindow, Slot — display camera preview overlay (main thread)., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board., Place a floating overlay in the middle of the HUD and show it.

### Community 3 - "gemini.py"
Cohesion: 0.11
Nodes (25): _gemini_headlines(), Fetches current headlines via Gemini grounded search. Optimised for speed:…, api_key(), as_json(), call(), client(), _cool(), _cooling() (+17 more)

### Community 4 - "file_controller.py"
Cohesion: 0.08
Nodes (55): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+47 more)

### Community 6 - "computer_control.py"
Cohesion: 0.18
Nodes (27): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+19 more)

### Community 7 - "mono_font"
Cohesion: 0.08
Nodes (15): QFont, QWidget, BiometricFingerprintWidget, _CameraPreview, ClipboardPanel, CRTReconWidget, MetricBar, mono_font() (+7 more)

### Community 8 - "qcol"
Cohesion: 0.08
Nodes (17): QColor, QPainter, QPixmap, HudCanvas, qcol(), True only when this canvas can actually be seen by the user., Draw subtle background CRT coordinate grid with + crosshairs (Screenshot 2)., 3D Rotating Vector Wireframe Globe (Matching Screenshot 2: WAKU CRT Globe).… (+9 more)

### Community 9 - "JarvisLive"
Cohesion: 0.07
Nodes (16): JarvisLive, Load the detector once (model loads on first start). Idempotent., Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Thread-safe: ask the run loop to tear down and rebuild the Live session. Called… (+8 more)

### Community 10 - "CustomizeOverlay"
Cohesion: 0.10
Nodes (9): QPointF, QRectF, CustomizeOverlay, _lbl(), HueWheel, Circular colour picker. The user drags the handle (small white circle) around…, Floating glassmorphic overlay for configuring Assistant Persona, Commander…, Highlight the selected voice pill; dim the rest. (+1 more)

### Community 11 - "desktop.py"
Cohesion: 0.21
Nodes (18): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+10 more)

### Community 12 - "code_helper.py"
Cohesion: 0.18
Nodes (25): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+17 more)

### Community 13 - "memory_manager.py"
Cohesion: 0.11
Nodes (30): Update Daily Briefing Preferences Action for JARVIS / Alfred Mark-LIV.…, Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json., _all_entries(), all_entries_for_ui(), _empty_memory() (+22 more)

### Community 14 - "plugin_loader.py"
Cohesion: 0.19
Nodes (13): discover_plugins(), _load_error(), _opt_upper(), PluginRecord, Exception, Path, Plugin discovery, validation, collision detection, and dispatch. Discovery runs…, Returns a PluginRecord; .valid=False + .error set on any problem. Never raises. (+5 more)

### Community 15 - "dev_agent.py"
Cohesion: 0.16
Nodes (21): _build_project(), _classify_error(), dev_agent(), _fix_files(), _get_model(), _has_error(), _install_dependencies(), _is_rate_limit() (+13 more)

### Community 16 - "tech_font"
Cohesion: 0.12
Nodes (10): _row(), CapabilitiesOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl(), SetupOverlay (+2 more)

### Community 17 - "json"
Cohesion: 0.12
Nodes (14): ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, Telling the user's voice apart from our own coming back through the speakers.…, Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, json, numpy (+6 more)

### Community 18 - "file_processor.py"
Cohesion: 0.24
Nodes (18): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+10 more)

### Community 19 - "confirm.py"
Cohesion: 0.21
Nodes (12): bind(), _log(), _Pending, pending_title(), core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, when nothing is waiting. Lets an action avoid stacking two banners., Wire this module to the HUD. Called once from main.py at startup. (+4 more)

### Community 20 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 21 - "llm_client.py"
Cohesion: 0.14
Nodes (22): call_llm(), call_llm_stream(), call_llm_text(), check_model_available(), ensure_ollama_running(), get_base_dir(), get_llm_provider(), get_llm_settings() (+14 more)

### Community 22 - "check_path_access"
Cohesion: 0.33
Nodes (8): check_path_access(), get_allowed_c_roots(), is_safe_path(), Path, core/path_guard.py — Centralized Path Security and Drive Access Control.…, Validate whether a given path is allowed to be accessed. Returns: (True, "") if…, Convenience boolean helper for path safety., Return list of permitted roots on C: drive (Desktop and Documents).

### Community 23 - "sys"
Cohesion: 0.15
Nodes (17): _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import)., Install all missing packages required by *config*. Blocking — always call from…, install_and_download(), is_installed() (+9 more)

### Community 24 - "audio_devices.py"
Cohesion: 0.12
Nodes (20): configure(), _display_name(), _is_pseudo(), list_devices(), prefetch(), _work(), _query(), _collect() (+12 more)

### Community 25 - "tts.py"
Cohesion: 0.07
Nodes (26): asyncio, _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth() (+18 more)

### Community 26 - "config_manager.py"
Cohesion: 0.13
Nodes (21): ensure_config_dir(), get_base_dir(), get_brief_enabled(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every…, Persist assistant name and user name to config., Persist the chosen Live voice. Unknown names collapse to the default so a bad… (+13 more)

### Community 27 - "FileDropZone"
Cohesion: 0.11
Nodes (5): QDragEnterEvent, QDropEvent, CyberGraphicLineButton, FileDropZone, Tactical button rendered strictly with vector graphic lines, sharp 2px border…

### Community 28 - "daily_brief.py"
Cohesion: 0.06
Nodes (54): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_live_weather(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for JARVIS Mark-LIV. Provides the ultimate morning and daily…, Check scheduled reminders in ~/.jarvis/reminders. (+46 more)

### Community 30 - "TronScoreBackgroundPlayer"
Cohesion: 0.11
Nodes (7): QObject, _base_dir(), Path, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Duck to 50% of base volume when speaking, restore to base volume when…, Background music audio engine. Plays background score continuously on loop…, TronScoreBackgroundPlayer

### Community 31 - "send_message.py"
Cohesion: 0.25
Nodes (19): _base_dir(), _clear_and_paste(), _desktop_send(), _get_os(), _open_app(), _open_browser_url(), _paste_text(), Path (+11 more)

### Community 32 - "screen_processor.py"
Cohesion: 0.16
Nodes (19): _base_dir(), _capture_camera(), _capture_screen(), _compress(), _cv2_backend(), _detect_camera_index(), _get_camera_index(), _get_os() (+11 more)

### Community 33 - "load_api_keys"
Cohesion: 0.11
Nodes (18): The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, get_assistant_name(), get_gemini_key(), get_media_resolution(), get_proactive_audio_enabled(), get_thinking_enabled(), get_turn_tuning(), get_voice() (+10 more)

### Community 34 - ".__init__"
Cohesion: 0.11
Nodes (10): ProactiveEngine, Decides when JARVIS should speak unprompted and builds a context-rich prompt.…, Build a context snapshot for Gemini. Rotates through three focus areas so…, _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved. (+2 more)

### Community 35 - "VisemeStream"
Cohesion: 0.13
Nodes (12): collections, coverage(), Text → mouth shape, fused with the audio the avatar is actually speaking. Why…, Reduce any character to a bare Latin letter, or "" if it has none. This is what…, Fraction of the letters in `text` we can reduce to a Latin sound., Split a line of speech into (viseme, duration-weight) pairs. Returns [] for…, Fuses the transcript's shape sequence onto the audio's timing. Thread note:…, Blend audio frames [(level, openness, width)] with the text queue. (+4 more)

### Community 36 - "action_loader.py"
Cohesion: 0.11
Nodes (18): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _is_heavenly_restricted_params(), _opt_upper(), Path, Action discovery, validation, and dispatch — the built-in twin of… (+10 more)

### Community 37 - "_tlog"
Cohesion: 0.11
Nodes (13): _clean_transcript(), _is_repeat_chunk(), _deliver_news(), main(), runner(), Format terminal log report without emojis using red bracketed tags, and…, Send a captured frame immediately after its tool response. The frame is already…, Two-phase briefing optimized for speed: Phase 1 — instant greeting (no tools) →… (+5 more)

### Community 38 - "._build_app"
Cohesion: 0.20
Nodes (11): _auth(), auto_login(), clear_chat_ep(), device_login_ep(), list_files(), login(), phone_audio_ws(), revoke_devices() (+3 more)

### Community 39 - "server.py"
Cohesion: 0.12
Nodes (14): base64, _derive_key(), _make_uploads_dir(), Path, dashboard/server.py — JARVIS Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return (and create) the cross-platform uploads folder., SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed)., fastapi (+6 more)

### Community 40 - "PushToTalk"
Cohesion: 0.20
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 41 - "background_monitor.py"
Cohesion: 0.23
Nodes (13): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+5 more)

### Community 42 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), paste(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured… (+8 more)

### Community 43 - "platform"
Cohesion: 0.18
Nodes (11): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _nvml_gpu(), System Monitor — background metric checks with voice alert support. Zero…, Snapshot of current system metrics for the system_status tool., Stateful monitor — cooldown state persists across session reconnections. Call…, GPU utilisation via NVML — zero subprocess on all platforms. (+3 more)

### Community 44 - "get_input_device"
Cohesion: 0.25
Nodes (8): get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default., save_input_device(), save_output_device()

### Community 45 - "._apply_name_update"
Cohesion: 0.14
Nodes (10): apply_ui_accent(), current_palette(), Read api_keys.json config dict. Returns {} on any error., Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to…, Update all name/theme-dependent UI elements and persist to config. (+2 more)

### Community 46 - "JarvisUI"
Cohesion: 0.05
Nodes (16): JarvisUI, Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: take the gate down., Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Thread-safe: post a schedule of (level, openness, width) mouth frames for…, Thread-safe: wipe the on-screen conversation chat feed., Thread-safe: post special note, research link, or structured data to the…, Thread-safe: clear the dedicated Notes Terminal. (+8 more)

### Community 47 - "setter"
Cohesion: 0.10
Nodes (3): setter, _work(), Combined state for the two wake-word buttons. Readiness is a cheap,…

### Community 48 - ".run"
Cohesion: 0.16
Nodes (10): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Forward phone mic PCM chunks from dashboard queue into the Gemini Live session., True if `exc` is a _ReconnectSignal, or a(n) (Base)ExceptionGroup that wraps…, Read `keep_context` off a reconnect signal, unwrapping the group the TaskGroup… (+2 more)

### Community 49 - "get_plugin_enabled"
Cohesion: 0.19
Nodes (7): _call_run(), PluginRegistry, One entry per settings SECTION, for enabled plugins that declare a…, Invoke run() passing only the kwargs it actually declares (or all of them if it…, How this plugin's result should re-enter the conversation, if it said., get_plugin_enabled(), Plugins are enabled by default the moment they're discovered (opt-out model).

### Community 50 - "._build_jarvis_icon"
Cohesion: 0.22
Nodes (4): Render a JARVIS arc-reactor icon at 4× resolution and downsample for crisp…, Create a Windows .lnk shortcut WITHOUT launching PowerShell or cmd. Tries…, Resolve the user's REAL desktop directory instead of assuming ~/Desktop, which…, Create a desktop shortcut on Windows / macOS / Linux. Never opens a terminal,…

### Community 52 - "TacticalAudioPlayerWidget"
Cohesion: 0.16
Nodes (4): _EqualizerBarsWidget, Mini animated cyber audio wave visualizer., Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /…, TacticalAudioPlayerWidget

### Community 53 - "web_search.py"
Cohesion: 0.19
Nodes (21): _compare(), _ddg_search(), _format_ddg(), _gemini_available(), _gemini_search(), _log_gemini_failure(), _news(), _note_gemini_error() (+13 more)

### Community 54 - "DashboardServer"
Cohesion: 0.23
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 55 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 56 - "WakeWordDetector"
Cohesion: 0.20
Nodes (4): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector

### Community 57 - "._play_audio"
Cohesion: 0.22
Nodes (7): callback(), _open_mic(), _pcm_level(), _pcm_visemes(), Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…, True while the speakers may still be finishing our last sentence.

### Community 59 - "._apply_ptt_shortcut"
Cohesion: 0.29
Nodes (5): qt_sequence(), The same chord as a QKeySequence string., _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 60 - "PluginSettingsOverlay"
Cohesion: 0.17
Nodes (6): QPushButton, QVBoxLayout, PluginManagerOverlay, PluginSettingsOverlay, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles., Floating overlay — renders per-plugin settings forms. Fully generic: it…

### Community 61 - "intel_notes.py"
Cohesion: 0.08
Nodes (27): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes() (+19 more)

### Community 62 - "main.py"
Cohesion: 0.14
Nodes (13): google, google_genai, LiveConnectConfig, _describe_limits(), _describe_tools(), _is_heavenly_restricted(), _load_system_prompt(), Check if any argument references the restricted Personal-Assistant directory. (+5 more)

### Community 63 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 64 - "MemoryOverlay"
Cohesion: 0.17
Nodes (8): AudioDeviceOverlay, _HudOverlay, MemoryOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, Choose which microphone JARVIS listens to and which speakers it uses. Both…, Everything JARVIS has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 65 - "ui.py"
Cohesion: 0.13
Nodes (10): pyqt6_qtcore, pyqt6_qtgui, pyqt6_qtmultimedia, pyqt6_qtwidgets, random, C, _file_category(), _fmt_size() (+2 more)

### Community 66 - "_SessionRegistry"
Cohesion: 0.15
Nodes (5): _detect_default_browser(), Manages all active browser sessions., Is there an active automation session for this browser (or any)?, Returns the last natively-opened URL once (consumed to avoid repeats)., _SessionRegistry

### Community 67 - ".__init__"
Cohesion: 0.29
Nodes (6): index(), _ensure_certs(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the…, _read()

### Community 68 - "_VolumeSliderPopup"
Cohesion: 0.33
Nodes (3): QFrame, Sleek tactical cyber popup for adjusting master background music volume.…, _VolumeSliderPopup

### Community 69 - "WhisperSTT"
Cohesion: 0.33
Nodes (4): ndarray, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., WhisperSTT

### Community 71 - ".__init__"
Cohesion: 0.14
Nodes (4): _fl(), Floating overlay panel shown when the ⚙ header button is toggled., Collapsible panel below the HUD — shows search results, news, briefings. Hidden…, Returns True if auto-start is currently registered on this OS.

### Community 72 - "browser_control.py"
Cohesion: 0.24
Nodes (11): browser_control(), _find_exe_windows(), _find_opera_windows(), _log(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like…, Opens the user's REAL browser normally — with their own profile, logged-in… (+3 more)

### Community 73 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 74 - "open_app.py"
Cohesion: 0.25
Nodes (5): _normalize(), open_app(), psutil, 🛡️ 1. The Heavenly Restriction & Drive Access Lockdown, shutil

### Community 75 - "._decrypt"
Cohesion: 0.40
Nodes (4): command(), ws_ep(), _decrypt_cbc(), Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7.

### Community 76 - ".__init__"
Cohesion: 0.14
Nodes (5): QApplication, ConfirmBanner, _DropCanvas, The gate in front of an action that cannot be taken back. The old confirmation…, _RootShim

### Community 77 - "._launch"
Cohesion: 0.29
Nodes (5): _firefox_profile_dir(), launch_persistent_context already opens a starting tab. Instead of opening a…, Launches the browser with the real user profile. Does nothing if the context is…, _real_profile_dir(), Page

### Community 79 - "pathlib"
Cohesion: 0.22
Nodes (8): math, pathlib, pil, _check_python(), main(), MARK LIV — one-time setup. Installs the Python dependencies for THIS operating…, Fail immediately and clearly rather than deep inside a pip resolver. A wrong…, _run()

### Community 80 - "threading"
Cohesion: 0.29
Nodes (5): _run(), chord_label(), Push-to-talk — hold a key, speak, release. Why this exists ---------------…, Human-readable name of the chord, for the UI and the logs., threading

### Community 81 - "get_plugin_config"
Cohesion: 0.50
Nodes (4): get_plugin_config(), get_plugin_setting(), All stored values for a namespace (empty dict if none set yet)., A single value from a namespace, or `default` if unset.

### Community 82 - "_template.py"
Cohesion: 0.50
Nodes (3): Drop-in JARVIS plugin template. Copy this file, rename it (no leading…, parameters: dict of the args Gemini extracted, matching PLUGIN['parameters'].…, run()

### Community 83 - "_get_base_dir"
Cohesion: 0.67
Nodes (3): _get_api_key(), _get_base_dir(), Path

### Community 86 - "_ddg_news"
Cohesion: 0.33
Nodes (6): _ddg_news(), _format_news(), _get_ddgs(), _ddg_attempt(), Returns the DDGS class. The package was renamed duckduckgo-search -> ddgs; the…, DDG news search — returns actual articles, not website homepages.

### Community 87 - "get_push_to_talk_enabled"
Cohesion: 0.40
Nodes (3): get_push_to_talk_enabled(), Hold-a-key-to-speak. When on, the mic is closed unless the chord is held., Repaint the push-to-talk row from the saved setting.

### Community 88 - "weather_report.py"
Cohesion: 0.50
Nodes (4): _log(), weather_action(), urllib_parse, webbrowser

### Community 90 - "_QuotaCooldown"
Cohesion: 0.67
Nodes (3): _QuotaCooldown, Raised instead of calling Gemini while the quota breaker is open., RuntimeError

## Knowledge Gaps
- **16 isolated node(s):** `C`, `1. New Project Setup (One-Time)`, `Autonomous Multimodal AI Desktop Assistant & Tactical Terminal`, `🔴 2. Emoji-Free Tactical Telemetry Stream`, `📱 3. iPhone 16 Quantum Dashboard & Remote Terminal` (+11 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 670 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **15 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `MainWindow` connect `MainWindow` to `MemoryOverlay`, `ui.py`, `config_manager.py`, `.__init__`, `mono_font`, `.__init__`, `._apply_name_update`, `.clear_chat`, `setter`, `tech_font`, `._build_jarvis_icon`, `get_push_to_talk_enabled`, `.resizeEvent`, `.closeEvent`, `._apply_ptt_shortcut`?**
  _High betweenness centrality (0.113) - this node is a cross-community bridge._
- **Why does `JarvisUI` connect `JarvisUI` to `ui.py`, `.__init__`, `_tlog`, `JarvisLive`, `.__init__`, `._apply_name_update`, `.clear_chat`, `setter`, `get_push_to_talk_enabled`, `._apply_ptt_shortcut`, `main.py`?**
  _High betweenness centrality (0.058) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `load_api_keys`, `.__init__`, `VisemeStream`, `_tlog`, `PushToTalk`, `background_monitor.py`, `platform`, `memory_manager.py`, `JarvisUI`, `.run`, `EchoGuard`, `DashboardServer`, `_SysMetrics`, `WakeWordDetector`, `._play_audio`, `main.py`?**
  _High betweenness centrality (0.043) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `1. New Project Setup (One-Time)`, `Autonomous Multimodal AI Desktop Assistant & Tactical Terminal` to the rest of the system?**
  _16 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06190476190476191 - nodes in this community are weakly interconnected._
- **Should `MainWindow` be split into smaller, more focused modules?**
  _Cohesion score 0.06262626262626263 - nodes in this community are weakly interconnected._