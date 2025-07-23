# 🛡 CyberGuard - Your Digital Security Companion

CyberGuard is an Android application designed to empower users with the knowledge and tools needed to stay secure in the digital world. Built using *Kotlin* and *Firebase*, the app provides a holistic approach to cybersecurity awareness, threat detection, and safe browsing practices.

---

## 🚀 Features

### 🔔 Real-time Security Alerts
Get notified about emerging cybersecurity threats and potential vulnerabilities.

### 🤖 Chatbot
Ask security-related questions and receive instant, best-practice responses through an integrated chatbot.

### 📱 Device Security Checkup
Analyze device configurations and identify potential weaknesses in settings.

### 🧼 Cyber Hygiene Tracker
Track your daily digital hygiene activities and get reminders to maintain best practices.

### ❓ Cybersecurity Quiz Module
Test your cybersecurity knowledge with interactive quizzes.

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
│&nbsp;└── src/<br>
│&nbsp;&nbsp;└── main/<br>
│&nbsp;&nbsp;&nbsp;├── java/com/sanjana/cyberguard/<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── RegisterActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── LoginActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── QuizActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── ChatbotActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── TerminalActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── NewsActivity.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── SecurityCheckup.kt<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── TrackerActivity.ktr<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   └── utils/<br>
│&nbsp;&nbsp;&nbsp;├── res/<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── layout/<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   ├── drawable/<br>
│&nbsp;&nbsp;&nbsp;│&nbsp;   └── values/<br>
│&nbsp;&nbsp;&nbsp;└── AndroidManifest.xml<br>
├── screenshots/<br>
│&nbsp;   ├── login.png<br>
│&nbsp;   ├── chatbot.png<br>
│&nbsp;   ├── quiz.png<br>
│&nbsp;   └── tracker.png<br>
├── google-services.json<br>
├── build.gradle <br>
├── app/build.gradle<br>
├── README.md <br>
└── LICENSE<br>

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
