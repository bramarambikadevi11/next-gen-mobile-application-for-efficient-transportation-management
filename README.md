CSM Batch- 2

📁 Project Contents (Folder Explanation)
1️⃣ Root Level Files
File	Purpose
pubspec.yaml	Main Flutter configuration file (dependencies, assets, version)
pubspec.lock	Locked dependency versions
analysis_options.yaml	Dart linting rules
package.json	Node/Firebase related dependencies (if web hosting used)
firebase.json	Firebase hosting configuration
.firebaserc	Firebase project mapping
README.md	Project documentation
2️⃣ lib/ (Main Application Code – Flutter)

This is the most important folder (not shown in truncated preview but exists in Flutter apps).

Typical contents:

lib/
 ├── main.dart          # Entry point of the application
 ├── screens/           # UI Screens (Login, Dashboard, Bus Details etc.)
 ├── models/            # Data models
 ├── services/          # API calls & Firebase services
 └── widgets/           # Reusable UI components

👉 This contains complete application logic written in Dart.

3️⃣ android/

Contains Android-specific configuration:

build.gradle.kts – Gradle build configuration

MainActivity.kt – Main Android launcher activity

google-services.json – Firebase Android configuration

res/ – Icons, styles, launch screen, raw audio (bus_alert_sound.mp3)

Framework Used Here:

Android SDK

Kotlin

Gradle Build System

4️⃣ web/

Contains web deployment files:

index.html

manifest.json

App icons

👉 This enables Flutter Web support.

5️⃣ windows/

Desktop support for Windows platform:

CMake configuration

Windows runner files

Native window setup

Framework Used:

CMake

Windows Desktop Flutter Embedding

6️⃣ assets/

Static resources used inside the app:

assets/
 ├── vtm_service.json   # Firebase service file
 └── images/
      ├── red_question.png
      └── vtm_logo.png

These are declared in pubspec.yaml.

7️⃣ .dart_tool/ & build/

Auto-generated Flutter build files

Should NOT be modified manually

🛠️ Frameworks & Technologies Used Clearly
📱 Frontend Framework

Flutter

Dart Programming Language

🔥 Backend / Cloud

Firebase

Firebase Authentication

Firebase Hosting

Possibly Firestore / Realtime Database

📦 Build & Deployment

Gradle (Android)

CMake (Windows)

Flutter Web Engine

🎨 UI

Material Design (Flutter default)

Custom assets (logo, images)

🔐 Authentication

Firebase Authentication (based on presence of firebase config)

🏗️ Platform Support

Your project supports:

✅ Android
✅ Web
✅ Windows Desktop

This makes it a cross-platform transport management mobile & web application.
