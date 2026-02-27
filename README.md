# 🌙 Ramadan RPG Tracker 2026

A beautiful, gamified, and minimalist Ramadan Ibadah Tracker designed as a Progressive Web App (PWA). Track your daily prayers, fasting, and sunnah acts while earning XP, leveling up, and collecting badges!

## ✨ Features

### 🎮 Core Gamification
- **🎯 XP System**: Earn XP for every ibadah completed
- **📈 Level Progression**: Level up your hero profile with XP milestones
- **🔥 Streak Tracking**: Maintain daily streaks with visual flame indicators
- **🏆 Badge Collection**: Unlock special achievements and rewards
- **👥 Multi-Profile Support**: Perfect for families with multiple hero profiles

### 🕌 Ibadah Tracking
- **📅 Daily Ibadah**: Track Subuh, Zohor, Asar, Maghrib, Isyak, Tarawih
- **🌞 Sunnah Acts**: Tahajud, Dhuha, Sunat Rawatib, Qiyamullail
- **📖 Quran Reading**: Track by Juz or pages with progress visualization
- **🤲 Dhikr & Charity**: Istighfar, Selawat, Sedekah tracking
- **⭐ Friday Special**: Event Mingguan - Surah Al-Kahfi with epic animations
- **🎯 Custom Missions**: Add personal ibadah goals with custom XP rewards

### 🌟 Special Features
- **📅 Smart Calendar**: Ramadan 2026 calendar with accurate day alignment (1 Ramadan = Thursday, Feb 19, 2026)
- **📖 Digital Mushaf**: Built-in Quran reader with Uthmani script
- **🎤 Hafiz Quiz**: AI-powered verse memorization testing
- **⏰ Prayer Times**: GPS-based prayer times with live countdown timer
- **🎨 Dynamic Theming**: 6 color themes with dark mode support
- **📱 PWA Ready**: Install as native app with offline support

### 🎨 Visual Features
- **🌈 Theme Integration**: Dynamic theme colors throughout the app
- **✨ Epic Animations**: Friday special with moving glow, rotation, and breathing effects
- **📊 Progress Visualization**: Daily percentages, perfect day stars, streak indicators
- **🎪 Gamified UI**: Level badges, XP displays, achievement notifications
- **🌙 Ramadan Theme**: Beautiful loading screen with orbiting particles

## 🚀 Getting Started

### Quick Start
1. **Open the App**: Simply open `index.html` in any modern web browser
2. **Create Hero Profile**: Enter your name and choose difficulty mode
3. **Start Tracking**: Begin logging your daily ibadah activities
4. **PWA Installation**: Add to home screen for native app experience

### Installation Options
```bash
# Clone the repository
git clone https://github.com/your-username/Ramadan-RPG.git

# Navigate to the app directory
cd Ramadan-RPG/public\ -\ Tebuk

# Open in browser
# Double-click index.html or serve with a local server
python -m http.server 8000  # Optional: for better PWA testing
```

### PWA Installation
- **📱 Mobile**: Open in Chrome/Safari → Menu → "Add to Home Screen"
- **💻 Desktop**: Click install icon in browser address bar
- **🔧 Offline**: Works offline once installed

## 🎮 Difficulty Modes

### 🟢 EASY Mode
Perfect for beginners focusing on core ibadah:
- Fardu prayers + Sunat Subuh + Sahur
- Basic Quran reading (10 pages)
- Simple dhikr (50x Istighfar/Selawat)
- **Total Focus**: Consistency building

### 🟡 NORMAL Mode  
Balanced approach for regular practitioners:
- All fardu + Sunat Rawatib + Tahajud
- Quran by Juz (1-2 Juz daily)
- Comprehensive dhikr (100x)
- **Total Focus**: Complete spiritual routine

### 🔴 HARD Mode
Maximum challenge for advanced users:
- Extended Tahajud (4-8 Rakaat)
- Full Sunat Rawatib + Qiyamullail
- Advanced Quran (2-4 Juz)
- Enhanced dhikr (200x)
- **Total Focus**: Peak spiritual performance

## 🌟 Friday Special: Event Mingguan

### Surah Al-Kahfi Features
- **⭐ Weekly Event**: Only appears on Fridays (Jumaat)
- **🎨 Epic Animations**: Moving glow, rotation, breathing effects
- **🌈 Theme Colors**: Dynamic colors matching user's theme selection
- **📜 Two Options**: 
  - 10 Ayat Awal Al-Kahfi (5 XP)
  - Full Surah Al-Kahfi (10 XP)
- **✨ Visual Effects**: 
  - Breathing animation (opacity: 100% → 60% → 100%)
  - Continuous rotation (360° every 8 seconds)
  - Pulsing ring effects
  - Theme-colored glow and border
  - Slight scaling for prominence

## ⏰ Prayer Times Integration

### GPS-Based Detection
- **📍 Auto-Detection**: Uses device GPS to find Malaysian prayer zones
- **🗺️ Zone Support**: All Malaysian prayer zones (WLY01-WLY14)
- **⏱️ Live Countdown**: Shows time until next prayer (e.g., "1j 15m")
- **🔄 Auto-Update**: Refreshes every 30 seconds
- **📱 Front Page Display**: Shows next prayer when enabled

### Prayer Sequence
1. **Subuh (Fajr)** → **Zohor (Dhuhr)** → **Asar (Asr)** → **Maghrib** → **Isyak (Isha)**
2. **After Isyak**: Shows "Subuh (esok)" for next day
3. **Bilingual Support**: Malay/English prayer names

## 🎨 Theme System

### Available Themes
- **🟢 Emerald**: Green theme with natural vibes
- **🌹 Rose**: Pink theme with warm tones  
- **🌊 Ocean**: Blue theme with calming colors
- **🟣 Purple**: Royal purple theme
- **🌸 Pink**: Soft pink theme
- **🏆 Gold**: Luxurious gold theme

### Theme Features
- **🌓 Dark Mode**: Dedicated dark/light mode toggle
- **🎯 Dynamic Colors**: All UI elements adapt to theme
- **✨ Consistent Design**: Buttons, badges, glows use theme colors
- **🔄 Instant Switch**: No page reload required

## 📊 Progress Tracking

### Daily Visualization
- **📅 Calendar View**: Visual Ramadan calendar with daily percentages
- **📊 List View**: Sequential day selection with progress bars
- **⭐ Perfect Days**: Star indicator for 50+ XP days
- **🔥 Streak Flames**: Visual streak continuity indicators
- **📈 Percentage Display**: Color-coded progress (80%+ green, 40%+ yellow, <40% red)

### Achievement System
- **🏆 Level Badges**: Bronze, Silver, Gold based on total XP
- **🎯 Special Badges**: 
  - "Baitul Jannah" (12 Rakaat Sunat)
  - "Perfect Day" (50+ XP)
  - "Streak Master" (Consecutive days)
- **📊 Statistics**: Total XP, current level, progress to next level

## 🛠️ Technical Features

### Built With Modern Tech
- **[Alpine.js](https://alpinejs.dev/)**: Reactive state management
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first styling
- **[Lucide Icons](https://lucide.dev/)**: Beautiful icon system
- **[Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)**: PWA capabilities

### Data & Privacy
- **🔒 Local Storage**: All data stored locally in browser
- **🚫 No Accounts**: No registration or internet required
- **📱 Offline First**: Works completely offline
- **💾 Auto-Save**: Progress saved automatically
- **🔄 Data Persistence**: Survives browser restarts

### API Integrations
- **🕌 Prayer Times**: `https://api.waktusolat.app/v1/solat/` for Malaysian prayer times
- **📖 Quran API**: `https://api.alquran.cloud/v1/` for Quran verses and surah data
- **📍 Geolocation**: Browser GPS for zone detection

## 🧪 Quality Assurance

### Built-in Testing
- **🔍 Self-Test Suite**: Automatic logic verification on startup
- **📝 Console Logging**: Detailed debugging information
- **🎯 Error Handling**: Graceful fallbacks for API failures
- **🔧 Validation**: Input validation and data integrity checks

### Browser Compatibility
- **🌐 Modern Browsers**: Chrome, Firefox, Safari, Edge
- **📱 Mobile Support**: Responsive design for all screen sizes
- **🔧 PWA Features**: Service workers, manifest, offline support

## 🎯 Usage Tips

### Best Practices
1. **📅 Daily Routine**: Check in each day for consistent tracking
2. **🎯 Set Goals**: Use custom missions for personal targets
3. **👥 Family Mode**: Create profiles for all family members
4. **📱 PWA Install**: Install for best experience and notifications
5. **⏰ Prayer Times**: Enable for accurate prayer schedules

### Advanced Features
- **📖 Quran Reader**: Use built-in mushaf for reading tracking
- **🎤 Hafiz Quiz**: Test memorization with AI voice recognition
- **🎨 Theme Customization**: Switch themes for visual variety
- **📊 Progress Analysis**: Review stats for improvement areas

## 💖 Support & Community

### Get Help
- **📧 Report Issues**: Use GitHub Issues for bug reports
- **💡 Feature Requests**: Suggest improvements via discussions
- **📖 Documentation**: Check inline comments for code understanding

### Support the Developer
If you find this project useful for your Ramadan journey:

- **☕ [Buy Me a Coffee](https://buymeacoffee.com/nikirfan)**: Support continued development
- **⭐ [Star Repository](https://github.com/Nik-Irfan/Ramadan-Tracker)**: Show appreciation
- **🔗 [Connect on LinkedIn](https://my.linkedin.com/in/nikirfan98)**: Professional network
- **📱 Share App**: Help others benefit from this tool

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Setup
```bash
# Fork the repository
# Create your feature branch
git checkout -b feature/AmazingFeature

# Make your changes
# Test thoroughly

# Commit your changes
git commit -m 'Add some AmazingFeature'

# Push to the branch
git push origin feature/AmazingFeature

# Open a Pull Request
```

---

## 🌟 Ramadan 2026 Information

**Important Dates for Ramadan 2026:**
- **1 Ramadan**: Thursday, February 19, 2026
- **Tarawih Start**: Wednesday night, February 18, 2026
- **Total Days**: 30 days
- **Eid al-Fitr**: Friday, March 21, 2026 (estimated)

**App Features for Ramadan 2026:**
- ✅ Accurate day alignment with Islamic calendar
- ✅ Friday special events properly positioned
- ✅ Malaysian prayer times integration
- ✅ Localized for Malaysian users
- ✅ Dark mode for night-time ibadah tracking

---

*Built with ❤️ and 🌙 for a more productive and spiritually fulfilling Ramadan 2026*

**May your Ramadan be blessed with barakah, spiritual growth, and consistent ibadah. 🤲✨**
