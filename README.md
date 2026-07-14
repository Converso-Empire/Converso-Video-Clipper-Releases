# Converso AI Video Clipper - Releases

Welcome to the official public release distribution repository for **Converso AI Video Clipper**.

This repository hosts compiled standalone binaries (`.exe` files) and version configuration files (`version.json`) used by the clipper's automated updater. 

> [!NOTE]
> The source code of Converso AI Video Clipper is maintained in a private repository to secure intellectual property, custom rendering pipelines, and license validation routines. Public users only need to download and run the compiled binaries from the Releases page here.

---

## 🚀 Key Features

* **Intelligent Vertical Crop**: Automatically detects the center of action or custom coordinates and outputs high-definition portrait videos ideal for TikTok, YouTube Shorts, and Instagram Reels.
* **Bypass Bot Checks**: Connects seamlessly with Chrome, Firefox, Edge, Brave, Opera, or Safari browser cookies to bypass YouTube bot prompts and `HTTP 429 Too Many Requests` limit walls.
* **OS-Level Temp Auto-Clean**: Performs all temporary downloading and rendering operations inside the system's temporary directory to save local disk space.
* **Clean Background Rendering**: Spawns rendering subprocesses (FFmpeg, yt-dlp, and metadata analyzers) invisibly without popping up command prompt terminal windows.
* **Taskbar Brand Association**: Explicit AppUserModelID registration binds custom application logos directly onto the Windows taskbar.
* **Forced Security Updates**: Validates startup client version manifests synchronously with the releases server on launch, locking access and applying hot-patches immediately when new updates are issued.

---

## 💾 Installation & Usage

1. Navigate to the **[Releases](https://github.com/converso-empire/Converso-Video-Clipper-Releases/releases)** section.
2. Download the latest `ConversoVideoClipper.exe` executable.
3. Run the application. On startup, the configuration files will be set up automatically under `%AppData%\Converso Developers\Converso Video Clipper\`.
4. Output clips will default directly to a space-free sanitized directory on your **Desktop**.

---

## 📄 License

This software is distributed under the MIT License. See the accompanying `LICENSE` file for details.
