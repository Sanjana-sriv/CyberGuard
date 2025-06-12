# 🛡 CyberGuard - Your Digital Security Companion

CyberGuard is an Android application designed to empower users with the knowledge and tools needed to stay secure in the digital world. Built using *Kotlin* and *Firebase*, the app provides a holistic approach to cybersecurity awareness, threat detection, and safe browsing practices.

---

## 🚀 Features

### 🔔 Real-time Security Alerts
Get notified about emerging cybersecurity threats and potential vulnerabilities.

### 🤖 AI-based Chatbot
Ask security-related questions and receive instant, best-practice responses through an integrated chatbot.

### 📱 Device Security Checkup
Analyze device configurations and identify potential weaknesses in settings.

### 🧼 Cyber Hygiene Tracker
Track your daily digital hygiene activities and get reminders to maintain best practices.

### ❓ Cybersecurity Quiz Module
Test your cybersecurity knowledge with interactive, gamified quizzes.

### 📰 Cybersecurity News Feed
Stay up-to-date with the latest cyber threats and news from trusted sources.

### 💬 Terminal Emulator (Simulated)
Practice and learn basic security commands in a simulated terminal environment.

---

## 🏗 Tech Stack

- *Frontend*: Kotlin (Android Studio)
- *Backend*: Firebase Realtime Database
- *Authentication*: Firebase (email-password based)
- *Chatbot*: Rule-based local bot (expandable to ML-based bot)
- *UI*: Material Design Components
- *Dev Tools*: Android Emulator, Firebase Console

---

## 📁 Project Structure

CyberGuard/
├── app/
│   └── src/
│       └── main/
│           ├── java/com/sanjana/cyberguard/      # Kotlin source files
│           │   ├── RegisterActivity.kt           # User registration logic
│           │   ├── LoginActivity.kt              # User login & auth
│           │   ├── QuizActivity.kt               # Quiz logic and UI
│           │   ├── ChatbotActivity.kt            # AI-based chatbot interface
│           │   ├── TerminalActivity.kt           # Simulated terminal emulator
│           │   ├── NewsActivity.kt               # Live cybersecurity news feed
│           │   ├── SecurityCheckup.kt            # Device vulnerability scan
│           │   ├── TrackerActivity.kt            # Cyber hygiene tracker
│           │   └── utils/                         # Helper classes & utils
│           ├── res/
│           │   ├── layout/                        # All XML layout files
│           │   ├── drawable/                      # Icons, background images
│           │   └── values/                        # Colors, strings, styles
│           └── AndroidManifest.xml               # App manifest
├── screenshots/                                   # App UI preview images
│   ├── login.png
│   ├── chatbot.png
│   ├── quiz.png
│   └── tracker.png
├── google-services.json                           # Firebase config
├── build.gradle                                   # Gradle build (Project-level)
├── app/build.gradle                               # Gradle build (App-level)
├── README.md                                      # Project documentation
└── LICENSE                                        # License information




---

## 🔧 Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project and enable *Realtime Database*
3. Add your Android app to Firebase and download google-services.json
4. Place google-services.json in your app's /app directory
5. Update your build.gradle files:
Enable read/write rules for development in Firebase Realtime Database:
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
