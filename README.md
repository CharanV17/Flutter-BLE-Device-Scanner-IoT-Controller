# 📱 Flutter BLE Device Scanner & IoT Controller

A high-performance, cross-platform mobile application built with **Flutter** to interact with **Bluetooth Low Energy (BLE)** devices. This project serves as a bridge for IoT ecosystems, allowing users to scan for nearby peripherals and control them seamlessly.

---

## 🚀 Features

- **Device Discovery:** Real-time scanning for BLE devices with RSSI (Signal Strength) indicators.
- **Detailed Insights:** View device names, MAC addresses, and advertising data.
- **Secure Connection:** Robust connection handling to BLE peripherals.
- **Service Discovery:** Automatic mapping of GATT Services and Characteristics.
- **IoT Controller:** Read, Write, and Notify capabilities to interact with hardware sensors and actuators (e.g., ESP32, Arduino).
- **Modern UI:** Clean and intuitive interface designed for a smooth developer/user experience.

---

## 🛠 Tech Stack

* **Framework:** [Flutter](https://flutter.dev/)
* **Language:** Dart
* **BLE Plugin:** [flutter_blue_plus](https://pub.dev/packages/flutter_blue_plus)
* **State Management:** Provider / Riverpod (Recommended)
* **Permissions:** [permission_handler](https://pub.dev/packages/permission_handler)

---

## 📂 Project Structure (Proposed)

```text
lib/
├── core/
│   ├── constants/      # UUIDs, UI constants
│   └── theme/          # App styling
├── models/             # Device & Data models
├── providers/          # Logic for Bluetooth State Management
├── services/           # BLE interaction logic (BleService)
├── views/
│   ├── scan/           # Scanner UI components
│   └── controller/     # Device control dashboard
└── main.dart
