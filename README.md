# 🌍 Timezone Display App

A beautiful, interactive timezone converter that displays multiple world timezones simultaneously with drag-and-drop customization and real-time updates.

## ✨ Features

### 🎯 **Core Functionality**
- **Fixed Base Timezones**: EDT (top) and PDT (main) are always visible
- **Customizable Countries**: Select and reorder up to 100+ countries in the bottom grid
- **Real-time Updates**: Automatic time synchronization every minute
- **Manual Time Control**: Set specific times with 5-minute increment buttons
- **Click-to-Edit**: Direct time input with validation

### 🎨 **Visual Design**
- **Three Theme Modes**: Dark, Light, and Blue gradients
- **Glassmorphism UI**: Modern blur effects and transparency
- **Responsive Design**: Optimized for desktop and mobile devices
- **Smooth Animations**: Polished transitions and hover effects

### ⚙️ **Customization**
- **Drag & Drop Reordering**: Rearrange countries by dragging
- **Auto-Save Settings**: Changes are saved instantly to localStorage
- **Country Selection**: Choose from 90+ countries worldwide
- **Visual Feedback**: Live preview of changes

### 🔗 **Advanced Features**
- **URL Parameters**: Share specific times with `?time=6pm` or `?date=07-10-2025&time=6:00pm`
- **Screenshot Sharing**: One-click Twitter sharing with image capture
- **Usage Statistics**: Track page loads and active time
- **Keyboard Shortcuts**: ESC to close modals, Enter to save edits

## 🚀 Getting Started

### Quick Start
1. **Download**: Get `timezone-mini-v6.html` (recommended for production)
2. **Open**: Launch the file in any modern web browser
3. **Customize**: Click the ⚙️ gear icon to select your preferred countries
4. **Enjoy**: Real-time timezone conversion with your personalized layout

### File Versions
- **`timezone-v6.html`** - Full version with readable code (52KB)
- **`timezone-mini-v6.html`** - Minified production version (23KB)

## 🎛️ How to Use

### Basic Controls
- **🌛 Theme Button**: Cycle through Dark → Light → Blue themes
- **SHARE**: Screenshot and share to Twitter/X
- **RESET**: Return to current time with live updates
- **⚙️ Settings**: Customize displayed countries
- **HELP**: View detailed usage instructions

### Time Manipulation
- **Arrow Buttons**: Adjust time in 5-minute increments
- **Click PDT Time**: Direct time input (format: h:mm AM/PM)
- **URL Parameters**: 
  - `?time=7am` - Set time (uses today's date)
  - `?date=12-25-2025&time=6:30pm` - Set specific date and time

### Country Customization
1. **Open Settings**: Click the ⚙️ gear icon
2. **Reorder Countries**: Drag and drop items in the "Bottom Countries" section
3. **Add Countries**: Click + next to countries in the "Available Countries" section
4. **Remove Countries**: Click × to remove countries from your selection
5. **Reset**: Use "Reset to Defaults" to restore original country set

## 🌐 Supported Countries

The app includes 90+ countries spanning all major timezones:

### Popular Regions
- **North America**: USA (EDT/PDT), Canada, Mexico
- **Europe**: UK, Germany, France, Spain, Italy, Netherlands
- **Asia**: Japan, China, India, Singapore, South Korea
- **Oceania**: Australia, New Zealand, Fiji
- **South America**: Brazil, Argentina, Colombia, Chile
- **Africa**: South Africa, Egypt, Nigeria, Kenya
- **Middle East**: UAE, Saudi Arabia, Turkey, Israel

### Special Timezone Support
- **Half-hour offsets**: India (UTC+5:30), Iran (UTC+3:30)
- **Quarter-hour offsets**: Nepal (UTC+5:45)
- **Unusual offsets**: Myanmar (UTC+6:30)

## 🔧 Technical Details

### Architecture
- **Pure HTML/CSS/JavaScript** - No frameworks required
- **localStorage** - Settings persistence across sessions
- **html2canvas** - Screenshot functionality for sharing
- **Responsive CSS Grid** - Adaptive layout for all screen sizes

### Browser Compatibility
- **Modern Browsers**: Chrome, Firefox, Safari, Edge (last 2 versions)
- **Mobile**: iOS Safari, Android Chrome
- **Features**: ES6+ JavaScript, CSS Grid, Flexbox, localStorage

### Performance
- **Lightweight**: 23KB minified (55% smaller than original)
- **Fast Loading**: Single file with embedded assets
- **Efficient**: Minimal DOM manipulation, optimized animations

## 🎯 Use Cases

### Personal
- **Travel Planning**: Compare times across destinations
- **Remote Work**: Coordinate with international colleagues
- **Family & Friends**: Stay connected across time zones
- **Event Planning**: Schedule global meetings and calls

### Professional
- **Business Operations**: Multi-timezone team coordination
- **Customer Support**: Global service hour tracking
- **Project Management**: International deadline management
- **Trading & Finance**: Market hour monitoring

### Educational
- **Geography Learning**: Understanding world time zones
- **Cultural Awareness**: Global time consciousness
- **Travel Education**: Trip planning and jet lag preparation

## 🛠️ Customization Options

### Settings Persistence
- **Auto-Save**: All changes save immediately
- **Cross-Session**: Settings persist between browser sessions
- **Local Storage**: No server required, works offline

### URL Sharing
Share specific times with colleagues:
```
https://yoursite.com/timezone-mini-v6.html?time=9am
https://yoursite.com/timezone-mini-v6.html?date=12-25-2025&time=6:30pm
```

### Theme Customization
Three built-in themes with smooth transitions:
- **Dark**: Professional dark gradient
- **Light**: Bright blue gradient  
- **Blue**: Classic blue gradient

## 📱 Mobile Experience

### Responsive Design
- **2-Column Layout**: Optimized country grid for mobile
- **Touch-Friendly**: Large touch targets and gestures
- **Centered Theme Toggle**: Accessible theme switching
- **Compact Header**: Space-efficient button layout

### Mobile Features
- **Drag & Drop**: Full touch support for reordering
- **Swipe Gestures**: Natural mobile interaction
- **Zoom Optimized**: Proper viewport handling
- **Offline Ready**: Works without internet connection

## 🔒 Privacy & Security

### Data Handling
- **No Server**: Completely client-side application
- **No Tracking**: No analytics or user tracking
- **Local Storage Only**: Settings stored in browser only
- **No Network Calls**: Except for Twitter sharing

### Security Features
- **Input Validation**: Safe time input parsing
- **XSS Protection**: Sanitized user inputs
- **CSP Ready**: Content Security Policy compatible

## 🤝 Contributing

### Development Setup
1. Clone or download the repository
2. Open `timezone-v6.html` in your browser
3. Make changes to the readable version
4. Test across different browsers and devices
5. Minify for production if needed

### Code Structure
- **HTML**: Single-file structure with embedded CSS/JS
- **CSS**: Organized by component (theme, layout, responsive)
- **JavaScript**: Modular functions with clear separation of concerns

## 📄 License

MIT License - Feel free to use, modify, and distribute as needed.

## 🏷️ Version History

- **v6**: Auto-save functionality, removed save button
- **v5**: Fixed EDT/PDT positions, simplified settings
- **v4**: Added drag & drop reordering
- **v3**: Removed country limitations
- **v2**: Added country selection interface
- **v1**: Initial release with basic timezone display

## 🙏 Acknowledgments

- **html2canvas**: Screenshot functionality
- **Emoji Flags**: Country representation
- **Modern CSS**: Glassmorphism design inspiration
- **Timezone Data**: Accurate UTC offset information

---

**Built with ❤️ for the global community**

*Perfect for remote teams, travelers, and anyone working across time zones!*