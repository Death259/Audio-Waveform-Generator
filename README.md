# 🎵 Audio Waveform Generator Pro

A beautiful, feature-rich Progressive Web App (PWA) that generates stunning waveform images from your audio files. Create professional-looking visualizations with extensive customization options and powerful export capabilities.

![Waveform Generator](https://img.shields.io/badge/PWA-Ready-blue) ![License](https://img.shields.io/badge/license-GPL--3.0-blue)

## ✨ Features

### 📁 **Audio Management**
- **Easy Upload** - Drag & drop or click to upload audio files
- **Multiple Format Support** - MP3, WAV, OGG, M4A, and more
- **Instant Processing** - Fast audio analysis and visualization

### 🎨 **Extensive Customization**

**Color Options:**
- Solid colors
- Preset gradients: Rainbow, Sunset, Ocean, Red/White/Blue
- Custom gradients with 2-5 colors and smooth transitions
- Real-time gradient preview

**Waveform Styles:**
- **Bars** - Classic vertical bars centered in the waveform
- **Rounded Bars** - Smooth bars with rounded corners
- **Line** - Symmetrical wave pattern (top and bottom)
- **Mirror** - Bars extending up and down from center
- **Filled** - Smooth filled area under the waveform
- **Particles** - Dotted particle-based visualization

**Advanced Controls:**
- **Smoothing** - Control waveform detail level (10-200)
- **Opacity** - Adjust transparency (0-100%)
- **Custom Dimensions** - Width: 400-4000px, Height: 100-2000px
- **Background Color** - Any solid color

### 🔧 **Productivity Features**
- **Undo/Redo** - Step through your changes (up to 50 history states)
- **Keyboard Shortcuts** - Work faster with hotkeys
- **Dark Mode** - Easy on the eyes for low-light environments
- **Auto-save Settings** - Your preferences persist across sessions

### 💾 **Export**
- **PNG Export** - High-quality raster images
- **One-Click Download** - Save directly to your device
- **Copy to Clipboard** - Quick sharing (coming soon)

### 📱 **Progressive Web App**
- Install on your device like a native app
- Works offline after first visit
- Full-screen experience
- No app store required
- Cross-platform (Android, iOS, Desktop)

### ⌨️ **Keyboard Shortcuts**
- **Ctrl/Cmd + Z** - Undo
- **Ctrl/Cmd + Y** - Redo
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
   - **Color Mode**: Choose solid color or gradient presets (Rainbow, Sunset, Ocean, Red/White/Blue)
   - **Custom Gradient**: Pick 2-5 colors with checkboxes to enable/disable colors 3-5
   - **Background Color**: Set any solid background color
   - **Dimensions**: Adjust width (400-4000px) and height (100-2000px)
   - **Waveform Style**: Select from 6 different styles
   - **Smoothing**: Control detail (10 = very detailed, 200 = very smooth)
   - **Opacity**: Adjust transparency (0-100%)

3. **Generate & Download**
   - Click "🎨 Generate Waveform" to create your visualization
   - Click "💾 Download PNG" to save to your device
   - Use Undo/Redo buttons to step through changes
   - Toggle Dark Mode for comfortable viewing in any lighting

## 🎨 Waveform Styles

- **Bars** - Classic vertical bars centered in the waveform
- **Rounded Bars** - Bars with smooth rounded corners for a softer look
- **Line** - Symmetrical continuous waveform (top and bottom mirrored)
- **Mirror** - Bars extending up and down from the center line
- **Filled** - Smooth filled area under the waveform curve
- **Particles** - Dotted particle-based visualization for a unique look

## 🎨 Color Options

- **Solid** - Single color waveform
- **Rainbow** - Classic 7-color rainbow spectrum
- **Red/White/Blue** - Patriotic color scheme
- **Sunset** - Warm pinks, yellows, and oranges
- **Ocean** - Cool blues and purples
- **Custom** - Your own combination of 2-5 colors with smooth transitions

## 💡 Tips & Best Practices

- **High Resolution**: Use larger dimensions (1800x400 or higher) for professional results
- **Aspect Ratio**: Wide aspect ratios (3:1 or 4:1) work best for most waveforms
- **Contrast**: Ensure good contrast between waveform and background colors
- **Smoothing**: Lower values (10-30) for detailed waveforms, higher (100-200) for smooth, minimalist designs
- **Style Selection**: 
  - Use **Bars** or **Rounded Bars** for classic podcast/music visualizations
  - Use **Line** for a more technical, oscilloscope-style look
  - Use **Mirror** for symmetrical, modern aesthetics
  - Use **Filled** for smooth, flowing designs
  - Use **Particles** for creative, artistic effects
- **Dark Mode**: Use dark mode when working in low-light environments
- **Keyboard Shortcuts**: Press Ctrl+Z for undo, Ctrl+Y for redo to quickly iterate on designs
- **Custom Gradients**: Start with 2-3 colors and add more if needed - too many colors can look busy

## 🛠️ Technical Details

### Built With

- **HTML5 Canvas** - For high-performance waveform rendering
- **Web Audio API** - For audio processing
- **Vanilla JavaScript** - No frameworks, lightweight and fast
- **PWA Technology** - Service workers and manifest for app-like experience
- **LocalStorage** - For saving dark mode preferences

### Key Features Under the Hood

- Real-time audio analysis and visualization
- Configurable sample rate and smoothing algorithms
- Multi-style rendering engine (6 distinct visualization styles)
- Gradient generation with smooth color interpolation
- Undo/Redo state management (50 history states)
- Optimized canvas rendering for large dimensions
- Efficient memory management for audio processing

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
git clone https://github.com/death259/Audio-Waveform-Generator.git
cd Audio-Waveform-Generator
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
- 🎨 Share your waveform designs
- ⭐ Star the repository if you find it useful!

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
- Inspired by the need for a powerful, free, and privacy-focused waveform generator
- Thanks to the open web platform for making this possible
- Special thanks to the Web Audio API and Canvas API communities

## 📧 Contact & Support

Found a bug? Have a feature request? Want to say thanks?

- Open an issue on GitHub
- Star the repository if you find it useful!
- Share it with others who might benefit
- Follow the project for updates

---

**Made with 🎵 by AI and Death259**

[⬆ Back to Top](#-audio-waveform-generator-pro)
