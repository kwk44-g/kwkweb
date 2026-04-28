# Retro Profile Website with Doom Mini-Game

A retro-styled profile website featuring an integrated Doom mini-game.

## Features

- **Retro Terminal Esthetic**: Green/amber color scheme with CRT effects
- **Profile Section**: User information and stats
- **Game List**: Interactive game collection with progress bars
- **Music Player**: YouTube API integration
- **Doom Mini-Game**: Fully playable browser-based Doom clone

## Project Structure

```
├── index.html          # Main profile page
├── doom.html           # Dedicated Doom game page
├── css/               # Stylesheets
├── js/                # JavaScript files
│   └── doom.js       # Doom game logic
├── lib/               # External libraries
│   ├── easeljs-0.6.0.min.js
│   ├── preloadjs-0.3.0.min.js
│   └── soundjs-0.4.0.min.js
├── audio/             # Game sound effects
├── img/               # Game assets
└── assets/            # Static assets
```

## Setup

1. Clone the repository
2. Start a local server:
   ```bash
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser

## Game Controls

### Doom Mini-Game
- 🎯 **Aim**: Move mouse to target
- 🔫 **Shoot**: Left-click
- 🔊/🔇 **Mute**: Toggle sound
- 🟤 **Brown Monsters**: 100 points
- 🟢 **Green Monsters**: 1000 points

## Navigation

- **Main Page**: `/` - Profile and game list
- **Doom Game**: `/doom.html` - Dedicated game page

## Technologies Used

- HTML5 Canvas
- CreateJS Suite (EaselJS, PreloadJS, SoundJS)
- CSS3 with custom properties
- Vanilla JavaScript
- YouTube IFrame API

## Credits

- **Doom Mini-Game**: Based on [Mini-Doom-Game-HTML5-Canvas](https://github.com/dmk12/Mini-Doom-Game-HTML5-Canvas) by dmk12
- **Design**: Retro terminal/crt aesthetic

## License

This project maintains the same license as the original Doom mini-game.
