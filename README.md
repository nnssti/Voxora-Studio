# 🎙️ Voxora Studio

**Voxora Studio** is a powerful, open-source, offline-first video translation and AI dubbing desktop application. Engineered with a strong focus on high-quality Arabic localization, Voxora Studio offers full control over your workflows—supporting both local, privacy-focused offline engines and high-accuracy cloud APIs.

---

## ✨ Key Features

* **🌍 Arabic-First Localization:** Built with full support for RTL (Right-to-Left) text formatting, Arabic numeral normalization, and natural-sounding Arabic synthetic voices.
* **🎙️ Hybrid Dubbing Engine:** 
  * **Local & Offline:** Process audio completely on-device using local models like `whisper.cpp`, `Piper TTS`, and `Windows SAPI` with zero API fees or privacy leaks.
  * **Cloud Services:** Easily connect your own API keys (OpenAI, DeepL, Google Cloud Translation, etc.) for high-tier cloud performance.
* **🎨 Subtitle & Translation Customization:** Advanced subtitle styling options including custom colors, fonts, positioning, and visual tweaks.
* **⚡ Lossless Video Processing:** Powered by FFmpeg, Voxora Studio copies the original video stream whenever container specs allow—ensuring fast rendering with zero loss in video quality.
* **🔒 Privacy & Transparency:** Honest status indicators verify model files, keys, and binaries before execution. Your data stays under your control.

---

## 🛠️ Supported Integrations

| Feature | Supported Engines / Services |
| :--- | :--- |
| **Speech-to-Text (STT)** | `whisper.cpp` (Local), Custom APIs |
| **Translation** | LibreTranslate (Local/Self-hosted), Argos Translate (Offline), OpenAI Chat Translation, DeepL, Google Cloud Translation |
| **Text-to-Speech (TTS)** | Piper TTS (Offline), Windows SAPI (Local), Cloud Voice APIs |

---

## 🚀 Getting Started

1. **Download:** Grab the latest executable release from the [Releases]https://github.com/nnssti/Voxora-Studio/releases/tag/1.1.0) page.
2. **Import Video:** Drag and drop your video file (`MP4`, `MKV`, `MOV`, `AVI`, `WebM`, etc.).
3. **Configure Settings:** Choose your preferred translation and voice engines in the **Settings** menu.
4. **Generate:** Click to process translation, styling, and video dubbing!

---

## 📄 License

Voxora Studio is an open-source project released under the **MIT License**. Free to use, modify, and distribute.
