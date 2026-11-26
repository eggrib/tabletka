# tabletka

[![Version](https://img.shields.io/badge/Windows_x64-v0.9.8.64-a855f7?style=flat-square&logo=windows11&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F68_Clean-10b981?style=flat-square&logo=virustotal&logoColor=white)](https://www.virustotal.com/gui/file/aac80299cdda284c3e951c1fbd3ee865bd090ed9e455caf119728b34432d2cfd)
[![.NET 8](https://img.shields.io/badge/.NET_8-WPF_60_FPS-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)

Lightweight native desktop overlay pill and widget center for **Windows (.NET 8 / WPF)** with optional **tabletkaCompanion (Android)** sync via `relay.699718.space`.

- **Official Landing & Download:** [tabletka.699718.space](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
- **Android Companion App:** [tabletkaCompanion / Android](https://699718.space/companion.html?utm_source=github&utm_medium=readme&utm_campaign=companion)
- **Latest Windows x64 Installer:** [tabletka_0.9.8.64_x64_Setup.exe](https://699718.space/tabletka/tabletka_0.9.8.64_x64_Setup.exe) (`SHA-256: aac80299…432d2cfd` · [VirusTotal 0/68](https://www.virustotal.com/gui/file/aac80299cdda284c3e951c1fbd3ee865bd090ed9e455caf119728b34432d2cfd))
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

### What's New in v0.9.8.64
- **Voice Recorder 2.0 & Call Studio:** 3 one-click CoreAudio WASAPI 48 kHz capture modes (`🎙 Mic`, `🎙+🔊 Mic+PC` with real-time resampling and soft-clip limiting for synchronized call & lecture recording, and `🔊 PC Audio` loopback), Windows microphone picker, and one-click OS unmute.
- **Live Waveform & Built-in Mini-Player:** 28-bar real-time scrolling waveform, seamless Pause / Resume (`⏸ / ▶`) into a single file, cancel take (`✕`), `MP3 (192 kbps)` / `M4A` / `WAV` output formats, instant playback & seek bar right inside `tabletka`, one-click file copy to clipboard (`📋` → `Ctrl+V` into chat apps), Drag & Drop, and global `Ctrl+Alt+D` hotkey.
- **Audio Glow Color Modes & Compact Pill Controls:** 4 audio glow & spectrum presets (`Album Art`, `Signature Cyan`, `White Monochrome`, `Windows Accent`), directly clickable Pause/Stop recording buttons on the collapsed pill without expanding, and enriched hardware/timezone diagnostics.
- **Zero Idle/Gaming CPU & .NET 8 Reliability:** `128 px` SMTC cover decoding (-99% cover bitmap RAM), `.NET 8 DATAS` adaptive GC, automatic 100 Hz WASAPI/timer sleep in fullscreen games and tray, and hardened `.NET 8` JSON state persistence.
