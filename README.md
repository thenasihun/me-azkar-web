# Morning Evening (ME) Azkar - Daily Supplications

[![GitHub Pages Deployment](https://github.com/thenasihun/me-azkar-web/actions/workflows/static.yml/badge.svg)](https://github.com/thenasihun/me-azkar-web/actions) ![License](https://img.shields.io/badge/License-MIT-blue.svg) [![Get it on Google Play](https://img.shields.io/badge/Google_Play-414141?style=flat&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.is360.me_azkar&hl=en)

A beautiful, responsive web interface for reading daily morning evening azkar Islamic supplications (duas) with audio playback and multilingual support.

## Features

### 🕒 Time-Based Display
- Automatically shows morning/evening supplications based on current time
- Manual toggle between morning and evening views

### 📖 Rich Content Display
- Original Arabic text with proper typography
- Urdu and English translations
- Detailed supplication explanations
- Reference information (book sources and hadith numbers)

### 🔊 Audio Integration
- Built-in audio player controls
- Play/pause functionality
- Repeat mode
- Seamless audio file integration

### 🌍 Multilingual Support
- Toggle between English and Urdu translations
- Responsive Urdu font rendering
- Language preference saving

### 📱 Responsive Design
- Mobile-first approach
- Cross-browser compatibility
- Accessible interface
- Smooth animations and transitions

### ✨ Additional Features
- Direct sharing functionality
- SEO optimization for search engines
- Automatic JSON data loading
- Progressive Web App (PWA) ready

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge)
- Web server for local development (optional)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/thenasihun/me-azkar-web.git
```

2. Navigate to project directory:
```bash
cd me-azkar-web
```

3. Open in browser:
open ```index.html``` file in any modern browser

### Project Structure
.
├── index.html          # Main application entry
├── supplications.json  # Supplication data
├── assets/             # Media assets
│   ├── audio/          # MP3 files (1.mp3, 2.mp3, etc.)
│   └── fonts/          # Custom web fonts
├── .github/
│   └── workflows/      # GitHub Actions config
└── README.md           # This documentation

### Configuration
1. Edit ```supplications.json``` to modify content
2. Add audio files in assets/audio/ as [id].mp3
3. Adjust styling in CSS variables:
```css
:root {
  --primary: #2c3e50;
  --secondary: #3a5f5f;
  --accent: #2ecc71;
}
```

### Deployment
Automatically deployed via GitHub Pages:
1. Push to ```main``` branch
2. GitHub Actions builds and deploys
3. Live at: https://your-username.github.io/your-repo

## Contributing
1. Fork the repository
2. Create feature branch:
```bash
git checkout -b feature/new-feature
```
3. Commit changes:
```bash
git commit -m 'Add some feature'
```
4. Push to branch:
```bash
git push origin feature/new-feature
```
5. Open a Pull Request

## License
Distributed under the MIT License. See ```LICENSE``` for more information.

## Acknowledgements
[Noto Arabic Font](https://fonts.google.com/noto/specimen/Noto+Naskh+Arabic)
[Noto Nastaliq Urdu](https://fonts.google.com/noto/specimen/Noto+Nastaliq+Urdu)

Visit _nasihun.com_ official website & join our whatsapp channel for daily islamic content


