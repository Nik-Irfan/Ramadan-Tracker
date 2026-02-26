# Changelog

All notable changes to Ramadan RPG Tracker will be documented in this file.

## [2026-02-27] - v1.3.0

### Added
- **Waktu Solat Integration**: GPS-based JAKIM zone detection via `api.waktusolat.app`.
- **Prayer Times UI**: Compact pill on Tracker and panel on Profil with placement options.
- **Daily Caching**: Reduces API calls; refreshes every 30 seconds.
- **Zone Settings**: Display detected zone and manual refresh button.
- **Islamic Quotes**: Daily random quote with copy button and source/reference.
- **Level Badge Polish**: Adjusted glow, size, and border opacity.
- **Prayer Pill Alignment**: Matches streak pill styling and removes label.

### Changed
- Switched from AlAdhan API to Waktu Solat API for Malaysia-specific zones.
- Improved error handling: shows "No data/Tiada data" on API failure.
- Auto-detects zone on first enable; fallback to WLY01.

### Fixed
- Removed misplaced prayer panel from onboarding screen.
- Ensured `prayerRows()` method only exists on Alpine object.
- Fixed Quran font size 20px not applying (reduced line-height).
- Moved Edit button from floating to bottom of ibadah list.

## [2026-02-26] - v1.2.0

### Added
- **Hafazan Quiz**: MCQ and continuation modes with AI voice recognition.
- **Voice Mode**: Whisper + Tarteel integration for recitation analysis.
- **Quran Mushaf**: Page, surah, and juz views with adjustable font.
- **Community (Qariah)**: Mosque search, join, distance tracking, auto check-in.
- **Custom Missions**: User-defined ibadah with custom XP.
- **Retro Egg Companion**: Evolution system based on level/XP.

### Changed
- Refactored data structure to support multiple profiles and community.
- Enhanced badge definitions and unlock logic.
- Improved calendar view with streak indicators.

## [2026-02-25] - v1.1.0

### Added
- **Gamification Core**: XP, levels, badges.
- **Daily Streaks**: Visual calendar with streak tracking.
- **Multi-Profile Support**: Create and switch between profiles.
- **Dynamic Themes**: 6 color themes + dark mode.
- **PWA Support**: Service worker, manifest, install prompt.

### Changed
- Migrated from static HTML to Alpine.js reactivity.
- Centralized state in `localStorage`.

## [2026-02-18] - v1.0.0

### Added
- **Initial Release**: Basic ibadah tracking for Ramadan 2026.
- **Onboarding**: Profile creation and mode selection.
- **Core Missions**: Subuh, Zohor, Asar, Maghrib, Isyak, Tarawih, Witir, Quran, etc.
- **Simple Calendar**: Day selector with manual input.
- **Basic Stats**: Daily completion percentage and XP.

---

*Format: [YYYY-MM-DD] - vX.Y.Z*
