<div align="center">

# 📋 Changelog

All notable changes to **V-Raykally** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

</div>

---

## [1.4.2] - 2026-06-28

> 🍎 **macOS 1.4.2 Distribution Update**

### Changed

- **macOS Apple Silicon Package** — Updated the public Apple Silicon DMG to V-Raykally 1.4.2.
- **macOS Intel Package** — Updated the public Intel x64 DMG to V-Raykally 1.4.2.
- **Download Links** — Updated public release links and documentation for the current macOS packages.

### Verification

- Both DMG files are Developer ID signed.
- Both embedded `.app` bundles report version 1.4.2.
- `codesign --deep --strict` passes for both macOS builds.

## [1.4.1] - 2026-06-09

> 🚀 **Local AI, Store Delivery & Workflow Polish**

### ✨ Added

- **Local AI Diagnostics** — On-device assistance for understanding render failures without relying on a cloud AI service.
- **Microsoft Store Delivery** — Public Windows distribution through the Microsoft Store.
- **Store-Ready Delivery Foundation** — Better packaged resources for local rendering, diagnostics, languages, licenses, and notices.
- **Expanded Public Guidance** — Clearer release, download, privacy, and V-Ray setup messaging.

### 🔄 Changed

- **V-Ray Setup Experience** — Improved discovery and validation language for V-Ray Standalone paths.
- **Queue Experience** — Refined public messaging around live status, retry workflows, and drag-and-drop priority.
- **macOS Distribution** — Updated public downloads for Apple Silicon and Intel DMG packages.
- **Windows Positioning** — Clarified the Microsoft Store path for Windows users.
- **Author Naming** — Normalized public author credits to Adrien Lejeune.

### 🐛 Fixed

- **Documentation Versioning** — Replaced outdated 1.3.1 references across the public README.
- **Release Presentation** — Reworked the GitHub home page into a clearer product landing page.
- **License Clarity** — Clarified that Chaos V-Ray and Chaos licenses are separate requirements.

---

## [1.3.1] - 2026-01-17

> 🔧 **Stability & Polish Release**

### ✨ Added

- **Smart Language Detection** — Improved auto-detection of system language for seamless localization.

### 🔄 Changed

- **UI Responsiveness** — Better layout stability when resizing the window; improved resistance to width reduction.
- **Mac Optimization** — Slight performance improvements on macOS.

### 🐛 Fixed

- **Windows Stability** — Fixed specific bugs on the Windows version.
- **Visual Polish** — Corrected various visual glitches and layout issues.
- **Platform Detection** — Fixed regression in platform detection hook.

---

## [1.3.0] - 2026-01-15

> 🎉 **Windows Store Launch**

### ✨ Added

- **Windows Store Release** — First official release on the [Microsoft Store](https://apps.microsoft.com/detail/9P6T4BVX32J6) for Windows x64 & ARM64.
- **Architecture Overhaul** — Major internal refactoring and optimization for better cross-platform support.

### 🐛 Fixed

- **Legacy Bug Fixes** — Resolution of various issues from previous versions.

---

## [1.2.0] - 2026-01-13

> ⚡ **Power User Features**

### ✨ Added

- **Simple/Pro Settings Modes** — New toggle in settings to switch between a streamlined "Simple" view and a granular "Pro" view.
- **Drag-and-Drop Job Reordering** — Ability to reorder jobs in the queue directly from the dashboard.
- **Improved Job Management** — Enhanced control over jobs during active rendering (stop, restart, reorder).
- **15 Language Support** — Complete translations for:
  - 🇬🇧 English, 🇫🇷 French, 🇩🇪 German, 🇪🇸 Spanish, 🇮🇹 Italian
  - 🇵🇹 Portuguese, 🇨🇳 Chinese, 🇯🇵 Japanese, 🇰🇷 Korean, 🇸🇦 Arabic
  - 🇮🇳 Hindi, 🇷🇺 Russian, 🇮🇩 Indonesian, 🇹🇷 Turkish, 🇵🇱 Polish
- **Resilient State Synchronization** — Improved backend-frontend synchronization for job statuses and queue state.

### 🔄 Changed

- Refined UI styling for the Settings Modal and Dashboard.
- Optimized backend startup and shutdown procedures for better reliability.
- Centralized translation keys for better maintainability.

### 🐛 Fixed

- Resolved issues with job execution order in the queue.
- Fixed various UI alignment and styling bugs in the header and settings.

---

## [1.1.0] - 2025-12-20

> 🚀 **Initial Public Release**

### ✨ Features

- **Intuitive Dashboard** — Real-time render queue management with light/dark themes.
- **Powerful V-Ray Integration** — Seamless connection with V-Ray Standalone and smart job queuing.
- **Multi-Language Support** — Available in 7 languages (EN, FR, DE, ES, IT, ZH, TR).
- **Cross-Platform** — Native macOS support (Apple Silicon & Intel).
- **Privacy First** — 100% local operation, no data collection.

---

## [1.0.1] - 2025-12-12

> 🛠️ **Internal Beta**

- Initial production-ready version for internal testing.

---

<div align="center">

**Made with ❤️ by [Workally](https://workally.com.br) in São Paulo, Brazil**

[Website](https://v-raykally.online) • [GitHub](https://github.com/workallybrasil/V-Raykally) • [Microsoft Store](https://apps.microsoft.com/detail/9P6T4BVX32J6)

</div>
