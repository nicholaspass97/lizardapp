# 🦎 Lizard Button Web App 🦎

A fun interactive web application where you can click a button to add lizard emojis to the page and hear lizard sounds! You can use a custom sound clip from [this YouTube video](https://www.youtube.com/watch?v=wE41R_lJI9A).

## Features

- **Lizard Button**: Click the big green button with lizard emojis to add more lizards
- **Interactive Lizards**: Each lizard emoji bounces when added and can be clicked to remove
- **Lizard Sounds**: Every time you click the button, a lizard-like sound is played
- **Counter**: Keep track of how many lizards you've added
- **Beautiful UI**: Modern gradient design with smooth animations

## How to Use

1. Open `index.html` in your web browser
2. Click the "🦎 Click for Lizard! 🦎" button
3. Watch as lizard emojis appear with a bounce animation
4. Listen to the lizard sound that plays with each click
5. Click on individual lizard emojis to remove them
6. Watch the counter to see how many lizards you've added

## Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies required
- **Web Audio API**: Generates lizard sounds using oscillators
- **Responsive Design**: Works on desktop and mobile devices
- **Modern CSS**: Uses gradients, animations, and hover effects

## Browser Compatibility

This app works best in modern browsers that support:
- Web Audio API
- CSS Grid and Flexbox
- CSS Animations

## Getting Started

Simply open the `index.html` file in any modern web browser to start playing with lizards!

### Using Custom Audio

To use the custom lizard sound from the YouTube video:

1. Open `audio-setup.html` for detailed instructions
2. Download the audio from the YouTube video
3. Convert it to MP3 format
4. Rename it to `lizard-sound.mp3`
5. Place it in the same folder as `index.html`

The app will automatically use your custom audio file, with a fallback to the generated sound if the file isn't found.

---

*Note: The lizard sound is generated using the Web Audio API and may require user interaction (like clicking the button) to work in some browsers due to autoplay policies.*
