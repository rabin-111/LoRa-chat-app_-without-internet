📡 No-Net P2P LoRa App

Offline peer-to-peer communication app using LoRa radio technology — no internet, no cellular network required.

About
No-Net P2P LoRa App is a Flutter-based mobile application that enables device-to-device communication using LoRa (Long Range Radio) technology. It works completely without internet or cellular connectivity, making it ideal for:

Remote areas with no network coverage
Emergency/disaster communication
Off-grid hiking, trekking, and outdoor activities
Secure local communication


✨ Features

📨 Offline Messaging — Send and receive messages without internet
📡 LoRa P2P Communication — Long-range radio-based data transfer
🔒 No Server Required — Fully decentralized, no cloud dependency
📱 Cross-Platform — Works on Android and iOS
🗺️ Works Anywhere — Mountains, forests, remote areas
💾 Local Storage — Messages stored locally using SQLite


🛠️ Tech Stack
LayerTechnologyMobile AppFlutter / DartLocal DatabaseSQLite (sqflite)Radio CommunicationLoRa ModulePlatform SupportAndroid, iOS, WindowsState ManagementFlutter native

📋 Requirements
Software

Flutter SDK >=3.0.0
Dart SDK >=3.0.0
Android Studio / VS Code
Android API Level 21+ or iOS 12+

Hardware

LoRa module (e.g., ESP32 + LoRa SX1276/SX1278)
2x devices for P2P communication


🚀 Getting Started
1. Clone the repository
2. Install dependencies
bashflutter pub get
3. Run the app
bash# Debug mode
flutter run

# Release mode
flutter run --release
4. Build APK
bashflutter build apk --release

📁 Project Structure
no_net_p2p_lora-app/
├── lib/
│   ├── main.dart          # App entry point
│   ├── screens/           # UI screens
│   ├── models/            # Data models
│   ├── services/          # LoRa & BT services
│   └── widgets/           # Reusable widgets
├── android/               # Android-specific files
├── ios/                   # iOS-specific files
├── assets/
│   ├── images/            # App images
│   └── icon/              # App icons
├── pubspec.yaml           # Dependencies
└── README.md

⚙️ Hardware Setup

Connect LoRa module to your microcontroller (ESP32 recommended)
Flash the firmware to the LoRa device
Pair the mobile app with the LoRa hardware via Bluetooth/USB
Start communicating offline!


📦 Dependencies
yamldependencies:
  flutter:
    sdk: flutter
  sqflite: ^2.0.0          # Local database
  permission_handler: ^11.0.0  # Device permissions
  path_provider: ^2.0.0    # File storage paths

🤝 Contributing
Contributions are welcome!
bash# 1. Fork the repo
# 2. Create your feature branch
git checkout -b feature/your-feature

# 3. Commit your changes
git commit -m "feat: add your feature"

# 4. Push and create PR
git push origin feature/your-feature

👨‍💻 Author
Rabin Poudel

GitHub: @rabin-111


📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

⭐ Support
Yo project helpful lagyo bhane star dinus! ⭐
