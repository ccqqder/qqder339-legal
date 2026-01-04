# qqder339-legal

Centralized legal documents and privacy policies for all apps developed by **ChengChe Lee** (qqder339).

🌐 **Live Site**: [https://ccqqder.github.io/qqder339-legal/](https://ccqqder.github.io/qqder339-legal/)

## Purpose

This repository hosts privacy policies and legal documents for my apps in a centralized, maintainable format. All policies are:

- ✅ **Bilingual** (Traditional Chinese + English)
- ✅ **Mobile-responsive** with clean design
- ✅ **Shared components** for consistent messaging
- ✅ **Version controlled** for transparency

## Repository Structure

```
qqder339-legal/
├── index.html                    # Portal page listing all apps
├── assets/
│   └── style.css                 # Shared stylesheet
├── _shared/                      # Reusable legal components
│   ├── contact_info.md
│   ├── offline_ai.md
│   └── data_security.md
├── english-n-plus-1/             # English N+1 app
│   └── privacy.html
└── README.md                     # This file
```

## Current Apps

### English N+1
- **Privacy Policy**: [english-n-plus-1/privacy.html](./english-n-plus-1/privacy.html)
- **App Store**: _Coming soon_
- **Features**: CEFR-leveled vocabulary, i+1 reading articles, on-device LLM, Write Better chatbot
- **Privacy**: Fully offline, no analytics, on-device AI

## Adding New Apps

To add a privacy policy for a new app:

1. Create a new directory: `new-app-name/`
2. Copy and adapt `english-n-plus-1/privacy.html`
3. Update `index.html` to add the new app card
4. Commit and push changes
5. GitHub Pages will auto-deploy

## Shared Components

Located in `_shared/`, these markdown files contain reusable legal language:

- **contact_info.md**: Developer contact information
- **offline_ai.md**: On-device AI privacy explanation
- **data_security.md**: Local storage and no third-party services clause

These are referenced in privacy policies but not directly linked (for maintainability).

## Privacy Commitment

All apps by ChengChe Lee follow these principles:

- 🔒 **Fully offline operation** - Data stored only on user's device
- 🚫 **No personal information collected** - Developer cannot access user data
- 📵 **No tracking services** - No Google Analytics, Facebook SDK, etc.
- 🤖 **On-device AI** - AI features run locally when applicable
- 📖 **Open and transparent** - Privacy policies are public and easy to understand

## Local Development

To preview changes locally:

```bash
# Serve with Python
python3 -m http.server 8000

# Or with Node.js
npx http-server -p 8000

# Visit http://localhost:8000
```

## Deployment

This repository uses **GitHub Pages** for hosting:

- **Branch**: `main`
- **Source**: `/` (root)
- **Custom domain**: None (uses default GitHub Pages URL)

Changes pushed to `main` automatically deploy within a few minutes.

## License

Privacy policies and legal documents:
- © 2026 ChengChe Lee. All rights reserved.

Shared components and templates:
- May be adapted for personal use with attribution

## Contact

**Developer**: ChengChe Lee
**Email**: qqder339@gmail.com
**Location**: Taiwan 🇹🇼
**GitHub**: [@ccqqder](https://github.com/ccqqder)

---

Made with ❤️ in Taiwan
