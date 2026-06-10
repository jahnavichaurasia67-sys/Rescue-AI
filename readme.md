# 🚨 Rescue AI - Autonomous Disaster Response System

> **AI-Powered Emergency Navigation | Camera Detection | Voice Commands | Clean Unobstructed View**

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/jahnavichaurasia67-sys/Rescue-AI)
[![TensorFlow](https://img.shields.io/badge/TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/js)
[![License](https://img.shields.io/badge/License-Educational%20Use-blue.svg)](LICENSE)

---

## 📱 Live Demo

**🌐 Try it now:**  https://jahnavichaurasia67-sys.github.io/Rescue-AI/

> ⚠️ **Best Experience:** Chrome on Android | Safari on iOS | Allow Camera & Location

---

## 🎯 What Makes Rescue AI Different?

Rescue AI is a clean, unobstructed emergency navigation system that helps you find safety during disasters.

| Feature | Description |
|---------|-------------|
| 👁️ **Sees** | Camera detects fire, people, and obstacles in real-time |
| 🧠 **Thinks** | AI makes instant decisions based on detected hazards |
| 🗣️ **Speaks** | Voice guidance for hands-free operation |
| 📍 **Locates** | GPS tracking with nearest shelter finder |
| 🎤 **Listens** | Voice commands like "Help", "Where is safe" |
| 🆘 **Responds** | One-tap SOS shares your exact location via SMS |
| 🚫 **No Arrow** | Clean camera view - nothing blocking your path |

---

## ✨ Features

| Feature | Status | Description |
|---------|--------|-------------|
| 🔥 **Fire Detection** | ✅ Live | AI detects fire and triggers evacuation alert |
| 👤 **Person Detection** | ✅ Live | Recognizes people needing assistance |
| 🪑 **Obstacle Detection** | ✅ Live | Identifies hazards in your path |
| 🧭 **Direction Guidance** | ✅ Live | Shows AHEAD/LEFT/RIGHT in top-left corner |
| 🤖 **Autonomous Mode** | ✅ Live | AI chooses safest destination automatically |
| 📍 **Real-time GPS** | ✅ Live | Live tracking with location display |
| 🏥 **Emergency Services** | ✅ Live | Finds hospitals, fire stations, police nearby |
| 🎨 **Distance Color Coding** | ✅ Live | Green → Orange → Red as you approach safety |
| 🆘 **SOS Alert** | ✅ Live | One-tap shares location via SMS |
| 🎤 **Voice Commands** | ✅ Live | "Help", "Where is safe", "Stop", "Start" |
| 🗣️ **Voice Guidance** | ✅ Live | AI speaks directions aloud |

---

## 🎮 How It Works

### 1. Start Autonomous Mode

Press the **START AUTONOMOUS MODE** button - AI instantly:
- Activates camera to scan for hazards
- Gets your GPS location
- Finds nearest emergency services
- Begins guiding you

### 2. Look at the Top-Left Corner

The direction guidance appears in the **top-left corner** - completely out of your way:

| Arrow | Meaning | Action |
|-------|---------|--------|
| ⬆️ | **AHEAD** | Keep walking straight |
| ↗️ | **RIGHT** | Turn right slightly |
| ➡️ | **HARD RIGHT** | Sharp right turn |
| ↖️ | **LEFT** | Turn left |
| ⬅️ | **HARD LEFT** | Sharp left turn |
| 🔄 | **TURN BACK** | You're going the wrong way! |

### 3. Check the Top Status Bar

- **📍 LOCATION:** Your current GPS coordinates
- **🏥 NEAREST:** Closest hospital/fire station/police and distance

### 4. Voice Commands

Hold the **🎤 VOICE** button and say:

| Command | Response |
|---------|----------|
| "Help me" or "SOS" | 🆘 Triggers emergency SOS with your location |
| "Where is safe" | 🎯 AI announces nearest safe zone and distance |
| "Stop" or "Pause" | ⏸️ Pauses autonomous mode |
| "Start" or "Resume" | ▶️ Reactivates AI guidance |

---

## 🔥 AI Disaster Recognition

| Detected Object | AI Decision | Action |
|----------------|-------------|--------|
| 🔥 **Fire** | EVACUATE IMMEDIATELY | Speaks warning, changes status to EVACUATE |
| 👤 **Person** | ASSIST MODE | Alerts user, shows person detected |
| 🪑 **Obstacle** | CAUTION | Warns user to navigate carefully |
| ✅ **No Threat** | NORMAL NAVIGATION | Guides to nearest hospital/fire station |

---

## 🗺️ AI Decision Flow
┌─────────────┐
│ START │
└──────┬──────┘
│
▼
┌─────────────┐
│ Camera │
│ Scanning │
│ for Hazards │
└──────┬──────┘
│
▼
┌─────────────┐
│ Fire │
│ Detected? │
└──────┬──────┘
│
┌────────────┴────────────┐
│ │
▼ ▼
┌─────────────┐ ┌─────────────┐
│ EVACUATE │ │ Person │
│ IMMEDIATELY │ │ Detected? │
└─────────────┘ └──────┬──────┘
│
┌────────────┴────────────┐
│ │
▼ ▼
┌─────────────┐ ┌─────────────┐
│ ASSIST │ │ Get │
│ MODE │ │ GPS Fix │
└─────────────┘ └──────┬──────┘
│
▼
┌─────────────┐
│ Find │
│ Nearest │
│ Emergency │
│ Service │
└──────┬──────┘
│
▼
┌─────────────┐
│ Show │
│ Direction │
│ & Distance │
└──────┬──────┘
│
▼
┌─────────────┐
│ Distance │
│ < 50m? │
└──────┬──────┘
│
┌────────────┴────────────┐
│ │
▼ ▼
┌─────────────┐ ┌─────────────┐
│ SAFETY │ │ Continue │
│ REACHED! │ │ Navigation │
└─────────────┘ └─────────────┘

text

---

## 📱 Device Compatibility

| Device | Browser | Camera | GPS | Direction | Voice |
|--------|---------|--------|-----|-----------|-------|
| Android Phone | Chrome | ✅ | ✅ | ✅ | ✅ |
| iPhone | Safari | ✅ | ✅ | ✅ | ✅ |
| Android Tablet | Chrome | ✅ | ✅ | ✅ | ✅ |
| iPad | Safari | ✅ | ✅ | ✅ | ✅ |
| Desktop | Chrome | ⚠️ | ⚠️ | ✅ | ✅ |

> ⚠️ Desktop has limited GPS (uses network location) and may use front camera only

---

## 🚀 Quick Start

### For Users (No Installation!)

1. Open **Chrome** on your mobile device
2. Visit your Netlify link
3. Tap **Allow** for Camera access
4. Tap **Allow** for Location access
5. Press **START AUTONOMOUS MODE**
6. Look at **top-left corner** for direction guidance!

### For Developers

```
# Clone the repository
git clone https://github.com/jahnavichaurasia67-sys/Rescue-AI.git

# Navigate to project
cd Rescue-AI

# Start local server (Python)
python -m http.server 8000

# OR use Node.js
npx serve .

# Open browser
open http://localhost:8000
---

## 📂 Project Structure
text
Rescue-AI/
│
├── index.html          # Complete application (all-in-one)
└── README.md           # This file

Single-file architecture - Everything in index.html for easy deployment!

---

## 🛠️ Technology Stack

| Category | Technology | Purpose |
|-----------|-----------|-----------|
| AI/ML | TensorFlow.js + COCO-SSD | Fire, person, obstacle detection |
| Maps & Data | OpenStreetMap + Overpass API | Emergency service locations |
| Location | Geolocation API + Haversine Formula | GPS tracking & distance |
| Voice | Web Speech API | Voice command recognition |
| Speech | Web Speech Synthesis | Voice guidance output |
| Hosting | Netlify / GitHub Pages | Deployment |

---

## 📊 Distance Color Coding

| Distance | Color | Meaning |
|-----------|--------|---------|
| > 300m | 🟢 Green | Safe distance – continue walking |
| 100–300m | 🟠 Orange | Getting close – stay alert |
| < 100m | 🔴 Red | Almost there! Safety nearby |

---

## 🧪 Testing

### Test Voice Commands

```text
1. Click and hold 🎤 VOICE button
2. Say "Where is safe" clearly
3. Release button
4. AI should respond verbally
```

### Test AI Detection

```text
1. Point camera at a person
2. Check top of screen for "👤 PERSON DETECTED NEARBY"
3. AI Status should show "👤 ASSIST MODE"
```

### Test Fire Detection

```text
1. Point camera at a red/orange object or fire source (safely!)
2. AI should detect and announce "FIRE DETECTED! EVACUATE!"
3. Status changes to "🔥 EVACUATE!"
```

---

## 🚀 Deployment

### Deploy to Netlify (Recommended)

```text
1. Save the code as index.html
2. Go to app.netlify.com/drop
3. Drag and drop your index.html file
4. Your site is live in 10 seconds
```

### Deploy to GitHub Pages

```text
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select Branch: main → / (root)
4. Save and wait 2 minutes
5. Visit:
https://jahnavichaurasia67.github.io/Rescue-AI/
```

---

## 🗺️ Roadmap

### ✅ Completed

- Fire Detection (Camera AI)
- Person Detection
- Obstacle Detection
- Direction Guidance
- Voice Commands
- SOS Functionality
- GPS Tracking
- Emergency Services Integration
- Clean UI (No Obstructing Arrows)
- Distance Color Coding
- Voice Guidance Output

### 🚧 Coming Soon

- Multi-language Support (Hindi, Spanish)
- Battery Saver Mode
- Earthquake Early Warning Integration
- Flood Zone Alerts
- Offline Mode with Service Worker

---

## 🤝 Contributing

Contributions are welcome!

| Area | Description |
|--------|------------|
| 🐛 Bug Reports | Open an issue on GitHub |
| 💡 Feature Ideas | Start a discussion |
| 🌐 Translations | Add language support |
| 📝 Documentation | Improve this README |

---

## 👥 Team

| Role | Name | Institution |
|--------|--------|------------|
| Lead Developer | Jahnavi Chaurasia | FGIET, Rae Bareli |
| Co-Developer | Sakina Kazmi | FGIET, Rae Bareli |

> "Because survival should never depend on guesswork" — HackHer Duo

---

## 📞 Emergency Numbers (India)

| Service | Number |
|----------|--------|
| Police / Emergency | 112 |
| Ambulance | 102 |
| Fire Brigade | 101 |
| Women Helpline | 1090 |
| Child Helpline | 1098 |

---

## ⚠️ Disclaimer

- 🔥 AI detection works best in good lighting conditions.
- 📍 GPS accuracy varies by device (typically 5–20 meters).
- 🆘 SOS opens SMS app and does **not** auto-call emergency services.
- 🎯 Always dial **112** in real emergencies.
- 🧪 Test only in safe environments.
- 📱 Use Chrome (Android) or Safari (iOS) for best results.

---

## 📄 License

```text
✅ Educational Use - Allowed
✅ Personal Use - Allowed
✅ Modification - Allowed
❌ Commercial Use - Requires Permission
```

For commercial licensing, contact via GitHub.

---

## ⭐ Support This Project

| Action | Why |
|---------|------|
| ⭐ Star this Repo | Helps others discover the project |
| 🔄 Share with Friends | Spreads life-saving technology |
| 🐛 Report Issues | Helps improve the system |
| 💡 Suggest Features | Shapes future development |

---

## 📞 Contact

| Platform | Link |
|----------|------|
| Live Demo |  https://jahnavichaurasia67-sys.github.io/Rescue-AI/ |
| GitHub | https://github.com/jahnavichaurasia67-sys/Rescue-AI |
| Issues | GitHub Issues |

---

## 📊 Repository Stats

![Stars](https://img.shields.io/github/stars/jahnavichaurasia67-sys/Rescue-AI?style=social)

![Forks](https://img.shields.io/github/forks/jahnavichaurasia67-sys/Rescue-AI?style=social)

![Watchers](https://img.shields.io/github/watchers/jahnavichaurasia67-sys/Rescue-AI?style=social)

---

<div align="center">

# 🚨 Rescue AI

### Navigate Emergencies Smarter

Made with ❤️ by **HackHer Duo**

© 2026 Rescue AI Project

*"Technology that saves lives — that's our mission."*

</div>