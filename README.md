# Voice Note (GitHub Pages Version)

This is a lightweight, pure-frontend voice note application designed to be deployed on GitHub Pages. It uses the browser's native **Web Speech API** for speech recognition.

## 🚀 Features

- **No Backend**: Runs entirely in the browser.
- **Privacy First**: Audio is processed by the browser vendor (Apple/Google) and not sent to any third-party server.
- **Cyberpunk UI**: Cool dark mode design.
- **Mobile Ready**: Optimized for iOS (Safari) and Android (Chrome).
- **QR Code**: Built-in QR code generator for easy sharing.

## 📦 How to Deploy

1. **Create a Repository**:
   - Go to GitHub and create a new public repository (e.g., `my-voice-note`).

2. **Upload File**:
   - Upload the `index.html` file from this folder to your repository.

3. **Enable Pages**:
   - Go to `Settings` -> `Pages`.
   - Source: `Deploy from a branch`.
   - Branch: `main` (or master) / Folder: `/ (root)`.
   - Click **Save**.

4. **Enjoy**:
   - Wait a minute, then visit your site at: `https://<your-username>.github.io/my-voice-note/`

## ⚠️ Requirements

- **HTTPS**: The Web Speech API requires a secure context (HTTPS). GitHub Pages provides this automatically.
- **Browser Support**:
  - **iOS**: Must use **Safari**.
  - **Android**: Must use **Chrome** (requires Google Services/Network access) or Edge.
  - **Desktop**: Chrome, Edge, Safari.
  - *Note: Firefox and WeChat built-in browsers are NOT supported.*

