# tabletka

[![Version](https://img.shields.io/badge/Windows_x64-v0.9.8.65-a855f7?style=flat-square&logo=windows11&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F68_Clean-10b981?style=flat-square&logo=virustotal&logoColor=white)](https://www.virustotal.com/gui/file/f40685ebf6e045ad09b46d7b25c27a5cc2b13ca0eb8405ffd1477bfc0ab0ef7e)
[![.NET 8](https://img.shields.io/badge/.NET_8-WPF_60_FPS-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)

Lightweight native desktop overlay pill and widget center for **Windows (.NET 8 / WPF)** with optional **tabletkaCompanion (Android)** sync via `relay.699718.space`.

- **Official Landing & Download:** [tabletka.699718.space](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
- **Android Companion App:** [tabletkaCompanion / Android](https://699718.space/companion.html?utm_source=github&utm_medium=readme&utm_campaign=companion)
- **Latest Windows x64 Installer:** [tabletka_0.9.8.65_x64_Setup.exe](https://699718.space/tabletka/tabletka_0.9.8.65_x64_Setup.exe) (`SHA-256: f40685eb…0ab0ef7e` · [VirusTotal 0/68](https://www.virustotal.com/gui/file/f40685ebf6e045ad09b46d7b25c27a5cc2b13ca0eb8405ffd1477bfc0ab0ef7e))
- **Contact & Support:** [@eggrib](https://t.me/eggrib)

## Preview

![tabletka compact pill](assets/backdrop-392x105-20261123-015717.png)

| Compact Capsule on Desktop | Expanded Media Widget |
| --- | --- |
| ![tabletka desktop capsule](assets/backdrop-491x250-20261123-015839.png) | ![tabletka expanded media player](assets/backdrop-491x250-20261123-015852.png) |

| 16 Modules Control Panel | Edge Docking, Game Hide & 10 Languages |
| --- | --- |
| ![tabletka 16 modules settings](assets/backdrop-647x376-20261122-171356.png) | ![tabletka system settings and 10 languages](assets/backdrop-647x376-20261122-171407.png) |

![tabletka hardware monitors](assets/backdrop-647x300-20261122-171108.png)

## Key Features

- **Compact Pill Form-Factor:** Edge-dragging top screen capsule with instant expansion into full widgets.
- **16 Built-in Modules:** Media player with live lyrics, clipboard link downloader, screen backdrop & recorder, screenshot auto-copy, File Pocket, system & market monitors, server pulse, notes/snippets, Pomodoro timer, habits, and quick tools.
- **Performance & Throttling:** Two-thread download queue, fullscreen game auto-hide, and smart background module throttling.
- **10 Languages:** Full UI localization (`en`, `ru`, `de`, `fr`, `es`, `he`, `ja`, `ko`, `zh`, `tr`).

## Distribution Policy

Official builds are distributed exclusively as compiled Windows x64 installers via [tabletka.699718.space](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo) and GitHub Releases. Source code is private to ensure binary integrity and prevent unauthorized clones.

### What's New in v0.9.8.65
- **Safe Categorized Disk Cleaner:** Interactive category checkboxes (`Temp`, `Cache`, `Logs`, `Recycle Bin` — Recycle Bin unchecked by default), live size recount, folder-breakdown tooltips on hover, and strict OS/GPU system paths only (`%TEMP%`, `Windows\Temp`, GPU shader & Windows Update caches, WER dumps) with immediate RAM cleanup.
- **Complete UI Anti-Freeze & RelaySync Stability:** Moved CoreAudio COM calls, background STA audio output switching, direct non-blocking Win32 `CF_UNICODETEXT` clipboard reads, system proxy updates, and drive/network probes off the WPF UI thread; eliminated 22-second WebSocket reconnect loops on `relay.699718.space`.
- **Voice Recorder 2.0 & Call Studio:** 3 one-click CoreAudio WASAPI 48 kHz capture modes (`🎙 Mic`, `🎙+🔊 Mic+PC` with real-time resampling and soft-clip limiting, and `🔊 PC Audio` loopback), live 28-bar waveform, Pause/Resume (`⏸ / ▶`), built-in mini-player, and global `Ctrl+Alt+D` hotkey.
- **Zero Idle/Gaming CPU & Installer Refinements:** Persistent first-install settings across updates, 4 Audio Glow color modes, `128 px` SMTC cover decoding, `.NET 8 DATAS` adaptive GC, and automatic 100 Hz WASAPI/timer sleep in fullscreen games and tray.
