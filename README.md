# ⚡ S Cleaner

S Cleaner is a lightweight, high-performance system utility and automation engine for Android 12+. Designed with a custom Neumorphic UI and dot-matrix aesthetics, it automates memory optimization and deep-sweeps storage to keep your device running smoothly.

## ✨ Features
* **Automated RAM Boost:** Utilizes Android's Accessibility Services to act as an automated "ghost finger," rapidly force-stopping hidden background applications to free up memory.
* **Deep Storage Sweep:** Scans and clears leftover application cache and junk files from public directories.
* **Privacy First:** S Cleaner operates entirely locally. It does not collect, transmit, or sell any personal user data. 

## 🚀 How to Install
1. Go to the **Releases** section on the right side of this repository.
2. Download the latest `S_Cleaner.apk` file to your Android device.
3. Open the file and tap **Install** (you may need to allow "Install from Unknown Sources" in your browser/file manager settings).

---

## 🔒 Permissions Guide (Important!)
Because S Cleaner acts as a powerful system optimizer, it requires two specific permissions to function correctly. 

### 1. All Files Access (Storage)
* **Why it's needed:** To scan the file system and delete hidden cache/junk files.
* **How to grant:** When you first tap the center sweep button, you will be prompted to allow "All Files Access." Toggle this switch ON and swipe back to the app.

### 2. Accessibility Service (RAM Boost)
* **Why it's needed:** Android does not allow apps to instantly kill other apps in the background. S Cleaner uses the Accessibility Service to automatically click the "Force Stop" and "OK" buttons in your system settings at high speed.
* **How to grant:** Tap the "Force Stop" button in the app to be taken to your Accessibility menu, then turn on S Cleaner.

> ⚠️ **ANDROID 13+ USERS: "RESTRICTED SETTINGS" BYPASS**
> If you are on Android 13 or newer and downloaded this APK directly from GitHub, Android will gray out the Accessibility toggle for your safety. To unlock it:
> 1. Go to your phone's main **Settings > Apps > S Cleaner**.
> 2. Tap the **three vertical dots** in the top right corner.
> 3. Tap **Allow restricted settings** and enter your PIN/Fingerprint.
> 4. Return to the Accessibility menu, and the toggle will now be unlocked!

## 🛠️ Technical Specs
* **Minimum SDK:** Android 12 (API Level 31)
* **Architecture:** Universal (Fat APK)
* **Package:** `com.hesi.scleaner`
* **Language:** Kotlin
