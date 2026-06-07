# IZE! – DJ Project Website

A cutting-edge, interactive DJ portfolio website featuring real-time facial recognition and cinematic visual effects. Experience music through an immersive web interface powered by advanced computer vision and creative coding.

## 🎵 About

**IZE!** is an experimental HTML-only DJ portfolio that combines music production with creative coding. This project explores what's possible with vanilla JavaScript and modern web APIs—no frameworks, no build tools, just pure web innovation. Explore my music across multiple platforms while experiencing an interactive, face-tracked visual experience.

> **💡 Experimental Focus:** This is a lightweight, single-file experiment designed to maximize creative coding while keeping dependencies minimal. Everything runs in a single `index.html` file with zero external build processes.

**Music Platforms:**

- 🎵 [SoundCloud](https://soundcloud.com/izemakesbeats)
- 🎵 [Bandcamp](https://izedbeats.bandcamp.com/music)
- 🎵 [Spotify](https://open.spotify.com/artist/60jOGU1IiVZ4VSInmCDT5a)
- 🎵 [Mixcloud](https://www.mixcloud.com/izedbeats/)
- 🎵 [Facebook](https://www.facebook.com/izedbeats/)
- 📸 [Instagram](https://www.instagram.com/izedbeats/)

## 🛠️ Tech Stack

A **lightweight, framework-free** experiment built with pure web standards:

### Frontend

- **HTML5** – Semantic markup & responsive structure in a single file
- **CSS3** – Advanced styling with CSS variables, flexbox, and fixed positioning
- **Vanilla JavaScript** – No frameworks, no dependencies—just creative coding with core web APIs

### Computer Vision & Face Recognition

- **MediaPipe Face Mesh** – Real-time facial landmark detection (468 points per face)
- **Camera Utils** – Cross-browser camera stream handling via CDN

### Visual Effects & Processing

- **Canvas API** – Real-time video rendering and post-processing
  - Horizontal motion blur
  - Film grain simulation
  - Vignette effect
  - Random film scratches
  - Dynamic brightness flicker
  - Edge detection and contrast enhancement

### Design & UX

- **Google Fonts** – Inter typeface for clean, modern typography
- **Responsive Design** – Optimized for mobile & desktop viewports
- **Interactive Overlays** – Dynamic landmark-linked navigation elements

## ✨ Key Features

### Real-Time Face Tracking

- Detects facial landmarks in real-time using your device's camera
- Maps music platform links to specific facial features
- Smooth positioning and smooth animations

### Cinematic Visual Effects

- **Motion Blur** – Horizontal blur for dynamic effect
- **Film Grain** – Vintage film aesthetic overlay
- **Edge Enhancement** – Sculpted edge details with adjustable strength
- **Vignette** – Dark edges for focused composition
- **Film Scratches** – Random vertical scratches for authentic film look
- **Color Flicker** – Dynamic brightness variations

### Privacy First

- No video data is recorded or stored
- Camera feed is processed locally only
- Transparent privacy policy on load

## 🎯 How It Works

1. **Camera Access** – Grant browser permission to access your camera
2. **Face Detection** – MediaPipe detects your facial landmarks
3. **Link Positioning** – Music links appear near specific facial features (cheekbones, forehead, lips, etc.)
4. **Interactive Experience** – Hover over links to reveal music platforms
5. **Visual Feedback** – Real-time video processing with cinematic effects

## 🎨 Customizable Settings

The following parameters can be tweaked in the JavaScript code:

```javascript
LINK_COLOR = "#00B2FF"; // Link color (default: cyan)
EDGE_STRENGTH = 0.2; // Edge brightness (0.5 = subtle, 3.0 = strong)
EDGE_MIX = 0.3; // Edge blend ratio
CONTRAST = 2; // Overall contrast level
TRAIL_FADE = 0.1; // Motion trail persistence
GRAIN = 1; // Film grain intensity
H_BLUR = 2; // Horizontal motion blur radius
VIGNETTE_ON = true; // Enable dark edges
SCRATCHES_ON = true; // Enable film scratches
FLICKER_ON = true; // Enable brightness flicker
```

## 📋 Browser Support

Requires modern browser with:

- WebRTC & getUserMedia API
- Canvas API with advanced context options
- ES6 JavaScript support
- CDN access (jsDelivr for MediaPipe)

**Tested on:**

- Chrome/Chromium (recommended)
- Safari (macOS & iOS)
- Firefox
- Edge

## 🔒 Privacy

This site prioritizes your privacy:

- ✅ No video recording
- ✅ No data storage
- ✅ No tracking cookies
- ✅ All processing happens locally in your browser

[Read full Privacy Policy](https://docs.google.com/document/d/1MMNRecqMcnHCLwZg1T7U5tKf-E4Bdj8mh50nIl--Cn8/edit?usp=sharing)

## 📂 Project Structure

```
test/
├── index.html          # Main application (HTML, CSS, JavaScript)
├── ize.png            # Logo/branding
├── README.md          # This file
└── [other assets]     # Images, audio files, etc.
```

## 🚀 Getting Started

1. **Clone or Download** the repository
2. **Serve locally** using any web server:
   ```bash
   python -m http.server 8000
   # or
   npx serve
   ```
3. **Open in browser** at `http://localhost:8000`
4. **Grant camera permission** when prompted
5. **Explore** the interactive experience

## 🎧 Follow IZE

- 🎵 **Music**: Check out my latest tracks on any of the platforms above
- 📱 **Social**: [@izedbeats](https://www.instagram.com/izedbeats/) on Instagram
- 💬 **Connect**: Reach out through Facebook or Instagram DMs

---

**Built with passion for music and web innovation.**

_Last Updated: 2026_
