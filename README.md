# ClarifyThis Website

Official website for ClarifyThis - a native macOS productivity app that provides instant, context-aware AI explanations.

🌐 **[Visit Live Website](https://clarifythisnow.netlify.app)** <!-- Replace with your actual domain -->

## About

This repository contains the marketing website for **ClarifyThis**, a productivity tool for macOS that gives you instant AI-powered explanations without breaking your workflow.

### ClarifyThis Features

- **Screenshot Mode** — Capture anything on your screen for instant AI explanations
- **Voice Mode** — Ask questions naturally using your voice  
- **Explain Panel** — Floating panel with rich formatting, LaTeX, graphs, and code snippets
- **Context Vault** — Persistent AI memory for personalized responses
- **History** — Local-only saved clarifications for privacy
- **Stats Dashboard** — Track time saved and usage insights
- **Native macOS UI** — Apple-style design and system menu integration

## Website Tech Stack

- **React** — UI framework
- **Tailwind CSS** — Styling
- **Vite** — Build tool
- **HTML5/CSS3** — Core web technologies

## Project Structure

```
.
├── index.html          # Main landing page
├── thank-you.html      # Post-download page
├── dist/               # Production build
├── appcast.xml         # App update feed
├── *.mp4               # Feature demo videos
└── *.png               # Brand assets
```

## Demo Videos

The website showcases ClarifyThis features through interactive video demonstrations:

- `codemode.mp4` — Code explanation mode
- `graphmode.mp4` — Graph generation
- `latexmode.mp4` — LaTeX rendering
- `screenshotmode.mp4` — Screenshot capture
- `tablemode.mp4` — Table generation
- `voicemode.mp4` — Voice input

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/clarifythis-website.git
cd clarifythis-website
```

2. Open `index.html` directly in your browser, or serve with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

3. Visit `http://localhost:8000`

## Building for Production

The production build is located in the `dist/` folder and is ready to deploy to any static hosting service.

## Download App

ClarifyThis is available for macOS 12.0 and later. Visit the website to download the latest version.

## Privacy & Security

- No persistent storage of screenshots or voice recordings
- Local-only history by default
- AES-256 encryption for stored data
- TLS 1.3 for all network communication
- No training on your content

## Support

For app support or inquiries:
- **Email**: clarifythisofficial@gmail.com
- Use the in-app support form

## Developer

Built by a 16-year-old student developer passionate about creating tools that help people learn faster and work smarter.

## License

© 2026 ClarifyThis. All rights reserved.

---

Built with ❤️ for students, developers, and lifelong learners.
