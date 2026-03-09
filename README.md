# 🎤 Offline Audio Translator - Web Version

> **Translate speech in real-time without internet**

A privacy-first web application for speech transcription and translation. Part of the **OfflineAudioTranslator** portfolio project for German Data Science Master's applications.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Vercel-blue?style=flat-square)](https://offline-audio-translator.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square)](https://github.com/JatinTaori1904/offline-audio-translator-web)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

## ✨ Features

- 🌐 **No Internet Required** - Works completely offline for maximum privacy
- 🎯 **Real-Time Processing** - Instant audio recording and result display
- 🔒 **Privacy First** - Your audio data never leaves your device
- 🗣️ **Multi-Language Support** - English, German, Spanish, French
- 📱 **Responsive Design** - Beautiful UI on desktop and mobile
- ⚡ **Fast & Lightweight** - Optimized React app deployed on Vercel
- 🎨 **Modern UI** - Gradient backgrounds, smooth animations, accessibility-first

## 🚀 Quick Start

### Prerequisites

- Node.js 14+ and npm
- Git

### Installation & Development

```bash
# Navigate to project
cd offline-audio-translator-web

# Install dependencies
npm install

# Start development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 🌐 Deployment

This app is ready to deploy on **Vercel** (free hosting with auto-deployment).

See [DEPLOYMENT.md](DEPLOYMENT.md) for step-by-step instructions:

```bash
# 1. Push to GitHub
git add .
git commit -m "My portfolio project"
git push origin main

# 2. Deploy on Vercel (https://vercel.com)
# - Sign in with GitHub
# - Select this repository
# - Click Deploy
# That's it! Your app is live!
```

## 📦 Build for Production

```bash
npm run build
```

Creates optimized production build in `/build` folder ready for deployment.

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **React 19** | Modern UI framework |
| **Web Audio API** | Browser audio recording |
| **CSS3** | Responsive styling with animations |
| **Vercel** | Free hosting & auto-deployment |

## 📁 Project Structure

```
offline-audio-translator-web/
├── public/
│   └── index.html          # Main HTML file
├── src/
│   ├── App.js              # Main React component (350+ lines)
│   ├── App.css             # Styling (750+ lines)
│   └── index.js            # React entry point
├── package.json            # Dependencies & scripts
├── README.md               # This file
└── DEPLOYMENT.md           # Deployment guide
```

## 💡 Usage

1. **Open the app** - Visit the Vercel-hosted URL
2. **Select languages** - Choose source and target from dropdown
3. **Record audio** - Click "Start Recording" and speak
4. **View results** - Transcription and translation appear below
5. **Download** - Save results as text file
6. **Translate again** - Click "Clear Results" to reset

## 🎯 Features Showcase

### Language Selection
- Visual language selector with flag emojis
- Swap button to reverse source/target
- 4 language pairs supported

### Audio Recording
- Real-time recording timer
- Visual feedback (blinking dot)
- Automatic microphone permissions handling
- Echo cancellation and noise suppression enabled

### Results Display
- Live transcription and translation boxes
- Highlight effect when results are available
- Large text areas for easy reading
- Copy-friendly formatting

### Additional Features
- Download results as `.txt` file
- Clear results to record again
- Feature showcase section
- Responsive design (mobile-optimized)
- Professional footer with links

## 🎨 Customization

### Change Color Scheme
Edit the gradient colors in `src/App.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Add More Languages
Update the `languages` object in `src/App.js`:
```javascript
const languages = {
  en: '🇬🇧 English',
  de: '🇩🇪 Deutsch',
  es: '🇪🇸 Español',
  fr: '🇫🇷 Français',
  pt: '🇧🇷 Português',  // Add more
};
```

### Modify Header/Footer
Edit the `<header>` and `<footer>` sections in `src/App.js`

## 📊 Portfolio Value

This project demonstrates:

✅ **Frontend Development**
- Modern React with Hooks
- Responsive CSS design
- Web APIs (Audio)
- Component architecture

✅ **Full-Stack Thinking**
- Ready for backend integration
- API-ready structure
- Scalable design

✅ **Deployment Skills**
- Git & GitHub usage
- CI/CD (Vercel auto-deployment)
- Production optimization

✅ **UX/UI**
- Accessibility (labels, keyboard nav)
- Responsive design
- User feedback & loading states
- Error handling

## 🔧 Developer Commands

```bash
npm start          # Start development server (localhost:3000)
npm run build      # Create optimized production build
npm test           # Run tests
npm audit fix      # Fix vulnerabilities
npm list           # Show all dependencies
```

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Microphone not working | Check browser permissions for microphone access |
| npm not found | Install Node.js from [nodejs.org](https://nodejs.org) |
| Deployment fails | Check Vercel dashboard logs for errors |
| Old version showing | Clear browser cache (Ctrl+Shift+Delete) |

## 📚 Learning Resources

- [React Documentation](https://react.dev)
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [Vercel Deployment Guide](https://vercel.com/docs)
- [GitHub Learning Lab](https://github.com/skills)

## 📄 License

This project is MIT licensed - feel free to use it for your portfolio!

## 👤 Author

Built as a portfolio project for German Data Science Master's program.

## 🙋 Contributing

Contributions welcome! Feel free to fork and submit pull requests.

---

**[✨ See Live Demo](https://offline-audio-translator.vercel.app)** | **[📖 Deployment Guide](DEPLOYMENT.md)** | **[💻 GitHub](https://github.com/JatinTaori1904/offline-audio-translator-web)**

*Made with ❤️ for Data Science enthusiasts*

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
