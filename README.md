# MacBook Pro - Interactive Product Showcase

A stunning, interactive 3D product showcase for the MacBook Pro, built with React, Three.js, and GSAP animations. This project features smooth scroll-triggered animations, interactive 3D models, and a premium Apple-inspired design.

## 🚀 Features

- **Interactive 3D Models**: Explore MacBook Pro in 14" and 16" sizes with real-time color switching
- **Scroll-Triggered Animations**: Smooth GSAP-powered animations that respond to user scroll
- **3D Product Viewer**: Fully interactive 3D models with PresentationControls
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Video Textures**: Dynamic video textures on MacBook screens
- **Performance Showcase**: Animated image positioning and content reveals
- **Feature Highlights**: Rotating 3D model synchronized with feature descriptions

## 🛠️ Tech Stack

- **React 19** - UI framework
- **Three.js** - 3D graphics library
- **React Three Fiber** - React renderer for Three.js
- **React Three Drei** - Useful helpers for React Three Fiber
- **GSAP** - Animation library with ScrollTrigger
- **Zustand** - State management
- **Tailwind CSS 4** - Styling
- **Vite** - Build tool and dev server

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd macbook_gsap_app
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
src/
├── components/
│   ├── Hero.jsx              # Hero section with video
│   ├── Navbar.jsx            # Navigation bar
│   ├── ProductViewer.jsx     # Interactive 3D product viewer
│   ├── Showcase.jsx          # M4 chip showcase section
│   ├── Performance.jsx       # Performance section with animations
│   ├── Features.jsx          # Features with rotating 3D model
│   ├── Highlights.jsx        # Highlights masonry grid
│   ├── Footer.jsx            # Footer component
│   ├── models/
│   │   ├── Macbook-14.jsx    # 14" MacBook 3D model
│   │   ├── Macbook-16.jsx    # 16" MacBook 3D model
│   │   └── Macbook.jsx       # Features section MacBook model
│   └── three/
│       ├── StudioLights.jsx  # Three.js lighting setup
│       └── ModelSwitcher.jsx # Handle model transitions
├── constants/
│   └── index.js              # App constants and data
├── store/
│   └── index.js              # Zustand state management
├── App.jsx                   # Main app component
├── main.jsx                  # Entry point
└── index.css                 # Global styles
```

## 🎨 Key Components

### ProductViewer
Interactive 3D viewer allowing users to:
- Switch between Space Gray and Dark colors
- Toggle between 14" and 16" models
- Rotate and examine the MacBook from all angles

### Features Section
Synchronized scroll animation featuring:
- 360° rotating MacBook model
- Five feature highlights with icons
- Dynamic video textures on screen
- Smooth opacity and position transitions

### Performance Section
Showcases gaming performance with:
- Parallax image positioning
- Scroll-triggered image animations
- Responsive text reveals

### Showcase Section
M4 chip presentation with:
- Pinned video background
- Mask overlay animation
- Performance statistics

## 🎮 State Management

Uses Zustand for lightweight state management:
- `color` - Current MacBook color
- `scale` - Current model size (14" or 16")
- `texture` - Active video texture for Features section

## 🎬 Animations

GSAP animations include:
- Scroll-triggered section reveals
- 3D model rotation synchronized with scroll
- Smooth opacity and position transitions
- Model fade and slide transitions
- Parallax effects on images

## 📱 Responsive Design

- Desktop (1024px+): Full interactive experience
- Tablet (768px-1024px): Adapted layouts and controls
- Mobile (<768px): Simplified layouts, touch-optimized

## 🎨 Custom Fonts

Includes custom font family:
- Regular
- Medium
- SemiBold
- Bold

## 🌈 Color Scheme

- Primary: `#0071e3` (Apple Blue)
- Dark: `#2e2e30`
- Light Gray: `#adb5bd`
- Text Gray: `#86868b`

## 📝 License

This project uses 3D models licensed under CC-BY-4.0 by [jackbaeten](https://sketchfab.com/jackbaeten).

## 🙏 Acknowledgments

- 3D Models from Sketchfab
- Design inspired by Apple's product pages
- GSAP for powerful animations
- React Three Fiber community

## 🔧 Configuration

The project uses:
- Rolldown Vite for faster builds
- Tailwind CSS 4 with custom utilities
- ESLint for code quality

## 🚧 Development Notes

- Models are preloaded for smooth transitions
- Videos are preloaded in Features section
- Scroll animations optimized with `scrub: true`
- Mobile performance optimized with smaller model scales

## 📞 Support

For issues or questions, please open an issue in the repository.

---

Built with ❤️ using React, Three.js, and GSAP
