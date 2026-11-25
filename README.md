# tabletka

[![Version](https://img.shields.io/badge/Windows_x64-v0.9.8.61-a855f7?style=flat-square&logo=windows11&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan_Report-10b981?style=flat-square&logo=virustotal&logoColor=white)](https://www.virustotal.com/gui/file/1d6e151c053e649e6c6ab113f66c8202e391481a4c46dfec7f5726b65ae922ba)
[![.NET 8](https://img.shields.io/badge/.NET_8-WPF_60_FPS-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)

Lightweight native desktop overlay pill and widget center for **Windows (.NET 8 / WPF)** with optional **tabletkaCompanion (Android)** sync via `relay.699718.space`.

- **Official Landing & Download:** [tabletka.699718.space](https://tabletka.699718.space/?utm_source=github&utm_medium=readme&utm_campaign=tabletka_repo)
- **Android Companion App:** [tabletkaCompanion / Android](https://699718.space/companion.html?utm_source=github&utm_medium=readme&utm_campaign=companion)
- **Latest Windows x64 Installer:** [tabletka_0.9.8.61_x64_Setup.exe](https://699718.space/tabletka/tabletka_0.9.8.61_x64_Setup.exe) (`SHA-256: 1d6e151c…5ae922ba` · [VirusTotal](https://www.virustotal.com/gui/file/1d6e151c053e649e6c6ab113f66c8202e391481a4c46dfec7f5726b65ae922ba))
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

### What's New in v0.9.8.61
- **Lower RAM Footprint:** capped SMTC album-art decoding at `128 px` (-99% cover bitmap memory, saving up to 16 MB), enabled `.NET 8 DATAS` adaptive GC with LOH compaction, and removed duplicate locale dictionaries from RAM.
- **Zero Idle & Gaming CPU:** media UI timer and COM volume polling sleep completely when paused/collapsed, and 100 Hz `WasapiLoopbackCapture` stops during fullscreen games and when hidden to tray (offloading both `tabletka.exe` and Windows `audiodg.exe`).
- **About Dialog, Installer 2.0 & UX:** one-click Update button, live 10-language switcher with localized changelog, 2-step installer, and `Esc` / `←` / `→` shortcuts.
- **Background & GPU Fixes:** stopped inactive 1 Hz background timers, detached offscreen D3D shadow from hidden sub-pill, and switched game-priority boosts to zero-allocation Win32 calls.
