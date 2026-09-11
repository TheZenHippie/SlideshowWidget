# 🖼️ SlideshowWidget v1.0.1

**SlideshowWidget v1.0.1** brings recursive subdirectory scanning, shuffled/randomized playback, continuous looping, custom interval presets, and zero-file-lock memory optimization to your Windows desktop.

---

## 🌟 What's New in v1.0.1

- 🔄 **Recursive Subdirectory Scanning**: Toggle subdirectory recursion directly from the Windows folder picker or the right-click menu to include all nested photos across deep folder structures.
- 🔀 **Randomized Playback (Shuffle)**: Plays through your photo library in randomized order, performing a full shuffle cycle before reshuffling to ensure all images are shown.
- 🔁 **Continuous Slideshow Looping**: Slideshows run seamlessly in endless loops without stopping until closed.
- ⏱️ **Custom Interval Slider & Extended Presets**: Fine-tune transition delay from 1s to 60s with the live slider or mouse wheel, or pick from extended presets (10s, 30s, 1m, 2m, 5m, 10m, 30m).
- 📐 **Automatic EXIF Orientation**: Native hardware-accelerated lossless orientation correction for portrait smartphone photos (iPhone, Samsung Galaxy, Google Pixel, DSLR).
- 🪟 **Multi-Instance Support**: Launch multiple independent widgets across multiple monitors with separate folders, intervals, and opacities.
- 🔒 **Zero File Locking**: Files on disk remain unlocked, allowing you to edit, move, or delete photos while the slideshow is running.

---

## 📦 Downloads & Installation

| Asset | Description | Size |
| :--- | :--- | :--- |
| **`SlideshowWidget.exe`** | **Standalone Executable** (Recommended) — Double-click and run immediately. No .NET runtime installation required. | ~69.5 MB |
| **`SlideshowWidget-v1.0.1-win-x64-standalone.zip`** | **Standalone ZIP** containing `SlideshowWidget.exe`, `README.md`, and `LICENSE`. | ~64.2 MB |
| **`SlideshowWidget-v1.0.1-win-x64-framework-dependent.zip`** | **Lightweight ZIP** for systems with [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) already installed. | ~1.4 MB |

---

## 🛡️ File Integrity & Checksums (SHA-256)

Verify downloaded binaries using Windows PowerShell:
```powershell
Get-FileHash SlideshowWidget.exe -Algorithm SHA256
```

Checksums:
```
69211db6eb345c1cb15c4a6f024c52d152ae8efd0897bda2d55ea198c1ae6d55  SlideshowWidget-v1.0.1-win-x64-framework-dependent.zip
820884df7badbb3d6a9cd039a818330703e11a4a4b8af64d18980dcd2288fc5e  SlideshowWidget-v1.0.1-win-x64-standalone.zip
c997aad26b43cee4c6a6c309c05afca76b26ae67d799aeaf9788f2a2aed383cf  SlideshowWidget.exe
```

---

## 💻 System Requirements
- **OS**: Windows 10 or Windows 11 (64-bit)
- **Dependencies**: None for the standalone edition; [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) for the framework-dependent edition.

