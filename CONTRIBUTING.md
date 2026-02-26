# Contributing to Ramadan RPG Tracker

Thank you for your interest in contributing! This document provides guidelines for contributing to this project.

## 🚀 Quick Start

1. **Fork the repository** on GitHub.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Ramadan-Tracker.git
   cd Ramadan-Tracker
   ```
3. **Create a new branch** for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes**.
5. **Test thoroughly**.
6. **Submit a pull request** with a clear description.

## 📁 Project Structure

This is a **single-file application**. All HTML, CSS, and JavaScript live in `index.html`. Please keep your changes confined to this file unless absolutely necessary.

## 🧪 Testing

- **Self-Test Suite**: The app includes a built-in test suite. Open the browser console (F12) after making changes to verify logic.
- **Cross-Browser**: Test in Chrome, Firefox, and Safari/Edge.
- **Responsive**: Test on mobile and desktop viewports.
- **PWA**: Verify installability and offline behavior.

## 🎨 Style Guidelines

- **Tailwind CSS**: Use utility classes. Avoid custom CSS unless necessary.
- **Consistent Spacing**: Follow existing spacing patterns (e.g., `p-8`, `gap-4`, `mb-6`).
- **Color Palette**: Use theme variables (`text-main`, `bg-card`, `border-theme`, `gradient-accent`).
- **Icons**: Use Lucide icons; keep them consistent (`data-lucide="icon-name"`).

## 📝 Code Guidelines

### JavaScript (Alpine.js)
- Keep functions inside `trackerApp()` object.
- Use `this.save()` to persist important state changes.
- Follow existing naming conventions (camelCase for methods, kebab-case for data properties).
- Add comments for complex logic.

### HTML
- Use semantic tags (`header`, `main`, `section`, `footer`).
- Keep accessibility in mind (`aria-label`, `alt` tags).
- Use `x-cloak` to prevent flash of unstyled content.

### Localization
- Add new strings to the `t(key)` helper pattern.
- Provide both English and Bahasa Melayu translations.
- Use `lang === 'en' ? 'English' : 'Bahasa'` for UI strings.

## 🐛 Bug Reports

When reporting bugs, please include:
- **Browser and version**
- **Device/OS**
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Console errors** (if any)

## 💡 Feature Requests

- Check existing issues first.
- Provide a clear use case.
- Consider the app’s scope (Ramadan-focused, gamified ibadah tracker).

## 📩 Pull Request Process

1. **Update README.md** if you added significant features.
2. **Run the self-test suite** and ensure no failures.
3. **Rebase** onto the latest `main` branch.
4. **Submit PR** with:
   - Clear title
   - Detailed description
   - Screenshots if UI changes
   - Link to related issues

## 🤝 Code of Conduct

Be respectful and constructive. This project is for the benefit of the Muslim Ummah.

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

JazakAllah Khair for your contribution! 🙏
