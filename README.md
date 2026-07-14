<div align="center">

# 🎬 Converso Video Clipper

**Turn any long-form video into scroll-stopping vertical clips — automatically.**

[![Latest Release](https://img.shields.io/github/v/release/converso-empire/Converso-Video-Clipper-Releases?label=latest&color=6C5CE7)](https://github.com/converso-empire/Converso-Video-Clipper-Releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/converso-empire/Converso-Video-Clipper-Releases/total?color=00b894)](https://github.com/converso-empire/Converso-Video-Clipper-Releases/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6?logo=windows)](#-installation--usage)
[![License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)

[Download](#-installation--usage) · [Features](#-key-features) · [FAQ](#-faq) · [Support](#-support)

</div>

---

Welcome to the official public release repository for **Converso Video Clipper** — the desktop tool for turning long videos into short, high-impact clips ready for TikTok, YouTube Shorts, and Instagram Reels.

This repo hosts the signed Windows binaries and the `version.json` manifest used by the app's built-in auto-updater.

> [!NOTE]
> The source code, rendering pipeline, and license-validation logic are maintained in a private repository to protect the intellectual property behind Converso. You only need the compiled app from this page — no setup, no dependencies, no command line.

---

## 🚀 Key Features

- **Intelligent Vertical Crop** — automatically detects the center of action (or lets you set custom coordinates) to output high-definition portrait video.
- **Bot-Check Bypass** — reads cookies from Chrome, Firefox, Edge, Brave, Opera, or Safari to get past YouTube's sign-in walls and `HTTP 429` rate limits.
- **Zero Disk Clutter** — all downloading and rendering happens in your system temp directory and is cleaned up automatically.
- **Silent Background Rendering** — FFmpeg, yt-dlp, and metadata analysis all run invisibly, with no terminal windows popping up.
- **Native Windows Branding** — proper AppUserModelID registration so the app icon shows correctly pinned to your taskbar.
- **Always Up To Date** — the app checks its version manifest on every launch and applies hot-patches immediately when a new release goes out.

---

## 💾 Installation & Usage

1. Go to the **[Releases page](https://github.com/converso-empire/Converso-Video-Clipper-Releases/releases/latest)**.
2. Download `ConversoVideoClipper.exe`.
3. Run it — on first launch it creates its config folder at `%AppData%\Converso Developers\Converso Video Clipper\`.
4. Finished clips land in a clean, space-free folder on your **Desktop** by default.

No installer, no admin rights, no extra downloads required.

---

## ❓ FAQ

**Is this safe to run?**
Yes — the binary is built and signed directly from our private source repository via automated CI. Nothing here is hand-uploaded.

**Why is the source code private?**
The clipper relies on proprietary rendering and licensing logic we're not open-sourcing. You get the compiled tool; the internals stay protected.

**How do updates work?**
The app checks `version.json` in this repo on launch and prompts (or auto-applies) an update when a newer release is published.

---

## 🛟 Support

Found a bug or have a feature request? Open an [issue](https://github.com/converso-empire/Converso-Video-Clipper-Releases/issues) — the Converso Developers team monitors this repo directly.

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE) for the full text.

<div align="center">

Built with ⚙️ by **[Converso Empire](https://conversoempire.world)**

</div>