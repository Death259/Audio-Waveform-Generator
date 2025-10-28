# 🎵 Audio Waveform Generator Pro

A beautiful, feature-rich Progressive Web App (PWA) that generates stunning waveform images from your audio files. Create professional-looking visualizations with extensive customization options, real-time audio playback, and powerful export capabilities.

![Waveform Generator](https://img.shields.io/badge/PWA-Ready-blue) ![License](https://img.shields.io/badge/license-GPL--3.0-blue)

## ✨ Features

### 📁 **Audio Management**
- **Easy Upload** - Drag & drop or click to upload audio files
- **Multiple Format Support** - MP3, WAV, OGG, M4A, and more
- **Sample Audio** - Try the app with built-in sample sounds (tone, sweep, beat)
- **Audio Playback** - Listen to your audio while designing
- **Timeline Scrubbing** - Seek to any position in your audio
- **Audio Trimming** - Select specific sections to visualize

### 🎨 **Extensive Customization**

**Color Options:**
- Solid colors or beautiful gradients
- Preset gradients: Rainbow, Sunset, Ocean, Red/White/Blue
- Custom gradients with up to 5 colors
- Background gradients or solid colors
- Real-time gradient preview

**Waveform Styles:**
- Bars
- Line
- Mirror
- Rounded Bars
- Filled Curve
- Particles

**Advanced Effects:**
- Smoothing control
- Opacity/transparency adjustment
- Stroke/outline with color and width
- Shadow effects with blur control
- Channel selection (Merged, Separate, Left, Right)

### 📐 **Dimension Presets**
Quick presets for popular platforms:
- 📱 Instagram Post (1080x1080)
- 📱 Instagram Story (1080x1920)
- 📺 YouTube Thumbnail (1280x720)
- 🐦 Twitter Post (1200x675)
- 📘 Facebook Cover (820x312)
- 🎙️ Podcast Cover (3000x3000)
- Custom dimensions (400-4000px width, 100-2000px height)

### 💾 **Export Options**
- **PNG** - High-quality raster images
- **SVG** - Vector format for infinite scaling
- **JPEG** - With adjustable quality
- **Copy to Clipboard** - Quick sharing
- **Batch Processing** - Multiple file support

### 🔧 **Productivity Features**
- **Undo/Redo** - Step through your changes (up to 50 steps)
- **Save Presets** - Store your favorite configurations
- **Load Presets** - Quick access to saved settings
- **Share Configuration** - Generate shareable URLs with your settings
- **Keyboard Shortcuts** - Work faster with hotkeys
- **Dark Mode** - Easy on the eyes

### 📱 **Progressive Web App**
- Install on your device like a native app
- Works offline after first visit
- Full-screen experience
- No app store required
- Cross-platform (Android, iOS, Desktop)

### ⌨️ **Keyboard Shortcuts**
- **Ctrl/Cmd + Z** - Undo
- **Ctrl/Cmd + Y** - Redo
- **Ctrl/Cmd + S** - Download
- **Ctrl/Cmd + C** - Copy to Clipboard
- **Space** - Play/Pause Audio
- **G** - Generate Waveform
- **D** - Toggle Dark Mode

## 🎯 Supported Audio Formats

- MP3
- WAV
- OGG
- M4A
- And most other browser-supported audio formats

## 🚀 Getting Started

### Online Version

Simply visit the live app and start creating waveforms immediately:
**[https://death259.github.io/Audio-Waveform-Generator/](https://death259.github.io/Audio-Waveform-Generator/)**

### Install as PWA (Recommended)

**On Android (Chrome/Edge):**
1. Visit the app URL in Chrome or Edge
2. Tap the install prompt that appears, or
3. Tap the menu (⋮) → "Install app" or "Add to Home Screen"
4. The app icon will appear on your home screen
5. Launch it anytime - works offline!

**On iOS (Safari):**
1. Visit the app URL in Safari
2. Tap the Share button
3. Select "Add to Home Screen"
4. Tap "Add"

**On Desktop (Chrome/Edge):**
1. Visit the app URL
2. Click the install icon in the address bar (➕ or computer icon)
3. Click "Install"

## 🎨 How to Use

1. **Upload Audio**
   - Click the upload area or drag & drop your audio file
   - Wait for processing (usually just a few seconds)

2. **Customize Your Waveform**
   - **Color Mode**: Choose between solid colors or gradients
   - **Waveform Color**: Pick your solid color
   - **Background Color**: Set the background
   - **Width & Height**: Adjust dimensions (400-4000px width, 100-2000px height)
   - **Waveform Style**: Select Bars, Line, or Mirror

3. **Create Custom Gradients** (Optional)
   - Select "Custom Gradient" from Color Mode
   - Choose 2-5 colors
   - Use checkboxes to enable/disable colors 3-5
   - Colors transition smoothly across the waveform

4. **Download**
   - Click "Download Waveform Image"
   - Save the PNG file to your device

## 🎨 Gradient Presets

- **Rainbow** - Classic 7-color rainbow spectrum
- **Red/White/Blue** - Patriotic color scheme
- **Sunset** - Warm pinks, yellows, and oranges
- **Ocean** - Cool blues and purples
- **Custom** - Your own combination of 2-5 colors

## 💡 Tips & Best Practices

- **High Resolution**: Use larger dimensions (1800x400 or higher) for professional results
- **Aspect Ratio**: Wide aspect ratios (3:1 or 4:1) work best for waveforms
- **Contrast**: Ensure good contrast between waveform and background colors
- **File Size**: Larger audio files may take a few extra seconds to process
- **Gradients**: Use 2-3 colors for subtle transitions, 4-5 for vibrant effects

## 🛠️ Technical Details

### Built With

- **HTML5 Canvas** - For rendering waveforms
- **Web Audio API** - For audio processing
- **Vanilla JavaScript** - No frameworks, pure performance
- **PWA Technology** - Service workers and manifest for app-like experience

### Browser Compatibility

- ✅ Chrome/Edge (Desktop & Mobile) - Full support
- ✅ Safari (Desktop & Mobile) - Full support
- ✅ Firefox (Desktop & Mobile) - Full support
- ✅ Opera - Full support

### Privacy & Security

- 🔒 All audio processing happens locally in your browser
- 🚫 No files are uploaded to any server
- 🚫 No data collection or tracking
- 🚫 No accounts or sign-ups required

## 📦 Local Development

Want to run it locally or contribute?

1. Clone the repository:
```bash
git clone https://github.com/yourusername/waveform-generator.git
cd waveform-generator
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then visit `http://localhost:8000`

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- 📖 Improve documentation

## 📄 License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

This means you are free to:
- ✅ Use this software for any purpose
- ✅ Study and modify the source code
- ✅ Share the software with others
- ✅ Share your modifications

**However, if you distribute modified versions, you must:**
- 📋 Make your source code available under GPL-3.0
- 📋 Include the original copyright notice
- 📋 State any changes you made
- 📋 Keep the same GPL-3.0 license

For the full license text, see the [LICENSE](LICENSE) file or visit [GNU GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).

## 🙏 Acknowledgments

- Built with ❤️ for creators, podcasters, musicians, and audio enthusiasts
- Inspired by the need for a simple, free waveform generator
- Thanks to the open web platform for making this possible

## 📧 Contact & Support

Found a bug? Have a feature request? Want to say thanks?

- Open an issue on GitHub
- Star the repository if you find it useful!
- Share it with others who might benefit

---

**Made with 🎵 by [Your Name]**

[⬆ Back to Top](#-audio-waveform-generator)
