# ❤️ Love You Heart Animation

Beautiful heart animation with particles effect and romantic background music.

## ✨ Features

- 🎨 Animated heart shape with particle system
- 🎵 Background music with play/pause controls
- 📱 Responsive design
- ❤️ Beautiful red heart particles
- 💕 Romantic message display
- 🔄 Auto-loop music
- 🎧 Audio controls for user preference

## 🚀 Technologies Used

- HTML5 Canvas for heart animation
- JavaScript for particle system and audio control
- CSS3 for styling and responsive design
- Web Audio API for background music

## 🎵 Audio Features

- Auto-play background music (with fallback for browser policies)
- Loop playback for continuous romantic atmosphere
- Volume control and play/pause functionality
- Browser compatibility with multiple audio formats

## 🌐 Live Demo

🔗 [View Live Demo on Vercel](https://loveyou-tmqthedev.vercel.app)

## 🛠️ Local Development

1. Clone this repository
   ```bash
   git clone https://github.com/tmqthedev/loveyou.git
   ```

2. Navigate to project directory
   ```bash
   cd loveyou
   ```

3. Open `index.html` in your browser
   ```bash
   # Or use a local server
   npx serve .
   ```

4. Enjoy the heart animation with music! 🎶

## 📦 Deployment on Vercel

This project is optimized for Vercel deployment:

1. **Automatic deployment**: Push to main branch triggers deployment
2. **Static optimization**: Configured for optimal static file serving
3. **Audio optimization**: MP3 files cached with proper headers
4. **Fast CDN**: Global distribution via Vercel's CDN

### Manual Deployment

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## 📁 Project Structure

```
loveyou/
├── index.html              # Main HTML file
├── background_music.mp3    # Background music file
├── package.json           # Project metadata
├── vercel.json           # Vercel configuration
├── .vercelignore         # Files to ignore during deployment
└── README.md             # This file
```

## 🎨 Customization

### Change Music
Replace `background_music.mp3` with your preferred song (keep the same filename).

### Modify Animation
Edit the particle settings in `index.html`:
```javascript
var settings = {
  particles: {
    length: 8000,    // Number of particles
    duration: 6,     // Particle lifetime
    velocity: 60,    // Particle speed
    effect: -0.8,    // Gravity effect
    size: 6,         // Particle size
  },
};
```

### Update Message
Change the romantic message in the HTML:
```html
<h1>love you whitney <span style="font-style: normal;">:3</span></h1>
```

---

Made with ❤️ by tmqthedev | Deployed on ⚡ Vercel