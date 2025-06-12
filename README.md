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

CyberGuard/<br>
├── app/<br>
│   └── src/<br>
│       └── main/<br>
│           ├── java/com/sanjana/cyberguard/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# Kotlin source files<br>
│           │   ├── RegisterActivity.kt&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# User registration logic<br>
│           │   ├── LoginActivity.kt              # User login & auth<br>
│           │   ├── QuizActivity.kt               # Quiz logic and UI<br>
│           │   ├── ChatbotActivity.kt            # AI-based chatbot interface<br>
│           │   ├── TerminalActivity.kt           # Simulated terminal emulator<br>
│           │   ├── NewsActivity.kt               # Live cybersecurity news feed<br>
│           │   ├── SecurityCheckup.kt            # Device vulnerability scan<br>
│           │   ├── TrackerActivity.kt            # Cyber hygiene tracker<br>
│           │   └── utils/                         # Helper classes & utils<br>
│           ├── res/<br>
│           │   ├── layout/                        # All XML layout files<br>
│           │   ├── drawable/                      # Icons, background images<br>
│           │   └── values/                        # Colors, strings, styles<br>
│           └── AndroidManifest.xml               # App manifest<br>
├── screenshots/                                   # App UI preview images<br>
│   ├── login.png<br>
│   ├── chatbot.png<br>
│   ├── quiz.png<br>
│   └── tracker.png<br>
├── google-services.json                           # Firebase config<br>
├── build.gradle                                   # Gradle build (Project-level)<br>
├── app/build.gradle                               # Gradle build (App-level)<br>
├── README.md                                      # Project documentation<br>
└── LICENSE                                        # License information<br>

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
