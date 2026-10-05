<div align="center">

# ☕ QuickOrder — iOS Food & Beverage Ordering Suite
### Native iOS SwiftUI Ordering System, Live Timers & Interactive Rating Flow

[![iOS](https://img.shields.io/badge/iOS-17.0%2B-000000?style=for-the-badge&logo=apple&logoColor=white)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.9%2B-F05138?style=for-the-badge&logo=swift&logoColor=white)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/UI-SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white)](https://developer.apple.com/xcode/swiftui/)
[![License](https://img.shields.io/badge/License-MIT-CEFF00?style=for-the-badge&logoColor=black)](LICENSE)

<br/>

**A native iOS food and coffee ordering application built with SwiftUI, order history persistence, preparation countdown timers, and interactive customer satisfaction rating flows.**

<br/>

[Overview](#-technical-overview) •
[Engineering Highlights](#-engineering-highlights) •
[Setup & Run](#-setup--run) •
[License](#-license)

</div>

<br/>

---

## 📌 Technical Overview

**QuickOrder** demonstrates mobile UX engineering, modular view composition, model modeling (`OrderHistory.swift`), and reactive real-time timer handling in SwiftUI. It provides users with an intuitive coffee and food ordering checkout pipeline with live order fulfillment tracking.

---

## 🏛️ Engineering Highlights

- **Modular View Hierarchy**: Decoupled component architecture (`WelcomeView.swift`, `TimerView.swift`, `RatingView.swift`).
- **Design Tokens & Extensions**: Custom Swift extensions for semantic brand colors, responsive image clipping, and formatted date representations.
- **Order State & Preparation Tracking**: Live order fulfillment countdown timer with progress animations and interactive completion alerts.
- **Interactive Review Flow**: Multi-criteria star rating and feedback submission component.

---

## 🚀 Setup & Run

### Prerequisites
- **Xcode 15.0+**
- **iOS 17.0+** Simulator or Physical Device

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/snaimio/quick-order.git
   cd quick-order
   ```

2. **Open in Xcode:**
   ```bash
   open iOSApp1.xcodeproj
   ```

3. **Build and Run:**
   - Select an iOS Simulator (e.g., *iPhone 15*) and press **⌘ + R**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
