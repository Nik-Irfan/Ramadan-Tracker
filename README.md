# 🌙 Ramadan RPG Tracker 2026

A beautiful, gamified, and minimalist Ramadan Ibadah Tracker designed as a Progressive Web App (PWA). Track your daily prayers, fasting, and sunnah acts while earning XP, leveling up, and collecting badges!

## ✨ Features

- **🎮 Gamified Experience**: Earn XP for every ibadah, level up your profile, and maintain daily streaks.
- **🏆 Badge System**: Unlock special badges like "Baitul Jannah" (12 Rakaat Sunat), "Perfect Day", and Tiered Hero badges (Bronze, Silver, Gold).
- **👥 Multi-Profile Support**: Perfect for families! Create multiple "Hero" profiles on a single device.
- **🎨 Dynamic Theming**: 6 beautiful color themes (Emerald, Rose, Ocean, Purple, Pink, Gold) with a dedicated Dark Mode.
- **📅 Smart Calendar**: Toggle between List View and Calendar View. Includes auto-sync for Ramadan 2026 (Starting Feb 18).
- **📖 Digital Mushaf**: Read Quran directly in the app with Uthmani script support and adjustable font size/family.
- **🎤 Hafazan Quiz**: Test your memorization by completing random verses from any Juz with AI voice recognition (Whisper + Tarteel).
- **🕌 Waktu Solat**: GPS-based JAKIM zone detection with daily caching; shows next prayer countdown and full list in modal.
- **🌍 Community (Qariah)**: Join a mosque, see distance from home/destination, and auto-check-in when nearby during prayer times.
- **📝 Custom Missions**: Add your own personal ibadah goals with custom XP rewards.
- **💬 Islamic Quotes**: Daily random quote with copy-to-clipboard and source/reference.
- **📱 PWA Ready**: Install it on your phone for a native app experience with offline support.
- **🔒 Private & Secure**: All data is stored locally in your browser's `localStorage`. No accounts or internet required for core features.

## 🚀 Getting Started

1. **Clone repository**:
   ```bash
   git clone https://github.com/your-username/Ramadan-RPG.git
   ```
2. **Open `index.html`**:
   Simply open `index.html` file in any modern web browser.
3. **PWA Installation**:
   - **On Mobile**: Open in Chrome/Safari, then select "Add to Home Screen".
   - **On Desktop**: Click the install icon in the browser address bar.
4. **Permissions**:
   - Allow Location for GPS-based prayer times and Qariah features.
   - Allow Microphone for voice mode in Hafazan Quiz.

## 🛠️ Built With

- [Alpine.js](https://alpinejs.dev/) - Reactive logic and state management.
- [Tailwind CSS](https://tailwindcss.com/) - Modern utility-first styling.
- [Lucide Icons](https://lucide.dev/) - Beautiful minimalist icons.
- [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) - For offline PWA capabilities.

## 📡 APIs Used

- **Waktu Solat**: `https://api.waktusolat.app` - Malaysia prayer times by JAKIM zones.
- **Quran**: `https://api.alquran.cloud/v1` - Quran verses and metadata.
- **Transcription**: OpenAI Whisper API - Arabic speech-to-text.
- **Recitation Analysis**: Tarteel API - Verse matching and error detection.

## 🧪 Self-Test Suite

The app includes a built-in self-test suite that runs automatically on startup. Check the browser console (F12) to see results of logic verification.

## ⚙️ Configuration

### API Keys
To enable voice transcription and recitation analysis:
1. Replace `YOUR_OPENAI_API_KEY` in the `transcribeWithWhisper` function.
2. Replace `YOUR_TARTEEL_API_KEY` in the `analyzeWithTarteel` function.

### Data Storage
All data persists in `localStorage` under key `ramadan_rpg_data`. Includes:
- Profiles and progress
- Settings (theme, language, prayer zone)
- Badge collection
- Community data

## 📁 Project Structure

```
index.html          # Single-page app with all HTML/JS/CSS
sw.js              # Service worker for PWA offline support
README.md           # This file
```

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch.
3. Keep changes single-file (`index.html`).
4. Submit a PR with a clear description.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Support Developer

If you find this project useful, please consider supporting my work:

- [☕ Buy Me a Coffee](https://buymeacoffee.com/nikirfan)
- [⭐ Star Repository](https://github.com/Nik-Irfan/Ramadan-Tracker)
- [🔗 Connect on LinkedIn](https://my.linkedin.com/in/nikirfan98)

---

*Built with ❤️ for a more productive Ramadan.*
