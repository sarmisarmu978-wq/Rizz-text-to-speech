# 🎙️ Rizz-Text-To-Speech

**Rizz-Text-To-Speech** is a modern, browser-based Text-to-Speech (TTS) web application featuring a sleek **Glassmorphism** design and interactive floating **Bubble** animations. It allows users to convert written text into natural-sounding speech with customizable languages, voice characters, speech rate, and pitch—completely free and without requiring any API keys or backend setup.

---

## ✨ Key Features

- **🫧 Bubble & Glassmorphism UI**: Frosted-glass card interface (`backdrop-filter`) paired with smooth, floating 3D-styled background bubbles and responsive design.
- **🌍 Automatic Language Filtering**: Automatically detects all languages supported by the user's device/browser and formats language codes into human-readable names.
- **🎭 Voice Character Selection**: Dynamically filters available voice characters based on the selected language (supporting standard system voices as well as browser *Neural Voices*).
- **🎚️ Real-Time Audio Controls**:
  - **Speech Rate**: Adjust speaking speed from `0.5x` to `2.0x`.
  - **Voice Pitch**: Adjust vocal pitch from `0.5` to `1.8`.
- **⏯️ Full Playback Controls**: Includes **Play**, **Pause / Resume**, and **Stop** buttons, complete with an animated sound-wave indicator while speaking and a live character counter.
- **⚡ Zero Dependencies & Instant Setup**: Powered natively by the browser's **Web Speech API** (`window.speechSynthesis`), packaged into a single standalone `index.html` file.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for the web interface.
- **CSS3**: Glassmorphism styling, CSS custom properties, CSS Grid/Flexbox layouts, and keyframe animations for floating bubbles and audio wave indicators.
- **Vanilla JavaScript (ES6+)**: Voice synthesis logic, dynamic language/voice filtering, and Web Speech API integration.
- **Google Fonts**: Styled with *Plus Jakarta Sans* typography.

---

## 🚀 Getting Started

1. **Clone or download this repository:**
   ```bash
   git clone [https://github.com/sarmisarmu978/rizz-text-to-speech.git](https://github.com/your-username/rizz-text-to-speech.git)
