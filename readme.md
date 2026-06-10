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

```text
┌─────────────┐
│    START    │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│   Camera    │
│  Scanning   │
│ For Hazards │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│    Fire     │
│ Detected ?  │
└──────┬──────┘
       │
 ┌─────┴─────┐
 │           │
 ▼           ▼
YES         NO
 │           │
 ▼           ▼
┌─────────┐  ┌─────────────┐
│EVACUATE │  │   Person    │
│NOW!     │  │ Detected ?  │
└─────────┘  └──────┬──────┘
                    │
              ┌─────┴─────┐
              │           │
              ▼           ▼
             YES         NO
              │           │
              ▼           ▼
       ┌──────────┐  ┌──────────┐
       │ ASSIST   │  │ GET GPS  │
       │  MODE    │  │ LOCATION │
       └──────────┘  └────┬─────┘
                           │
                           ▼
                  ┌────────────────┐
                  │ Find Nearest   │
                  │ Emergency Hub  │
                  └───────┬────────┘
                          │
                          ▼
                  ┌────────────────┐
                  │ Show Direction │
                  │ & Distance     │
                  └───────┬────────┘
                          │
                          ▼
                  ┌────────────────┐
                  │ Distance <50m? │
                  └───────┬────────┘
                          │
                   ┌──────┴──────┐
                   │             │
                   ▼             ▼
            ┌───────────┐ ┌───────────┐
            │  SAFETY   │ │ Continue  │
            │ REACHED!  │ │Navigation │
            └───────────┘ └───────────┘
```

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

### For Users

1. Open Chrome on Android or Safari on iPhone.
2. Visit the deployed website.
3. Allow Camera Permission.
4. Allow Location Permission.
5. Press **START AUTONOMOUS MODE**.

### For Developers

```bash
# Clone Repository
git clone https://github.com/jahnavichaurasia67-sys/Rescue-AI.git

# Enter Project Folder
cd Rescue-AI

# Run Local Server
python -m http.server 8000

# OR
npx serve .

# Open Browser
http://localhost:8000
```

---

## 🚀 Deployment

### Deploy to Netlify

```bash
1. Save project files
2. Visit https://app.netlify.com/drop
3. Drag & Drop project folder
4. Site goes live instantly
```

### Deploy to GitHub Pages

```bash
# Initialize Git
git init

# Add Files
git add .

# Commit
git commit -m "Initial Commit"

# Connect Repository
git remote add origin https://github.com/jahnavichaurasia67-sys/Rescue-AI.git

# Push Code
git push -u origin main
```

### Enable GitHub Pages

```text
GitHub Repository
  → Settings
  → Pages
  → Source: Deploy from Branch
  → Branch: main
  → Folder: /root
  → Save
```

Your site will be available at:

https://jahnavichaurasia67-sys.github.io/Rescue-AI/

'''
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

<div align="center">

# 🚨 Rescue AI

### Navigate Emergencies Smarter

Made with ❤️ by **HackHer Duo**

© 2026 Rescue AI Project

*"Technology that saves lives — that's our mission."*

</div>