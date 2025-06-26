# 🎧Share-Wave — Multi-TWS Audio Sharing from Android

**EchoCast** is a 100% software-based Android project that enables a single mobile device (such as a Motorola Edge 50 Fusion running stock Android) to stream the **same audio to multiple TWS (True Wireless Stereo) earphones simultaneously** — without rooting the device or using any external hardware.

---

## 🚀 Features

- 📱 Works on **stock Android** (no root required)
- 🔗 Attempts **dual Bluetooth audio streaming**
- 🎵 **Clones audio stream** to send to multiple paired devices
- 🎚️ Adjustable **latency/sync compensation**
- 🎨 Clean and simple UI to control connections and playback

---

## 🎯 Objective

The goal of this project is to bypass Android’s one-to-one Bluetooth A2DP limitation and stream identical audio to **multiple Bluetooth audio receivers (like TWS earbuds)** using just software, while maintaining playback sync and user control.

---

## 🛠️ Tech Stack

- **Platform:** Android (Stock)
- **Language:** Kotlin
- **Audio APIs:** `AudioTrack`, `AudioRecord`
- **Bluetooth APIs:** `BluetoothAdapter`, `BluetoothA2dp`, `BluetoothDevice`
- **Tools:** Android Studio, Logcat, Coroutines/Threads

---