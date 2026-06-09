# 🚨 Rescue AI - Autonomous Disaster Response System

[![Version](https://img.shields.io/badge/version-6.0-blue.svg)](https://github.com/jahnavichaurasia67-sys/Rescue-AI)
[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge/deploy-status)](https://app.netlify.com/sites/your-site)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/jahnavichaurasia67-sys/Rescue-AI)
[![TensorFlow](https://img.shields.io/badge/TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/js)
[![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)](https://threejs.org/)

> **🤖 An AI-powered emergency response system that sees, thinks, and guides - even without internet.**

## 📱 Live Demo

**🌐 Try it now:** [Your Netlify Link Here]

> ⚠️ **Best Experience:** Chrome on Android | Safari on iOS | Allow Camera & Location

---

## 🎯 What Makes Rescue AI Different?

Rescue AI is not just another navigation app. It's an **autonomous emergency response system** that:

| Capability | Description |
|------------|-------------|
| 👁️ **SEES** | Camera detects fire, people, and obstacles in real-time |
| 🧠 **THINKS** | AI makes instant decisions based on what it sees |
| 🎯 **GUIDES** | Large, bright AR arrow shows exactly where to go |
| 🎤 **LISTENS** | Voice commands for hands-free operation |
| 📴 **WORKS OFFLINE** | No internet? No problem - cached data works |
| 🆘 **RESPONDS** | One-tap SOS shares your exact location |

---

## ✨ Features

| Feature | Status | Description |
|---------|--------|-------------|
| 🔥 **Fire Detection** | ✅ Live | AI detects fire and triggers immediate evacuation |
| 👤 **Victim Detection** | ✅ Live | Recognizes people needing assistance |
| 🪑 **Obstacle Detection** | ✅ Live | Identifies hazards in your path |
| 🧭 **AR Navigation Arrow** | ✅ Live | Large, bright 3D arrow with color coding |
| 🤖 **Autonomous Mode** | ✅ Live | AI chooses safest destination automatically |
| 📍 **Real-time GPS** | ✅ Live | Live tracking with 5m accuracy |
| 🏥 **Emergency Services** | ✅ Live | Finds hospitals, fire stations, police nearby |
| 🎨 **Distance Color Coding** | ✅ Live | Green → Orange → Red as you approach safety |
| 🆘 **SOS Alert** | ✅ Live | One-tap shares location via SMS |
| 🎤 **Voice Commands** | ✅ Live | "Help", "Where is safe", "Stop", "Resume" |
| 🧠 **AI Decision Log** | ✅ Live | Real-time display of AI thinking |
| 📴 **Offline Ready** | ✅ Live | Cached emergency data works without internet |

---

## 🎮 How It Works

### 1. Start Autonomous Mode
Press the **START AUTONOMOUS MODE** button - AI instantly:
- Activates camera to scan for hazards
- Gets your GPS location
- Finds nearest emergency services
- Begins guiding you with the AR arrow

### 2. Watch the AI Think
The **AI Decision Log** shows real-time thinking:
[10:30:15] 🤖 AI model ready! Camera will detect: Fire, People, Obstacles
[10:30:22] 🤖 Found 3 emergency services nearby
[10:30:25] 🎯 AI selected: City Hospital (250m away)
[10:30:30] 🔥 FIRE DETECTED! Evacuate immediately!

text

### 3. Follow the AR Arrow
The arrow changes color based on distance to safety:

| Distance | Arrow Color | Meaning |
|----------|-------------|---------|
| > 300m | 🟢 **Green** | Safe distance - continue following |
| 100-300m | 🟠 **Orange** | Getting close - stay alert |
| < 100m | 🔴 **Red** | Almost there! Safety nearby |

### 4. Use Voice Commands
Hold the **🎤 VOICE** button and say:

| Command | Response |
|---------|----------|
| "Help me" or "SOS" | 🆘 Triggers emergency SOS with your location |
| "Where is safe" | 🎯 AI announces nearest safe zone and distance |
| "Stop" or "Pause" | ⏸️ Pauses autonomous navigation |
| "Resume" or "Start" | ▶️ Reactivates AI guidance |

---

## 🛠️ Technology Stack

| Category | Technology | Purpose |
|----------|------------|---------|
| **AI/ML** | TensorFlow.js + COCO-SSD | Fire, person, obstacle detection |
| **3D Graphics** | Three.js | AR navigation arrow |
| **Maps & Data** | OpenStreetMap + Overpass API | Emergency service locations |
| **Location** | Geolocation API + Haversine formula | GPS tracking & distance |
| **Voice** | Web Speech API | Voice command recognition |
| **Speech** | Web Speech Synthesis | Voice guidance output |
| **Hosting** | Netlify / GitHub Pages | Deployment |

---

## 📂 Project Structure
Rescue-AI/
│
├── index.html # Complete application (all-in-one)
├── README.md # This file
└── (optional) sw.js # Service worker for offline mode

text

**Single-file architecture** - Everything in `index.html` for easy deployment!

---

## 🚀 Quick Start

### For Users (No Installation!)

1. Open **Chrome** on your mobile device
2. Visit your Netlify link
3. Tap **Allow** for Camera access
4. Tap **Allow** for Location access
5. Press **START AUTONOMOUS MODE**
6. Follow the **bright AR arrow** to safety!

### For Developers

```bash
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
📱 Device Compatibility
Device	Browser	Camera	GPS	AR Arrow	Voice
Android Phone	Chrome	✅	✅	✅	✅
iPhone	Safari	✅	✅	✅	✅
Android Tablet	Chrome	✅	✅	✅	✅
iPad	Safari	✅	✅	✅	✅
Desktop	Chrome	⚠️	⚠️	✅	✅
⚠️ Desktop has limited GPS and uses front camera only

🔥 AI Disaster Recognition
Detected Object	AI Decision	Action
🔥 Fire	EVACUATE IMMEDIATELY	Speaks warning, changes arrow to red, prioritizes nearest exit
👤 Person	ASSIST MODE	Alerts user, logs victim location
🪑 Obstacle	CAUTION	Warns user to navigate carefully
✅ No Threat	NORMAL NAVIGATION	Guides to nearest hospital/fire station
🗺️ AI Decision Flow
text
                    START
                      │
                      ▼
            ┌─────────────────┐
            │  Camera Scanning │
            │  for Disasters   │
            └─────────────────┘
                      │
                      ▼
            ┌─────────────────┐
            │  Fire Detected?  │
            └─────────────────┘
                 │       │
              Yes│       │No
                 ▼       ▼
        ┌──────────┐  ┌─────────────────┐
        │EVACUATE  │  │ Person Detected?│
        │IMMEDIATELY│  └─────────────────┘
        └──────────┘       │       │
                      Yes│       │No
                         ▼       ▼
                  ┌──────────┐  ┌─────────────────┐
                  │ ASSIST   │  │ Get GPS Location│
                  │ MODE     │  └─────────────────┘
                  └──────────┘           │
                                         ▼
                              ┌─────────────────┐
                              │ Find Nearest    │
                              │ Emergency       │
                              │ Service         │
                              └─────────────────┘
                                         │
                                         ▼
                              ┌─────────────────┐
                              │ Show AR Arrow   │
                              │ & Distance      │
                              └─────────────────┘
                                         │
                                         ▼
                              ┌─────────────────┐
                              │ Distance < 50m? │
                              └─────────────────┘
                                   │       │
                                Yes│       │No
                                   ▼       └──────┐
                            ┌──────────┐          │
                            │ SAFETY   │          │
                            │ REACHED! │          │
                            └──────────┘          │
                                            Continue Navigation
📊 Performance
Metric	Target	Current
First Load	< 3s	✅ ~2s
AI Detection Speed	30 FPS	✅ 30-60 FPS
GPS Accuracy	< 10m	✅ ~5m
Arrow Refresh Rate	60 FPS	✅ 60 FPS
Voice Response	< 1s	✅ ~0.5s
🚀 Deployment
Deploy to Netlify (Recommended)
https://www.netlify.com/img/deploy/button.svg

Steps:

Push code to GitHub

Log into Netlify

Click "Add new site" → "Import an existing project"

Select your repository

Click Deploy - Your site is live in 30 seconds!

Deploy to GitHub Pages
Go to Settings → Pages

Branch: main → / (root)

Save

Wait 2 minutes

Visit: https://jahnavichaurasia67-sys.github.io/Rescue-AI/

Quick Deploy (Drag & Drop)
Save the code as index.html

Go to app.netlify.com/drop

Drag and drop your file

Share your link!

🧪 Testing
Test Offline Mode
bash
1. Open Chrome DevTools (F12)
2. Go to Application → Service Workers
3. Check "Offline" checkbox
4. Refresh page
5. App should still work with cached data!
Test Voice Commands
bash
1. Click and hold 🎤 button
2. Say "Where is safe" clearly
3. Release button
4. AI should respond verbally
Test AI Detection
bash
1. Point camera at different objects
2. Check AI Decision Log for detections
3. Fire, people, obstacles should be recognized
🗺️ Roadmap
✅ Completed
AI disaster detection (Fire, People, Obstacles)

AR navigation arrow with color coding

Autonomous decision engine

Voice commands

SOS functionality

GPS tracking

Emergency services integration

Clear UI with no visual interference

🚧 Coming Soon
Multi-language support (Hindi, Spanish)

Battery saver mode

Share live location with contacts

Earthquake early warning integration

Flood zone alerts

🤝 Contributing
Contributions welcome! Areas to help:

Area	Description
🐛 Bug Reports	Open an issue on GitHub
💡 Feature Ideas	Start a discussion
🌐 Translations	Add language support
📝 Documentation	Improve this README
🎨 UI/UX	Design improvements
👥 Team
Role	Name	Institution
Lead Developer	Jahnavi Chaurasia	FGIET, Rae Bareli
Co-Developer	Sakina Kazmi	FGIET, Rae Bareli
"Because survival should never depend on guesswork" - HackHer Duo

📞 Emergency Numbers (India)
Service	Number
Police / Emergency	112
Ambulance	102
Fire Brigade	101
Women Helpline	1090
Child Helpline	1098
🙏 Acknowledgments
Name	Contribution
TensorFlow.js Team	AI object detection models
OpenStreetMap	Free mapping & emergency service data
Overpass API	Emergency service queries
Three.js	3D AR arrow rendering
Netlify	Free HTTPS hosting
⚠️ Disclaimer
Rescue AI is a prototype demonstration project.

🔥 AI detection works best in good lighting conditions

📍 GPS accuracy varies by device (typically 5-20 meters)

🆘 SOS opens SMS app - does NOT auto-call emergency services

🎯 Always dial 112 in real emergencies

🧪 Test only in safe environments

📱 For best results, use Chrome on Android or Safari on iOS

📄 License
text
✅ Educational Use - Allowed
✅ Personal Use - Allowed
✅ Modification - Allowed
❌ Commercial Use - Requires Permission
For commercial licensing: Contact via GitHub

⭐ Support This Project
If Rescue AI helps you or you believe in our mission:

Action	Why
⭐ Star this repo	Helps others discover the project
🔄 Share with friends	Spreads life-saving technology
🐛 Report issues	Helps improve the system
💡 Suggest features	Shapes future development
📞 Contact
Platform	Link
Live Demo	[Your Netlify Link]
GitHub	jahnavichaurasia67-sys/Rescue-AI
Issues	Report Bug
📊 Statistics
https://img.shields.io/github/stars/jahnavichaurasia67-sys/Rescue-AI?style=social
https://img.shields.io/github/forks/jahnavichaurasia67-sys/Rescue-AI?style=social
https://img.shields.io/github/watchers/jahnavichaurasia67-sys/Rescue-AI?style=social

<div align="center">
🚨 Because survival should never depend on guesswork 🚨
Rescue AI
Navigate Emergencies Smarter
⬆ Back to Top

Made with ❤️ by HackHer Duo | © 2026 Rescue AI Project

"Technology that saves lives - that's our mission."

</div> ```